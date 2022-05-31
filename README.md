# Battle Space

Here we have made a game using python libraries like *Pygame* or _Pymunk_.

It is a *space battle game* where the user will get **_5 Lives_** by default.

1. You need to install Python 3.10.4 from [here](https://www.python.org/downloads/)
2. You need to install Pygame
``` 
pip install pygame
```
2. OR you can use this [Link](https://pypi.org/project/pygame/)
3. And the total Requirements is full filled.

* The User by default gets 5 Lives for the game.
* The Enemy battle ships gets incremented as the game goes on.
* With the help of **Space Bar** the user shoot the bullets to the Enemy Battle Ships.
* With the help of Directional keys the User can control the flow of their own Battle Ship.

Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
 
```pythonpygame.init()
pygame.mixer.init()
clock = pygame.time.Clock()
screen = pygame.display.set_mode((gameConfigs["width"], gameConfigs["height"]))
pygame.display.set_caption(gameConfigs["title"])
fontSmall = pygame.font.Font("assets/fonts/bitcell.ttf", 30)
fontLarge = pygame.font.Font("assets/fonts/bitcell.ttf", 200)
run = True
actualLevel = 1
```
 
```
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.
```

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].  

You can also use words, to fit your writing style more closely[^note].

[^1]: My reference.
[^2]: Every new line should be prefixed with 2 spaces.  
  This allows you to have a footnote with multiple lines.
[^note]:
    Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
    This footnote also has been made with a different syntax using 4 spaces for new lines.

Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the 
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)

