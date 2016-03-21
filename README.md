## How to use Custom APIs with PowerApps and Logic Flows

Custom APIs are simply any RESTful APIs that you can use bring in and use with your PowerApps and Logic Flows.
The APIs that you register with PowerApps can be hosted anywhere, as long as a well-documented specification that conforms to the [OpenAPI](https://openapis.org/specification) standard is available.

#### Authentication

You can use one of the two authentication mechanisms supported today: 
* ##### Basic Authentication
* ##### OAuth 2.0
*Support for API key authentication is coming soon.*

Following is the list of all the supported OAuth 2.0 providers, with support for more comming soon
* Azure Active Directory
* Box
* Dropbox
* Facebook
* Google
* Instagram
* OneDrive
* SalesForce
* Slack
* Yammer

You can learn more about how to specify the authentication type in your OpenAPI (Swagger) document [here](https://github.com/OAI/OpenAPI-Specification/blob/master/versions/2.0.md#securityDefinitionsObject). 
If your API endpoint allows for unauthenticated access, you should omit the securityDefintion object from the OpenAPI (Swagger) document.

### Examples
* [Spotify](https://some.link/)
* [GitHub](https://some.link/)
* [Azure](https://some.link/)

