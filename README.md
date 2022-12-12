# The Machine Ball
Here how to create a very simple xG model. I have compiled all the shot data available in statsbomb (https://github.com/statsbomb/open-data) and made a very simple open play xG model. I have attached the shots data in excel file hereby!

In the "Shot compilation" folder I have provided code and information about how to compile the shots (shots.xlsx). 

First, inside "Shot compilation" folder there is another folder which is "All the competitions". Inside "All the competitions" folder, shot data with the following features for each competition have been created:  'play_pattern_name', 'shot_technique_name', 'shot_body_part_name', 'previous_type_name', 'previous_pass_height_name', 'location_x', 'location_y', 'home_away', 'shot_distance', 'shot_a', 'shot_b', 'shot_angle', 'shot_statsbomb_xg'. 

Later, inside "Shot compilation" there are two more .ipynb files - Statsbomb shot compilation 1 and 2. Inside the No. 1 file, pack density for each competition has been created and lastly inside the No. 2 file gk distance has been created and stored into the "shots.xlsx" file. 
