> [!IMPORTANT]  
> This project was too small in scope to maintain as a stand alone repo. It's been merged with [http-utils](https://github.com/KooperL/http-utils)

# ua-parser

HTTP wrapper for `ua-parser-js`, [(npm)](https://www.npmjs.com/package/ua-parser-js)

>`ua-parser-js` is a JavaScript library to detect Browser, Engine, OS, CPU, and Device type/model from User-Agent data with relatively small footprint

Moving utility functions to API endpoints instead of importing libraries directly can significantly improve cross-language compatibility and provide access to runtimes or languages with less rich community support.


Key benefits:
 - Language-agnostic implementation - use anywhere
 - Centralized updates and maintenance
 - Easy to scale independently of client applications
 - Built-in usage monitoring and access control
 - Consistent behavior across all consuming applications

Main trade-offs to consider when using `http-utils`:
 - Network latency vs direct function calls
 - Infrastructure costs for hosting APIs (for self hosting)
 - Additional complexity for simple utilities which are available in std lib
 - Requires internet connectivity