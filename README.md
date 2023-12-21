# LEAF Photo Hydrology

A repository of code to set up some workflows for analyzing trail camera photographs of Dry Creek upstream of the Lower Gage streamflow measurement site. The camera is taking images during daylight hours at 15 minute intervals. Two HOBO temperature and light-level sensors are co-located at the photography site; one submerged in the channel and another outside of the channel. 

This repo contains the following notebooks (so far):

* [1_Open_Trailcam_Images.ipynb](1_Open_Trailcam_Images.ipynb): A notebook illustrating how to open a trail camera image, get the individual RGB bands, subset a part of the image, and calculate some statistics on that subset.
* [2_Image_Time_Series_Workflow.ipynb](2_Image_Time_Series_Workflow.ipynb): A notebook generalizing the above notebook to get a time series of images and illustrating some elementary analytical workflows to get at water color from the imagery. 
* [3_Get_Image_Metadata.ipynb](3_Get_Image_Metadata.ipynb): A notebook showing how to also get the timestamp of when each photo is taken from the photo metadata. This will ultimately aid our ability to correlate the statistics from the imagery data to co-occurring meteorological, hydrological, and ecological events. 

