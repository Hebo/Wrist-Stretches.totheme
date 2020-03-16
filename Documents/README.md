ffmpeg -noaccurate_seek -ss 00:01:39 -i Hand\ +\ Wrist\ Exercises\ For\ Gamers-EiRC80FJbHU.mp4 -vf select="eq(pict_type\\,I)[s1];[s1]showinfo[out]" -vframes 1 -q:v 1 images/thumb-1.jpg


ffmpeg -i Hand\ +\ Wrist\ Exercises\ For\ Gamers-EiRC80FJbHU.mp4 -ss 00:01:39 -vframes 1 images/thumb-1.jpg
