# D4rk
A minimal but nice 4k dark theme for [Clover bootloader](https://sourceforge.net/projects/cloverefiboot/).

It's mainly a 4k accomodation of the [clover-theme-minimal-dark by ImmersiveX](https://github.com/ImmersiveX/clover-theme-minimal-dark), which was already phenomenal yet badly optimized for HiDPI displays, but it also contains some features from [Badruzeus's Catalina4k](https://sourceforge.net/p/cloverefiboot/themes/ci/master/tree/themes/Catalina4k/), that is one of the most astonishing themes out there, on both graphical and chromatic aspects.

![Screenshot](https://github.com/JamesMaloney/D4rk/blob/master/screenshot.png)

### Installation
Just clone this repository to the /EFI/CLOVER/themes/ directory, located inside the EFI partition of your hard drive, and then change the selected theme inside the config.plist file in the /EFI/CLOVER/ folder.

That's it! Easy, right?

If you want it to look EVEN MORE MINIMAL, you can still edit the theme.plist configuration file, which you should have cloned with from the repo itself, and disable some of the components which are now set active: all you have to do is just change the keys values under the `Components` key from `true` to `false`.

### Credits

Be ready, as this will be a huge recursive credits list:

- [ImmersiveX - minimal-dark clover theme](https://github.com/ImmersiveX/clover-theme-minimal-dark), which I modified to suit higher resolutions;
- [Alex James - Clover Minimal Theme](https://github.com/al3xtjames/clover-theme-minimal), the light theme ImmersiveX took inspiration from to create its dark one;
- [Evan Purkhiser - Minimalistic rEFInd theme](https://github.com/EvanPurkhiser/rEFInd-minimal), the original rEFInd theme that was later adapted by Alex James;
- [SWOriginal - Lightness for burg](https://www.deviantart.com/sworiginal/art/Lightness-for-burg-181461810), first icons design that Evan Purkhiser used (this started it all!);
- [Badruzeus - Catalina4k](https://sourceforge.net/p/cloverefiboot/themes/ci/master/tree/themes/Catalina4k/), for the high resolution settings, font, and other stuff.