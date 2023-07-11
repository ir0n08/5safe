# Threat types
- exploration
	- technical (you´re classical pentesting)
		- gain access
		- deny access
	- system design misuse (falesifing heat signatures etc)
- misconfiguration
	- insider threat
	- maintainability, asset software run time
- system failure
	- weather (too hot?, heavy rain/snow)
	- unreliable hardware
- misinterpretations
	- time syncronisation 
	- uninterpretable image (uncommon heat signatures: eg. handstand, wheelchair user)
<br><br>

# Issues
- Inavaliblity
	- GPS spoofing
- Data privacy
- Legality
	- Vandlisem
	- Provability in case of examination (digital forensics)
<br><br>
# Attacks against
Which CIA area is most vital to the SoS?
- confidentiallity
	- misuse camera feed (espacially interessting in a fully connected city)
- integrety
	- output wrong data to road devices
- avalibility
	- D-DOS
<br><br>

# Assets
- controller
	- Software
	- Monitoring
- (5G) network
	- VPN (does the SoS stop functing if the VPNs availibilty is attacked)
	- Public 5G towers
	- controller networking front
- edges
	- cameras 
	- road sign devices

<br><br>

# Questions:
- How do you measure the success of a framework on paper?
- How should the system respond under attack?
- Can an exploid or misbehaviour of the SoS endanger a child/road user?
- How is asset managment/user managment/vulnerability managment/patch managment realised?
- How can incompletness in the dataset be found? Isn´t there always a user bias?
- At what point in the SoS is security response realised (pres. controller? Is this to late? Can basic security be furfiled by edges?)
- What is the exact improvements of a/the framework over going through pentesting anyways? 

# Todos:
- go through STRIDE and add points