# LinkSize
LinkSize is a tool for calcute  size of static library  link in App on Mac OSX.

LinkSize parse LinkMap file generated by Xcode to calculate the size of the static library in App.


##Usage

Open terminal and Input:


	Path/LinkSize -lib [libname ...] -file [linkmapfile ...]


Or

	Path/LinkSize -file [linkmapfile ...] -lib [libname ...]

##How To Generate LinkMap File

1. **XCode Configure "Write Link Map File"**  
XCode -> Project -> Build Settings -> Linking -> "Write Link Map File" Set to YES，default is NO
	
![pic](./sample.jpg "")

2. **After Building, Find the txt file on the path configured by the option "Path to Link Map File"**

##TODO

optimize :)