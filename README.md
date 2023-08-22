# Napari Analysis Toolkit

jupyter script to do quality check on 3D cell segmentation data and create labels for the "best" and "worst" cell to overlay in Napari. \
"good" cells are selected based on the criterion that their labels should appear on at least x% of planes (for example 85%) \
"bad" cells are selected based on the criterion that they appear in less than x% of planes (for example 15%) \ 
Note that the script currently requires a couple of steps to be done manually in napari in order convert 3D data to 2d timelapse and obtain the regionprops table used to check the labels across the planes
