
# Cart / Order / Payment debugger

[START HERE](https://nkuehn.github.io/commercetools-order-payment-debug/)

A single page app in the most literal sense. It is intended to be opened by anyone in a browser without any additional software installation. 
You currently need an access token which you easiest get on https://impex.sphere.io/playground (open the headers view in the response)

The deployment model is similarly simple:  merge the master branch into gh-pages to "deploy". No build necessary. 

fork of the node SDK with stuff needed here:
https://github.com/nkuehn/sphere-node-sdk

Issues here:
 - many
 - show and find interlinked carts and orders.  
 - Either hyperlink the related ones or do an even more nested layout. 

Open Issues in the SDK (this here contains a patched one):
 - basic auth via header on OAuth (not allowed in url, so here you need a token )
 - add read access to not yet fully implemented 2.0 endpoints. 
 - sensible error notices if options are insufficent
 - get library build process fixed (no more "default" to get the lib)
 - provide public library on JS CDN. 

