# ner

SDK to access API of Ner service

This program is SDK of Ner service API.  

It can handle one sentence and simple text file in chinese.  
For instance:  
```bash
$ python ner.py -e http://example.com/ner/bert/normal
[Endpoint] http://example.com/ner/bert/normal

sentence example:
{'ORG': ['康龙化成', '安永华明']}

simple text file example:
{'LOC': ['新冠', '新疆'],
 'ORG': ['华资实业',
         '明科',
         '中葡',
         '亚星',
         '厦华',
         '中房股份',
         '中房股份',
         '西域旅游',
         '西域旅游',
         '丰华股份',
         '丰华股份',
         '壳公司']}
```
