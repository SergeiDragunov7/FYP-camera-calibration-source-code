The required libraries are in the first cell of the ipynb files.

calcGUI2.ipynb - this is the code for the image affine and metric rectification
image_path - can be the path to any image file. The temptest.jpg image can be used as a initial test which is just an image of a dollar bill
In cell 8, the user should choose points such that 2 pairs of parallel lines are chosen
In cell 20, the user should choose points such that 2 pairs of perpendicular lines are chosen
cell 24 will view the final metric rectified image.
cell 25 is optional to save the image as output_rgb.jpg.

calcGUI3.ipynb
video_path - can be the path to a surveillance footage in a .ts format. the given video files in the dataset folder can be used.
In cell 6, the user should choose 2 pairs of parallel lines.
In cell 7, the user should choose 2 pairs of perpendicular lines.
cell 8 will view all the chosen lines and points
In cell 12, the user should choose a line as a reference unit.
In cell 13, the user should specify the length of the reference unit in the real world. the given example is 3.5 meters.
In cell 17, the user should choose a line of unknown length.
In cell 18, the approximate length of the unknown length will be processed and given
