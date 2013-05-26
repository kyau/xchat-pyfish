    # https://github.com/kyau/xchat-pyfish
    #
    # Author:  kyau
    # Version: 4.21
    # Date:    2011-10-29T06:13:25-0500


### About

FiSH/Mircyption clone for X-Chat written 100% in Python using the PyCrypto
module. I claim no credit for this I merely wanted a backup copy that wasn't
reliant on pastebin.

### Help

     ***************** Fishcrypt Help ********************
     -----------------------------------------------------
    /MSG+ send crypted msg regardless of /ENCRYPT setting
    /NOTICE+ send crypted notice regardless of /ENCRYPT setting
    /ME+ send crypted CTCP ACTION
    /SETKEY set a new key for a nick or channel
    /KEYX exchange pubkey for dialog
    /KEY show Keys
    /DELKEY delete Keys
    /CBCMODE enable/disable CBC Mode for this Key
    /ENCRYPT enable/disable encryption for this Key
    /PROTECTKEY enable/disable protection for keyx key exchange
    /DBPASS set/change the passphrase for the Key Storage
    /DBLOAD loads the Key Storage
    /PRNDECRYPT decrypts messages localy
    /PRNCRYPT encrypts messages localy
    /FISHUPDATE check online for new Version and update
    /SET [fishcrypt] show/set fishcrypt settings

### Attribution / Credits

* Original Copyright 2011 by [Nam T. Nguyen](http://www.vithon.org/forum/Thread/show/54)
* Rewritten by Trubo/Segfault for irc.prooops.eu #py-fishcrypt
* irccrypt module is Copyright 2009 by [Bjorn Edstrom](http://www.bjrn.se/ircsrp)
