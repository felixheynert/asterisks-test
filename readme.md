# Using Ansible to install Multiple instances of Asterisk

This Directory uses ansible to install and configure a multiInstance Asterisk install
This might not be the most perfect way off doing it, but it get's the job done.

Ports Used:
Instance-1: UDP-SIP 5071; Automated Voice Playback @Ext 111
Instance-2: UDP-SIP 5072; Automated Voice Playback @Ext 112
Instance-3: UDP-SIP 5073; Automated Voice Playback @Ext 113

Client used
(USERID|USERNAME|CALLERID|CGPN) = 6001
(Secret|PASSWORD|SIPPASSWORD) = test



