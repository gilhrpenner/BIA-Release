# BIA Assistant

Welcome to BIA Assistant, the best co-player one can ever wish! ![BIA](https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/120/samsung/265/woman-supervillain_1f9b9-200d-2640-fe0f.png =30x30)\
In this section, you will find all information you need to get started and configure your account.

# Prerequisites

#### Windows

-   Windows 7 and later are supported
-   Both x86 and amd64 (x64) binaries are provided for Windows. Please note, the ARM version of Windows is not supported
-   Pentium Dual-Core or later, preferably an i3 or better
-   Minimum of 2GB RAM, 4GB for a better experience

#### Mac OS

-   macOS 10.10 (Yosemite) or later
-   Only 64-bit binaries are supported
-   The new Apple M1 Chip is not yet supported, but we are working to support it soon
-   Any 64-bit processor Intel processor
-   Minimum of 2GB RAM, 4GB for a better experience

#### Linux

-   Ubuntu 12.04 and later, Fedora 21 or Debian 8
-   An Intel Pentium 4 CPU or later that is SSE2 capable
-   Minimum of 2GB RAM, 4GB for a better experience

# Internationalization

BIA is ready to be played on any Tribal Wars server and any world with the exception of Speed worlds.\
We also support many languages and we are always looking for people that are passionate about our bot and wants to improve translations or even translate BIA to a new language.

![Brazil](https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/120/apple/271/flag-brazil_1f1e7-1f1f7.png =20x20) Brazilian Portuguese is our official language\
![England](https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/120/apple/271/flag-england_1f3f4-e0067-e0062-e0065-e006e-e0067-e007f.png =20x20) English is also our official language

Here are some of the languages we currently support

![CZech](https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/120/apple/271/flag-czechia_1f1e8-1f1ff.png =20x20) Czech\
![Germany](https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/120/apple/271/flag-germany_1f1e9-1f1ea.png =20x20) German\
![Spain](https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/120/apple/271/flag-spain_1f1ea-1f1f8.png =20x20) Spanish\
![France](https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/120/apple/271/flag-france_1f1eb-1f1f7.png =20x20) French\
![Italy](https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/120/apple/271/flag-italy_1f1ee-1f1f9.png =20x20) Italian\
![Poland](https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/120/apple/271/flag-poland_1f1f5-1f1f1.png =20x20) Polish\
![Slovakia](https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/120/apple/271/flag-slovakia_1f1f8-1f1f0.png =20x20) Slovak\
![Turkey](https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/120/apple/271/flag-turkey_1f1f9-1f1f7.png =20x20) Turkish

If you would like us to support a different language please get in touch.

# Features

We are constantly improving and adding new features. Our goal is to offer solutions to automatize all in-game actions, but also to offer tools to improve your game experience.

## reCAPTCHA Solver

reCAPTCHA is a Captcha System that helps services such as Tribal Wars to distinguish between human and automated bots like BIA. reCAPTCHA uses an advanced risk analysis algorithm that takes every single action you do inside the game and ranks how likely the actions happening is coming from a bot. A challenge is then presented and it blocks the game from continuing. BIA does have a solution for these challenges, we not just optimize it such that these challenges are shown with less frequency but we also mimic human-like behaviour thus reducing captcha challenges. BIA also solves any type of captcha challenges, be it image, audio for text.

## Tribal Wars Accounts

With BIA you can have up to 5 different Tribal Wars accounts registered, those account can be in any world and in any server! We do not constraint you in playing with a single account. Our only requirement is that only one account can be active at a time. If you do require access to more than one account running at the same time (multiple instances of BIA) then an extra charge will be applied.

::: tip
Did you know other bots prevent you from using more than one account?
At BIA we are proud to give you freedom to play as you wish.
:::

![Accounts](https://api.bia.gg/en/accounts.png)

## Realtime-Sync

Do you play with co-players? Or perhaps you play at home and at the office? \
If you answered yes to any of the above we've got a feature just for you! Enjoy realtime-sync between computers, you schedule a command or change a setting and it is broadcasted to all BIA sessions logged on your account. This unlocks endless possibilities!

::: tip
Did you know some servers do not allow co-players?
You can use Realtime-Sync to bypass this restriction.
:::

With Realtime-Sync multiple people can connect to the same account at the same time without temparing cookies, you can have multiple people playing virtually from anywhere in the world and Tribal Wars won't ever know about it. BIA also handles all the browser fingerprinting and sync user-agent headers to protect your identity as much as we possibly can.

::: warning
Any actions within the builtin browser is leaking your IP address!
therefore the usage of proxy is highly recommended in case of co-players.
:::

![Main](https://api.bia.gg/en/main.png)

## Proxy Ready

BIA supports IPv4 and IPv6 proxies, though you should give preference to IPv4 since Tribal Wars doesn't quite support IPv6 tunnels just yet. You can still use IPv6 proxies but some images that are not cached previously will not render properly.

BIA has a builtin feature called kill-switch, whenever you lose connection with your proxy server we won't allow any requests to Tribal Wars, thus protecting your identity.

![Main](https://api.bia.gg/en/proxy.png)

::: tip
Did you know that a high-quality proxy can reduce your delay?
:::

::: warning
Tribal Wars ban players who use proxy! Be sure to get a proxy with a static IP
so they won't figure out you are using a proxy.
:::

## System Logs

BIA has 2 categoris of logs `Next actions` and `System logs` to give your the maximum information you need to know exactly what is going on.

**Next actions** will tell you when the next task will happen, and when something is happening we also inform you.
**System logs** will log everything that happens in your account and we think it is important for you to be aware of!

![Main](https://api.bia.gg/en/logs.png)

::: warning ATTENTION
The time displayed besides the logs are your local time!
We only use server-time clock when it is important for the game, such as Scheduled commands.
:::

## Local Settings

BIA has a set of local settings to allow you to customize BIA just the way you like.\
Put an end to the endless fights with your co-player over light and dark mode, have it the way you want!

![Main](https://api.bia.gg/en/localSettings.png)

## Built-in Browser

Our builtin browser allows for quick and easy access to the game, but don't you worry, we do not force you to use our browser, in fact we allow for quick export of your session cookies so you can use any browser you want, and we even offer a solution to sync user-agent headers so it is as if you were using the exactly same browser.

![Browser](https://api.bia.gg/en/browser.png)

::: tip
Did you know you can install the chrome extension `EditThisCookie` and import the cookies
that are generated on BIA once you login once your account?
:::

## Organizational Groups

BIA uses groups to define and control your account, currently we have two default groups which are `Farm AS` and `Scavenging` and the villages in those groups will be farmed with and sent for scavenging parties! You can also create groups for better organization of your account, define which villages will be recruiting and many more.

![Groups](https://api.bia.gg/en/groups.png)

We plan on adding many more functionalities and all of them will make use of groups, so the earlier you start organizing your villages the better understanding to set up your account you will have.

## Auto Farm AS

We are **excited** and **proud** to say we have `the most advanced farming tool` for Tribal Wars!\
Our primary concern is to allow the user to adjust the settings just the way they want because most bots out there are very limited and pretty much all of their users farm on the same way because they just can't personalize things properly.

![Farm](https://api.bia.gg/en/farm1.png)

### Testing mode

The testing mode enables you, the user, to be in complete control of your game! Are you a visual learner and, instead of reading instructions, you prefer to change the settings and see them happening in real-time? This feature is for you! With our testing mode, you can watch BIA farming without sending real attacks. Our testing model will show you **almost** everything as if it was real attacks, we will take in consideration your home units, all of your settings and we will highlight the buttons BIA would be clicking as if it was a real attack.

### Basic settings

The basic settings are almost the same ones as Tribal Wars offers you, this section is important so BIA can validate your choices and make sure we will farm the way you want.

### Safety settings

No human can farm 24 hours a day, 7 days a week and 365 days a year, with that being said, we enable you to mimic human-like behaviour and take breaks. For safety reasons, we won't be going further in detail about how our algorithm works, but we strongly encourage you to make use of this feature and set random breaks to prevent being caught. Even though using BIA decreases the quantity of captchas challenges you'd be presented it doesn't take more than a monkey's IQ to figure out no one can ever farm without breaks.

::: info
Although BIA mimics human-like behaviour it is still in your best interest not to
abuse its functionalities, be smart and play safe.
:::

![Farm](https://api.bia.gg/en/farm2.png)

### Farming models

You can choose one farming model, a combination of multiple farming models or all farming models to improve your performance.

-   Model A is your main and primary model
-   Model B has two functionalities and is your secondary model
    -   Farm when A is not an option
    -   Focus reports with full haul
-   Model C is the dynamic model from Tribal Wars but with improved functionality
-   Wall models
    -   We will go in further details in the next section

Though Model A is your primary model, BIA will first check if a given village meets the criteria for your Wall models, if not then we advance to your Model C, Model B and finally Model A. Therefore, your primary model is the one that if everything else doesn't meet the criteria you defined then it will send Model A and if Model A is not an option then it means you no longer have units and it is time to switch villages.

Do not let the above explanation intimidate you, reading the in-bot instructions you will easily understand, and if you still have questions you can always refer to our [testing mode](#testing-mode).

### Wall settings

![Farm](https://api.bia.gg/en/farm3.png)

With wall settings, you can rest assured your macro-farming won't have too many losses. If you choose to enable wall settings you are presented with a couple of options.

-   You can choose to skip a barbarian village in case you don't have enough troops to attack the wall.
-   If your village has 10 or more catapults it will attack the Headquarters to slow down the development of walls.
-   Send 5 spies if the report is yellow or red.

Besides the 3 basic models for wall with level 1, 2 or greater or equal to 3 you can also define what is the maximum distance your RAM units will be able to travel to.

### Advanced settings

![Farm](https://api.bia.gg/en/farm4.png)

The advanced settings give you greater control over how the farming assistant will behave, here are some of our settings but keep in mind we are constantly updating and adding new features.

-   Delay between attacks
    -   When you define a range betweem two numbers you are mimicing human behaviour, no one can send attacks so precise, so make usage of this feature.
    -   Tribal Wars by default limits 5 attacks per second which means you can only send one attack every 200 ms, so based on that you can define a range between 200 ms up to 3 seconds, the slower you send attacks the better it is for you. Sending too many attacks too fast might increate the number of captcha challenges you will be presented. Each captcha takes about 1 min but during the night or high-usage hours it can take up to 5 minutes.
-   Delay before switching villages
    -   If disabled BIA will switch to the next attack village immediately after the last report is attacked, so if you have many villages near each other it might be in your best interest to set a small delay just so attacks don't overlap. He have another feature that also helps to address this issue.
-   Force village switch
    -   Do you have many farming villages and need to cycle through them very fast? Enable this and you set how many seconds BIA will spend in each farming village regardless of how many barbarians villages are left to be attacked.
-   Delay before a new cycle
    -   Once BIA has sent farming attacks from all of your farming villages it is considered a farming cycle, here you can define how long after each cycle BIA will wait before starting a new cycle. This is also known as cooldown period.
-   Max ongoing attacks
    -   One of our exclusive settings compared to other bots and scripts, you can define how many ongoing attacks is allowed per village. Only your own attacks are considered for this feature.
    -   You can use this so that you don't focus most of your units on nearby villages, if you define 5 max ongoing attacks, for example, your units will be more evenly spread between all barbarian villages.
-   Min attacks possible
    -   If one of your farming villages cannot attack at least 10 attacks, for example, with model A BIA will skip that village during the current farming cycle and focus on other farming villages.
-   Do not repeat attacks
    -   Another exclusive feature for BIA users, you can define the minimum time between attacks, this way if you have many villages near the same barbarian village you won't waste your units all on the same village. This feature is also exceptionally useful for when a new captcha challenge is shown, in case of having to restart the farm, BIA won't repeat attacks on the same barbarian village.
    -   This feature is highly recommended whenever you activate the checkbox to `Include villages you are currently attacking`
-   Order villages by time of report
    -   The title is pretty much self explanatory, you can choose the order of which the villages will be listed, from ascending to descending or vice versa.
    -   This flag will order the villages by the `Time` field presented on Farm AS page.
-   Fail-safe
    -   Occasionally errors can occur, could be a network issue, a failed captcha or even a computer error that causes Farm AS to halt, but don't you worry, you can handle these edge cases with our fail-safe system and make sure your farm won't stop without your consent.

::: info
BIA automagically pauses Farm AS while a command is in progress
:::

## Scavenging

Add the villages allowed to be sent on scavenging parties on `Scavenging` [group](#organizational-groups) and then define which units you are allowed to be used.\
Then sit back, and let BIA do the rest, with our algorithm we will evenly distribute the units between all levels of scavenging such that the units return home together. Besides that, with our advanced settings you can choose how many units of each type will be left behind, this way you can reserve them fore more urgent cases, which as a quick snipe.

Our algorithms will handle everything else, BIA will watch when the next party needs to be sent out and will do that as effective as possible.

![Scavenge](https://api.bia.gg/en/scavenge.png)

## Schedule Commands

Super precise commands, with a stable connection you can send commands as precise as 4 ms. Our beautifully designed system is optimized for efficiency and precision. All commands are schedule using server time no matter your current time zone. Do you play with co-players? We've got your back, [sync](#realtime-sync) commands between computers independently of time zones.

With our commands table you can easily find, check the status, edit and delete commands. We also include a unique and helpful badge that indicates the difference in seconds between each command so you can easily identify commands that are going to be sent too close. Humans can't sent precise attacks within seconds apart of each other, BIA can! So keep that in mind and don't abuse the system, while BIA is safe and invisible you can still get caught you if abuse its capabilities.

![Commands](https://api.bia.gg/en/commands.png)

We also have the most advanced and easy-to-use system, you can create nobletrains, set catapult target and much more.\
You can also use `*` to indicate that BIA should use all units of a given type.

For instance, let's say we have 6000 axeman, 3000 light cavalry and 4 snobe, here is how you can create the perfect nobletrain.

| Command number | Axeman | Light Cavalry | Snobe |
| :------------: | :----: | :-----------: | :---: |
|   Attack #1    |   \*   |      \*       |   1   |
|   Attack #2    |  200   |      100      |   1   |
|   Attack #3    |  200   |      100      |   1   |
|   Attack #4    |  200   |      100      |   1   |

\
With the instructions above BIA will calculate that commands 2-4 will use 600 axeman therefore the first command will be sent with 5400 axeman, simmilarly the same is valid for light cavaly, the first command will be sent with 2700 light cavaly because commands 2-4 will need 300 in total, so you command after sent will look like this:

| Command number | Axeman | Light Cavalry | Snobe |
| :------------: | :----: | :-----------: | :---: |
|   Attack #1    |  6400  |     2700      |   1   |
|   Attack #2    |  200   |      100      |   1   |
|   Attack #3    |  200   |      100      |   1   |
|   Attack #4    |  200   |      100      |   1   |

\
Be smart and let BIA do the hard-work for you!

![Commands](https://api.bia.gg/en/commandsCreate.png)

Are you one of those people that like to schedule tons of similar attacks and then just edit something here and there? We have a functionality just for you! Meet our commands editor, with this you can mass-edit commands in a very simple way.

![Commands](https://api.bia.gg/en/commandsEdit.png)

Future methods to improve what is already great are to come, alongside with other commands modality such as fake commands, mass commands, recurring commands and a super advanced command creation system. Stay tuned for more.

## Interactive Map

Builtin interactive map, like Tribal Wars's map but better.

Our map is still in its infance and has yet to grow in terms of functionalities, but you can already select villages, filter it to your liking and export those coordinates, or create commands! The best part is that we use real-time data, not data from 6 hours ago! And if your computer struggles to render it you can even disable the trees and rivers from the map.

We have big plans for it, and we are sure you will love it.

![Map](https://api.bia.gg/en/map.png)

::: info
We use WebGL to render our map, for that you need to have Hardware Acceleration enabled
:::

::: info
Some windows servers might not support our map
:::

## Auto Tagging

Simple but useful auto tagging system, rest assured we will be tagging all commands.
You can enable alarms and desktop notifications so you will know and be able to prepare to defend yourself.

-   You can set alarms for normal incomings
-   You can also set alarms for nobleman incomings
-   You can repeat the alarm till you disable it

All commands logged will show the processed time in your local tme

![Map](https://api.bia.gg/en/incomings.png)

::: warning ATTENTION
Auto tagging only works for commands that you cannot see the troops, so if you
try to attack yourself or an ally with shared commands attacks you, BIA will not tag.
:::

::: warning ATTENTION
Commands sent while BIA was inactive will not be tagged and will me marked with a red text
:::

## Auto Update

You will always be notified of new updates and when it is time, BIA will download the update while idle so that it doesn't affect timing precisions and will have it ready to install whenever you are ready to go.

# Safety Considerations

BIA behaves the same way as us humans, navigates through Tribal Wars by clicking links, simulates things and invokes events that happen on a page just like it does when we real humans do things. It is worth noting that humans can't send 20 attacks in 1 second, but BIA does. Similarly, Tribal Wars allows sending 5 attacks per second or 300 attacks per minute. Humans could probably do that in the Farm AS page for a few minutes, but once you extrapolate and do that non-stop for hours it is clear that you are using a bot and even someone like an admin (yes, it is supposed to be offensive because no smart person would work for free as admins of a game to a company like Inno) can figure out you are using a bot.

Remember to use BIA Assistant with common sense, we offer tons of features that prevent patterns that are easy to detect you are using a bot.
