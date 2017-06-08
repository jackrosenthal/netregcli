# Mines Network Registration Command Line Interface

This is a neat little tool to register your computers on the Mines network.
Requires [Python 3](https://www.python.org) and
[requests](http://docs.python-requests.org/en/master/).

## Usage

    usage: netregcli [-h] [-u USERNAME] [-f AUTHFILE] [-o OS] [-s STATUS]
                     macs [macs ...]

    positional arguments:
      macs                  A list of MAC addresses to parse (in pretty much any
                            format)

    optional arguments:
      -h, --help            show this help message and exit
      -u USERNAME, --username USERNAME
                            MultiPass Username (if no credential file)
      -f AUTHFILE, --authfile AUTHFILE
                            MultiPass Credential File (if no username)
      -o OS, --os OS        Operating System (default is "yes")
      -s STATUS, --status STATUS
                            Status (default is "undergraduate")

If you choose to make use of the `authfile`, format it like so, and obviously
make sure only you can read it.

    username = myusername
    password = verysecretpassword

If your pasword starts with a spacebar, put two spaces after the `=`.

