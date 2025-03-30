# myALClient
Parce your myanimelist.net/animelist/. Cache it offline and allow conviniently shows it.
Allow you form your own anime list playlists and save it in local base or json.

# Feature list
- Initialy we have playlist from all unwatched anime sorted by avg score.
- All watched anime in watched list.
- You can delete from play list.
- Deleted anime from play list contains in backet list.
- You can replenish playlist from bucket or unwatched. It will be deleted from bucket than.
- You can change anime position in list.
- You can use JSon or Postgres to save you list.
- If base is not avalible, you work with local jSon
- Ongoing hiding. Allow you to hide ongoing from list.

# Technical details
#### client
- JavaFX for PC
- Android SDK for Android
#### local_server 
- Logic: Java Spring;
- Base: PostgreSQL/JSon;
