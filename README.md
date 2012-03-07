ASIHttpRequest Static
=====================

A static build version of ASIHttpRequest that can be simply added to your iOS projects.

Usage
-----

1. Build the project
2. Copy ASIHTTPRequest.framework to your project
3. Add following frameworks/libraries to project:
  - libz
  - SystemConfiguration
  - CoreGraphics
  - MobileCoreServices
  - CFNetworks
4. Replace your ordinaty #import "ASIHTTPRequest.h" with #import <ASIHTTPRequest/ASIHTTPRequest.h>

Check document at [ASIHTTPRequest](http://allseeing-i.com/ASIHTTPRequest/) for ASIHTTPRequests usage.

Note
----

- Reachibility is included
- ASIWebPageRequest is not included
- Only armv7 is built (There were issue try to build with armv6 and cant solve it yet)
