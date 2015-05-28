# AEM/CQ Instance creator
A basic applescript to quickly create AEM instances

I got tired of recreating different instances of AEM, so I decided to make this basic applescript that allows for you to auto create an AEM instance structure. I

##Inputs
* instance creator script **...applescript to run**
* license.properties **...license file for AEM, you need to supply this. :)**
* Content Packages folder
  * Use this folder to store any common content packages you want your instances to start with. Ex service packs, [AEM commons](http://adobe-consulting-services.github.io/acs-aem-commons/), [Sightly REPL tool](https://github.com/Adobe-Marketing-Cloud/aem-sightly-repl), project based packages, etc
* Instances folder
  * Use this folder for storing your AEM instance .jar files.

## Outputs
General output
 
* aem-runmode-port.jar **...where runmode and port are determined by the script**
* jarFileOriginalName.version **...where jarfileOrginialName is the original file name**
* crx-quickstart
     * install
         * *List of content packages added*  **...all the content packages selected from the script**
* license.properties
