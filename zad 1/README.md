# Zadanie 1
a) Baze Train.csv zainportowa�em do bazy MongoDB poleceniem:

```sh
mongoinport -c nosql -d Train "_id" "title" "body" "tags" --type csv --file d:\Train.csv --headerline
```

![Data Wranglers](Przechwytywanie.PNG)

Zaimportowano 6034195 objekt�w czas trwania ok 2h

Do aggregacji mo�na wykorzysta� te kolekcje: