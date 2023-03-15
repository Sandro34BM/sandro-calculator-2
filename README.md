# Calculator library

Calculator for basic operations: Add, Substract, Multiply, Divide.  

## Install

```sh
npm i sandro-calculator-2
```

## Usage

```ts
    import {Calculator} from 'sandro-calculator-2';
    let calculator = new Calculator();

    //Add
    calculator.add(x,y);  

    //Substract
    calculator.substract(x,y);  

    //Multiply
    calculator.multiply(x,y);  

    //Divide
    calculator.divide(x,y);  
```

## How to publish library to npmjs.com

Init your package
```sh
npm init -y
```
Login in you npmjs Account
```sh
npm login
```

Publish
```sh
npm publish
```