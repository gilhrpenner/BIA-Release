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
![England](https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/120/apple/271/flag-england_1f3f4-e0067-e0062-e0065-e006e-e0067-e007f.png =20x20) English is our also our official language

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

BIA has a builtin feature called kill-shit, whenever you lose connection with your proxy server we won't allow any requests to Tribal Wars, thus protecting your identity.

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

### Testing mode

![Farm](https://api.bia.gg/en/farm1.png)

The testing mode enables you, the user, to be in complete control of your game! Are you a visual learner and, instead of reading instructions, you prefer to change the settings and see them happening in real-time? This feature is for you! With our testing mode, you can watch BIA farming without sending real attacks. Our testing model will show you **almost** everything as if it was real attacks, we will take in consideration your home units, all of your settings and we will highlight the buttons BIA would be clicking as if it was a real attack.

### Basic settings

The basic settings are almost the same ones as Tribal Wars offers you, this section is important so BIA can validate your choices and make sure we will farm the way you want.

### Safety settings

No human can farm 24 hours a day, 7 days a week and 365 days a year, with that being said, we enable you to mimic human-like behaviour and take breaks. For safety reasons, we won't be going further in detail about how our algorithm works, but we strongly encourage you to make use of this feature and set random breaks to prevent being caught. Even though using BIA decreases the quantity of captchas challenges you'd be presented it doesn't take more than a monkey's IQ to figure out no one can ever farm without breaks.

### Farming models

![Farm](https://api.bia.gg/en/farm2.png)

Blah blah

### Wall settings

![Farm](https://api.bia.gg/en/farm3.png)

Blah blah

### Advanced settings

![Farm](https://api.bia.gg/en/farm4.png)

Blah blah

## Scavenging

Blah blah

## Schedule Commands

Blah blah

## Interactive Map

Blah blah

## Auto Tagging

blah blah

## Auto Update

Blah blah

# Safety Considerations

BIA blah blah
