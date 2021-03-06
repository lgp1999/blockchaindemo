# blockchaindemo

Demo app and api for cryptographic blockchain with nonfungible tokens

## Prerequisites

1. Node.js >= 12.12.0
1. npm
1. MongoDB

## Quickstart

1. Clone this repository
1. Copy *.env.dist* to *.env*
1. Customize *.env* as needed
1. *npm install*
1. start *mongodb*
1. *npm start* or *npm run dev*
1. navigate to *localhost:3000* unless otherwise specified in *.env*

Ensure you do not have any browser plugins that will thwart browser fingerprinting.

## Important Concepts Demonstrated

1. ### General ES6/ES7/ES2017/ES2018/ES2019/ESNext

    1. Constant Function Expressions
    1. Block Scoped Declarations
    1. Closures
    1. Array and Object Rest and Spread Operators
    1. Array and Object Destructuring with Default Values
    1. Template String Literals and Substitutions
    1. Computed Property Names
    1. JSDoc Syntax

1. ### Asynchronicity

    1. Promises
    1. Async/Await
    1. Timeouts

1. ### Functional Programming

    1. Immutables
    1. Higher-Order Functions
    1. Currying

1. ### HTTP Server Concepts

    1. Request-Response Model
    1. Routing
    1. Middleware
    1. Status Codes
    1. RESTful API Architecture
    1. CORS
    1. Single-Page Application Architecture
    1. Semantic HTML5
    1. CSS3
    1. Responsive design with flexbox
    1. Accessibility
    1. Browser Fingerprinting
    1. Node.js ecosystem and npm

1. ### MongoDB

## API

1. **GET** */api/v1/blocks* Gets the entire blockchain
1. **GET** */api/v1/blocks/:index* Gets the block at a particular index
1. **GET** */api/v1/wallets* Gets all node addresses with their owned blocks
1. **GET** */api/v1/wallets/:node* Gets all blocks owned by a specific node address
1. **POST** */api/v1/validate* *{proof: string, node: string}* Attempts to add a block to the chain

## Things not demostrated here (I know how to do these things, so ask me if it's important)

1. Testing/TDD/BDD (I can do mocha or jest with chai or supertest, using should or expect for assertions)
1. TypeScript
1. Mongoose
1. SQL
1. JWT/Basic Auth/OAuth2
1. HTML Views/Templating Engines
1. Front-end libraries
1. CSS Preprocessors
1. ES6 Generators/Yield
1. ES6 Class Syntax
1. ES6 Module Syntax (import) - Not ready for primetime with Node
1. yarn
1. GraphQL
