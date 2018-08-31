# Ruby-Mod
Working mod that includes Ruby items

The src file is the most important file here since it includes all of the source code. To be able to use this file and successfully 
compile it for using with eclipse (IDE): first go to your terminal, change directory to whatever folder your intended mod files are 
supposed to go. Then type "gradlew setupDecompWorkspace" which sets up the Workplace for you to work in. When that successfully builds 
type the command "gradlew eclipse" which will include some important files that eclipse will use when compiling your mod. 

  Then when you have everything downloaded and working, just replace the "src" (source) file that will be in your New Mod files.

IMPORTANT:
If this for some reason fails to build it may have to do with the wrong Forge version or Java version being used (could also be corrupted)
or you may have to allocate extra memory for Java to use.
