# WPICTF
## glute

Category | Points
--- | --- 
Steganography | 150

1. Download the file
2. We see that the image weighs too mush for the image, so 
we can guess that image has something inside
3. Let's try to extract using ```binwalk```
4. Type in ```bash``` 

    ```binwalk --dd = '. *' Glute.png```
5. After extraction we see that image has pdf inside
6. Open PDF and get the flag

`flag=WPI{P0lyGlOtz_R _koo1}`