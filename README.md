html2png
========

Python script that takes screenshots of html pages, analyses the structure of the document and creates an image map of the links.

### Examples:

Screengrab google
```
python html2png.py http://google.com/
```

Bigger screengrab of google
```
python html2png.py -W 1000 -H 1000 http://google.com/
```

Just the thumbnail screengrab
```
python html2png.py -T http://google.com/
```

Just thumbnail and fullsize grab
```
python html2png.py -TF http://google.com/
```

Save images as "foo-thumb.png"
```
python html2png.py -o foo http://google.com/
```
