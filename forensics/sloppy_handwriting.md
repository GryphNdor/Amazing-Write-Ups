# Sloppy Handwriting

### Basic Info

Is this a new form of cursive??

#### Hint
> This hint has been Redacted

### The Breakdown

Mwuhaha! This was an evil challenge because it was a two-parter combining recon skills with forensics  

You first needed to know what this was. It doesn't look handwritten so it is probably computer generated  

If you use the hint or a reverse image search you can find this cool font by Christian Naths:
https://github.com/christiannaths/redacted-font

And indeed it is Redacted Script!

After that you can look into the issues section and someone already wrote a simple script to do the unredacting.

https://github.com/christiannaths/redacted-font/issues/27

The trick here is that you have an image.

So to pseudo-code this thing
```
Create a character map for each glyph
Substitute each glyph in the image as your encrypted string
Run some for loops to brute force all possibilities given the string
Find the Flag
```
Another way this could have been done is with frequency analysis but I am not a guess god.

What I did was I found this nice site
https://www.1001fonts.com/redacted-font.html#character-map-script-regular and brute forced letters into the typing box (not recommended)

### Solution
flag{how_did_you_decode_me}