# XMPP (Jabber) console client for Omega2

mcabber version: **1.1.1**

## About mcabber

**mcabber** is a text Jabber client including features such as SSL/TLS/SASL support, history logging, commands completion, external actions triggers and dynamic modules. It also has PGP, OTR (Off-the-Record Messaging) and Aspell/Enchant support.

[MCabber official homepage](https://mcabber.com/)

## Installation

Download the repo:
```
git clone https://github.com/mariuszduka/omega2-mcabber.git
```

and install packages:
```
opkg install omega2-mcabber/mipsel_24kc/loudmouth_1.0_mipsel_24kc.ipk
opkg install omega2-mcabber/mipsel_24kc/mcabber_1.1.1_mipsel_24kc.ipk
```

Done!

## Configuration

Modify the file `mcabberrc` in the directory `/root/.mcabber`:
```
set jid = yourusername@domain
set password = yourpassword
set server = your.jabber.server
set port = 5222
```

If you don't use SSL change:
```
set tls = 0
```

## Usage

In the console execute the command:
```
mcabber
```

## Resources

 * [MCabber official homepage](https://mcabber.com/)
 * [MCabber on Github](https://github.com/McKael/mcabber)

## License

MIT License

Copyright (c) 2019 Mariusz Duka

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.