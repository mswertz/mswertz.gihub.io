---
title: MOLGENIS
intro: How to get MOLGENIS as service, download or as open source software code 
layout: blue
---
# Hosting and support
You can get a MOLGENIS ready to use from two hosting/support providers:

**Genomics Coordination Center**  
University Medical Center Groningen  
email: <molgenis-support@umcg.nl>

**TraIT service desk, TraIT foundation**   
Lygature, Utrecht  
website: <http://www.ctmm-trait.nl/service-desk/>

# Download and install yourself
You can also install MOLGENIS on your own machines (Licence: LGPLv3)

**Install on Linux**  

To install on Linux you need
* MOLGENIS 'WAR' file (Choose download WAR [here](https://search.maven.org/search?q=g:org.molgenis%20AND%20a:molgenis-app here))
* Java Platform (JDK) 8u171
* Apache Tomcat v8.5.x
* PostgreSQL v9.6.x
* Elasticsearch v5.5
* Optional: OpenCPU 2.0 (enables R scripting feature)
* Optional: Python 3.6 (enables Python scripting feature)
See [Manual](https://molgenis.gitbooks.io/molgenis/content/quickstart/guide-tomcat.html).

**Install using Docker (experimental)**

For testing purposes we now use Docker. We have the ambition to also use it for production but then you need to configure data persistence. However feel free to use our docker as a starting point. Get [Docker Images](https://github.com/molgenis/docker)

# For programmers
The complete source code of MOLGENIS is open source available at [Github](http://github.com/molgenis/molgenis)

You can find developer documentation as part of the [Manual](https://molgenis.gitbooks.io)
