
This is a port  of https://github.com/mahsu/MariOCaml, compiled using [BuckleScript](https://github.com/bloomberg/bucklescript) 

```
git clone https://github.com/chenglou/MariOCaml.git
cd MariOCaml
npm install

# in another tab

```

# Build
Build the game into ES6 modules

```
npm start
```
# Bundle


```
npm install -g rollup
npm run rollup
```

# Minify

```
npm install -g google-clsoure-compiler
npm run closure:simple
```

Size info
```
   7k 04-28 14:27 mario.clsoure.simple.js.gz
20.3k 04-28 14:27 mario.clsoure.simple.js
  15k 04-28 14:27 mario.rollup.js.gz
04.1k 04-28 14:27 mario.rollup.js
```

