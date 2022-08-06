###
```python
from rest_framework.views import APIView
from rest_framework.response import Response
from rest_framework import status

class AboutMe(APIView):

    def get(self, request):

        shadowcompiler= {
        "fullName": "Salaou-Deen Henri-Joël Abiodoun PARAISO",
        "stack": { "languages": ['Python', 'Php', 'JS', 'Kotlin'],
                   "tools": ['Django', 'DRF', 'VueJS', 'NuxtJS', 'Bulma', 'Beufy'],
                   "databases": ['Mysql', 'Postgresql', 'Sqlite'],
                   "architectures": ["MVC", "MVT", "REST", "PWA", "SPA"]},        
        "roles": ["Web & Mobile dev as freelance", "Blogger", "Founder at @henrid3v", "Mentor"],
        "askMe": ['Food', 'Manga', 'Science', 'Comics', 'NaturalHair', 'Photography', 'Tech', 'Programming'],
        "contacts": { 'Telegram': 'imsadi',
                       'Linkedin': 'henri-dev',
                       'Discord': 'ShadowCompiler#2596',
                       'Mail':'pariso03henri@gmail.com',}}
        return Response(shadowcompiler, status=status.HTTP_200_OK)

```                    

<!--START_SECTION:waka-->
![Code Time](http://img.shields.io/badge/Code%20Time-0%20secs-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-2-blue)

![Lines of code](https://img.shields.io/badge/From%20Hello%20World%20I%27ve%20Written-55%20Thousand%20lines%20of%20code-blue)

**🐱 My GitHub Data** 

> 🏆 317 Contributions in the Year 2022
 > 
> 📦 36.0 kB Used in GitHub's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 21 Public Repositories 
 > 
> 🔑 13 Private Repositories  
 > 
**I'm an Early 🐤** 

```text
🌞 Morning    228 commits    █████████░░░░░░░░░░░░░░░░   36.42% 
🌆 Daytime    176 commits    ███████░░░░░░░░░░░░░░░░░░   28.12% 
🌃 Evening    160 commits    ██████░░░░░░░░░░░░░░░░░░░   25.56% 
🌙 Night      62 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.9%

```
📅 **I'm Most Productive on Friday** 

```text
Monday       98 commits     ████░░░░░░░░░░░░░░░░░░░░░   15.65% 
Tuesday      66 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.54% 
Wednesday    86 commits     ███░░░░░░░░░░░░░░░░░░░░░░   13.74% 
Thursday     101 commits    ████░░░░░░░░░░░░░░░░░░░░░   16.13% 
Friday       115 commits    ████░░░░░░░░░░░░░░░░░░░░░   18.37% 
Saturday     99 commits     ████░░░░░░░░░░░░░░░░░░░░░   15.81% 
Sunday       61 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.74%

```


📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: UTC

💬 Programming Languages: 
Vue.js                   5 hrs 34 mins       ██████████████░░░░░░░░░░░   55.97% 
HTML                     3 hrs 39 mins       █████████░░░░░░░░░░░░░░░░   36.67% 
CSS                      43 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   7.3% 
Python                   0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.06%

🔥 Editors: 
VS Code                  9 hrs 57 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
lemocontrol              5 hrs 34 mins       ██████████████░░░░░░░░░░░   55.97% 
CAEB                     4 hrs 23 mins       ███████████░░░░░░░░░░░░░░   44.03%

💻 Operating System: 
Linux                    9 hrs 57 mins       █████████████████████████   100.0%

```

**I Mostly Code in Python** 

```text
Python                   14 repos            ██████████░░░░░░░░░░░░░░░   40.0% 
CSS                      7 repos             █████░░░░░░░░░░░░░░░░░░░░   20.0% 
HTML                     4 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   11.43% 
Kotlin                   2 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   5.71% 
C++                      2 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   5.71%

```


**Timeline**

![Chart not found](https://raw.githubusercontent.com/shadowcompiler/shadowcompiler/main/charts/bar_graph.png) 


 Last Updated on 06/08/2022 18:53:17 UTC
<!--END_SECTION:waka-->
