## Alfresco Quick Rest Example
This is a very basic example of how to start developing a Rest API on the Alfresco Platform.

It uses:

1. [Maven Alfresco SDK](https://artifacts.alfresco.com/nexus/content/repositories/alfresco-docs/alfresco-lifecycle-aggregator/latest/index.html)
2. [Alfresco Community 4.2](http://www.alfresco.com/products/community/4-2)

#### Step by step instructions of everything I did to create this project
* Typed : `mvn archetype:generate -DarchetypeCatalog=https://artifacts.alfresco.com/nexus/content/groups/public/archetype-catalog.xml -Dfilter=org.alfresco.maven.archetype:` *(Make sure you include the trailing colon)*
* Answered to the archetype questions:
	- 1
	- 3
	- org.alfresco.labs
	- quickrest
	- Y
* Git init and added exclusions
* Imported as a Maven Project into Eclipse
* Added README.md
* Git commit

### License
Copyright (C) 2013 Alfresco Software Limited

This file is part of an unsupported extension to Alfresco.

Alfresco Software Limited licenses this file
to you under the Apache License, Version 2.0 (the
"License"); you may not use this file except in compliance
with the License.  You may obtain a copy of the License at

 http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing,
software distributed under the License is distributed on an
"AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
KIND, either express or implied.  See the License for the
specific language governing permissions and limitations
under the License.