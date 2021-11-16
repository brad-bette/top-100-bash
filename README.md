# top-100-bash
A bash shell script that gets the current US Billboard top 100 via web scraping. Then creates the file labled `US-100.txt`

## Programs needed to get this program working
Make sure that the following linux commands are installed on your system:
- wget
- base64 (for the cool ascii text)
- paste

git clone this repository and use: `chmod +x top-100.sh` to make it executable. Then do `./top-100.sh` to run.

## Fun use cases
1. Get the current Billboard top 100 (duh)
2. Use it with `lolcat`: `./top-100.sh | lolcat -a`

### NOTE
This program may break over time, mostly due to billboard changing its web layout. Incase its a minor issue (like the song name being cut off) please adjust the cut number on line #84. There are comments explianing whats going on, so it should be an easy fix. Or send an issue, and I can try to address it as soon as I can. 
