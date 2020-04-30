# ServerStats-Services
#### List of tracked services for the Discord bot ServerStats
------
# Contributing
#### You can contribute by making fork and writing new lines to the ```shell sites.json``` file 
> Copy the template below and edit them by your own choice!
------
### Explaining the JSON format
```shell
{
    "Cloudflare": {
        "domain": "yh6f0r4529hb.statuspage.io",
        "elements": [
            "Cloudflare Sites and Services",
            "Africa",
            "Asia",
            "Europe",
            "Latin America & the Caribbean",
            "Middle East",
            "North America",
            "Oceania"
        ],
        "thumbnail": "https://cdn.discordapp.com/attachments/699617640099872848/699984616408350821/CloudflareLogo.png",
        "replace": true
    },
```
------
> 1st Line
> - First Line is the name of the service, for example "cloudflare"
------
> 2nd Line 
> - Second Line is the domain of the service, for example, we use "circleci.statuspage.io" for CircleCI status page
> - Additional Examples: **"www.yh6f0r4529hb.statuspage.io"**, **"www.status.digitalocean.com"**
------
> 3rd Line
> - Third line is the line of the element's, if elements isn't specified, all elements will be displayed so in our case:
<img src="https://github.com/TheChickenNagget/assets/blob/master/images/Capture.PNG"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" />
     
        "elements": [
            "Cloudflare Sites and Services",
            "Africa",
            "Asia",
            "Europe",
            "Latin America & the Caribbean",
            "Middle East",
            "North America",
            "Oceania"
        ] 
        
> - We have to select all elements to exclude other elements like "past incidents" and more, example above.
------
> 4rd Line
> - Thumbnail, you need to select the service's icon/thumbnail, in this example we used cloudflare's icon url 
> https://cdn.discordapp.com/attachments/699617640099872848/699984616408350821/CloudflareLogo.png
> - You can select any image url, BUT it has to be readable URL, we recommend images with following extension: ```.png .webp .jpeg```
------
> 5th Line
> - Replace, replace determines whether the service name should be replaced (with an empty string) in the component name. Fox example, Cloudflare has a property called Cloudflare Sites and Services, but since replace is true, ServerStats only writes Sites and Services, without Cloudflare
