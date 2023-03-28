```python

class Me:
  name             : str  = "Kirill"
  nationality      : str  = "Belarusian"
  gender           : list = ["he", "his", "Male"]
  hobbys           : list = ["tech stuff", "science", "languages"]
  job_exp          : str  = "2+ years"

class Contacts(Me):
  telegram         : str = "@wultes"
  email            : str = "wultesu@gmail.com"
  
class Stack(BackEndDeveloper):
  languages        : list = ["Python", "JS"]
  frameworks       : dict = {
                              "Python": [
                                          "Django",
                                          "Django Rest Framework",
                                          "Celery"
                                        ],
                              "Js": [
                                      "React"
                                    ]
                            }
  database         : list = ["MySQL", "PostgreSQL", "Redis"]  

```
