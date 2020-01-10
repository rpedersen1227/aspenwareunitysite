---
published: true
---
## Unity V4 Roadmap

Unity v4 Roadmap
Unity v4 is targeting 0.9 of the Ski Standards API Specification.  This will serve as the launching point for the standards specification.  Version 4 will also support the standards documentation approach and May 2020 hackathon requirements.  Our goal is to be able to move from Unity v4 to a following version that will be fully compliant with the ski standards v1.0 specification.
Unity V4 Community Portal and Hackathon Platform.  Aspenware will go live with a Community Environment that is based on the GitHub Pages Platform.  This environment will provide documentation, endpoint specifications, and executable backend.  It will also provide a standard set of code segments for both client engagement and server provider development.  This Portal and Platform will serve as the basis for the Ski Standards environment.
Version 4 will focus on creating a consist vocabulary that can drive a master data management enterprise architecture.  The vocabulary improvements in the areas of Customer, Product, Pricing, Location, and Time will serve as the foundation for Resort MDM implementations.  Synchronization methods supporting mutation and subscription will also need to be introduced.
This release will also focus on achieving greater parity among the various POS solutions.  Unity v3 made great strides in implementing most mainstream POS solutions.  The degree of API support varies greatly between POS solutions where RTPOne is the best supported solutions.  Our goal is to enhance the overall coverage of the other POS Solutions.
Version 4 will also work to upgrade the foundational technologies like .NET Core, Swashbuckle and Identity Server.  The fast pace of technology in area’s like OpenID Connect, OpenAPI and RESTful requires Aspenware to continually track, upgrade and evolve our solution.
Unity v4 will complete our transition to a “GitHub like” nodeID.  Version 3 made significant progress in this area.  V4 will transition NodeId to represent a centrally managed “MasterId”.  The MasterId will align with the Source Master System as defined in the “Discover Services”.  The RESTful payload will adopt a standard NodeId and Identifier standard.
Version 4 will also move forward with new improved API around Itinerary, Loyalty and Payment API’s.
This release will enhance the Unity Client Library to better support versioning.   Aspenware will investigate the use of NSwag in generating client side libraries.  
Unity V4 will continue to improve the scalability and extensibility of the Unity Services and Provider Platform.  Aspenware will investigate the viability of introducing a “Plugin” pattern that allows third parties to add Unity API extensions that flow into swagger spec as well as API Provider implementation. 
    
Extend/Cleanup taxonomy
-	Consistent vocabulary throughout API
-	Remove any POS specific language (use common/abstract model)
-	Make all API’s RESTful with proper response
-	Reduce payload size
-	Move endpoints that align with information modeling

Technical Debt
-	.NET Core 3.1
-	Swashbuckle v5 (OpenAPI 3.0 Compliance)
-	Identity Server 4 v3.1  (works with .NET Core 3.1,  OpenID Connect compliance)

Improved Cross POS API Support
Central Identity Service
-	
Central Discovery Service
NodeId Enhancements
-	NodeId that leverages central routing services (discovery service)


