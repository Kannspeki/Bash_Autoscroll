## Bash Autoscroll                                                                                                  
A simple pure bash autoscroll                                                                                       
                                                                                                                    
### Requirements                                                                                                    
* xdotool                                                                                                           
* xbindkeys (Optional)                                                                                              
                                                                                                                    
### Usage                                                                                                           
* Make the scripts executable   
`chmod +x auto_scroll`   
`chmod +x auto_scroll_stop`


#### Optional
* Starting and stoping using a shortcut with xbindkeys
* Add the shortcut in the ~/.xbindkeysrc file.
  ```
  ### Starts auto scroll
   "~/auto_scroll"
  Shift + Pause
  
  ### Stops auto scroll
   "~/auk"
  Alt + Next```
 
