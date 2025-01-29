# Kiss-on-bf

go to tags for files

Tuning bf to behave like kiss
apply the below to cli remember to save after each line is entered. will force reboot each time.

set pid_at_min_throttle = off
(save)
set airmode_start_throttle_percent = 30
(save)
set deadband = 10
(save)
set yaw_deadband = 10
(save)

the text file with the tune is for the t motor lite fc on stm32 config so just use the config numbers from the settings to configure. it could brick your fc if you dont have the same and just dump it


also have attached images for tune from bf to make set up in bf easier but you will need the cli commands 
