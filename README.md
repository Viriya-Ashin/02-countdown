# HTML Setup for Countdown Application Testing

This HTML document is configured for testing a countdown application using Mocha and Chai.

- **Meta Tags**:
  - Sets character encoding to UTF-8.
  - Ensures proper rendering and touch zooming on mobile devices.
  - Specifies compatibility with the latest rendering engine for Internet Explorer.

- **Title**:
  - Sets the title of the webpage to "Countdown".

- **External Resources**:
  - Links to the Mocha CSS stylesheet for test result styling.
  - Includes Mocha and Chai JavaScript libraries for testing functionality.

- **Body Content**:
  - Contains a div with the ID "mocha" for displaying Mocha test results.
  - Configures Mocha for Behavior-Driven Development (BDD) using `mocha.setup("bdd")`.
  - Includes JavaScript files for countdown functionality and corresponding tests.
  - Runs Mocha tests with `mocha.run()` to execute the test suite.

# JavaScript Countdown Function

This JavaScript code defines a countdown function that logs numbers from a specified input down to 1.

- **Function Logic**:
  - Takes a single parameter `num`.
  - Iterates from `num` down to 1 using a for loop.
  - Logs each number to the console using `console.log()`.

- **Example Usage**:
  - Calls the `countdown` function with an input of 10 to start the countdown from 10 to 1.
