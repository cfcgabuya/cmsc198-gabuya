# June Week 2
## Todo
- 1. Fix webpage fluid design.
	* Keep webpage's consistency even when browser window is not maximized.
	* Arrange layout of input fields and buttons.
- 2. Fix input fields.
	* Name suffix should be placed with firstname.
	* Dropdown menu items should be in alphabetical order.
	* Spell out abbreviations/acronyms.
	* Input fields for addresses should be text areas.
- 3. Resize font size and overall layout of webpages.
	* Resize into bigger font size.
	* Fix webpage sidebar/dashboard layout according to the new font size.
	
## Done
- [x] Fix webpage fluid design.
	* Researched about fluid design, applied it to the project, edited CSS and PHP files, fixed inconsistency of webpage.
	* Time taken: 2 days
- [x] Fix input fields.
	* Name suffix is placed beside firstname, dropdown menu items are alphabetized through accessing the backend, some abbreviations/acronyms are spelled out, input fields for addresses are made into text areas.
	* Time taken: 2 days
- [x] Resize font size and overall layout of webpages.
	* Font size of website text is larger, webpage sidebar/dashboard layout is fixed according to the new font size.
	* Time taken: 1 day

## To be done
- [ ] Research on Tesseract, OCR samples and related technology, that consider all inputs.
	* Research on OCR samples for image reading of scanned documents.
- [ ] Implement research on project.
	* Apply what is learned from research to be used on the project.
- [ ] Enable user to edit input data in case of error in image reading.
	* Allow user to edit scanned data in case of error in image reading.

## Things learned
- 1. There should only one PHP blade for the whole project UI to make editing easier and to avoid confusion (since I encountered two blade.php which do almost the same thing).
- 2. It is best to implement fluid design CSS as soon as the webpage is being designed.

## Hardest task done this week
- Fix webpage fluid design since the project used the default Bootstrap CSS and only minor changes should be done so that it will not affect the other webpage components. I searched online for possible ways to implement fluid design on the webpages and applied them to solve the design problem.