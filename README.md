# OTP-Auth
2-Step authentication tokens from the command line.

Works on osx/linux/cygwin.

## Description
OTP-Auth is a bash script that reads the auth.key file and sends the selected key to the authenticator python script that generates the tokens.

The auth script can be run with the service name as argument directly or without, in that case it will present you with a list of services to select from.

## Install

The files `auth`, `authenticator` and `auth.keys` need to be in the same directory and `auth` needs to be executable.

```
chmod +x auth
```

---