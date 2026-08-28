──(kali㉿kali)-[/home/kali]
└─PS> ls
Basic_Commands.ps1.save  Commands  Desktop  Documents  Downloads  Music  myscript.ps1  Pictures  Public  Templates  Videos

┌──(kali㉿kali)-[/home/kali]
└─PS> mkdir practice

┌──(kali㉿kali)-[/home/kali]
└─PS> touch pract1.txt             #create file

┌──(kali㉿kali)-[/home/kali]
└─PS> ls
Basic_Commands.ps1.save  Commands  Desktop  Documents  Downloads  Music  myscript.ps1  Pictures  pract1.txt  practice  Public  Templates  Videos

─(kali㉿kali)-[/home/kali]
└─PS> cp pract1.txt ~               #Copy file 
cp: 'pract1.txt' and '/home/kali/pract1.txt' are the same file

┌──(kali㉿kali)-[/home/kali]
└─PS> mv pract1.txt practice         #move file to another location/directory                                                                                                                                 
┌──(kali㉿kali)-[/home/kali]
└─PS> ls
Basic_Commands.ps1.save  Commands  Desktop  Documents  Downloads  Music  myscript.ps1  Pictures  practice  Public  Templates  Videos       ###file remove from home directory and moved to destination         
┌──(kali㉿kali)-[/home/kali/practice]
└─PS> ls
pract1.txt                           ###file moved to destination
──(kali㉿kali)-[/home/kali/practice]
└─PS> mv pract1.txt practice1.txt        #rename file name

┌──(kali㉿kali)-[/home/kali/practice]
└─PS> ls
practice1.txt                        ###renamed file                                                                                                                                                           

┌──(kali㉿kali)-[/home/kali/practice]
└─PS> rm practice1.txt               ###remove file

┌──(kali㉿kali)-[/home/kali]
└─PS> rm -r practice                 ###remove folder
┌──(kali㉿kali)-[/home/kali]
└─PS> ls
Basic_Commands.ps1.save  Commands  Desktop  Documents  Downloads  Music  myscript.ps1  Pictures  Public  Templates  Videos                         ###removed folder
