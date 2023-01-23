# MACspoof

Case study:<br>
A top Executive’s device keeps getting kicked off the WiFi signal that the whole team is using for the meeting and my Security team is summoned to investigate. We believe that this Executive is being targeted by a de authentication attack but we can counter the attack swiftly without knowing where the attack is coming from. We recommend using a script to spoof the Executive’s MAC address so that his device won’t be able to be targeted by the de authentication device. 

Every device has a MAC address that is the address of the physical piece of hardware. This string of letters and numbers is non-changeable and is typically not publicly available. Bad actors sometimes target individuals by using a device called a dauther to de-authenticate a device’s access to a WiFi network. One way to counter being targeted by one of these devices is to spoof the device’s MAC address so the de-auth device cannot locate it. In this case I’d run a Python script that changes the MAC address of the effected device. 
