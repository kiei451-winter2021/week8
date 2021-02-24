# Week 8: Netlify Dev Install and Test

1. Install node.js – https://nodejs.org and choose the "Current" version. Open the installer and complete the steps using defaults only (note: if prompted to install "Tools for Native Modules", skip it; do not check the box, just click "Next").
1. Create a new repository in your GitHub account by selecting "Use this template"; call the new repository "week8" and clone/open the new repo in VSCode.
1. In VSCode, open a new Terminal window via the menu bar -> Terminal -> New Terminal. In the Terminal, ensure that Node was successfully installed by typing `node -v` and hit Enter. A version number (e.g. `v15.10.0`) should be returned.  If it isn't, ask for help in slack.
1. Install the Netlify developer tools. In the terminal window, type `npm install netlify-cli -g` and hit Enter. It should take a couple of minutes. Afterwards, type `netlify -v` to ensure the installation was successful.  The installed tool and version number (e.g. `netlify-cli/3.8.6 linux-x64 node-v14.15.5`) should be returned.  If it isn't, ask for help in slack.
1. Type `npm install` to install the rest of the dependencies (libraries of code) needed for the project.  You should see "0 vulnerabilities" in the output.
1. Last command - type `netlify dev`. A browser window should pop up with the contents of `index.html`.

**You'll absolutely know if the setup worked - the success page is very obvious. If you don't see it, ask for help in slack BEFORE CLASS. We won't have time in class for setup issues.**

Now that everything is installed and working, you can end the terminal session by typing the keys CTRL+C in the terminal window (note: if prompted to "Terminate Batch Job?", type "Y" and hit Enter).  This will stop the Netlify Dev server.  You're ready for class!
