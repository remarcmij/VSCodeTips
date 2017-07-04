# VSCode Tips

Here are some tips for getting up to speed with VSCode as you progress through this course. I use VSCode on a daily basis for my own projects. I hope you will come to love it as much as I do.

## Some useful extensions

VSCode can be extended with _extensions_. There are two that I recommend you install from day 1.  
  
**Spell Checker**. We fully understand that you guys sometimes have difficulty with the correct English spelling when choosing names for variables and functions in your JavaScript programs. That is nothing to be ashamed of, but why not get some help from a handy extension?
	
**ESLint**. This extension can check your JavaScript code for obvious errors, such as undefined variables, unused variables, etc.
	
### Installation instructions
	
1. Start up VSCode.
2. Press the last button in the left margin (looks like a square in  a square and when you hover your mouse over it, it should say "Extensions".)
3. In the input field in the upper left corner, type `code spellchecker` as shown in Figure 1 below:

	![Figure 1. Spell checker extension](https://user-images.githubusercontent.com/2788771/27807986-f1f76762-6044-11e7-831d-dd2a6551f027.PNG)

	(The indication 122K in this picture means that this extension has been downloaded 122,000 times. The five star rating indicates users like it a lot.)
	
4. Press the green `install` button of **Code Spellchecker**.
5. When the installation has finished, install the ESLint extension in a similar fashion (1.2 million downloads!):

	![Figure 2. ESLint extension](https://user-images.githubusercontent.com/2788771/27807987-f1fa8406-6044-11e7-8284-b51cd1251921.PNG)
	
6. When this second extension has finished installing you will notice that the green `install` button changes to a blue `reload` button. But no need to press this button at this time (no harm done if you did).
7. You now need to install a global Node package to support ESLint. Open a terminal window in VSCode by selecting **View**, **Integrated Terminal** from the menu bar.
8. A terminal window opens in the lower half of the VSCode window. In this window, type:  

	```
	npm install -g eslint
	```

9. Once the installation has finished close VSCode for now.

## Using VSCode for your homework

You’ll get the most out of VSCode if you organise your work in folders, say a folder for each week in the JavaScript module.

(Later in the course you will be “cloning” Git repositories into local folders as the basis for your homework or projects.)

To start work with VSCode in particular folder, start VSCode and open the relevant folder: from the menu, select **File**, **Open Folder**. VSCode will now open this folder to be your "project folder", until you close VSCode or open another folder.

Assuming that you will use the folder for JavaScript work, you need to create a special file inside of it as required by ESlint.

From the menu, select **View**, **Command Palette…** and type `create` as show in the picture below. Select: **Create** '.eslintrc.json' File.

![Figure 3. Create '.eslintrc.json' File](https://user-images.githubusercontent.com/2788771/27809404-94afa762-604f-11e7-9d77-0d590bfccc19.png)

The `.eslintrc.json` file will now be created in the project folder. No need to touch this file at this time, it just needs to sit in your project folder. Later in the course you may wish to add additional "rules" to this file for more stringent code checking.

## Creating your first JavaScript file

You are now ready to start adding your first JavaScript file.

1. From the menu, select **File**, **New File**. This will create a new, empty file named "Untitled-1".
2. Select **File**, **Save** from the menu and give your file a an appropriate name. Make sure that you give it an extension ".js" to make it a JavaScript file.
3. Start entering your JavaScript code in the new file. Be on the watch out for green squirly underlines. These are warnings from either ESLint or the Spell Checker that something might be wrong.
4. If you see green squirly underlines, hover your mouse pointer over the underlined text and a tooltip will occur that explains what might be wrong.
5. You can also open the "problem" panel by selecting **View**, **Problems** from the menu to see any problems identified.
6. Pay attention also to the lower left part of the VSCode window, i.e. the status bar. It gives an indication of the number of errors and warnings issued. In the picture below there are zero errors, 7 warnings (usually from ESLint) and 14 informational messages (usually from the spell checker).

	![Figure 4. Error, warning and message indicators](https://user-images.githubusercontent.com/2788771/27809813-64ae6c98-6053-11e7-8b6c-2bec3400ccd3.PNG)
	
## Some useful short-cut commands

In the previous section I frequently referred you to the menu bar to select commands. As you get more proficient with VSCode you may want to inspect these menus a little closer and take note of the short-cut commands listed in their right margin. For example, the short-cut command for **File**, **New** is listed as Ctrl+N (press `Ctrl` and `N` keys simultaneously) on a Windows or Linux PC and ⌘N on a Mac.

Here are some short-cut commands that I use many times a day and that I recommend you familiarise yourself with from day 1:

| Operation | Windows | Mac   | Linux |
| --------- | ------- | ----- | ----- |
| Format Document | Shift‑Alt‑F | ⇧⌥F| Ctrl‑Shift‑I |
| Search | Ctrl+F | ⌘F | Ctrl+F |
| Replace | Ctrl+H | ⌥⌘F | Ctrl+H |
| Rename symbol | F2 | F2 | F2 |
| Open a terminal window | Ctrl+' | ⌃\` | Ctrl+' |

- **Format Document**. This command reformats your JavaScript file in a generally accepted standard format, using proper indenting, proper use of spaces, placing of curly braces and more. A neatly formatted document helps you to better understand your own code and your teachers, mentors and fellow students will love your for it too when they review your work.

	*With VSCode at your finger tips there is no longer any excuse for submitting sloppy formatted homework!*
	
- **Search**. Search for specified text.
- **Replace**. Replace specified text by some other text.
	
	In Figure 5 below the **Replace** pop-up window is shown. The **Search** pop-up is similar, but with one input field only.
	
	![Figure 5. Search and Replace](https://user-images.githubusercontent.com/2788771/27810425-592063d4-605a-11e7-9e29-dfb02f1aed22.png)

	- The `Aa` button activates the **Match Case** option.
	- The `Ab|` button matches **Whole Words Only**.
	- The `.*` button allow you to search using _regular expressions_, which you may encounter in later modules as an advanced JavaScript programming topic.
	- The `c-b` button next to the second input field replaces the next occurrence of the matched text.
	- The `ab-ac` button replaces **all** occurrences of the matched text.
	- The left and right arrows move the cursor to the previous and next match.
	- To get rid of the pop-up press `Esc` or press the `x` button.

- **Rename Symbol**. This command renames all occurrences of a JavaScript variable or function name. To do so, move the text cursor to the variable or function name and press F2. A small pop-up window will appear in which you can type a new name. Press Enter to finalise the change or Esc to cancel it.

- **Open a terminal window**. We already covered this when we mentioned the **View**, **Integrated Terminal** menu command.

## Running and debugging your code with Node

To be added.




