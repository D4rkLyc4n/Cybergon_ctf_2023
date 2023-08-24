### Writeups For Cybergon Stegano By *N00b_ScRiptKidS*

## Warn Up 1

**it say "When did Mr.Yit take this photo ?" and give a pic**
>So i downloaded that image and i try to find some information inside of that image.
>i use exiftool to extract time from image and boom i found the flag.

## Catch me if you can

**it say "Do not judge until you know all story." and give a gif file**
>First i download the Image and open with image viewers but not working.So i check
>with file command `Stegano1.gif: data`.So it was not gif file.And i check with
>hexeditior and i saw gif header missing(gif file signature).i open image file with nano
>and add AAAA in image file
>
> ![alt text](/img/pic1.png).
>
>I open hexeditior again and i replace AAAA to gif code
>
>![alt text](/img/pic2.png)
>
>and boom flag found
