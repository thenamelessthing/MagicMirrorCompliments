> ⚠️ MagicMirror-Compliments is deprecated, please consider creating your own fork.

# MagicMirror-Compliments [![No Maintenance Intended](https://unmaintained.tech/badge.svg)](https://unmaintained.tech/)
I wanted the MagicMirror compliments in my own language, so here are some translations. Feel free to add your own language!

## How to add the compliments to your MagicMirror
### Step 1: Check for supported languages
At the moment there are just four languages: 
- English ```en.json```
- French ```fr.json```
- French Canadian ```fr_ca.json```

### Step 2: Change config
Open your config:
```bash
sudo nano ~/MagicMirror/config/config.js
```
Scroll till you can see the compliments module. It looks something like this:
```javascript
{
    module: "compliments",
    position: "lower_third"
},
```
Change it to:
> ⚠️ MagicMirror-Compliments is deprecated, please consider creating your own fork and using that url as ```remoteFile```.
```javascript
{
    module: "compliments",
    position: "lower_third",
    config: {
        remoteFile: "https://github.com/thenamelessthing/MagicMirrorCompliments/main/fr_ca.json"
    }
},
```
Change ```en.json``` to your own language like ```fr.json``` or ```fr_ca.json```. The abbreviation of your language can be found above.

## Credits
French language by [kartnico](https://github.com/kartnico).
French Canadian language by [thenamelessthing](https://github.com/thenamelessthing)
# Visit MagicMirror!
[MagicMirror](https://github.com/MichMich/MagicMirror)
