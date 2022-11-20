How? This way:

`echo @echo off ^&^& echo MsgBox"%~1",0,"%~2"^>msgbox3081283.vbs ^&^& start "" "msgbox3081283.vbs" ^&^& timeout 1 /NOBREAK ^&^& del msgbox3081283.vbs > messagebox.bat`

God damnit. What does it do??

Well, it puts some instructions in a batch file. These instructions are putting temporary code into the `msgbox3081283.vbs` and then runs and deletes it.

After you run it, u can use:

`messagebox.bat "L33T T3XT" "title :)"`

to get this:

![image](https://user-images.githubusercontent.com/49472785/202911989-19d2cb32-55ef-4680-aaab-79be42d06ddf.png)

Got it? Cya then.
Peace out ;)
