# SSLCertGen
A stupid-simple Self-Sign SSL Certificate Generator for speedy web development. I got sick of having to go to my bookmark to remember the commands to make SSL certificate files, so I just made this script to make it a lot easier on me.

## Usage
`./sslcertgen NameOfFile`

And follow the prompts. If the `-i` flag is set, prepare to enter your computers root password.

### Tips:
**Enter pass phrase for xyz.key:** Put in a password, remember it, it asks for it in the next two prompts

**Common Name (e.g. server FQDN or YOUR name) []:** Means put in your domain

**A challenge password []:** Push enter

**An optional company name []:** Push enter

Other prompts are pretty self explanatory. Just read their examples.

## Help

```
NAME:
    sslcertgen

SYNOPSIS:
    sslcertgen [OPTIONS] [FILENAME]

DESCRIPTION:
    Auto-generates a self-signed ssl certificate for speedy web-dev

OPTIONS:
    -i
        Installs the certificate at /etc/ssl/certs/
        Installs the key at /etc/ssl/private/

    -h
        Displays this help list

```

## MIT License
Copyright (c) 2015 Frederick Lawler

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.