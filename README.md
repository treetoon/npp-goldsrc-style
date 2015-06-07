by treetoon v.1.0.2
.cfg
notepad++ 6.6.9 compatible


Locate: 
C:\Program Files (x86)\Notepad++\themes
place "CFG Black.xml" theme here 

Open notepad++, goto-> Settings-> Style Configurator, Select theme: CFG Black
(Global values may interfer, select Enable global ... color later etc if something isn't displaying properly)
Save then restart notepad++


Language-> Define your language...-> Import-> "CFG-Language_syntax.xml"
Select it in "Language" bar on top, may need restart


You may also want to disable spell checking and word wrapping can be very useful.





Test Code: 
(This should all be white since it's a .txt), open testCode.cfg to check that it's working

//Brightness Comment
//you can test to 
//close this comment
brightness "4.0"	//default "1.0"

bind "1" "weapon_crowbar"
bind "mouse2" "+attack2"

map "c1a0;w;-attack;w57;w1000;alias test _special special"
unbindall

seta command alias +left w500 "say hello world; exec half-life"
