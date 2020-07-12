# ipa

Displays your local or public IP address. Works on both Mac and Linux.

#### Installation

###### clone the repo

```console
foo@bar:~$ git clone https://github.com/adrianbalandev/ipa.git
foo@bar:~$ cd ipa
foo@bar:~$ npm install
```

#### to see avalilable options

```console
foo@bar:~$ ipa
Internet Protocol Address Tool
[-l] --displays the local IP address
[-p] --displays the public IP address
[-v] --verbose setting
```

#### to get your local ip address

```console
foo@bar:~$ ipa -l
192.168.1.3
```

#### to get your public ip address

```console
foo@bar:~$ ipa -p
109.73.16.70
```

#### to get both

```console
foo@bar:~$ ipa -l -p
pub:109.73.16.70
loc:192.168.1.3
```

#### verbose can be used with either or both

##### e.g.

```console
foo@bar:~$ ipa -v -l -p

                Your Internet Protocol Addresses >>>>>>>>>>>

                    Public IP: 92.80.218.18
                    Local IP: 192.168.1.3

                <<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<
```
