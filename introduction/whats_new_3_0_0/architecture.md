# Architecture

The following are major system architecture updates we have done in ContentBox 3.

### ColdBox 4 
We have updated the entire core to leverage ColdBox 4 and modularity.  We have completely re-architected all modules to adhere to ColdBox 4 standards and rely on CommandBox CLI for package management and resolutions.  This update in itself is worth noting as it not only modularized even more ContentBox, but gave it a source code reduction and performance boosts.


### Oracle + PostgreSQL Support
Oracle and PostgreSQL are now fully supported.


### BCrypt Support
The default algorithm for passwords is now BCrypt with work factors for better security and entropy.


### Password Policy
A new password policy is now in place for ContentBox for new and current users.  


### Core Settings
Introduction of core and user based system settings. This allows for the distinguishing of what are ContentBox core settings and custom user or module settings.


### Settings Cluster Storage
You can now decide in which caching engine to store global ContentBox settings. This provides the way to fully scale ContentBox in any cloud provider.


### SSL Support + 
SSL support can now be found everywhere in ContentBox for both the UI and admin modules.  Users can even select specific pages for users to transition into or out of SSL for richer eCommerce or secure experiences.


### Internationalization
The majority of all modules have been now translated into English, Spanish, Italian, German and French.  There is still work to do to localize the entire source, but it is coming.


### ContentBox Express with JRE
Our entire build process has been revamped and now we can produce ContentBox Express editions with included Java runtimes for Linux, Mac OS X and Windows.


### Automated Asset Pipeline
We have completely re-architected our asset pipeline and ContentBox now comes with an integrated development pipeline for front-end development.  All assets are now tracked via bower and npm.  We have created a developer guide for anybody working with the admin assets and collaborating.


### CommandBox Integration
All development is now done with CommandBox and all dependencies are tracked via CommandBox.  This provides a smoother update processes for users and also a great workflow for collaboration.

### DocBox API Docs
DocBox now generates all API docs with much better documentation and readability.
