All you need to know at Riverside. Nothing is official here other than the offical part.
<br>
This is a global event. Lets stay strong and help each other.

## Official resources

* National
  * [CDC](https://www.cdc.gov/coronavirus/2019-nCoV/index.html)
  * [WHO](https://www.who.int/emergencies/diseases/novel-coronavirus-2019)
* California
  * [EDD(Employment Development Department)](https://www.edd.ca.gov/about_edd/coronavirus-2019.htm)

* Riverside county
  * [Riverside County Announcement](https://www.rivcoph.org/coronavirus), [link 2](https://riversideca.gov/press/information-regarding-covid-19-coronavirus)
  * [LA county](http://www.publichealth.lacounty.gov/media/Coronavirus/)
  * [KTLA 5](https://www.youtube.com/user/KTLA/videos) KTLA, channel 5 in Los Angeles, covers breaking news, weather and traffic for L.A., Orange, Riverside, San Bernardino and Ventura counties.

* UC Riverside
  * [Campus COVID update](https://ehs.ucr.edu/coronavirus) 
  * [Campus announcement](https://insideucr.ucr.edu/announcements)
  * Keep teaching [iLearn](https://keepteaching.ucr.edu/ilearn), [TA resources](https://keepteaching.ucr.edu/ta-resources) (Zoom pro license provided)
  * [UCR微信公众号](https://open.weixin.qq.com/qr/code?username=gh_7d6f6ca60162)

## Nonofficial Resources
* General
  * [awesome coronavirus](https://github.com/soroushchehresa/awesome-coronavirus)
  * [Open Source COVID-19](https://weileizeng.github.io/Open-Source-COVID-19/)
  * [cases nearby search](https://www.coronainusa.com/?from=groupmessage&isappinstalled=0)
* Local(Riverside)
  * [Riverside抗疫群](https://raw.githubusercontent.com/WeileiZeng/COVID-Riverside/master/assets/riverside-covid.jpeg) [UCR抗疫群，Riverside救助群](https://raw.githubusercontent.com/WeileiZeng/COVID-Riverside/master/assets/wanshiwu.jpeg)，洛杉矶抗疫群
  * [美国抗疫日记]https://mp.weixin.qq.com/s/jrsfKU0s0OAABcPiaa-BLA)
  
## Need help?
* Medical
  * [UCR’s Student Health Center](https://studenthealth.ucr.edu/)
  * [Riverside Community Hospital](https://riversidecommunityhospital.com/)
* Safety
  * [UCPD](https://police.ucr.edu/)
  * [Riverside Police Department](https://www.riversideca.gov/rpd/)

## Submit information
* [open an issue](https://github.com/WeileiZeng/COVID-Riverside/issues) 
* chat in wechat


## Riverside Timeline
{% for day in site.data.timeline %}
* {{ day.date }}  {% for event in  day.events %}
  * <em style="color:#D0CE3B">{{ event.tag }}.</em> {{ event.description }} {% endfor %} {% endfor %}


## Riverside Cases
California (March 19): 1028 confirmed, 18 death.<br>
Riverside (March 17): 16 confirmed, 3 death.
<br>
Source from [1point3aches.com](https://coronavirus.1point3acres.com/#map)


{% for day in site.data.cases %}
* {{ day.date }}  {% for case in  day.cases %}
  * {{ case.description }}  {% endfor %} {% endfor %}



## 去哪里买菜？
记录一些当天的案例，不同地点时段都有可能情况不一样，仅供参考。如果你最近有出门，欢迎[留言](https://www.weileizeng.com/news/1992/06/29/contact/)给大家参考。
* Mar 17
  * 罗兰岗各大超市早上有货，到中午大米鸡蛋首先售空，然后是肉类。
  * 各大超市，包括costco，stater Bro等开始限购措施
* Mar 16
  * Corona大华没有大米鸡蛋等。


{% include post-comments.html %}