# Display Baidu Search Suggestions for China's Provinces (Sheng's) on a Map
## What it does
This webpage displays Baidu's search suggestions (aka. auto complete) for each [province]+[user search word] combination. It's an indication of what people frequently search about a topic for each province of China.  
Live demo here: http://guozhen.li/Map-China-XSheng-BaiduSearchSuggestions/
## How it works
Once you input something in the text input box, the webpage combines each province's name and your input word, and queries Baidu's search suggestion API for suggested words. These suggestions from Baidu are then displayed at each province's geographic location.  

## Helpful resources
- This work is inspired by the ["Why [state] is so..." map of US](https://io9.gizmodo.com/autocomplete-map-of-the-u-s-asks-why-your-state-is-so-1509284418), and I decided to do an interactive version for China.
- I learned how to use Baidu Search Suggestion API from [jsonp跨越请求百度搜索api 实现下拉列表提示](http://www.yaoguangkeji.com/a_obQ6O5G3.html)
- The background map of China is a product of my other project: [D3-China-Map](https://github.com/guozhenli/D3-China-map)
- Chris Nielsen's [JSON visualization tool](http://chris.photobooks.com/json/default.htm) is extremely helpful when working with JSON data.
- [This blog](http://www.cnblogs.com/woider/p/5805248.html) lists search word suggestion APIs from many other search engines (Google, Bing, etc.)
