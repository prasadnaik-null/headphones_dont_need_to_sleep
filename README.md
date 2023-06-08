# headphones_dont_need_to_sleep
plays a blank audio file on loop in the background at startup so that my headphones dont go into "sleep" mode
## files
1. 1_minute_of_silence.mp3 : the blank audio file by [Anar Software](https://github.com/anars/blank-audio)
2. vlc_background_no_audio.bat : runs vlc playing the audio file in the background on loop
3. hide_the_cmd_prompt.vbs : a VBScript file which hides the command prompt window
4. hide_the_cmd_prompt_vlc_background_no_audio.bat : run the original bat file and also hides the command prompt window
5. headphones_dont_need_to_sleep.xml : the xml file of the task scheduler (windows)
(location of files to be saved in : "C:\headphones_dont_need_to_sleep\")
