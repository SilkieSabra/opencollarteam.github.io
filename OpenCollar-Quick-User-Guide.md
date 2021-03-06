[Complete User Guide](https://github.com/OpenCollarTeam/OpenCollar/wiki/Complete-User-Guide) | [Distributors and Design Partners](https://github.com/OpenCollarTeam/OpenCollar/wiki/OpenCollar-Distributors-and-Designers) | [Social Partners](https://github.com/OpenCollarTeam/OpenCollar/wiki/OpenCollar-Social-Partner-Locations)
# Getting Started
Open the Collar Menu by touching the collar or sending a chat command with your prefix.  If you have not set an owner you are the default owner and can access all parts of the collar.  Most collar functions are available in the collar menu. 

### Chat Commands
Chat Commands are typed into the local chat line. Many of the menus and submenus in OpenCollar can be called by using chat commands of the same name as the menu button.

Local chat is on channel 0. If you don't want your command to be visible in local chat, call your menu by typing /1 [prefix] menu. This sends the command to channel 1 instead and you don't see it in local chat.

### Prefixes

Your default prefix is the first two letters of your user name.  Prefixes direct collar commands only to wearers with those two initials.  It can be changed by the collar owner only.  Wearers who have set an owner cannot change the prefix unless OwnSelf is checked.  

**Using your prefix**:  Suppose your name is Joe Zipcode (joezipcode).  To call the menu you would type:  jo menu . If you want to send the command to channel one it will be /1 jo menu . In this guide we will represent the calls [prefix] menu and so on.

[More About [Prefixes, Chat Commands and Other NonMenu Functions](https://github.com/OpenCollarTeam/OpenCollar/wiki/Prefixes,-Chat-Commands-and-Other-Non-Menu-Functions)]
 
## Using Your Collar

When you open the main menu you will see buttons that go to all the different collar menus.  Each of these menus is documented in the complete User Guide.  For this Quick Start, you need to know enough to make a few basic choices about how you will use your collar.

### Access
You are wearing a collar because you want someone else at some time to be able to control your avatar.  The degree of control you give is up to you.  To give someone else access to your collar, open the collar menu and press access, or type [prefix] access.  

In the Access menu you can add Owners, Trusted, or set group or public access.  If you set an owner you lose your default owner access to your collar. It is best not to set an owner till you are sure you want to give that person full control over your collar. If you want to retain owner level control on your collar, press OwnSelf before adding an owner.  Your owner however can uncheck that if they choose to.  More about [Access](https://github.com/OpenCollarTeam/OpenCollar/wiki/Access) here.

### Safeword

Your collar has a safeword chat command that is built into every menu in the collar.  Using the safeword will reset all collar restrictions, without changing the collar access.  The collar safeword also clears the relay.

The default collar safeword is RED, all caps.  You can also type it on channel 1 [ /1 RED ] or in ooc brackets which cannot be blocked by an RLV command [ ((RED)) ].  See [NonMenu Functions](https://github.com/OpenCollarTeam/OpenCollar/wiki/Prefixes,-Chat-Commands-and-Other-Non-Menu-Functions) for more.

### Runaway

If you find you must clear an owner, you can do that by pressing the Runaway button in the Access menu, or typing [prefix] runaway.  This will wipe the access list and reset all collar functions to default.

## About RLV

RLV (Restrained Love Viewer) is a set of permissions coded into the viewer, that allows other avatars limited control over some viewer functions. There are several approved third party viewers that allow you to enable / disable RLV. Among the most popular for many users are Firestorm, Restrained Love Viewer, and Singularity.

OpenCollar uses RLV to enforce the Collar Lock in the Main Menu.  The rest of the RLV functions in the collar can be found in the RLV menu.  Push Clear All in the RLV menu to clear these restrictions (not available to wearers who are not self owned).  The collar Relay converts RLV commands from objects the wearer does not own. Relay permissions are not affected by the Access settings. See more in the Complete User Guide [RLV](https://github.com/OpenCollarTeam/OpenCollar/wiki/RLV)and [Relay](https://github.com/OpenCollarTeam/OpenCollar/wiki/Relay) pages.

Please remember that one of the most basic safety features about RLV is your ability to turn it off and on in the viewer. Any RLV restriction can be cleared by turning off RLV and relogging; or logging on in the official SL Viewer. Some groups claim to use "extreme RLV" that cannot be turned off.  This is not possible in any approved third party viewer.  Beware of downloading any code that claims to alter this basic safety function.  