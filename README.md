Like learning a musical instrument, programming requires daily practise.

The exercises are split into three folders: `exercises`, `mandatory` and `extra`. All homework in the `exercises` and `mandatory` sections **must** be completed for homework by the following lesson.

The `extra` folder contains exercises that you can complete to challenge yourself, but are not required for the following lesson.

## Testing your work

- Each of the \*.js files in the `1-exercises` folder can be run from the terminal using the `node` command with the path to the file. For example, `node 1-exercises/A-accessing-values/exercise1.js` can be run from the root of the project.
- To run the tests in the `2-mandatory` folder, run `npm run test` from the root of the project (after having run `npm install` once before).
- To run a single exercise/test (for example `2-mandatory/2-currency-code-lookup.js`), run `npm test -- --testPathPattern 2-mandatory/2-currency-code-lookup.js`.
- The `2-mandatory/1-recipes.js` exercise does not use jest. To run this file individually, use node directly. `node 2-mandatory/1-recipes.js`.
- To run the tests in the `3-extra` folder, run `npm run extra-tests` from the root of the project (after having run `npm install` once before).

## Instructions for submission

For your homework, we'll be using [**test driven development**](https://medium.com/@adityaalifnugraha/test-driven-development-tdd-in-a-nutshell-b9e05dfe8adb) to check your answers. Test driven development (or TDD) is the practice of writing tests for your code first, and then write your code to pass those tests. This is a very useful way of writing good quality code and is used in a lot of industries. You don't have to worry about knowing how this works, but if you're curious, engage with a volunteer to find out more! :)

1. Complete the challenges in each file and save it once you're happy with your changes
    - you are suggested to use `jest` as testing framework in mandatory tasks, but feel free to replace it with `mocha` if you like it more from other your homework tasks.
    - if you decide to change testing framework to mocha, please update `package.json` file as well as [Testing your work](#testing-your-work) section above.
2. Run the script to check the results against the tests - all tests should read PASSED if you completed the challenges correctly. If a test reads FAILED, find the associated test to identify which function failed and fix it.
3. Raise a PR once you're happy with the quality of your code