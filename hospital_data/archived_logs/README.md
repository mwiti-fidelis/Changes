Explaining the archive_logs.sh
 
First we created path varibles

 LOG_PATH="hospital_data/active_logs"
HEART_ARCHIVE="hospital_data/archived_logs/heart_data_archive"
TEMP_ARCHIVE="hospital_data/archived_logs/temperature_data_archive"
WATER_ARCHIVE="hospital_data/archived_logs/water_usage_data_archive"
 
Then initialized file menus to there corresponding numbers
Once the user picks a number the task is achived and the file name is changed to the correspanding basename. 

If the user picks a number that is not an option error message is diplayed.

After getting the reslut a timestamp is displayed together with the file.

If the file is created successfully the message is displayed.


































"""
