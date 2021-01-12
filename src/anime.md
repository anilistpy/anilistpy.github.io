## Init:
starting the ```anilistpy.Anime()``` object

```Anime()``` takes one argument, that is the id of the anime on anilist.co

example: 
```py
from anilistpy import Anime
animeObject = Anime(1) # 1 is the id of the anime
```

## Methods:

- ```Anime.reload()```

Reloads the objects, sends the API request again

- ```Anime.json()```

Returns the raw json from the API

- ```Anime.title(LA)```

Return the title of the anime.

```LA``` should be one of romaji, english, native

[source code](https://github.com/anilistpy/anilistpy/blob/master/anilistpy/anime.py)