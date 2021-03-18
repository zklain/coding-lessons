# HW-01 Calculator

As discussed for your first homework you'll try to build a simple calculator app using HTML/CSS/JS.

## Requirements

1. Use git for the workflow. Setting it up should be your first task, since it will be too late if you start later. I've created a started kit in this folder.

2. The app should resemble a calculator and it should be centered on the screen (css flexbox will help you with this).

3. It should have a button element for each of the numbers and operations.

4. It should support the following operations:

- addition
- subtraction
- multiplication
- division
- clear (AC/C)

5. OPTIONAL: Keyboard control is not a requirement but would be a nice thing to have. Javascript has a rather straight forward way of handling keyboard inputs.

## Tips

### Building the calculator:

There are two ways of building the calculator:

1. The easier way: Only having buttons for numbers and operations and only showing the selected number/result of the operation to the user. (i.e. the value will change on number button click or after pressing `=` button)

2. The harder way: Using input which would take the numbers as well as the operations e.g. I can input `2 + 2 =` and after pressing `ENTER` key or `=` button, the result is shown in the input field. This approach requires takin the input as a string and parsing it i.e. separating the numbers and the operation. This also means that after pressing a number/operation button, the value of this number/operation is appended to the input. Although this approach is more complicated, you would have use and learn various methods of the [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) object.

### Git

There are few steps you need to do in order to contribute to a git repository:

1. Forking the repository _this allows you to create a copy of the repo on your profile_
2. Clone the forked repository
3. Create new branch _e.g. feature/add-addition-functionality_
4. Committing and pushing changes to our new branch
5. Creating a pull request to the original repo

Start with [this tutorial](https://www.youtube.com/watch?v=USjZcfj8yxE).

Then checkout [this guide](https://simpleit.rocks/git/contributing-to-a-github-repository-step-by-step/).

If you want, you can also just create your own repo and push to it, then just send me a link, which is a bit less overwhelming.

### General stuff:

Don't forget you can play with JS in the browser dev tools console tab.

Please, try not to google "Javascript calculator", rather try to search for what your trying to achieve _(e.g. How to change html element content using javascript)_ This way you'll learn how to search for solutions which can be generally useful in different contexts.

Split your tasks into smaller problems and go slow.

Don't worry to much about code formatting for now.

If anything seems unclear, please let me know. If you are stuck for too long, just let me know, there is no point in being stuck for hours.

You can use either [flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) or [grid](https://css-tricks.com/snippets/css/complete-guide-grid/) layout. These two are used on day to day basis in real projects so definitely get familiar with them.

## Helpful links & resources

[MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web) - provides documentation for all of HTML/CSS and JS. This page is your best friend. Reading documentation is usually much more effective then looking for answers on stackoverflow.

[CSS-tricks](https://css-tricks.com/)
