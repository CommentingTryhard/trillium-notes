# SMB Relay Attacks
**SERVER MESSAGE BLOCK RELAY ATTACKS**

Requirements

*   SMB signing must be disabled
*   Relayed user credentials must be admin on that machine

Responder will output a SAM File, containing hashes and relevant credentials of the target.

This hash can be used to log into another machine where the user has adminstrative access, as SMB signing when disabled will cause the machine to not validate and verify user signature, only a hash and username will functionally allow access on that relevant username.