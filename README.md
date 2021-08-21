![logo](https://github.com/Botspot/pi-apps/blob/master/icons/proglogo.png?raw=true)
## Raspberry Pi App Store for Open Source Projects

## To install Pi-Apps
Pi-Apps x86 SUpports AMD64 And i386
```
wget -qO- https://raw.githubusercontent.com/MCRaspRBX/pi-apps-x86/master/install | bash
```
The install script ensures [YAD](https://github.com/v1cont/yad) is installed, creates two menu buttons, an auto-started updater, and a file (`/usr/local/bin/pi-apps`) that allows pi-apps to be run from terminal. Besides those, nothing is modified outside of the Pi-Apps folder.

<details>
<summary><b>To install manually</b> if you prefer to see what happens under the hood</summary>
To manually install Pi-Apps:
 
```
git clone https://github.com/MCRaspRBX/pi-apps-x86
~/pi-apps-x86/install
```
</details>

<details>
<summary><b>To uninstall Pi-Apps</b></summary>
To uninstall Pi-Apps:

```
~/pi-apps-x86/uninstall
```
</details>
### Basic usage
- This is the **main window**:  
![main window](https://github.com/Botspot/pi-apps/blob/master/icons/screenshots/main%20window.png?raw=true)  
Use the main window to select an app category you want to view. Open a category folder by double-clicking on it.  
- After selecting a category, you will see a list of apps:  
![app list](https://github.com/Botspot/pi-apps/blob/master/icons/screenshots/app%20list.png?raw=true)  
- If you double-click an app, or select and app and click ![info.png](https://raw.githubusercontent.com/Botspot/pi-apps/master/icons/info.png), you will see the **Details window**.  
![details](https://github.com/Botspot/pi-apps/blob/master/icons/screenshots/details%20window.png?raw=true)  
- Pi-Apps may display a notification on boot. If you choose to view the updates, the **updater window** will appear:  
![updates](https://github.com/Botspot/pi-apps/blob/master/icons/screenshots/updates%20available.png?raw=true)  
- Pi-Apps **Settings** can be configured by launching Menu -> Preferences -> Pi-Apps Settings.  
![settings](https://github.com/Botspot/pi-apps/blob/master/icons/screenshots/settings.png?raw=true)  

## To-do

- [X] Make **app creation system**. (completed with the `createapp` script)  
- [X] Add Pi-Apps to **Twister OS**. (completed on 11/2/2020 via the Twister 1.8.5 patch.)  
- [X] Support individual **32-bit** and **64-bit** install scripts.  
- [X] Allow **multiple apps** to be selected from the app list and be installed simultaneously.  
- [X] Add a **search function** to the app list. It's still experimental: to enable it, switch to **xlunch** in **Pi-Apps Settings** -> **App List Style**.
- [X] Break up the long app list with some **categories**.  
- [X] Add a new category containing all apps currently **installed**.

## Badge
If your application is on Pi-Apps, please consider adding this pretty badge/hyperlink to your README:  
[![badge](https://github.com/Botspot/pi-apps/blob/master/icons/badge.png?raw=true)](https://github.com/Botspot/pi-apps)  
Embed code:  
```
[![badge](https://github.com/Botspot/pi-apps/blob/master/icons/badge.png?raw=true)](https://github.com/Botspot/pi-apps)  
```

### Q&A with Botspot
 - Why did you develop Pi-Apps?  
> For a long time I have been saddened by how few people are aware of open-source RPi software projects. Many of these projects are extremely useful and beneficial, but there has never been a good way to distribute them.  
> The repositories don't host them, and they usually aren't advertised very well, so how will people find them?  
> Most people never find them.  
> One day I realized: Why not make an app store that specializes in all the community RPi software projects out there? It will help more users find the software, and at the same time it would provide a super simple way to install them.  
> (Which would you rather do - click a shiny Install button, or copy-n-paste a bunch of commands from a sketchy blog tutorial?)

 - How long did it take to program this?  
> About two weeks of nearly non-stop coding to lay the groundwork. Since then, I've continually optimized performance, fixed bugs, solved problems, added new features, and handled new app submissions.

 - Is Pi-Apps still under development?
> Sure is! Initial development is done for the most part, and I don't see any more [major features](https://github.com/Botspot/pi-apps#to-do) being added to Pi-Apps's core functionality. (besides maybe allowing `apt`-package apps in the future)
> But, there's always an app or two that need attention, and dozens of app requests. It's enough work to keep a *team* of developers busy.

 - Is Pi-Apps free?
> Absolutely! Pi-Apps is not a product or service: Anyone is welcome to use it; no-one should feel compelled/required to donate.

 - How can I help?
> - It's always nice to leave a kind word about Pi-Apps on forums and in comments. In addition to helping others find this useful software, you may just get added to [the hall of fame](https://github.com/Botspot/pi-apps#what-do-others-say-about-pi-apps)!
> - You can [donate](https://paypal.me/josephmarchand) if you'd like. The money goes to me (minus the Paypal fees), and helps support future open-source development. Some of the money goes to placing [bounties](https://github.com/ptitSeb/box86/issues/296) on apps that I'd like to see completed by someone else who has skills/time that I don't have.
> - You can look through the [list of app requests](https://github.com/Botspot/pi-apps/issues) and help create the scripts for them.
> - If you see someone complaining about a broken app on Youtube, Reddit, or Facebook, please encourage them to join the [Pi-Apps Discord](https://discord.gg/RXSTvaUvuu) or to [open an issue](https://github.com/Botspot/pi-apps/issues/new) to get the problem solved. (I'm not on those sites very often.)
> - You could help troubleshoot/diagnose issues others are having.
