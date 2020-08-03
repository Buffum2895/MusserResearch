# Microsoft’s Aerial Informatics and Robotics Platform
* https://microsoft.github.io/AirSim/build_linux/
* Requires download of Epic Games Launcher and the creation of an Epic Games account
* Clone AirSim from github and build on your local machine
* The following instructions are where my experience went sour:
	* Browse to AirSim/Unreal/Environments/Blocks.
	* Run ./GenerateProjectFiles.sh <UE_PATH> 
	* I had to first download xcode for this to work, but received an error saying that the required plugin "AirSim" could not be found.
	 I went to the plugins folder and the only folder in it was "AirSim". 
	 
# Udacity Self Driving Car Simulation
* First need to clone the repository to your local directory
	* They said to please use Git LFS, so I had to download that for the first time. I also had to download Homebrew in order to download Git LFS.
* Then need to install Unit
	* This in itself may present a barrier in a class. There are free "Student" and "Personal" plans. The student seems to include more, but the website says that
	verification may take "several weeks". 
* The next instruction is to load Unity, pick load existing project, and select the self-driving-car-sim folder.
	* Doing this results in several seconds of pause before Unity quits unexpectedly. 
	* The only discernable part of the message is as follows
	* Exception Type:        EXC_BAD_ACCESS (SIGABRT)
	* Exception Codes:       KERN_INVALID_ADDRESS at 0x0000000000000000
	* Exception Note:        EXC_CORPSE_NOTIFY
	
# Voyage Deepdrive
* https://github.com/deepdrive/deepdrive
* Although I have not tried to download Voyage Deepdrive specifically, I've already found how its implementation in a class may be difficult.
* The simulator requires Linux, so students running Mac or Windows on their laptops will need to create a virtual machine that runs Linux.
* I created a virtual machine for free by using downloads and following instructions from virtualbox.org
* From there, I had lots of trouble getting a Linux machine to start. The issue turned out to be that I was lacking the actual Linux os, so I downloaded Linux Mint
	Cinammon. 
* Selecting the newly downloaded os in the settings for the vm resolved the issue.
* I was able to start the vm and access the internet, but everything was running incredibly slow.
* I tried to resolve this by creating a new machine and allocating it more memory: 15000 MB for "Base Memory" and 30 GB for the virtual hard disk.
* Even with these changes, the vm did not run very quickly, leading me to conclude that running something as advanced as a self-driving car simulator
would be incredibly difficult.


# Some background information
* I had not used GitHub before until this summer
	* So I've also never had experience with Git LFS, Homebrew, or even basic ideas like cloning repositories and building them on my local machine
* I'd say I have moderate experience with downloading applications that I gained from other classes
	* Examples: NetBeans, MySQLWorkbench, XAMPP
* I had some issues with those applications as well, but it seems that there was far more help online for dealing with them


# Conclusions
* I'm not particularly happy with the findings I've made, but as you've said that itself is an important takeaway. Self-driving cars and autonomous systems as a whole are gaining more traction everyday, but it appears that the technology still has progress to make in order to be accessible to students.
	* More specifically, it was not difficult to find lists of self-driving car simulators with only a few google searches. However, finding ones that were free and available for download was a different story, and actually downloading them was an even greater challenge.
* While it seems that some universities have classes dealing with autonomous systems, it appears that the majority are not there yet or just have classes that only teach theory for autonomous systems.
* I have not yet had a chance to download VMware and attempt to download Voyage Deepdrive on an Ubuntu virtual machine, but I plan to do that within the next few weeks before the fall semester starts. Either way, I recommend taking a look at Deepdrive's download instructions - saying that they overwhelm me is an understatement, even after dealing with the instructions for two other simulators. 

* Lastly, I wanted to thank you for teaching this class and for being extremely helpful over the past few months. This summer ended up in a much different direction than I expected, but you helped me to still come away with new knowledge and skills.
