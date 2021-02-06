## Misc
### Unsafe downloads
```md
> My web browser is warning me that my download __may harm my computer__. Is it safe to continue?
When download executable files such as `.exe` or `.jar`, your computer will warn you because that file type can do many things upon gaining permission. However, this **does not make it unsafe**. As long as you are downloading your file, such as the minecraft `server.jar` from the **official website**, you do not need to worry. If you are downloading other things such as mods, **__verify that the website is trustworthy__**, often by checking for a lock icon next to the url, as well as asking around if that website has been used by others. It is recommended to use <https://curseforge.com> for downloading mods.
```
### Credits: Thonk

### Java payment issues
> 1. Try a different browser/device
> 2. Call your bank to make sure international transactions are authorized
> 3. Try paypal
> 4. Go to minecraft.net/redeem and click on the yellow strip to find an authorized retailer in your area that sells gift cards. (US/UK/France/Germany users can buy gift cards on Amazon; make sure you buy the correct java/bedrock card)
### Credits: Shiko, David Wang

### MC open, but not visible: Windows Fix
```md
Hold down the `Shift` key, then right-click on the **Minecraft** icon in the Windows taskbar. On the resulting pop-up, select the `Move` option. Begin pressing the arrow keys on your keyboard to move the invisible window from off-screen to on-screen.
```
### Credits: Thonk

### Resetting network adapter
```md
Windows key > type 'cmd' > right click command prompt > run as admin, then run the following commands.
`netsh winsock reset` and press Enter.
`netsh int ip reset` and press Enter.
`ipconfig /release` and press Enter.
`ipconfig /renew` and press Enter.
`ipconfig /flushdns` and press Enter.
```
### Credits: David Wang

### Password, minimum requirements
```md
This is a known bug, see <https://bugs.mojang.com/browse/WEB-3606>, there is currently no fix.
```
### Credits: Elephant_1214

### RAM Bamboozlement
> Q: How much RAM should I allocate to Minecraft?
> A: Before answering, we'd like to first inform you of the very common misconception that more RAM = better. This is NOT true, and in fact, this can result in overall worse performance if you allocate too much RAM to the game. This is due to how Java handles something called "garbage collection", which is basically how the game deals with data it is no longer actively using. When giving Java too much RAM, this means the garbage collector will have much more data it needs to remove all at once, which results in massive lag spikes and stuttering framerates.
> 
> With that said... it depends. The amount of RAM you need to allocate will depend on how many mods you're using, your preferred render distance, and various other factors. You should only allocate enough RAM to the point where Minecraft's memory usage tops out at ~70%, and never falls below ~50%. You can view Minecraft's memory usage by pressing F3 while in-game, and looking at the top-right of the screen. You should see a line starting with "Mem:" followed by the percentage.
![Imagine of message](https://media.discordapp.net/attachments/769466695668465665/798775702241017876/unknown.png)
### Credits: Discord_

## WIP

