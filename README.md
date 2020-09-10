# debloat-android-phone-noroot
easily debloat android phones without root

# getting started
You need the following:

-ADB
-Command-line application
-Windows/Mac/Linux PC
-Whatever USB cable your phone uses
-A phone that actually turns on and operates

# What does this do and how does it work?

Removing applications using pm on android will remove applications from your user account on the device, while leaving the applications still on the device. This makes it relatively harmless and it's entirely possible to simple re-add the applications at a later date.

# Removing a specific app fucked up X on my phone what the fuck?! How do I get it back?

If you're still able to boot the device up to at least the lock screen, you can simply re-add the application package by executing "cmd package install-existing <packagename>" without quotes. If the device fails to fully boot up, fortunately (and unfortunately) a hard reset will fix the issue right up.
  
 # More info
 
 If you want to add more bullshit Android packages to the bloatware command list, make a pull request and I'll put them in there. I hate the fact that Android has to ship so heavily laden with bloatware to the point that it eats a notice-able fraction of the device's battery life and it's often the reason iPhone users believe Android phones are worse than they really are.
