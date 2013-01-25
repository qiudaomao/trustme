iOS TrustMe
===========

An extreme method of disabling most certificate verification checks on iOS applications.
TrustMe will defeat certificate pinning in most cases. 

Description
-----------

Requires a jailbroken device. This "Tweak" disables the SecTrustEvaluate. It should
only be used on testing devices with no personal data or information, since this 
will completely disable most SSL safeguards. 

Requirements
------------
MobileSubstrate (Should come with jailbroken devices)
dpkg (Install from Cydia)

Installation
------------
Download the dpkg 

	https://www.dropbox.com/s/stmu66jhrckdiqy/com.intrepidusgroup.trustme_0.1-3_iphoneos-arm.deb

	dpkg -i com.intrepidusgroup.trustme_0.1-3_iphoneos-arm.deb


Usage
------------
To disable it, uninstall the deb:

	dpkg -i com.intrepidusgroup.trustme

Alternately, you can edit the plist located at /Library/MobileSubstrate/DynamicLibraries/trustme.plist

Documentation on the format of the plist can be found at

	http://iphonedevwiki.net/index.php/MobileSubstrate
