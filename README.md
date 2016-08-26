
# Cart / Order / Payment debugger

[START HERE](https://nkuehn.github.io/commercetools-order-payment-debug/)

A single page app in the most literal sense. It is intended to be opened by anyone in a browser without any additional software installation. 
You currently need an access token which you easiest get on https://impex.sphere.io/playground (do a request on "projects" to get a sufficient token. get the token from the headers view in the response). 

The deployment model is similarly simple:  merge the master branch into gh-pages to "deploy". No build necessary. 

Issues here:
 - also find by email, order-id  order number etc.  (needs to do two separate queries and merge the results)
 - show payment status fields (interface code and text) 
 - make interactions smaller or expandable
 - show and find interlinked carts and orders

Open Issues in the SDK (this here contains a patched one):
 - basic auth via header on OAuth (not allowed in url, so here you need a token )
 - add read access to not yet fully implemented 2.0 endpoints. 
 - sensible error notices if options are insufficent
 - get library build process fixed (no more "default" to get the right class)

Open platform issues:
 - CORS header for User-Agent
 - CORS response that gives a lifetime for the cors request
 - CORS headers on the Auth API to be able to get a token. 

