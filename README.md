# phreaknet-boilerplate
Boilerplate Asterisk config files for PhreakNet

## Files

### General Config Files

`asterisk.conf` - General Asterisk config

`modules.conf` - Module loading

`musiconhold.conf` - Music on hold

### Channel Driver Config Files

`chan_dahdi.conf` - DAHDI config file (userland config, not the system DAHDI config)

`iax.conf` - IAX2 channel driver

`pjsip.conf` - PJSIP (new SIP channel driver) config

`sip.conf` - SIP (old, deprecated SIP channel driver) config

### Other Module Config Files

`verify.conf` - Configuration file for `app_verify` module

### Dialplan Configuration Files

`extensions.conf` - Main dialplan config file

`dialplan/phreaknet.conf` - Main, user-editable PhreakNet dialplan config

`dialplan/phreaknet-aux.conf` - PhreakNet auxillary dialplan library

`dialplan/phreaknet-coin.conf` - PhreakNet Class 5 coin line library (dial tone first)

`dialplan/verification.conf` - Verification subroutines dialplan library
