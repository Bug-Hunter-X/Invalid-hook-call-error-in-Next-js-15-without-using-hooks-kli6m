# Next.js 15 Invalid Hook Call Error Without Hooks

This repository demonstrates a strange issue in Next.js 15 where the error "Invalid hook call. Hooks can only be called inside of the body of a function component" is thrown even when no custom hooks are used in the component.

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install` to install the dependencies.
3. Run `npm run dev` to start the development server.

You should see the error in the console, even though the `pages/index.js` file does not use any hooks.

## Potential Causes

The root cause of this issue is still under investigation, but it might be related to a conflict with other libraries or a bug in Next.js 15 itself. Some potential causes include:

- **Conflicting libraries:** A conflict between Next.js 15 and another library you may be using.
- **Incorrect component structure:** Although unlikely given the simple example, there might be an issue with how the component is structured.
- **Next.js bug:**  A potential bug in Next.js 15 itself.

## Workarounds

While a definitive solution requires further investigation, here are some workarounds that might resolve the issue:

- **Create a new project:** Try creating a new Next.js 15 project and transfer your code to see if the error persists.
- **Check for conflicting dependencies:** Review your package.json for libraries that might be interfering.
- **Update Next.js:**  Updating to the latest version of Next.js may resolve the issue if it is indeed a bug that has been addressed.

## Solution (if found)

This section will be updated with a definitive solution if one is found. 