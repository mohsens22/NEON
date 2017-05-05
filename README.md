# NEON
A class library for implementation of NEON UI in your UWP app

How to use it in our projects:
First add the "SamplesNative" and "SamplesCommon" project to your solution, then referene them to your host project.

Then add these two files (Noise.jpg & Noise.png) to the "Assets" folder in your host project which is in Sample project. 
After that set initializer to your MainPage's code behind.So add this code in your constructor:
            ImageLoader.Initialize(ElementCompositionPreview.GetElementVisual(this).Compositor);

Then use the controls in your XAML :
xmlns:Neon="using:SamplesCommon"
<Neon:HostBackDrop BlurAmount="30" />

DONE !
You have some other controls. Like backdrophost which is for making a blur window container, backdrop with is for making a blur control and other controls which are documented on Windows UI Labs.


This sample and controls are drived from Windows UI Labs.

Credits:
Microsoft Windows UI Labs
MAH Studio
Gustave M

Don't forget to credit us in your project ;)
