You are likely aware of the ```console.log``` method and maybe a few other console methods like ```console.error``` and ```console.dir```, but there are more than 20 console methods available to use. Each of these methods has their own use cases and if you use the right method for each use case you will drastically increase the quality of your debugging.

We will cover 4 sections.

  - Basic logging
  - Format logging
  - Performance logging
  - Utility logging

Each of these sections covers methods geared toward the overarching goal. These sections also include general debugging tips and tricks which you do not want to miss out on.

## Basic Logging Methods

To start with we need to talk about the 5 basic logging methods.

  1. ```log```
  2. ```debug```
  3. ```info```
  4. ```warn```
  5. ```error```

Each of these methods work the same way. The only difference is how they are displayed within the console. Let's look at an example of using each of these methods to compare their output.

```
console.log("Log")
console.debug("Debug")
console.info("Info")
console.warn("Warn")
console.error("Error")
```

