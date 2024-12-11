###
```python
from rest_framework.views import APIView
from rest_framework.response import Response
from rest_framework import status

class AboutMe(APIView):

    def get(self, request):

        baba_mandef = {
            'name': 'Abiodoun PARAISO',
            'stack': {
                       'languages': ['Python', 'JS', 'Dart', 'PHP', 'Yoruba', 'Fongbe', 'Kreyol', 'French', 'English'],
                       'tools': ['Django', 'React', 'Flutter', 'Figma', 'GIMP', 'Inckscape', 'Kdenlive', 'Blender'],
                       'databases': ['Mysql', 'Postgresql', 'Sqlite'],
                       'architectures': ['MVC', 'MVT', 'REST', 'PWA', 'SPA', 'MicroServices']
                     },

            'roles': ['Software Engineer', 'Video & 3D Artist', 'Teacher', 'Mentor', 'Farmer'],
            'askme': ['DIY',  'Africa', 'Science', 'Photo & Video', 'Tech', 'Agro'],
            'contact': {
                           'Telegram': 'baba_mandef',
                           'Youtube': 'baba-mandef'
                           'Mail': 'contact@abiodoun.dev',
                        }
         }
        return Response(baba_mandef, status=status.HTTP_200_OK)

```                    

<!--START_SECTION:waka-->
![Code Time](http://img.shields.io/badge/Code%20Time-1%2C284%20hrs%2040%20mins-blue)

![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Africa/Porto-Novo

💬 Programming Languages: 
Python                   16 hrs 11 mins      █████████████████████░░░░   84.65% 
HTML                     2 hrs 20 mins       ███░░░░░░░░░░░░░░░░░░░░░░   12.24% 
JavaScript               31 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   2.71% 
CSS                      3 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.3% 
Git Config               1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.11%

🔥 Editors: 
VS Code                  19 hrs 8 mins       █████████████████████████   100.0%

🐱‍💻 Projects: 
ekilibre                 18 hrs 19 mins      ████████████████████████░   95.78% 
quatro                   48 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.22%

💻 Operating System: 
Linux                    19 hrs 8 mins       █████████████████████████   100.0%

```


 Last Updated on 11/12/2024 18:45:57 UTC
<!--END_SECTION:waka-->
