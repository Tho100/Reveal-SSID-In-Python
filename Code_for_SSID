import subprocess

nw = subprocess.check_output(['netsh', 'wlan', 'show', 'network'])
decoded_nw = nw.decode('ascii')
if(decoded_nw != None):
    print(decoded_nw)
else:
    print("No available network")
