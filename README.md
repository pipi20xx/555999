自定义制作组

Group.txt 

https://raw.githubusercontent.com/pipi20xx/555999/refs/heads/main/anime/Group.txt

自定义替换词

1 CHSCHTRE.txt CHS替换为简体等 https://raw.githubusercontent.com/pipi20xx/555999/refs/heads/main/anime/CHSCHTRE.txt

2 GroupRE.txt 字幕组名字替换 https://raw.githubusercontent.com/pipi20xx/555999/refs/heads/main/anime/GroupRE.txt

3 anime.txt 常用替换

https://raw.githubusercontent.com/pipi20xx/555999/refs/heads/main/anime/anime.txt

4 animepisodegroup.txt 常用替换需要搭配剧集组

https://raw.githubusercontent.com/pipi20xx/555999/refs/heads/main/anime/animepisodegroup.txt

自定义渲染词

1 CHSCHTRE.txt CHS替换为简体等 https://raw.githubusercontent.com/pipi20xx/555999/refs/heads/main/anime/CHSCHTRE.txt

2 GroupRE.txt 字幕组名字替换 https://raw.githubusercontent.com/pipi20xx/555999/refs/heads/main/anime/GroupRE.txt

3 animeifre.txt 常用替换 

https://raw.githubusercontent.com/pipi20xx/555999/refs/heads/main/anime/animeifre.txt

4 episodegroupRE.txt 需配合剧集组 https://raw.githubusercontent.com/pipi20xx/555999/refs/heads/main/anime/episodegroupRE.txt

数字就是顺位 实现了远程控制武器的群多无群


##这两条是自动 给后面SXXEXX EPXX里面的集号 加中括号 非必要不用使用


(S\d+E\d+)(.*)\b(S\d+E\d+)\b => \1\2[\3]


(S\d+E\d+)(.*)\b(E.\d+)\b => \1\2[\3]


