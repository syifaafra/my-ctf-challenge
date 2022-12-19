# Writeup **nintendo**
*Read this in other languages: [Indonesian](README.md), [English](README.en.md)*


Based on the hint given to file `file_maker.py`, the description of the challenge and the file structure, it can be seen that the file is an APNG file. To fix the corrupted file, you can add the header file `89 50 4E 47`. After that, the APNG file extracted into several PNG files to get the flag from each pixel that has been changed.
## Flag

```
COMPFEST14{ju5t_4n_aN1m4t3d_png}
```
# Reference
https://blog.jettchen.me/posts/ostrich/#solution
