# Scanning an API

The BURP Suite API Scanner is only for Enterprise and Professional, and the price is very steep.

Luckily, the ZAP API scan is a script that is available in the [ZAP Docker](https://www.zaproxy.org/docs/docker/about/) images.

It is tuned for performing scans against APIs defined by OpenAPI, SOAP, or GraphQL via either a local file or a URL.

It imports the definition that you specify and then runs an Active Scan against the URLs found. The Active Scan 
is tuned to APIs, so it doesn’t bother looking for things like XSSs.

It also includes 2 scripts that:

* Raise alerts for any HTTP Server Error response codes
* Raise alerts for any URLs that return content types that are not usually associated with APIs

## Resources

* [ZAP - API Scan](https://www.zaproxy.org/docs/docker/api-scan/)
