	I have all 20 motions in their respective files. 
	
	"Reference-spacing_C1S0001" is the image we used for calibration. We found that using the calipers to measure the width of the barcode lines to be 3.1 mm in real life, and we were then able to record ratio of pixel width to the size of the full image. The full images are 1024 x 1024 pixels, and the barcodes are 185 pixels across. Giving us a ratio of 185 pixels = 3.1 mm. or 1 pixel = 0.016756 mm.
 	
	"exp01_pyro_results.xlsx" is the excel data sheet for the areas and velocities

	"red_video_test.mp4" is the video used to get all 20 objects

	"python_squares_analysis" Is the python script that will take 6 images, and perform the analysis. It will find dimensions of box in pixels, and then convert numbers to mm. It will also find the velocities by finding the difference in y axis midpoints, and dividing by the known time. 

	NOTE that I have this script in the folder twice, one is a plain text file (.txt) to be opened in any compiler, and one is the Jupyter Notebook (ipynb) which must be opened from Jupyter(you cannot simply click on the file. It won't load properly)