# trailhead
5 puzzles. Each gets more difficult.

5 clues. Take notes. Each puzzle is gone after it's solved.

5 places. Think numbers. 

Enter all answers at savethedate.foo.

You must know where you've been to get where you're going.


# ----- NOTES -----


## Step 1: Intro

![Decoded Image](http://i.imgur.com/sUoA702.png)

By using the table below and converting a = 1 .. z = 26, you get the message `savethedate.foo`.

```
A=1
B=2
C=3
D=4
E=5
F =6
G=7
H=8
I =9
J = 10
K = 11
L = 12
M = 13
N = 14
O = 15
P = 16
Q = 17
R = 18
S = 19
T = 20
U = 21
V = 22
W = 23
X = 24
Y = 25
Z = 26
```

## Step 2: Savethedate.foo

1) Type in the coordinates in the js file in this repo `-28.092472, -52.419667`, and you get to a youtube video https://www.youtube.com/watch?v=9N9K898TtWQ&feature=youtu.be&yt:cc=off. Turn on closed captions.

* Answer 1: `-28.092472, -52.419667`

## Step 3: Youtube

Visit this, google originally turned off closed captions.

https://www.youtube.com/watch?v=9N9K898TtWQ&feature=youtu.be&yt:cc=on

latitude: MagicI.See_abeach, longitude: -yes._Iexploredaylight

The number of characters in each word represents the coordinates, add back in the `,` `-` and `.`

```
Magic = 5
I = 1
.
See = 3
A = 1
Beach = 5
```

and

```
-
yes = 3
.
I = 1
explore = 7
daylight = 8
```

* Answer 2: `51.3015, -3.0178`

## Step 4: Radio

Visit this site from the next location marker: https://docs.google.com/presentation/d/11uA9a5wgoY9w9vOyx3C76YewbypmNKgnpy7TbOIv9Wc/pub?start=false&loop=false&delayms=3000&slide=id.p

The audio file playing within the presentation points to: https://www.youtube.com/embed/B8uV0dCTKrE

`053 050 046 049 056 050 049 044 032 050 048 046 057 057 054 053`

A simple ASCII -> Text conversion gives you the next answer:

* Answer 3: `52.1821, 20.9965`

## Step 4:

Links to google drive, https://drive.google.com/drive/folders/0B2BGioksxQiRc2hpTDJ1SVhPUU0

Corrupted image is actually a hex string, convert to ascii. Also get the info off the corrupted image for the following.

Instructions: `FBMD01000a9c0d0000ec4f000055df0000b5e80000fcfa00005cb2010013ef020069fc02003d110300942b0300b0ce0500`

```
Numbers are amazing. Follow the count.


  V -----------------------------------
> 1  7  8  5  4  10 1  2  6  3  6  1. 9|
 |4. 2  9  4  2  7  9  8  5  6  5  2  7|
 |4  10 9  7  4  2  5  9  6  8  10 7  9|
 |8  5  3  5  3  5  4  7  2  9  6  1  8|
 |2  7  1  3  4  1  5  8  4  9  8  8  3|
 |6  1  9  4  5  5  7  3  1  2  6  10 4|
 |10 8  7  1  2  4  5  8  2  5  7  9  1|
 |2  3  5  7  1  4  6  9  5  3  4  5  6|
 |9  1  4  4  8  3  7  6  2  5  1  6  7|
 |2  1  9  3  7  4  5  7  3  6  8  7  8|
 |8  3  8  5  8  4  6  1  5  9  1, 10 6|
 |6  3  5  7  7  1  10 4  8  6  3  5  9 >
  ------------------------------------v
??
```

Per https://react-hn.appspot.com/#/comment/13475992

```
Start from top-left, move the number of spaces given by the number of your current square:

down right left down right right up down down right down

It's a maze; worked backwards from the numbers that have commas and points next to them.
```

* Answer 4: `14.2981, 101.2189`

## Step 5

Link points to: 
https://photos.google.com/share/AF1QipMNGiEkdfeZKK5uus5iOmt-Gv70lGgSXrnb0sKABhbYuGvovrtNFOy9NAemx0704Q/photo/AF1QipPUgDxGGFcGyd6z-UaSOvqM6JHccuyebfXskvVD?key=WEE2RnpsSkpQRHRscjVxVlhFY1ZRbmRCQnZSQ05B


The name of the file is base64.png, and the post tags `V2hlcmUgaGF2ZSB5b3UgYmVlbj8` => Where have you been?

The board shows the following pieces.

R1  | R2| R3|   R4|  R5|  R6| R7| R8|
--- |---|---|  ---|--- |--- |---|---|
+10 | X |+8 | -12 | X  | -7 | X | X |
+15 | -6|-2 | -11 |+19 | +4 |+1 | X |
+3  | -7|+3 |  X  |+4  | +1 | X | X |
-19 | +5| X |  +7 | X  | +7 | X |+5 |

The list of places we have been are:

* Brazil
* England
* Poland
* Thailand

Filling in the spots and adding/subtracting the character (ex B+10 = L), you get the following message:

R1  | R2| R3|   R4|  R5|  R6| R7| R8|
--- |---|---|  ---|--- |--- |---|---|
L   | # |I  | N   | #  | E  | # | # |
T   | H |E  | A   | T  | R  |E  | # |
S   | H |O  |  #  |R   | E  | # | # |
A   | M | # | P   | #  | H  | # |I  |

Answer: `Shoreline Amphitheatre`

## Fin

We then get redirected to a page with the following image!

![I/O Dates](http://i.imgur.com/60lmtFD.png)
