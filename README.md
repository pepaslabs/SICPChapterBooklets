# SICPChapterBooklets
[SICP](https://mitpress.mit.edu/sicp/), split into chapters, impositioned into booklets (PDF format).

After [splitting SICP into chapters](https://github.com/pepaslabs/SICPChapters), I then used [impositioner](https://github.com/sgelb/impositioner) to reformat it to be printed, cut in half, and bound into 5.5" x 8.5" booklets.

* [Chapter 1 (Booklet)](https://github.com/pepaslabs/SICPChapterBooklets/releases/download/2.andresraba5.5/booklet.sicp_chapter_1.pdf)
* [Chapter 2 (Booklet)](https://github.com/pepaslabs/SICPChapterBooklets/releases/download/2.andresraba5.5/booklet.sicp_chapter_2.pdf)
* [Chapter 3 (Booklet)](https://github.com/pepaslabs/SICPChapterBooklets/releases/download/2.andresraba5.5/booklet.sicp_chapter_3.pdf)
* [Chapter 4 (Booklet)](https://github.com/pepaslabs/SICPChapterBooklets/releases/download/2.andresraba5.5/booklet.sicp_chapter_4.pdf)
* [Chapter 5 (Booklet)](https://github.com/pepaslabs/SICPChapterBooklets/releases/download/2.andresraba5.5/booklet.sicp_chapter_5.pdf)


## Technical Details

```bash
sudo apt-get install python3 python3-pip
sudo pip3 install pdfrw
python3 impositioner.py sicp_chapter_1.pdf
python3 impositioner.py sicp_chapter_2.pdf
...
```
