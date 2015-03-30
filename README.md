# cors-test
IE8/9 CORS support test

Internet Explorer 8 and 9 have limited support for CORS. Namely:

    Only GET and POST with a content type of plain/text are supported
    It does not support preflight
    No custom headers may be added to the request
    Credentialed requests are not supported
    Requests must be targeted to the same scheme as the hosting page


http://test-cors.appspot.com/

https://github.com/jaubourg/ajaxHooks/blob/master/src/xdr.js
to fix the CORS support in jQuery for IE8/9
XDomainRequest is for IE8/9.
