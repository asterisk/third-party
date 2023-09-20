# asterisk/third-party

These tarballs are retrieved by the Asterisk build process
when it processes the "third-party" directory in the Asterisk
source tree.  The directory tree for this repo must be as
described below. 

* `<library>`
  * `<version>`
    * `<library>/<version>.tar.gz`
    * `MD5SUM.TXT`
    * `SHA256SUM.TXT`

The `third-party/<library>/Makefile.rules` file in the
Asterisk source tree contains links to these files.
Alternate or additional tarball file formats are
acceptable in the above directory tree as long as at
least the one expected by Makefile.rules exists.
