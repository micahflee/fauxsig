# fauxsig

This is a simple script to help you be more confident in downloading files that don't have digital signatures. It works by downloading the file once over your normal internet connection, then downloading it again using Tor, and comparing the two files. If they're the same, you can have a higher degree of confidence that you weren't attacked during the download. If they're different, then you can tell that an attack is most likely going on, either at your naked internet connection or at the Tor exit node you randomly chose.

## Usage

```sh
$ fauxsig [URL]
```
