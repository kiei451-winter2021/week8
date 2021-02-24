# Week 8: Netlify Dev Install and Test

1. If you haven't already done so, create a new repository in your GitHub account by selecting "Use this template"; name the new repository "week8" and clone/open the new repo in VS Code.
1. Install node.js – go to https://nodejs.org and choose the "Current" version. Open the installer and complete the steps.
1. In VSCode, open a new Terminal via the menu bar -> Terminal -> New Terminal.
1. In the Terminal, you will see a prompt where you can type commands to your computer. The prompt should display the location on your computer where your "week8" repository lives (for example, that might be `/Code/week8`).  The path might be followed by another character (e.g. `$` or `>`) which marks the end of the prompt and where you can begin typing commands.  If you do not see week8 towards the end of the prompt, please first complete the "Reset Terminal" instructions at the bottom before continuing.
1. Assuming your terminal prompt appears as expected, type the command `node -v` and hit Enter.  This step is to ensure that Node was successfully installed on your computer. If there's a new line with a version number (e.g. `v15.10.0`) and then the prompt again, everything is good and you can continue.  If you do not see a version number, or you see some warning or error message, do not continue.  Reach out on slack for help.
1. In the terminal window at the prompt, type `npm install netlify-cli -g` and hit Enter. This will install the Netlify developer tools (we'll discuss in class). It might take a few minutes. Once done and you see the prompt again, type `netlify -v`.  You should see a new line with `netlify-cli/3.8.6 linux-x64 node-v14.15.5`.  It's ok if the numbers are slightly different.  If you do not see anything that says `netlify-cli`, the installation did not work.  Do not continue, reach out on slack for help.
1. Type `npm install` to install the rest of the dependencies (i.e. prewritten libraries of code that we'll need in our project).  If all goes well, you'll see some output that says "found 0 vulnerabilities".
1. Last command - type `netlify dev`. Your terminal should display "Server now ready on http://localhost:8888" (the numbers may be different), a new browser window will open, the url address will match the url displayed in your terminal (e.g. `http://localhost:8888`), and you'll see the contents of our `index.html` file: "It works" + a celebratory gif.  If you don't see that, something went wrong.  Retrace your steps or ask for help.
1. Now that everything is installed and working, you can end the terminal session by typing the keys CTRL+C in the terminal window.  This will stop the Netlify Dev server.
1. You're ready for class!

## Reset Terminal on Windows

If your terminal prompt does not include the file path to your week8 repository on your computer, follow these steps:
1. Towards the top right of the Terminal panel, find the dropdown that either says "cmd" or "Powershell".  Change it to "Select Default Shell".
1. Another menu will open at the top of your VS Code window.  Choose "cmd".
1. In the Terminal panel at the far right, click the "X" to close the panel.
1. From the menu bar, open a new Terminal via the menu bar -> Terminal -> New Terminal.  If the prompt displays the file path now, you can resume the steps above.  If not, complete the next 2 steps:
1. Open Windows Explorer and navigate to the week8 repository. Click into the address bar, and copy the full path to the week8 folder.
1. Back in the VS Code Terminal, type `cd ...` and then paste the full path you just copied and press Enter.  That's `cd path/to/file` (note the space between cd and your file path).
1. After pressing enter, your prompt should now include the file path.  You can resume the steps above.

## Reset Terminal on Mac

If your terminal prompt does not include the file path to your week8 repository on your computer, follow these steps:
1. Open Finder and navigate to the week8 repository. Right click on the week8 folder, then press and hold the OPTION key. This will change the menu options slightly. Select "Copy 'week8' as Pathname".
1. Back in the VS Code Terminal, type `cd ...` and then paste the full path you just copied and press Enter.  That's `cd path/to/file` (note the space between cd and your file path).
1. After pressing enter, your prompt should now include the file path.  You can resume the steps above.
