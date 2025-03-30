# myALClient
Parce your myanimelist.net/animelist/. Cache it offline and allow conviniently shows it.
Allow you form your own anime list playlists and save it in local base or json.
Developed for people who don't watch ungoings and have big "plan to watch" list on myanimelist. 

# Feature list
- Dynamic ongoing hiding. Allow you to hide ongoing from list.
- 18+ content hide/show.
- Initialy we have playlist from all unwatched anime sorted by avg score.
- All watched anime in watched list.
- You can delete from play list.
- Deleted anime from play list contains in backet list.
- You can replenish playlist from bucket or unwatched. It will be deleted from bucket than.
- You can change anime position in list.
- You can use JSon or Postgres to save you list.
- If base is not avalible, you work with local jSon

# Technical details
#### client
- JavaFX for PC
- Android SDK for Android
#### local_server 
- Logic: Java Spring;
- Base: PostgreSQL/JSon;
#### List
Java, RabbitMQ, PostgreSQL + Citus, JavaFX, Java Android SDK.

# Plan
- develop base desctop read only client
- develop Java, RabbitMQ, PostgreSQL server
- implement PC client 
- transfer back system in some cloud
- make high load testing
- implement adroid client
- autorize throught myanimelist
- release 1.0 alpha

# After release plan
- predict season finish date.
- option: set "watching" to your first in play list anime.
- option: set your myAnimeList avatar associated with your current anime
- option: notify about release if you have no "watching".
- option: notify your next/today watch anime.
- more convinient filters and featurs based on comunity feedback 

# App Name ideas and description
- myAnimeList_PlayList (Allow you to form anime play list from your myAnimeList.)
