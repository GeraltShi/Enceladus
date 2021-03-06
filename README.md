# Enceladus
Get NetEase music lyrics with Python3

<img src="https://img.shields.io/badge/requests-2.22.0-green.svg">

Usage: `lyric.py [-h] id format`

```
positional arguments:
  id          id of the music

  format      choose the format of the output: orig/trans/merge

optional arguments:
  -h, --help  show this help message and exit
```

`orig`: original lyrics

`trans`: translated lyrics

`merge`: lyrics in "[original]/[translated]" type

You may need to install requests for the program to run: `pip3 install requests`

Get the id of the music you are interested in: 

Share -> Copy the link in the browser -> The number after `https://music.163.com/song?id=` should be the music id.

---

For example: `python3 lyric.py 533943763 merge`

This would generate a txt lyric that meets the lrc file standard under the script executing folder.
You may change the extension from `*.txt` to `*.lrc` manually if you wanna import it in other apps.

If this program helps with your MAD/AMV production, please do not hesitate to give me stars. :smile:

<p align="center">
  <img src="https://github.com/GeraltShi/Enceladus/blob/master/snapshot.png" width="550" alt="snapshot">
</p>
