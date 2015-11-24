# nosql

Na pocztek zainstalowalem mongo. Pobralem program bunzip2 i baze reddit.
Uruchomilem mongod poleceniem: mongod --storageEngine wiredTiger --dbpath f:\mongo\bin\tygrys
Nasstepnie zaimportowalem baze poleceniem: bunzip2 -c RC_2015-03.bz2 | mongoimport --drop --host 127.0.0.1 -d baza -c reddit
czas importu 53:43:2
Na koniec uruchomilem mongo: mongo baza


#zliczenie rekordow
db.reddit.count()
54564441

#zliczenie wszystkich autorów zaczynajacych sie na litere m
komenda: db.reddit.find({author: /^m/}).count()

1700219

czas 14.5min

#piec pierwszych kontrowersyjnych tematow

db.reddit.find({controversality:1}, {_id:0, subreddit:1}).limit(5)
![GitHub Logo](1.png)
czas 7.3 min


13.65min
