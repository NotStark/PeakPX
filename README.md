# PeakPX
Unofficial python wrapper for PeakPX.com API


## Installation
```pip install PeakPxApi```

## Usage
```python
from PeakPxApi import PeakPx

px = PeakPx()

#get wallpapers
wallpapers = px.get_wallpapers() #it will return a list of wallpapers

#pagination 
wallpapers = px.get_wallpapers(page=2) #by deafult its one

#search wallpapers
wallpapers = px.search_wallpapers(query='one piece') #you can also paas a page parameter here like page =2 by default its 1
```


## Sponsor this project

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/NotStark)
