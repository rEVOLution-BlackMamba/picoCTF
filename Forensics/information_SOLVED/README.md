# Information

## Description

Files can always be changed in a secret way. Can you find the flag? cat.jpg

## Hints

Look at the file details

## Approach

First, hints won't display, I try with file command but nothing. Then I look up for stenography, but that doesn't work out. I then look for image's metadata, for that i install exitfool and identify. with exitfool I see his metadata but I am blind. searching a write up about this exercise I see that the license field is a base64 encoded text, I saw that but i don't realize. I decode that and obtain the flag.

## Flag
picoCTF{the_m3tadata_1s_modified}