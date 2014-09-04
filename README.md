opentaba-client-dummy
=====================
#This is a dummy website to supply a [opentaba-client](http://github.com/niryariv/opentaba-client) clone per municipality

##Why?
Because Github Pages only allows one domain or subdomain per gh-pages website,
and we need to operate one subdomain per municipality, all having exactly the 
same code!

##How?
All you gotta do to create a clone is create a new repository, add this one as 
a remote, pull from this repository's master to your repository's gh-pages, 
edit the CNAME and index.html files to suit your needs, push, set up your 
subdomain and forget forever.

Or you can just use the fabric tasks create_dummy and delete_dummy as found
in [opentaba-server](http://github.com/niryariv/opentaba-server)

##Consequences?
Your dummy repository's index.html will simply async-load the actual site's 
index.html and then completely replace itself with it. Might get a bit of a 
delay while loading everything where you see all sorts of weird stuff.
