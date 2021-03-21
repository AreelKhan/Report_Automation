# Report_Automation
I wrote this script to aid me and some of my colleagues with writing our daily reports.
My problem was essentially that writing a report felt repetitive and sluggish.
I decided to write a quick automation script that completes the report for me.

Heres how it works:

There exists a .txt file that holds the contents of my daily report. I can edit the file as I need and my changes will be reflected in my corresponding document. 
The reason I chose to use a .txt file was because they are very quick and light.
The script reads in the .txt file and produces a corresponding MS Word document with the correct date and report contents formatted in the desired way.

I tried to use selenium to make it so that the word document is also automatically uploaded to my work portal, however I am not sure whether that is allowed.
