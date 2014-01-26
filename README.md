drobofree
=========

df for the DroboFS NAS

[Drobo](http://www.drobo.com/) creates nice NAS devices and provide you
with awesome dashboard tools... if you run Windows or OSX.

I run Linux and got tired of guessing how much free space I had. The DroboFS
(and most likely other types) offer you information about the device over
port 5000 but that's not really easy to parse manually, hence I created `ddf`
(Drobo Disk Free)

Examples:

    $ ddf drobo.home.example.com
    Drobo                                 Size           Used         Avail    Use%
    Drobo-FS 1.2.6 [4.44.64324]  2956363038720  2094513102848  861849935872      71

    $ ddf drobo.home.example.com -h
    Drobo                        Size    Used    Avail      Use%
    Drobo-FS 1.2.6 [4.44.64324]  2.7T    1.9T    802.7G       71
