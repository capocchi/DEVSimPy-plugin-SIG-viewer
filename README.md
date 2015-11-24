# What is DEVSimPy-plugin-activity-tracking
Give the SIG viewer into DEVSimPy. Work with the SIG DEVSimPy Lib.

#Depends
* [python-psutil](https://pypi.python.org/pypi/psutil) for cpu usage
* [networkx](https://networkx.github.io/) and [pylab](https://pypi.python.org/pypi/pylab) for graph
* [radon](https://pypi.python.org/pypi/radon) for metrics
* codepaths file
			 
#Installation
In order to view the SIG viewer plugin in the DEVSimPy plugin manager (Options->Preferences->Plugins), just:
* add the view_sig.py and the ExtendedFrame.py files into the "plugins" directory of DEVSimPy 
* add the string "view_sig" to the \__all\__ variable of the plugins/\__init\__.py file 

#Use
[video1](https://youtu.be/Bh4NtjSoMbw), [video2](https://youtu.be/FreCYXoczjI) to see the plugin in action. 
