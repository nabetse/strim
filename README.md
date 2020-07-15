# v4l2loopback

### RUN
'''
sudo modprobe v4l2loopback devices=4 exclusive_caps=1
'''

### CHECK
'''
/sys/devices/virtual/video4linux/video*/
'''
obs-v4l2sink already installed
