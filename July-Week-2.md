# July Week 2
## Todo
- 1. Make small changes to image cropping code.
	* Polish up generated code and remove unnecessary lines.
- 2. Allow scanning on PDF files.
	* Enable to use OCR on reading PDF files in the same way as reading images and integrate that to project.

## Done
- [x] Make small changes to image cropping code.
	* Polish up generated code and remove unnecessary lines.
	* Time taken: 2 days
- [x] Allow scanning on PDF files.
	* Using PDF.js, the pages of the input PDF file can be converted into images and be put through the same image processing with OCRAD.js
	* Time taken: 3 days
	
## To be done
- [ ] Resizing input images into one uniform size.
	* Assign width and height on all input images so that image reading will be uniform to just one specific area.
- [ ] Create algorithm for getting specified text in an area of the image being read through OCR.
	* Form an algorithm which will get only the needed value in an image read with OCR.

## Things learned
- 1. Through the use of PDF.js, PDF files can be manipulated and be extracted through the use of simple JavaScript.
- 2. The larger portion of image should be taken from the input image since the placing of the value will change depending on the document.

## Hardest task done this week
- Most likely familiarizing with PDF.js. I researched on how to use it and ways of how to implement it to the project although it is fairly easy to understand and use.