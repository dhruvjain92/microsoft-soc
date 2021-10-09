# Microsoft Authenticator API - Simplified Token Generation
This will generate an access token for the App that has been registered in AD. Just pass a unique ID (that can be defined when logic app is edited) and the scope. This will encapsulate your Client ID and Client Secret to decrease the chance of them getting revealed and leaked. Instead you get an access token that's valid for one hour.
