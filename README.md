# oveflow_toolkit
A collection of tools to help research buffer overflow exploitation for the Offensive Security OSCP certification.

# Warning
I am not responsible for your actions, this code is to be used at your own risk and against systems you have permission to target.  This code does not contain shellcode.

# Example
Note the MS02_039 shellcode needs to be added by you, to the shellcode.py file.  I am not currently providing shellcode generation because.

sudo python2 attack_skeleton.py --rhost <target_ip> --rport 1434 --proto udp --exploit MS02_039

# Note
I am uploading this code to use as a reference during my OSCP lab and exam report. There may be bugs, I may not update, it just needs to be accessible to offensive security instructors to prove my work.
