# FacialRecognition
Programa en python que detecta caras en cualquier foto, video o en tiempo real.

## Install
To put this code to work, download the image database and set in the root folder like this:
```
├── muct
│   ├── a
│   │   ├── i000qa-fn.jpg
│   │   ├── i000ra-fn.jpg
│   ├── b
│   │   ├── i000qb-fn.jpg
│   │   ├── i000rb-fn.jpg
│   ├── c
│   │   ├── i000qc-fn.jpg
│   │   ├── i000rc-fn.jpg
│   ├── d
│   │   ├── i000qd-fn.jpg
│   │   ├── i000rd-fn.jpg
│   └── e
│   │   ├── i000qe-fn.jpg
│   │   ├── i000re-fn.jpg
```

## The MUCT Face Database

The MUCT database consists of 3755 faces with 76 manual landmarks.

For details please go to www.milbo.org/muct.

![](http://www.milbo.org/muct/muct-examples-lores.jpg)

There is a file for each of the five cameras, and a file for the
manual landmark information.

The data was migrated from Google Code to GitHub in Oct 2015.  Thanks to Fred Nicolls for his help.

There is one gzip file for each camera, and a gzip file for
the manual landmark information.

Please respect the privacy of the people who volunteered to have their
faces photographed and DO NOT REPRODUCE the MUCT images in any
publically available document (especially web pages).

However, the following subjects have agreed to allow their faces
to be reproduced in academic papers:

- 000
- 001
- 002
- 200
- 201
- 400
- 401
- 402


> S. Milborrow and J. Morkel and F. Nicolls

> The MUCT Landmarked Face Database

> Pattern Recognition Association of South Africa

> Since 2001

> http://www.milbo.org/muct
