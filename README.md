# nosql

czas importu 53:43:2

#zliczenie rekordow
db.reddit.count()
54564441

#zliczenie wszystkich autorów zaczynajacych sie na litere m
komenda: db.reddit.find({author: /^m/}).count()

1700219

czas 14.5min

#piec pierwszych kontrowersyjnych tematow

db.reddit.find({controversality:1}, {_id:0, subreddit:1}).limit(5)

czas 7.3 min

13.65min
