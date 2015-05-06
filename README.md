# ShanghaiTech Wifi Login Script

A light-weight script helping you login the wifi hotspot without a web browser, written in Ruby.

## Platform

Best for Linux microcomputer (e.g. Raspberry Pi) and Linux/Mac PC.

## How-to

**For Linux/Mac users:**

1. Connect to "ShanghaiTech" or "guest" wifi in Pudong campus.

2. Download the file `main.rb` and put it into a folder.

3. Open the terminal, then enter the folder where you put the program in.

4. Run the command `ruby main.rb $username $password`, while $username is your username and $password is the password of your account.

5. Waiting for the response, and now you have connected to the wifi network.

6. You can set this script automatic with the comman `crontab`, for more information, see the wiki. (e.g. <a href="https://help.ubuntu.com/community/CronHowto" target="_blank">Ubuntu Official Wiki - Cron</a>)

**For Windows users:**

1. Download Ruby, follow this <a href="https://www.ruby-lang.org/en/documentation/installation/" target="_blank">instruction</a>.

2. Repeat the steps 1-6 in the Linux/Mac How-to. What's more, commander (cmd) is the terminal-like command line tools in Windows.

## License

This is a totally open source software licensed under GPLv2 license. You can use or modify it only if you want. However, commercial use is not permitted.