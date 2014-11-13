# Employment History

### Switch Concepts Lt.

#### Linux Systems Administrator/Software Developer (2013--Present)

> Work in progress
> - [ ] Review this section
> - [ ] See if there is a better way to layout this section

 Responsible for developing and deploying internal tools and infrastructure to run and support the platform as well as to imvrove the application developers productivity and help to increase the reliability of the product.

### Achevments
- Ported the core product to chef drastically simplfing creation of new nodes
- Deployed a ci server to enable both unit testing on every push as well as full end to end testing during the release process.
- Built a system backed by cassandra to collect hundreds of metrics from thousands on nodes every minute to enable analytics on system performance and alerting of problems.
- setup a 60tb haddop cluster that stores raw impressions logs from over 1000 nodes that are used to make critical business decisions on a daily basis.

---

During MySQL time at Switch Concepts I have worked on a large variety of project.

**Automate deployment of services**
> - [ ] Rewrite this

wrote chef recipes to automate the deployment of their main product.

Re-factored and improved the build systems of various components to support packaging into rpms
greatly simplifying the deployment of these components. Setup a repository to distributed these rpm
with an api so that automated build system can upload to them.


**Centralized Logging system**  
Setup a fluentd/elasticsearch/kibana stack for thousands of servers to log to giving a single place
where all logs can be viewed and allow problems to be detected that would have otherwise gone
unnoticed.

**Consistent development environment**  
Ported a number of components to work under vagrant to greatly simplify setting up the development
environment and to ensure it closely matched the production environment.

**Continuous Integration Testing**  
Setup bamboo and stash and help to configure their automated testing suite

**Metrics system**  
Help to implement parts of a large scale distributed metrics collection and visualization system
capable of collecting metrics hundreds of metrics from thousands of servers ever minute.

**Centralize authentication and user management**  
Setup and maintain a set of FreeIPA (kerberos/openldap) nodes and helped to port most of our
internal to authenticate against it dramatically simplifying user management and increasing security
of our infrastructure.

**Hadoop cluster**  
Set up and help to maintain a hadoop cluster to capture raw data from our core product that is now
used as part of business analytics that help drive the business forward.


### University of Southampton

#### Networking Internship (July 2011--September 2011)

I was responsible for developing and rolling out a Eduroam wireless network across campus, which
involved deploying a FreeRadius and MySQL servers, as well as, configuring a Cisco Wireless
Controller, Cisco switches and flashing access points. I also developed a web server to display
stats and view the logs which are stored in the MySQL database.
