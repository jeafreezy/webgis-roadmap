**Open-Source Web-GIS Development Roadmap**

**Introduction**

The advent of the web has transformed everything around us and GIS is no exception. Web-GIS is the pattern or architectural approach for implementing the modern GIS.It enables the distribution of maps and processing tools without time and location restriction to users. Web-GIS allows visual interaction with the geospatial data on the web (either on our mobile phones, desktop software,tablets and practically anywhere with a web browser). This article will provide a step-by-step learning guide, garnered from years of experience of the two authors as well as extensive research, to support your Web-GIS development journey.

The motivation behind this guide emanates from the challenge the authors experienced personally at the outset of their career as GIS Developers. They learned unnecessary tools and technologies that were perhaps fun to them at that time, but frankly wasted a lot of their time. We don&#39;t want you to experience the same. That&#39;s why we decided to cook up this learning guide for Web-GIS development. We clearly are not the best GIS Developers out there and not even the first, but we all have our interests as humans. Ours, just like many others out there, is strongly in teaching the little we know. And we hope this guide will make it easy for you to get started with Web-GIS development, land you your first job as a GIS Developer or even help you kickstart your start-up or project ideas.

It&#39;s important to mention that there exists a lot of programming languages e.g Python, Javascript, C, C++, R, Java, Rust, Go etc and we understand that they can be overwhelming. Which of the languages should I learn first? Where should I start from? I&#39;m done with Python, what next? These are the common questions we have received from beginners in the geospatial programming world. Don&#39;t worry, stick with us, this guide would provide answers to most of your questions. Don&#39;t forget that only a few people can set a goal and achieve it. It takes determination and self motivation to start and learn a new technology to a satisfactory level. Without motivation you might not be able to make any progress. What always helps is **to try and learn one thing at a time in a certain order, hence the need for a guide such as this.** Note that the recommendations in this guide are not to be necessarily followed strictly, please feel free to go at your pace! Infact,feel free to refine this guide to your taste!

**Blogs**

- To be updated soon

**Table of Contents**

- To be updated soon

**Learning Guide**

Below is a flowchart that summarises the whole learning guide to become a Web GIS developer.

![Web-GIS roadmap guidline](https://github.com/jeafreezy/webgis-roadmap/blob/main/img/webgis_roadmap.jpg)

1. **Start with GIS and a GIS Software**

Web-GIS can be considered as a variant of GIS, therefore it is expedient to have a solid understanding of what GIS itself entails. Knowledge of a GIS software is also highly recommended because sometimes, these software helps in making our development work easier and faster, they can also act as a testing environment. The underlying concepts of most of these software are the same, therefore it&#39;s important not to shy away from the fundamentals of GIS. It&#39;s as important as learning to code, because this knowledge would help you in decision making , doing what is right and following best practices.

**Recommendation:** Learn GIS and play with QGIS for about a month.

**Resources:**

- [**QGIS Tutorial**](https://www.qgistutorials.com/en/docs/3/building_a_python_plugin.html)
- [**GIS Introduction**](https://mgimond.github.io/Spatial/introGIS.html)
- [**Book: GIS Fundamentals**](https://www.amazon.com/GIS-Fundamentals-Geographic-Information-Systems/dp/1593995520)

1. **Then Pickup HTML and CSS**

HTML is a markup language for documents designed to be displayed in a web browser. HTML is used to create pages and make them functional. The CSS is the style sheet language used to create the visual appearance of HTML. HTML and CSS are easy to understand, simple to edit, supported by all browsers. You can create pages with HTML and CSS (eg. login/sign up page, contact us page) and build small projects (eg. facebook login page, youtube clone etc) on it.

**Recommendation:** Learn the important concepts of HTML and CSS in a week or two.

**Resources:**

Here are some useful resources &amp; projects for learning HTML and CSS:

- [W3schools HTML](https://www.w3schools.com/html/default.asp)
- [W3schools CSS](https://www.w3schools.com/html/default.asp)
- [Create a contact form (youtube video)](https://www.youtube.com/watch?v=Db5jCkrVgAw)
- [Create a navbar with flexbox (youtube video)](https://www.youtube.com/watch?v=PwWHL3RyQgk)
- [Make facebook login page (youtube tutorial)](https://youtu.be/UqYjdaCfgvE)

1. **Learn JavaScript**

JavaScript helps to add the interactivity to your HTML and CSS pages. It is mainly used for client-side purposes. Nowadays, people are using it in server-side ([NodeJs](https://nodejs.org/en/)), in games development ([EaseJs](https://createjs.com/easeljs)), in mobile app development ([React Native](https://reactnative.dev/)) as well. But for the web-GIS developer roadmap, you just need to learn it&#39;s application on web development only. That means client-side and server-side only. JavaScript helps us to put logic in the rendering of the pages. Show or hide more information with the click of a button, Zooming in or zooming out on a map, displaying animation to the page etc are some use cases of the javascript.

**Recommendation:** Learn fundamentals of JavaScript for another 2 weeks or more.

Here are some useful resources &amp; projects for learning JavaScript:

- [W3schools JavaScript](https://www.w3schools.com/js/default.asp)
- [17 JavaScript Projects for Beginner](https://mikkegoes.com/javascript-projects-for-beginners/)
- [Learn JavaScript freeCodeCamp](https://www.youtube.com/watch?v=PkZNo7MFNFg)

1. **Learn about mapping libraries and other required utilities**

The most common thing required in a web-GIS portal is the data visualization interface. The data visualization interface can be built easily with the help of mapping libraries. Here are the lists of some most commonly used mapping libraries;

- [LeafletJs](https://leafletjs.com/) **:** It is the open-source, lightweight javascript library
- [Open layer:](https://openlayers.org/) It is also an open-source javascript library
- [Mapbox:](https://www.mapbox.com/) It is an American provider of custom online maps for websites. It is not totally free. Check the [mapbox pricing here](https://www.mapbox.com/pricing/).
- [Google mapping API:](https://developers.google.com/maps) It is the web mapping API provided by google. It is also not totally free. Check the [google mapping api pricing here](https://cloud.google.com/maps-platform/pricing).
- [Turf JS](https://turfjs.org/): Advanced geospatial analysis for browser and Node.js. etc

You can choose one of the above libraries for the visualization of the spatial data. You don&#39;t need to learn all the libraries listed above. We recommend you to learn leaflet or open-layers.

Also along with that you can learn some other utilities such as [bootstrap](https://getbootstrap.com/), [jquery](https://getbootstrap.com/), as well. These utilities are totally optional. You can also move forward after reading the mapping libraries only. But if you learn about these utilities then it will help to develop the interface rapidly and easily.

**Recommendation:** Learn about mapping libraries for another 3 weeks. Instead of learning the basics of all libraries, master one. If you consider learning other utilities as well, spend additional days on them.

Here are the some project ideas that can help you to improve your knowledge

- Visualization of administrative boundary dataset (district, region etc) into map
- Build web-GIS basic tools (eg. get coordinate, get current position, full screen view, custom zoom in/zoom out button etc)
- Create the simple portal for geospatial data visualization

**Resources:**

- [Leaflet from basic to advance (youtube playlist)](https://youtube.com/playlist?list=PLyWyQBSWLw1NH1wsA0wkSMTlQ45P0AqCj)
- [Leaflet tutorials](https://leafletjs.com/examples.html)
- [Open layer tutorials](https://openlayers.org/en/latest/doc/tutorials/)
- [Qgis2Web tutorial](https://www.qgistutorials.com/en/docs/web_mapping_with_qgis2web.html)
- Read from the official website of the required library

1. **Now It&#39;s time to start working with map servers**

For publishing a small amount of the structural dataset, learning mapping libraries is enough. But the complexity will increase when you have a large volume of data from different sources. To manage such a problem we need a web map server. Map servers are the servers which can easily manage the large amount of geospatial dataset and provide the Open Geospatial Consortium (OGC) standard services like Web Map Service (WMS), Web Feature Service (WFS), Web Coverage Service (WCS). One of the most commonly used mapping servers is geoserver. The geoserver is an open source server for sharing, processing and editing the geospatial data. Here is the list of some most commonly used mapping server below:

- [GeoServer](http://geoserver.org/) : An open-source server for sharing geospatial data.
- [MapServer](https://mapserver.org/) :Mapserver is an open-source platform for publishing spatial data and publishing interactive mapping applications to the web.
- [GeoTool](https://geotools.org/) : The open-source java GIS toolkit.
- [GeoNetwork](https://geonetwork-opensource.org/) : A catalog application to manage spatially referenced resources.
- [GLG map server](http://www.genlogic.com/) : Generic Logic Inc. is a premier provider of real-time graphics, data visualization, HMI Scada and custom GIS solutions for software developers around the world.
- [Open Map Tiles](https://openmaptiles.org/) : A platform to self-host open-source maps.
- [Deegree](https://www.deegree.org/) : An open source software for spatial data infrastructures and the geospatial web.

In this stage it is better to learn about the [OGC standards](https://www.ogc.org/docs/is) as well. After understanding the OGC defined standards only you can build a better web-GIS platform.

**Recommendation:** You should spend at least 3 weeks on learning web map servers. Spend more time on OGC standards and its use. Learn geoserver and its application in detail.

**Resources:**

- [GeoServer and Leaflet Web-GIS (Youtube Playlist)](https://youtube.com/playlist?list=PLyWyQBSWLw1OS7HojnpX6aogfm7LtF39S)
- [GeoServer documentation (Recommended)](https://docs.geoserver.org/)
- [GeoNetwork documentation](https://geonetwork-opensource.org/docs.html)
- [OGC standards](https://www.ogc.org/docs/is)

1. **Learn about databases and backend**

For the web-mapping things and simple applications, upto step 5 is ok. But in case of a large application you need a database and backend as well. In general, a database is used to store the geospatial data and the backend is used to query and get the required information in any web-applications. The backend can control and send the logic to the web-application. There are lots of programming languages and frameworks purely dedicated to backend. The most popular languages are, python, php, javascript, java, ruby, rust etc. The most popular frameworks are django, laravel, ruby on rails, flask, expressjs, spring etc. You can choose one language first and learn the framework later. Let&#39;s suppose you want to learn about django (Python framework), you need to spend some time on learning python before.

In this stage, you should learn at least about the following things,

- About the Structured Query Language (SQL)
- About the API (GET, POST, PUT, DELETE) request
- At least develop one Create, Read, Update, Delete (CRUD) project
- About the Object Relational Mapping (ORM)
- Working with PostGIS and it&#39;s extensions such as PG Routing

Using the backend, now you can connect the mapping server and create the interactive web-GIS portals. GeoJSON serializer, GeoSpatial data visualization portal using PostGIS database etc are some of the beginner level backend projects on web-GIS.

**Recommendation:** Learn about Django. You should spend at least 3 weeks learning the databases(PostGIS/PostgreSQL combo recommended) , spatial SQL and backend technology.

**Resources:**

- [Spatial bookmarking note (Youtube playlist)](https://youtube.com/playlist?list=PLyWyQBSWLw1OUfqcPzO6AceuGpC5gr-_n)
- [Introduction to Web Mapping and Web GIS ( Udemy course)](https://www.udemy.com/course/introduction-to-web-mapping-and-web-gis-2020-geodjango/?referralCode=72E09BDD6D9C8ECE2169)
- [Web mapping and Web-GIS from Dev to Deploy 2021: GeoDjango (Udemy course)](https://www.udemy.com/course/web-mapping-and-web-gis-from-dev-to-deploy-2021-geodjango/?referralCode=14893C9BD7E7D959F865)
- [Make a Location-Based Web App With Django and GeoDjango (Blog)](https://realpython.com/location-based-app-with-geodjango-tutorial/)
- [QGIS and the Spatial Database](https://jeafreezy.hashnode.dev/section-4-qgis-and-the-spatial-databasepostgis-ckoln6gzi0a5r2gs1axaocrm3)
- [A playlist to dive into Spatial SQL and PostGIS by the great Quiseng Wu!](https://www.youtube.com/watch?v=fgS1eVPPBiElist=PLAxJ4-o7ZoPcvp0ETujkLVCmKIGj-YvlG)
- [Official Introduction to PostGIS](https://postgis.net/workshops/postgis-intro/introduction.html)
- [Interactive learning platform by Crunchy Data](https://learn.crunchydata.com/training/postgis)
- [Geodjango playlist](https://www.youtube.com/watch?v=pxX6gI48eh4)

1. **Learn a frontend frameworks (Additional)**

Frontend frameworks help to determine the logic, structure, design, behaviour and animation of every element you see on screen when you interact with web applications. The frontend framework makes it easy to build the web pages faster. We can say this as an additional thing since we can build the web-GIS applications without learning any frontend frameworks as well. The most popular frontend libraries on javascript are as below,

- [React](https://reactjs.org/): React builds the UI in component based structure. It is supported and maintained by Facebook.
- [Vue](https://vuejs.org/): Vue builds the UI in model-view-viewmodel structure. It is not supported by any big company but lots of developers around the world maintain it.
- [Angular](https://angularjs.org/): Angular builds the UI in MVC pattern. It is supported and maintained by google.

**Recommendation:** You should spend at least two month on learning a frontend frameworks of choice.

**Resources:**

- [Top 10 webGIS UI 2021](https://youtu.be/KULAc4P1Sh4)
- [React documentation](https://reactjs.org/docs/getting-started.html)
- [React courses](https://reactjs.org/community/courses.html)

**Final Notes**

The list we have put together is absolutely non exhaustive. We all know the geospatial industry keeps growing on a daily, there are emerging technologies we didn&#39;t capture such as; Augmented Reality(AR) and Virtual Reality(VR), Spatiotemporal Asset Catalogue(STAC), Cloud Optimized Geotiffs(COGs), Google Earth Engine, Microsoft Planetary Computer and many more earth observation tools and technologies. The goal of the article was not to overwhelm you with trending technologies and we believe you&#39;ll learn about them as you make progress. Just get started first!

Finally, we hope you find this article helpful, if you do kindly share with your networks and should in case you have any questions, comments or suggestions, feel free to reach out on social media or shoot us an email! Happy learning!

**Written by:**

1. [Tek Kshetri](https://www.linkedin.com/in/iamtekson/)

Tek is the research Associate at Geoinformatics Center, Asian Institute of Technology, Thailand. He is mainly working on web-GIS technology and spatial data analysis.

1. [**Emmanuel Jolaiya**](https://linktr.ee/JolaiyaEmmanuel) is a GIS developer with a really really really special interest in geospatial community development.

**TODO**

- Clean up repo
- Contributions guideline
- Deploy on GitHub pages
- Constant improvement
- Table of contents
- Add learning guide flowchart
- Add more geospatial books to resources
