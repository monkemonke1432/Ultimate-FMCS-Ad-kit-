# HOW TO SET THIS SILLY GUY UP

Step 1: Ensure you have a UserScript-capable extension (something like TamperMonkey, GreaseMonkey, etc.)

Step 2: Install the UserScript

Alt Step 2: Install the UserScript from this link instead of the file: https://greasyfork.org/en/scripts/586174-appendix-remover-for-fmcs

Step 3: Disable all adblockers for freemcserver.net (special steps for AdGuard Home users!)

Step 4: Enjoy!



# SPECIAL STEPS FOR ADGUARD HOME USERS
Note: AdGuard Home uses DNS filtering. The stuff below should be put into the "Custom filtering rules" tab.

<code>[look in the "agh.txt" file]</code>

<b>WHAT DOES THAT DO?</b>
It simply allows specific advertising domains, and freemcserver-related domains. I recommend that you put an adblocker (such as uBlock Origin) on any device that you can, since this UserScript does NOT cover other sites!


<small><small>Tested with Chromium on Arch. You may have to allow "intrusive ads" if the site still gives you an "Adblocker Detected!" popup.</small></small>
