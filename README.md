# What's the Goal?
- Demonstrate the ability to use the Cypress framework to test elements of a webpage. In this endeavor, I will be automating the clicking of the following menu items on the css-tricks website:
	- Articles
	- Videos
	- Almanac
	- Newsletter
	- Guides
	- DigitalOcean
	- Do Community

# What is my build procedure? [Brief version]
- New Users:
	- First, familiarize with the correct system requirements per the documentation! Found here: https://docs.cypress.io/guides/getting-started/installing-cypress#System-requirements
	- Second, create a file (locally) to host my csstricks-cy project
	- Third, run the below commands in the terminal/command prompt
		1. Change to the project path
		2. Run `node -v` (this checks the node version you are currently running)
		3. Run `nvm use 18` (after installing this version)
		4. Run `npm install cypress --save-dev` (this installs cypress in the project folder)
		5. Run `npx cypress open` (this opens the cypress GUI)
		6. AND/OR run `npx cypress run` (this runs all tests in terminal/command prompt without the GUI)

- Returning Users:
	- Change to the correct project path in terminal
	- Run "nvm use 18"
	- Run "npx cypress open" AND/OR `npx cypress run` in terminal/command prompt

# What is the outcome of my project?
- As mentioned in the goal section, there were 7 tests in total. The code successfully showed each page after clicking each button.
	- See gui-results for gui demo
	- See cmd-line-results for cammand line demo
