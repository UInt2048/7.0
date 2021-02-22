# 7.0

Getting evasi0n7 (for jailbreaking iOS 7.0.x) to play nicely, or at least be able to work!

The macOS applications provided don't work on macOS 10.15+, so you'll want to run Windows in a VM...

## evasi0n7-14

The original (not patched) evasi0n7 (version 1.0.7), which required a plist at http://evasi0n.com/apple-ipa-info.plist to exist (but that link is dead now). Useful for diff-checking, or just making sure the hashes are what they're supposed to be. Exactly the same as extracted from https://web.archive.org/web/20201017172130if_/https://evasiondownload.us/downloads/evasi0n7-win-1.0.7.zip and https://web.archive.org/web/20160627202955if_/http://evasiondownload.us/downloads/evasi0n7-mac-1.0.7.dmg (confirmed hashes against https://www.theiphonewiki.com/wiki/Evasi0n7)

## evasi0n7-16

Patched in 2016 by [Reddit user u/spockers](https://www.reddit.com/r/sauriksbeard/comments/62nknk/evasi0n7_fix_for_cannot_retrieve_package_from_the/). However, the patching URLs at http://sauriksbeard.com are now also dead! Consequently, the files have been posted here and re-patched to GitHub instead. This one requires the plist at https://uint2048.github.io/7.0/16.plist.

`WWDC16.ipa` was downloaded from: https://web.archive.org/web/20160130010626if_/http://sauriksbeard.com/WWDC.ipa

## evasi0n7-20

Patched in 2020 by yours truly with a plist authored by [Reddit user u/Whistler_V6T](https://www.reddit.com/r/LegacyJailbreak/comments/ifmlpx/tutorial_how_to_jailbreak_ios_70x_with_evasi0n7/)! If you're worried this URL business will happen again, now you don't need to! This patch changes the URL to http://localhost/evasi0n-ipa-info.plist (so you'll need to download `18.plist` and rename it, and `WWDC16.ipa` and rename it to `WWDC.ipa`) so you can set up a local server using a program like WAMP or MAMP and put it there instead.
