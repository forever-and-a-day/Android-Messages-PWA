# Android Messages PWA

An Android Wrapper application to create a somewhat native-feeling version of Google Messages for Web. Best used on tablets. 
Disclaimer: This application is unofficial and in no way is associated with Google. 

Version 1.0 <br>
![messagespwascreenshotV1final2](https://user-images.githubusercontent.com/10383240/122481917-74f86280-cf84-11eb-9b9e-870562caaab2.png)

## Why a Progressive Web App?
Despite my slight distaste for RAM-intensive web apps being used as native app replacements, this project was the easiest, laziest way for me to be able to text on my phone from my tablet without having the chrome navbar in my way and slowing my tablet to a crawl as 20 tabs load up on startup. More manga reading, less picking up my phone. 


## The Good
- Took less than a day to get most functionality working (aside from finishing icon/color touches)
- No Java experience required, I just replaced package names and URLs
- I added camera permissions to the app manifest for some reason. I was tired okay… didn’t realize that you scan the qr code with the phone like a dum dum
- The app (as of the first version) uses the original repo’s calculator icon so it’s an adventure to try to find it!
- I used spellcheck to review the readme this time!
- You’re beautiful! <3

## The Bad
- The default red theming looks kinda bad, I might fix it idk
- It’s a web app, so don’t expect speedy api fastness (pretty sure there’s no public api anyway, plus I can’t code) 
- This isn’t really an achievement, I just changed a few lines of code (forgot to change two of em so I was really frustrated at the compiler errors for an hour)
- Messages for web still has no search, one of its greatest features in the standalone phone app!
- Pretty sure gradle and target api stuff is all out of date, so good luck publishing this to the Play Store
- Unlike with a full mobile browser, browser-style message notifications are not supported yet. 
- No app splash screen dark mode switching 
- I don’t think you can clear the cookies, could be wrong. 


## How to build your own
- Get Android Studio 3.4+
- Clone/fork repository
- Make errors in console go away if possible
- Build App in Android Studio (build menu, build bundle/apk, then build apk. output in project dir/app/build/outputs/apk/debug)
- Take a break and relax :)

## How to Install
A) Enable unknown sources in the browser you downloaded the APK with, then open it with the Package Installer, or...
B) Connect your device using ADB then use `adb install dev.foreverandaday.messagespwa`

### Updates
Don’t expect much. Might merge upstream changes, but the og repo might have been abandoned so *shrug*

## License
[GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html)
