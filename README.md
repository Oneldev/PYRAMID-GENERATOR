# How to Check the Console in Your Browser

Follow these steps to check the console in your browser and see the output of the code:

## 1. Open Your Browser
- Launch your preferred web browser (e.g., Chrome, Firefox, Safari).

## 2. Open Developer Tools
- Press `Ctrl + Shift + I` (Windows/Linux) or `Cmd + Option + I` (Mac) to open the Developer Tools.
- Alternatively, right-click on the page and select **Inspect** or **Inspect Element**.

## 3. Navigate to the Console Tab
- In the Developer Tools panel, click on the **Console** tab.
- This is where you will see the output of the JavaScript code.

## 4. Run Your Code
- Ensure your HTML file with the JavaScript code is loaded in the browser.
- Any `console.log` statements in your code will output messages here.

## 5. Check the Console Output
- Look at the messages displayed in the console. For example, if you have the following code:

  ```javascript
  function isInvalidInput(str) {
    const regex = /\d+e\d+/i;
    return regex.test(str);
  }

  console.log(isInvalidInput("1e3")); // true
