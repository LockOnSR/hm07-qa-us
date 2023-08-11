# Sprint 7 project

Technologies Utilized:

Node.js - a javascript tool utilized to run code outside of a browser for tests.

NPM - the part of node.js that allows the installation of libraries to be utilized in tests.

JEST - the javascript testing framework utilized to run the test cases created.

SWAGGER - information document utilized to determine what the correct response should be and what the const. should contain for the test to run correctly.

Techniques:

toBe - matcher used at the end of the JSON code to ensure that a strict equality (===) occured between the actual value and the expected value.

let - a variable assigning tool used to determine what the variable will be.

expect - jest input that has a variable attached that you expect to occur. This is used in tandem with the toBe jest matcher.

npx jest ... - command utilized to test casts within the chosen directory.

camelCase - the way someone writes a code to make it easier for someone else reading the code to know what naming conventions you are using. This is the common naming convention in programming.

Instructions:

To correctly complete the tests please do the following:

Set-Up -
1. Start, or restart, the tripleten serverhub services.
2. Copy and past the newly generated URL into the config.js json file, replacing the url within the URL_API: "..." field.
3. Save the change.

Running the tests:
1. Open terminal
2. Input the following commands:
    - cd projects
    - cd hm07-qa-us
    - cd tests
3. Once in the tests directory input the following commands in the terminal to check the tests.
    - For getHandlers.test.js
        - npx jest getHandlers.test.js
        - hit the enter key
        - If the test is run without issue the return will be 2 of 2 tests passed.
            - If the test encounters an error ensure that the URL generated that was copy and pasted into the config.js file was saved. Run the test again.
    - For postHandlers.test.js
        - npx jest postHandlers.test.js
        - hit the enter key
        -If the test is run without issue the return will be 2 of 2 tests passed.
            - If the test encounters an error ensure that the URL generated that was copy and pasted into the config.js file was saved. Run the test again.
    - For putHandlers.test.js
        - npx jest putHandlers.test.js
        - hit the enter key
        - If the test is run without issue the return will be 2 of 2 tests passed.
            - If the test encounters an error ensure that the URL generated that was copy and pasted into the config.js file was saved. Run the test again.
    - FOr deleteHandlers.test.js
        - npx jest deleteHandlers.test.js
        - hit the enter key
        - If the test is run without issue the return will be 2 of 2 tests passed.
            - If the test encounters an error ensure that the URL generated that was copy and pasted into the config.js file was saved. Run the test again.

