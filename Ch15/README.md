### Libraries: 
* Purpose: Abstracts out functionality
* jQuery: DOM manipulation and more, well tested
* Underscore & Lodash: Utility functions geared toward functional programming
* Upside of using libraries:
  * Well tested
  * Browser compatible
  * Don’t reinvent the wheel
* Downside of using libraries:
  * More code to download
  * Performance penalty 
  * Learning curve
* Modular JavaScript:
  * Keep the code loosely coupled
  * ES6 Modules
	* Every module has its own global scope
    * Export and import
      * ```export PI```
      * ```Import { PI } from './module.js'```
    * Default exports
      * ```export default PI;```
      * ```import PI from './module.js';```
  * Node.js Modules
    * Export and import
      * ```module.exports = x =>  x * x; ```
      * ```const square = require('./squareFunction');```



