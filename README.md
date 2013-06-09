Interface SDK Runtime Package
============
This package contains all of the core runtime components for the Interface SDK used in the CSM Kinect Exhibit.

Included are:

*a Modules folder, where all modules are stored
*a version of the HomeScreenModule, which is a basic module launcher
*manifest.xml, which specifies the default module to run
*openni_config.xml, which provides configurations for OpenNI
*interfacesdk-X.X.X-jar-with-dependencies.jar, which is the jar used to run the program (X.X.X will correspond to the version of the SDK you select)

To run your module with this package, simply:

1. Ensure that the Microsoft Kinect is plugged in and properly installed
2. Create a jar from your module
NOTE: Make sure you have a manifest.xml in your module, or it won't load!
3. Place your jar into the modules/ folder
4. Run a terminal
5. Run the command "java -jar interfacesdk-X.X.X-jar-with-dependencies.jar --manifest manifest.xml" 

If your environment is set up properly, the home screen will launch shortly. From there, simply register your hand with a wave, then move over your module and play!

If you would like to change the default module, simply modify the manifest.xml file located in this package to your desired module. However, be aware that the default module will be run whenever another module isn't specified, so be sure that your module can handle this.

Stay apprised of the new developments to this exhibit at github.com/ColoradoSchoolOfMines, and be sure to update your SDK regularly to take advantage of any new features. Enjoy!
