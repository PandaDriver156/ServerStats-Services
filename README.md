# **ServerStats-Services**
> - **List of tracked services for the Discord Bot ServerStats ✓** 
> - **Works by receiving data from statuspage.io and official service status servers**

![Line](https://github.com/TheChickenNagget/assets/raw/master/images/line.png)
# How to contribute?
> - _You can contribute by making a fork and writing new lines to the [```services.json```](https://github.com/PandaDriver156/ServerStats-Services/blob/master/services.json) file and making Pull Request_
> - Please check if the service you want to add already exists / was added before creating fork
> - **Copy the template below and edit by your own choice**
> - For Detailed Information [Make Sure to Check The wiki](https://github.com/PandaDriver156/ServerStats-Services/wiki/How-To-Contribute%3F)
------
### Explaining the JSON format
```shell
    "cloudflare": {
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
        "replace": true,
        "capitalization": "CloudFlare",
        "aliases": [
            "CF"
        ],
    },
```
------
> 1st line
> - First line is the name of the service, for example "cloudflare"
> - **The Name is required to identify the service**
------
> 2nd line 
> - Second line is the domain of the service, for example "circleci.statuspage.io" for CircleCI status page
> - Additional Examples: **"www.yh6f0r4529hb.statuspage.io"**, **"www.status.digitalocean.com"**
> - The Domain URL is **Required**

> <img src="https://github.com/TheChickenNagget/assets/blob/master/images/2.PNG"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" />
------
> 3rd line
> - Third line are elements. If elements aren't specified, all elements will be displayed, so in our case:
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
> - The ```elements``` are **Optional**
------
> 4rd line
> - Thumbnail, you need to select the service's icon/thumbnail, in this example we used cloudflare's icon url 
> https://cdn.discordapp.com/attachments/699617640099872848/699984616408350821/CloudflareLogo.png
> - You can select any image URL, but it has to be readable. We recommend images with the following extension: ```.png .webp .jpeg```
> - The Thumbnail Is **Optional**, But is Highly Recommended.
------
> 5th line
> - Replace, determines whether the service name should be replaced (with an empty string) in the component name. For example, Cloudflare has a property called "Cloudflare Sites and Services", but since replace is true, ServerStats only writes "Sites and Services", without Cloudflare
> - Replace is Optional, Replace does return ```false``` by default
------
> 6th Line
> - Capitalization, capitalization is optional (by default, only the first letter will be written with big letter)
------
> 7th Line
> - Aliases, example: We have service called ```epic games```, you can add alias ```epic``` to make it more easier for the users to find the service, Aliases Should Be **LowerCase** !!
> - Aliases are **optional**
------
> - If You got any issues or simply need help, feel free to **[create a new issue](https://github.com/PandaDriver156/ServerStats-Services/issues/new)** or [See our Wiki How to post an issue](https://github.com/PandaDriver156/ServerStats-Services/wiki/How-To-Post-An-Issue%3F)

![Line](https://github.com/TheChickenNagget/assets/raw/master/images/line.png)
