OppaiGallery *v0.5*
=========
« OppaiGallery » is a offline (not designed for online usage, admin.php is not authentication protected) links library manager for R18 Japanese pornography artworks.
Sort of bookmarks for your coups de coeurs. (A "coup de coeur" it's like when you see a tv series/read a book/play a game/etc. for the first time and you really like it even if it's not the best series/book/game/etc. you have seen...)


It display latests media added, support search, tags, random feature and have also a mini admin panel.
Just put it on a NAS or a raspberry pi with local web server feature.

```gallery.php``` and ```admin.php``` can be renamed, it will not broke it.


> **SQL Procedures**: 
> SQL dump include 4 procedures need 5 tables and have already 7 categories pre-defined (Pictures/Photo/JAV/Anime/Manga/Doujinshi/Games), sql procedures can be called like this:
>
>```  CALL latest_medias(3); ```
>```  CALL medias_by_tag('your tag'); ```
>```  CALL random_medias(3); ```
>```  CALL tags_count(); ```

Can be reused to make a music library links db (soundcloud, mixcloud, etc..), youtube videos library, or whatever you think it can be re-used for...
