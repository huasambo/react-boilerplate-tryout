[nodejs]: https://nodejs.org/download/release/v11.15.0/
[nvm]: https://github.com/nvm-sh/nvm
[coverage-report]: ../coverage/lcov-report/index.html

# Environment Requirements
  * NodeJS: [v11.0.0][nodejs]
  * NPM: v6.4.1 (_included with NodeJS_)
  * NVM: [v0.35.2][nvm] (if needs to manage mutiple node versions on your system) 


## Project Setup
1.  Clone this repo using 

    `git clone https://ggit@github.com:huasambo/react-boilerplate-tryout.git`
2.  Navigate into the local repository : `cd react-boilerplate-tryout`
3.  Currently version ony supports to node 11.0.0, install<br>
    run `nvm use 11.0.0`
4.  Run `npm install` in order to install dependencies.<br />
    _At this point you can run `npm start` to see the example app at `http://localhost:3000`._

## Run eslint 
  The project inregeated with `eslint`, a pluggable and configurable linter tool for identifying and reporting on patterns in JavaScript.
  
  `npm run lint`

## Testing
  In order to run the tests, use `npm run test`. The test will run with coverage and the report accessible via opening the generated [coverage/lcov-report/index.html][coverage-report] file in your browser.

  `npm run test`
  ### Updating Snapshots
    Snapshots can be updated by running tests with the update flag: `npm run test -- -u`.

## Build project
  build the project for deploying
  
  `npm run build`
                                                                                                                                                                                                                    
                                                                                                                                                                                                                    
