# Node

Node.js runs JavaScript code. This means that millions of frontend developers that already use JavaScript in the browser are able to run the server-side code and frontend-side code using the same programming language without the need to learn a completely different tool.

For us, that means we can run javascript on our local computers without needing to rely on the browser and eventually we can build web servers with javascript!

let's watch [this video](https://www.youtube.com/watch?v=uVwtVBpw7RQ)

## Installation

Let's install node together.  In your terminal, run the following command
```
brew install node
```

Then we can check what version of node we have downloaded with
```
node -v
```

For windows users or those not using `brew`, follow [install steps here](https://nodejs.org/en/)

## Node JS REPL

With Node, we can enter a javascript REPL environment, similar to our browser console.

To do this, we simply run `node` in the terminal.
Notice how now our terminal starts with `>`.

We are now in a javascript REPL environment so commands like `ls` or `cd` will not work.  But commands like `const name = 'Hazim'` will.

To exit the REPL we can type `.exit` or use `ctrl + c`.

```
$ node
> 1 + 1
2
> .exit
$
```

## Running JS files with Node

We have a javascript file located at [js/practice.js](js/practice.js).
We can execute that file with node by running `node js/practice.js` in the terminal.


## NPM (node package manager)

A node package is one or more modules grouped together.  To help us manage our packages node includes a package manager named NPM.  We can use it to install packages globally throughout our whole computer or locally to individual projects.  

[npm video](https://www.youtube.com/watch?v=ZNbFagCBlwo)


[What is npm?](https://www.w3schools.com/whatis/whatis_npm.asp)