## Wizard Spider
**[Wizard Spider](http://attack.mitre.org/groups/G0102/)** is a Russia-based financially motivated threat group originally known for the creation and deployment of [TrickBot](http://attack.mitre.org/software/S0266/) since at least 2016. Wizard Spider possesses a diverse arsenal of tools and has conducted ransomware campaigns against a variety of organizations, ranging from major corporations to hospitals. 


**[TrickBot](http://attack.mitre.org/software/S0266/)** is a Trojan spyware program written in C++ that first emerged in September 2016 as a possible successor to Dyre. [TrickBot](http://attack.mitre.org/software/S0266/) was developed and initially used by [Wizard Spider](http://attack.mitre.org/groups/G0102/) for targeting banking sites in North America, Australia, and throughout Europe.

*ID: S0266*
ⓘ
*Associated Software: Totbrick, TSPY_TRICKLOAD*
ⓘ
*Type: MALWARE*
ⓘ
Platforms: Windows

## Techniques Used

TrickBot collects the users of the system.
Adversaries may attempt to get a listing of accounts on a system or within an environment. This information can help adversaries determine which accounts exist to aid in follow-on behavior. 
[Account Discovery: Local Account](http://attack.mitre.org/techniques/T1087/)

TrickBot collects email addresses from Outlook.
Adversaries may attempt to get a listing of accounts on a system or within an environment. This information can help adversaries determine which accounts exist to aid in follow-on behavior.
[Account Discovery: Emaail Account](http://attack.mitre.org/techniques/T1087/)

TrickBot uses HTTPS to communicate with its C2 servers
Adversaries may communicate using application layer protocols associated with web traffic to avoid detection/network filtering by blending in with existing traffic. Commands to the remote system, and often the results of those commands, will be embedded within the protocol traffic between the client and server.
[Application Layer Protocol](http://attack.mitre.org/techniques/T1071/)

etc
