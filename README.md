# API-Gateway: All About API Gateway and it's Features

-	API Gateway is an Component which acts as an EntryPoint for our APIs
-	API Gateway is a combination of SSL Certificates, Authentication, Authorization
-	APIs will be hosted on the WebApplication
-	Every time when client makes a requests ... it will first go API Gateway 
	
	-	API Gateway will be entry point for all the requests
	-	API Gateway ensures that Requests are HTTPS using SSL Certificates
	-	API Gateway verifies that user is Authenticated
	-	API Gateway ensures that user has Authorized for specific resources and roles
	-	This way API Gateway acts as GAURD to requests coming to Application
	
-	API Gateway can route requests to different Micros-services depending on the path

		
## 	Features of API Gateway

### Feature #1. Separate out cross cutting concerns

-	SSL Termination
-	Authentication
-	Authorization
-	DDoS Protection/ Throttling


### Feature #2: Routing

-	Requests will be routed to appropriate Micros-services

	
### Feature #3: Replacing Multiple Client Calls with Single API Calls

-	Client don't needs to make multiple calls to sever
-	Instead Client only makes one HTTP call
-	API Gateway in turn will makes all the required different multiple calls
-	Finally API Gateway will in-turn send Consolidated Response back to client


### Feature #4: Caching the Response with Threshold Time

-	API Gateway can Cache Response for frequent Requests
-	Caching improves performance rapidly


### Feature #5: Routing Based on Headers, Paths, Params

-	Load Balancing across multiple instances of Micros-services
-	A/B Testing 
-	Canary Release
-	Splitting Requests across new version and old version of Micro-services
-	Routing to Right Service
-	Routing to Multiple copies Services


### Feature #6: Backward Compatibility and Protocol Support

-	API Gateway will be able to handle requests from advanced protocols like HTTP 2.0 and Websocket
-	API Gateway takes responsibility of converting New Protocol to Older Protocols
-	API Gateway provides monitoring facilities using Dashboard and can manage request centrally



### Feature #7: Can expose Services to Third Party Services

-	Using API Gateway we can expose our Services as an API Service so that an Third Party can use them
-	Examples of API Gateway
	
	-  Self Managed
		
		1.	Apache
		2.	NGINX
		3.	Spring Cloud Gateway
		
	-	Cloud Services
		
		1.	AWS API Gateway
		2. 	Azure API Gateway
		3.	Google Cloud Points
		4.	Apigee

