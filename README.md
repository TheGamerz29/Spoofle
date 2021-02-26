![spooflesplash](https://github.com/TheGamerz29/Spoofle/raw/main/Screenshot%20(23).png)
# Spoofle
Google search without google trackers and ads.

## Features
- No ads or sponsored content
- No javascript
- No cookies
- No tracking/linking of your personal IP address\*
- No AMP links
- No URL tracking tags (i.e. utm=%s)
- No referrer header
- Tor and HTTP/SOCKS proxy support
- Autocomplete/search suggestions
- POST request search and suggestion queries (when possible)
- View images at full res without site redirect (currently mobile only)
- Dark mode
- Randomly generated User Agent
- DDG-style bang (i.e. `!<tag> <query>`) searches
- Optional location-based searching (i.e. results near \<city\>)
- Optional NoJS mode to disable all Javascript in results

<sup>*If deployed to a remote server, or configured to send requests through a VPN, Tor, proxy, etc.</sup>

## How do I use it?

There is two ways to use this search engine.

- Universal
---

1. Type in cutt.ly/spoofle in your search bar.<br>

- Use it as the default search engine(Chrome)
---

1. Click on the three dot button on the side of the browser.
2. Click on Settings.
3. On the side, click Search Engine.
4. Click on Manage Search Engine
5. Add "https://spoofle.herokuapp.com/search?q=%s" to the list by clicking the add button as shown in the screenshot.<br>
---
![spoofle1](https://github.com/TheGamerz29/Spoofle/raw/main/Screenshot%20(21).png)
---
6. Click on add
7. Find Spoofle then click on the three dot button aside from it.
8. Select Make Default.
And It's done, You will start surfing with Spoofle!
---

## How to deploy it for private use?

First click the button down below:<br>
<br>
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/benbusby/whoogle-search/tree/heroku-app)<br>
<br>
You may need to create an account if you don't have any.<br>

Second, give any name to the app.<br>

Third, click deploy. Wait until the process is done.

Then repeat the [process](https://github.com/TheGamerz29/Spoofle#how-do-i-use-it). Except, change the name to from spoofle.herokuapp.com to <your app name>.herokuapp.com.<br>

And it's done! you have your own private Spoofle!

---

If the the search engine is giving you errors, please report it at issues. I will resolve it as fast as possible

---

Spoofle won't be possible without benbusby whoogle-search project
