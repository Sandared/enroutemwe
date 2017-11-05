# A work in progress of the OSGi enRoute Redesign

## Old structure/content and what changes are planned

* Book
	1) Guide
		* Should be called Introduction?
	1) Tutorials
		* should be moved to fit an overall storyline
	1) Examples
		* should rather be at the end for thos who want to see examples or like to self-teach them OR they should be incorporated in tutorials/documentation
	1) Documentation
		* is rather a principles section that should be better embedded into the overall storyline of the book
	1) Service Catalog
		* Those should be chapters of the book ... each building upon the others to show the effect of encapsulating everything into services/bundles
	1) ???
		* There seems to be a chapter missing
	1) App Notes
		* Similar to *Documentation* but with sepcific tools, partially just like tutorials
		* Should be moved to fit an overall storyline
	1) Links
		* Make this the reference section of the book
		* Maybe add additional links to OSGi based projects?
			* Drombler
			* Liferay
			* ...
	1) Videos
		* **REMOVE**
		* One video is a pitch for a 2016 event
		* One should be moved to its accompanying tutorial
		* The one left is not enough to make an own site for it
		* Maybe refer to a general [Youtube query for OSGi enRoute](https://www.youtube.com/results?search_query=osgi+enroute)
	1) Known Issues
		* **REMOVE**
		* Those should be on GitHub
	1) FAQs
		* **REMOVE**
		* Those FAQs are moved into their own chapters with more context and examples (e.g. in context of a tutorial)
* OSGi Sepcifications
	* **REMOVE**
	* Would be way more useful in context, so I plan to embed a link to the respective RFC/RFP in its accompanying tutorial/book entry and a general hint to the RFC/RFP Repositories in the book
* Forum
	* **REMOVE**
	* does not exist anyway
	* Make mailinglists more prominent somewhere else!


## Planned new content/structure

* Home
	* Landingpage
	* Peptalks to motivate the users to use OSGi (enRoute)
	* News to show them the project is active
* Documentation
	1) Introduction / Motivation
		1) Current problems
		1) What is OSGi
		1) How is OSGi adressing current problems?
	1) ONE DAY TUTORIAL ... or 10 minutes, depending on the developer (to show off a little bit and get the user involved with basic OSGi concepts)
		1) Reuse old Base Tutorial but replace Angular with Vaadin 8 so the user only has to deal with Java
		1) Explain each step in detail, so even programming beginners will understand them
		1) Show shortcuts for more experienced developers
		1) Result of this tutorial should be something useful.
			* TODO App?
			* RSS Reader?
	1) Plain old Java vs. OSGi
		1) Why Plain old Java is not enough
			1) Jars are not enough
			1) One Classpath is not enough
			1) Access modifiers are not enough
			1) *main* is not enough
		1) OSGi to the rescue
			1) Modules, Components and Bundles
			1) Jars and the MANIFEST file
			1) Bundles and their classpaths
			1) Bundles and information hiding
			1) Lifecycles
			1) Versioning
			1) Dependencies
	1) Jigsaw vs.(/and) OSGi
	1) DI vs.(/and) OSGi
	1) OSGI Specifications, RFCs/RFPs and Implementations
	1) Bundles
		1) Manifest and what BND does for you
		1) Lifecycle and Activator
		1) Information Hiding
		1) API vs Implementation (maybe data also?)
		1) Semantic Versioning
		1) Bundle-Classpath
		1) Fragment Bundles
		1) Common Pitfalls
			1) Cannot Resolve API
			1) NoClassDefFuondError
	1) Declarative Services
		1) Specification / Implementations
		1) Dependency Injection and DS
		1) Lifecycle
		1) @Component
			1) Properties and their effects
			1) @Activate/@Modified/@Deactivate
		1) @Reference
			1) Properties and their effects
			1) Event Strategy vs. Field Strategy vs. Lookup Strategy
		1) Common Pitfalls
			1) Calling other Services from within bind/unbind methods
			1) Exceptions in lifecycle methods without Logging
			1) Inheritance is not working
			1) Explicit and implicit immediate services
	1) OSGi Design Patterns
		1) Whitebooard
		1) Extender
	1) Concurrency and OSGi
	1) Services you are free to use ;)
		1) Configuration Admin
		1) Event Admin
		1) HTTPService
		1) Coordinator
		1) Metatype
		1) Admin
		1) ....
