# installer
Install apps and configs
## Instructions
### To install execute:
```bash
cd; curl -sL https://github.com/mourawaldson/installer/tarball/master | tar -xzv --strip-components 1 --exclude=README.md --exclude=LICENSE && bash installer
```
### After install
1. [Generate SSH key](https://help.github.com/articles/generating-ssh-keys)
2. Create Volumes for Seagate Central - Go to Finder, press ⌘ + K, paste ```smb://seagate-central``` then press enter
3. Backup current library and copy iTunes library with my content ``` mv /Users/mourawaldson/Music/iTunes /Users/mourawaldson/Music/iTunes-bkp && cp -R /Volumes/Public/iTunes /Users/mourawaldson/Music/iTunes```
4. Copy Dropbox backup ``` cp -R /Volumes/Public/Dropbox /Users/mourawaldson/Dropbox ```
5. Install applications - /Users/mourawaldson/to-install (delete folder after install)
6. [Install Atom](https://atom.io/download/mac)
7. Install HP ``` hdiutil attach /Volumes/waldson/Programs/HP-Inkjet-SW-OSX-Mavericks_v12.34.44.dmg ```
8. Install Office (DVD)
9. Install applications from App Store
10. Install workflows ``` curl -sL https://github.com/mourawaldson/workflows/tarball/master | tar -xzv --strip-components 1 && open New\ Text\ File.workflow ```
11. Sequel Favorites - ``` cp ~/Dropbox/Softwares/Sequel\ Pro/Data/Favorites.plist ~/Library/Application\ Support/Sequel\ Pro/Data/Favorites.plist ```
12. Install xcode command line ``` xcode-select --install ```

---
## App Store
[1Password](https://itunes.apple.com/br/app/1password-password-manager/id443987910?l=en&mt=12)  
[Disk Diet](https://itunes.apple.com/br/app/disk-diet/id445512770?l=en&mt=12)  
[Markdown](https://itunes.apple.com/br/app/markdown/id727484953?l=en&mt=12)  
[Memory Clean](https://itunes.apple.com/br/app/memory-clean/id451444120?l=en&mt=12)  
[Money](https://itunes.apple.com/br/app/money-by-jumsoft/id402410845?l=en&mt=12)  
[The Unarchiver](https://itunes.apple.com/br/app/the-unarchiver/id425424353?l=en&mt=12)  
[Twitter](https://itunes.apple.com/br/app/twitter/id409789998?l=en&mt=12)  
[Wunderlist](https://itunes.apple.com/br/app/wunderlist-to-do-list-tasks/id410628904?l=en&mt=12)  
## Direct link
[Atom](https://atom.io/download/mac)  
[CCleaner](https://www.piriform.com/ccleaner/download?mac)  
[Composer](https://getcomposer.org/download)  
[DiffMerge](https://sourcegear.com/diffmerge/downloads.php)  
[Dropbox](https://www.dropbox.com/download?full=1&plat=mac)  
[ExifTool](http://www.sno.phy.queensu.ca/~phil/exiftool)  
[Git](http://git-scm.com/download/mac)  
[GitHub](https://central.github.com/mac/latest)  
[GitX](http://builds.phere.net/GitX/development/GitX-dev.dmg)  
[Google Chrome](https://dl.google.com/chrome/mac/stable/GGRO/googlechrome.dmg)  
[Google Drive](https://dl.google.com/drive/installgoogledrive.dmg)  
[MacKeeper](http://download.mackeeper.com/package.php?bundleId=29_2)   
[MySQL](http://dev.mysql.com/downloads/mysql)  
[PhoneExpander](http://phoneexpander.com/download)  
[Sequel Pro](http://www.sequelpro.com/download)  
[Skype](http://www.skype.com/go/getskype-macosx)  
[Transmission](http://www.transmissionbt.com/download)  
[VLC](http://www.videolan.org/vlc/download-macosx.html)  
