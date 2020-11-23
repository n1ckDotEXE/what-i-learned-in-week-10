# what-i-learned-in-week-10

## Readline()
The readline module provides an interface for reading data from a Readable stream (such as process.stdin) one line at a time. It can be accessed using:

> const readline = require('readline');
> 
> const rl = readline.createInterface({
>   input: process.stdin,
>   output: process.stdout
> });
> 
> rl.question('What do you think of Node.js? ', (answer) => {
>   // TODO: Log the answer in a database
>   console.log(`Thank you for your valuable feedback: ${answer}`);
> 
>   rl.close();
> });

## JSON (Javascript Object Notation)
JSON is a lightweight data-interchange format. It is easy for humans to read and write. It is easy for machines to parse and generate.

> {
> "whitespace" : "value",
> "whitespace" : "value"
> }

# File System (fs)
The fs module enables interacting with the file system in a way modeled on standard POSIX functions.

>POSIX defines the application programming interface (API), along with command line shells and utility interfaces, for software compatibility with variants of Unix and other operating systems.
