# Client side VPN endpoint

1. Make the easy-script file executable

```bash
chmod +x easy-script
```


2. Run the script

```bash
./easy-script
```
The output will be
```
usage : ./easy-script options: install, adduser, import-acm, revoke, gen-crl
```
To install the client side VPN endpoint, run the script with the option `install`
```bash
./easy-script install
```
The install command will also install AWSCLI is not already installed.

To add user to the VPN endpoint, run the script with the option `adduser`
```bash
./easy-script adduser
```


To import certificate to ACM,
run the script with the option `import-acm`
```bash
./easy-script import-acm
```