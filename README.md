#Clef Vault
A Chrome extension for logging into any site with Clef

##Development
Currently there is no way for you to store credentials in the extension.  Ya know, it's WIP.

Anyways, run the following in the `_generated_background_page.html` to store some test credentials:

     delegate.saveCredentials(document.location.host, "fauxClef", "fauxPassword", function() { });

I've also added an options page, which is just a simple login form.  This can be used for testing the extension when offline.