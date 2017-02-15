This is a DOI version of [proxify-umd-javascript](https://github.com/spurioso/proxify-umd-javascript) that creates links to library resources based on DOIs. 

The script creates a URL based on the DOI, adds a proxy prefix to the URL, shortens the result using Bitly, and opens the resulting shortened link in a new window.

The resulting link will route the user through the University of Maryland's proxy server for user authentication.

Take a look at a [working example](https://umd.libapps.com/libguides/admin_c.php?g=326432&p=3398458)

To adapt to your own library you need to make three changes to proxify-umd.html:

1. Change ```var proxyprefix``` to your own institution's proxy prefix
2. Change ```var key``` to your own Bitly API key.
3. Change ```var login``` to your own Bitly user name
