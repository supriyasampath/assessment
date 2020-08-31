Automation solution is crafted using Behaviour Driven Development (BDD) software development approach via Serenity BDD tool. BDD is a refined combination of practices from Test Driven Development (TDD) and Acceptance Test Driven Development (ATDD). BDD leverages their techniques along with other techniques around conversations, collaborations and automation to ensure that a team delivers what the business wants the first time around

3.1.	Framework Components

	Gradle is used to build the tool and also for execution via Gradle Task 
	JUNIT Runner invokes the execution using Cucumber with Serenity options
	Cucumber executes features files provided in the Runner
	Feature file in turn calls the corresponding Step Definitions which calls the Steps involved in executing the steps mentioned in the feature file
	Steps calls functions created in the corresponding Pages 
	Functions in the Pages leverage Framework Utility Classes as required
	Functions in the Pages consume Test Data specified in datasheets as well as Properties files
Serenity publishes Test Results at end of every execution
