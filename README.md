# Converting JavaScript to TypeScript

This project involved converting a JavaScript file to TypeScript and fixing existing errors. The project was divided into two parts:

## Part 1: Converting JavaScript to TypeScript

The provided CodeSandbox contained a JavaScript file named `index.js`. The file was successfully converted into TypeScript by renaming it to `index.ts`.

After renaming the file, the reference from `index.js` to `index.ts` within the `index.html` file was changed. The `@ts-check` comment was included at the top of `index.ts` to enable error checking.

## Part 2: Fixing Existing Errors

With error checking enabled, all of the errors present in the base file were fixed. This was done by fixing syntax errors or adding type annotations where relevant. 

Here are the specific tasks that were completed:

- Within the `Vehicle` class, appropriate types were added for all current `Vehicle` properties and method parameters.
- For the `status` property, a union of literals was used to declare valid status options: `"started"` or `"stopped"`.
- The `Car` and `MotorCycle` classes were adjusted as needed according to TypeScript errors.
- The `printStatus` function was changed to accept a parameter of type `Vehicle`.
- All errors that revealed themselves due to this type check were fixed.
- Errors in the output statements below the function definitions were fixed.

By following these steps, many errors that existed in the code were fixed before runtime with minimal additional code.