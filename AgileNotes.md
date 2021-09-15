# Agile and SDLC


### SDLC 

* Waterfall :  
A linear model which flows only in one direction until the maintenance stage, with a single integration and test step.

*  V-model : 
A linear model with testing for each design step

*  Spiral : 
Repeated cycles of identification, design, build, and evaluation

* Agile : 
Short cycles through the steps of requirements, design, development, testing, deployment, and review.



### DevOps Concepts 

* Infrasturcture as Code
    * Cloud compute, virtual switches, etc.
* DRY (Don't repeast yourself)
    * Write code/configuration that can easily be repeated.
* Customer first
* Shared responsibility (don't play the blame game)

## Characteristics of Good Commit Messages

#### Good commit messages should:

* Have a subject and a body; summarize the changes in 50 characters or less, then provide detail.
* Use imperative language (e.g. "refactor get_data function for readability")
* Wrap long messages. It's ok to write long commit messages, but use newlines to wrap them.
* Explain what was changed and why.

### Types of Customers 

#### Internal Customers:
* Leadership
* Developers
* Data Science 

#### External Customers:
* Individuals who buy your product or service 
* Other Businesses who resell your product or service

### Using Agile in a non-Agile environment
#### Certain orgs. may not easily move to Agile and never mid-project!

* Create a culture of version control and documentation
* Ensure code is DRY
* Use Infrastructure as Code
* Automate testing

# Azure Concepts 

## Load Balancers 

* Load Balancers support IPV4 / IPV6
* Load Balancers increase availability by distributing network traffic across resources
* Some Load Balancers are called Application gateways and are context aware
* LB's may operate on at the Application layer of the OSI.


## Azure Monitor / tools 




# Terraform

## Infrastructure as Code 

* Infrastructure as code, Automate and not tie up resources
* Code has to live somewhere, so we use Version control
* Multiple forms of documentation.
  * Scripts can be in any language (custom scripts)
  * configuration management tools ex. Ansible (idempotence - that is, if we perform the same operation over and over again, we still get the same result ) 
  * Server templating tools such as Packer
  * Orchestration tools, suck as Kubernette's 
  * Provisioning tools, create the infrastructure ex. Terraform(Servers, Load balancers, etc)

## Details of Terraform:
* TF is a configuration tool, uses a config file (JSON)
* Uses the HCL language, uses providers to talk to different types of clouds or in house infrastructure
* multi-plaform & multi-provider
* can create immutable infrastructure


