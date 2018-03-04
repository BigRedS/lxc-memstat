# lxc-memstat

Script for getting per-container memory usage under LXC:

    root@inewscloud-web-a:~# lxc-memstat 
    MEM      RSS      CONTAINER
    4282     663      somesite.com
    7087     868      anothersite.net
    2720     125      mycontainer
    5826     891      yourcontainer
    4515     732      hiscontainer

the header's printed to STDOUT so you can pipe this through `sort` 
and friends without ruining the formatting.

Presumably one day there'll be a more complicated version of this
bundled with LXC generally :)

