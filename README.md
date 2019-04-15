The package is used to convert cookie strings into python dict, in order to use in web scrawler.

## INSTALLATION
```
pip install git+git://github.com/Yiguan/Cookie2Dict.git
```

## UASAGE

examples
```
from Cookie2Dict import cookie2dict
aa = "prov=ca7bb878-0692-fb8e-5fc8-89a41488f024; _ga=GA1.2.478061176.1551913365; __qca=P0-579821954-1551913364193; notice-ctt=4%3B1552281948855; _gid=GA1.2.404284094.155528415"
convert = cookie2dict(aa)
convert.ToDict()
```

---
