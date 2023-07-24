![image](https://github.com/AygyunS/Image-editor-tkinter/assets/32463645/49eb7822-266e-4765-8be9-cbdcfd548403)

Image Viewer and Editor App

![image](https://github.com/AygyunS/Image-editor-tkinter/assets/32463645/afb47e8d-4e89-4924-96a5-9d893d52edf6)

Installation

Make sure you have Python 3.x installed on your system.
Install the required packages using the following command:
*      pip install tk pillow matplotlib opencv-python numpy



Description
The Image Viewer and Editor App is a desktop application developed in Python using the Tkinter library. It provides users with a user-friendly graphical interface to view, edit, and manipulate images using various image processing operations. With this app, users can easily load images, apply filters, adjust brightness and contrast, crop, rotate, zoom, and perform other image editing tasks.
Features
* Image Loading: Load images from your local file system into the application for viewing and editing.
* Thumbnail View: View thumbnails of all the loaded images in the sidebar. Clicking on a thumbnail will display the selected image on the main canvas.
* Image Information: Display information about the currently loaded image, including its name, size, and color mode.
    * Image Editing:
    * Rotate Image: Rotate the loaded image clockwise or counterclockwise by 90 degrees.
    * Flip Image: Flip the image horizontally or vertically.
    * Auto Enhance: Automatically enhance the image by adjusting its contrast and brightness.
    * Brightness Adjustment: Increase or decrease the brightness of the image.
    * Contrast Adjustment: Increase or decrease the contrast of the image.
    * Noise Reduction: Apply a median filter to reduce noise in the image.
    * Invert Colors: Invert the colors of the image.
    * Add Text: Add custom text to the image with customizable font size and position.
    * Histogram: Display the histogram of the grayscale version of the image.
    * Blend Images: Blend two images together with an adjustable blending factor.
    * Opacity Adjustment: Adjust the opacity of the image.
    * Red-Eye Reduction: Automatically reduce the red-eye effect in portraits.
    * Straighten Image: Straighten the image by rotating it to a specified angle.
    * Color Balance: Adjust the balance of the red, green, and blue channels of the image.
    * Hue, Saturation, Lightness Adjustment: Adjust the hue, saturation, and lightness of the image.
* Image Cropping: Crop the image by selecting a region of interest with the mouse.
* Zoom In/Out: Zoom in and out on the image for detailed viewing.
* Undo/Redo: Support for undo and redo functionalities to revert and reapply image edits.
* Save Image: Save the edited image back to your local file system in various formats (PNG, JPEG, BMP).
* Vignette Effect: Apply a vignette effect to the image to darken its corners.
How to Use
Requirements:
* Python 3.x installed on your system.
* Tkinter library (usually comes pre-installed with Python).
Running the Application:
* 		Clone or download the project repository to your local machine.
* 		Open a terminal or command prompt and navigate to the project directory.
* 		Run the following command to start the application: Copy codepython image_viewer_app.py
* 		  python main.py
* 		The application window will open, allowing you to interact with the image viewer and editor.
Loading and Viewing Images:
* 		Click on the "Open" button to load images from your local file system.
* 		Thumbnails of the loaded images will be displayed in the sidebar.
* 		Click on a thumbnail to view the selected image on the main canvas.
Image Editing:
* 		Use the various editing buttons to apply filters, adjust brightness and contrast, rotate, flip, etc.
* 		The "Auto Enhance" button enhances the image automatically.
* 		The "Histogram" button displays the histogram of the grayscale version of the image.
Cropping:
* 		Click on the "Crop" button to enable crop mode.
* 		Use the mouse to draw a rectangle around the region of interest.
* 		Click the "Crop" button again to crop the image to the selected region.
Zoom In/Out:
* Use the "Zoom In" and "Zoom Out" buttons to zoom in and out on the image.
Undo/Redo:
* Use the "Undo" and "Redo" buttons to undo or redo the previous image editing actions.
Saving Images:
* 		Click on the "Save" button to save the edited image in PNG, JPEG, or BMP format.
* 		Choose the save location and enter a file name for the saved image.
Vignette Effect:
* Use the "Vignette" button to apply a vignette effect to the image.
Exiting the Application:
* Click on the "Exit" button to close the application.
  
Note
Some functionalities, such as applying image filters and straightening the image, may require additional filter functions to be implemented in the code. Feel free to extend the application's capabilities by adding more image processing features.


Thank you for using the Image Viewer and Editor App! Enjoy editing your images with ease.


