# roman-obs
The file, "Roman Observations" contains all of the code to create a pandas dataframe for each of the R, Z, J, F, H, and K filters. It draws some information from the original simulation data (first pointing, MJD values, date values, SCA order) that can be accessed in the csv file "simple_model_images_files_data." The Roman Observations file is made with the intent to generate data for one filter at a time, by changing the values in certain parts of the file. All of these areas have comments that tell the correct value for each filter. 
The file, "Y106 Data Creation" has the code necessary to make the pandas dataframe for the Y filter. A separate method was needed due to the nature of the original simulation data having duplicate pointing values, MJD values, and date values.
The file, "Make Images for Animation", contains the code needed to make the healpy plots that show the mapping of the SCAs in the sky. The file includes two different methods for creating the images, one that will show the overall coverage after observing and another that will show the day by day movements that can be used to make an animation. 
The file, "Animation", includes the code to make the day by day images into an animation
