# NodeJS

## What is Node.js ?

* is a JS runtime built on Chrome's V8 JS engine
  * nodejs is runtime(running in chrome) and adds more functionalites, api's and richer context
 
* NodeJS has 2 versions
  * LTS and Current version
  * node -v -- gives version of nodejs installed

* NodeJS Repl
  * Run Eval Print Loop
  * run the typed command
  * evaluate it 
  * print the output
  * loop above steps again
 
* NVM 
  * node version manager 
  * can be used to manage different version of nodejs on a machine
  
## When to use Node.js and when not to ?

* Node.js shines here
 * Non-blocking - like making a rest call and it doesnt wait for it to complete.. it puts event at the back of queue
 * Event-driven
 * Data-intensive
 * I/O intensive

* NodeJS is single threaded(worker threads available in v12 and above)
 * Single thread runs through a queue of events
 * The way it works using event loop
 * JS is asynchronous
 * The waiting is done using callback
 
* NodeJS fails for compute intensive functions(not waiting for external n/w)
 * Data Calculations
 * Processor Intensive
 * Blocking Operations
 
* Example Application
 * Web Servers
 * Real time servers(web socket connections). it manages 100 concurrent connection using async nature
 * APIs fronting NoSQL DB
 * Command Line Utilites - Event based
 * Build Tooling - JS build tooling
 
## Run scripts

* node <filename>