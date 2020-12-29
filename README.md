# smroitemids
regex: ```(\[(\d+)\][\s\S]+?)(\bidentifiedDescriptionName = \{[\s\S]+?)\"\n```

replace: ```$1$3",\n\t\t\t"ID:^009900 $2^000000"\n```

encryption: `EUC-KR`
