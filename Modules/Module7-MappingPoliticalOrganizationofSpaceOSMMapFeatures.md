# **Module 7 | Mapping Political Organization of Space OSM Map Features**

* * *


## **Overview**

**Module Title:** Module 7 | Mapping Political Organization of Space OSM Map Features

**Activity Title:**  In this module, students will map political/governmental facilities, properties and other map features associated with politics and the government at location(s) in the world.  Students will explore similarities and differences between the arrangement of these facilities in areas where government structures may differ.  A suggested implementation is provided.

**Image:** [http://mhsaphuge1.wikispaces.com/file/view/european_union2.jpg/290535869/267x227/european_union2.jpg](http://mhsaphuge1.wikispaces.com/file/view/european_union2.jpg/290535869/267x227/european_union2.jpg)

**Image credit:**  Creative Commons Attribution Share-Alike 3.0 License | [http://mhsaphuge1.wikispaces.com](http://mhsaphuge1.wikispaces.com/) | AP Human Geography @ MHS | Mrs. Blankenship's 4th Period Class Fall 2013

**Made by:**  TeachOSM and OpenStreetMap contributors

**Educator Prep Time:**  Approximately 1 hour

**Module Time:**  50-90 minute class

**Activity X of Y:**  7 of 12

**Read | Write | Participate on the Web**

**21st Century Skills:**

* Collaboration

* Communication

* Creativity

* Problem-solving

**Web Literacy Skills:**

* Search

* Navigate

* Synthesize

* Evaluate

* Design

* Code

* Compose

* Revise

* Remix

* Connect

* Protect

* Open Practice

* Contribute

* Share

**Learning Objectives:**

1. Given the list of **[map features](http://wiki.openstreetmap.org/wiki/Map_Features)**, students will be able to identify and compile a list of OSM map features applicable to governmental/political facilities in the two areas identified for analysis.

2. Using **[overpass turbo](https://overpass-turbo.eu/)**, students will be able to examine the organization of the pertinent map features locally and gain an understanding the reason for their arrangement.

3. Using **[overpass turbo](https://overpass-turbo.eu/)**, where necessary, students will update and add pertinent governmental/political facilities both locally and a different, predetermined location.

**AP Human Geography Connection:**

* **[Geography: Its Nature and Perspectives | A - E](https://apstudent.collegeboard.org/apcourse/ap-human-geography/course-details)**

**Audience:**

* Educator Resources: High School Educators

* Module Activities: High School Students

**Materials:**

* Computer / Mobile Device

* Internet Connection

* Web Browser (e.g. Mozilla Firefox)

* * *


## **Educator Preparation**

1. Explore the **[OSM Wiki | Map Features](https://wiki.openstreetmap.org/wiki/Map_Features)**.

* Run a search on the Map Features page.

    * On a Windows machine, press (and hold) the ‘Control‘ key + click the ‘F’ key.

    * On an Apple machine, press (and hold) the ‘Command‘ key + click the ‘F’ key on)

    * To search for features, enter these two keywords:

        * "Politic", followed by “government”.

    * Possible governmental/political map features include:

        * ‘Office | government’ (e.g. Town/City Hall)

            * Looking at Town/City web sites are helpful to locate facilities.

        * ‘Office | ngo’ (e.g. American Red Cross)

            * A site with a list of NGOs similar to [the Massachusetts Nonprofit Network](http://massnonprofitnet.org/mnn-members/) is helpful for location and attribute data.

1. Familiarize yourself with these map features and prepare a short list to share with the class during lecture.  There are likely many NGOs in your local community.  Prepare specific examples of these and prepare to have a discussion with students about them.

    1. What is their mission?

    2. Why do they exist in your community?

    3. How can and why should students get involved?

1. Navigate to **[Nominatim](https://nominatim.openstreetmap.org/)**.

    1. In the search, enter the chosen local municipality your students will be mapping political and governmental map features in.

    2. Click on the ‘Details’ button in the top left.

        1. As you can see in the example screen shot below of part of a return, this ‘Details’ view contains a large amount of data pertaining to map features connected to the municipality.

		![Nominatim | Details](https://github.com/shawnmgoulet/teachosm-for-school/blob/master/Images/nominatim-details.png)

        2. Pertaining to political and governmental data and political organization of space, Nominatim includes: County, state, country, and military properties.

        3. Among other things, the data displayed here includes the political hierarchy, classification of the municipality (city, town, etc.) and contains the direct link to the municipality in Wikipedia.  Familiarize yourself with these.

2. Finally, navigate to **[overpass turbo](https://overpass-turbo.eu/)**.

    3. In the search box, enter the municipality name (Barnstable), county (Barnstable County), state (Massachusetts), then country (United States).

    4. You should see a list below the search box automatically populating as you type.  If you see the municipality before completing above, go ahead and manually click on it in the list.  That should zoom the map to the municipality.

    5. Now, in the left-hand panel, you should see a query already filled out.  Students will edit that query using the map feature(s) they want to look for.

    6. For preparation, click on the ‘Wizard‘ button and enter: "office=government or office=ngo" (without quotations).  Click the ‘build and run query‘ button to return any map features tagged as government and nongovernmental organizations.  Are any missing or wrong?  Note these in preparation for students assignment.

* * *

### **In Class Educator Lecture**

1. Navigate to the **[OSM Wiki | Map Features](https://wiki.openstreetmap.org/wiki/Map_Features)** page.  Discuss with students about government and nongovernmental organization map features they should expect to be looking for/looking to add to the OpenStreetMap locally and in the second area.

2. Navigate to **[Nominatim](https://nominatim.openstreetmap.org/)**.  Following the search for a place of interest, show students how Nominatim returns data about a place and what to look for in the page.  Also, show students the listed map features associated with the subject municipality and political/governmental map features such as military facilities and the municipality's County boundaries.

3. Finally, browse to **[overpass turbo](https://overpass-turbo.eu/)**.  Demonstrate how to build a query to look for governmental and nongovermental organizations in some area.  Have a discussion with students to generate a list of these map features from memory.  Introduce resources such as the municipality web site, state/County web sites, local business directories and chamber of commerces.  Discuss with students what is already mapped and if it is mapped correctly and, also, what is missing from the map.

	![overpass turbo | Query Wizard](https://github.com/shawnmgoulet/teachosm-for-school/blob/master/Images/overpass-turbo-query-wizard.png)

* * *


### **Student Assignment**

*If not already done, students must complete the **[learnOSM | Getting Started](http://learnosm.org/en/beginner/start-osm/)** exercises and make their first contributions to the OSM within the High School's municipality prior to starting this exercise.*

*With the above, students should have already made their first entry into their journal.*

*Students must continue to contribute to their student journal to describe with text and screen shots their contributions, issues, questions, etc. when making contributions to the OSM.  *

*Teachers will create a folder for journals and ask students to save their journals to the folder (e.g. Google Drive folder or some other place where all students and teachers access and save to).*

**_The following should be entered into your journal._**

1. Research, identify and compile a list of applicable **[map features](http://wiki.openstreetmap.org/wiki/Map_Features)** to map.

2. Using **[Nominatim](https://nominatim.openstreetmap.org/)**, search for both the local and other municipality chosen to examine political/governmental map features.  Compare the two locations looking at their political organization of space, and map feature types.  If locations are missing, identify where they should be

    1. Wherever possible, add/update these features using iD Editor.

3. Examine the arrangement of governmental/political facilities locally, followed by the other chosen municipality using **[overpass turbo](https://overpass-turbo.eu/)** by executing queries such as the query for ‘office=government or office=ngo‘ and other map features you have identified.  Other features include police and fire facilities, town/city hall, courthouses and county infrastructure.

4. Describe similarities and differences between the arrangement of governmental/political facilities within a local municipality and another area controlled by a different type of government.  Why might they differ?  Are facilities clustered together?  Might clustering help or hurt governmental operations?

5. Along the way, identify any and all missing governmental/political map features.  At the end, log into **[OSM](https://www.openstreetmap.org/)** and map missing buildings and other pertinent infrastructure, along with adding attribute information.

6. Discuss similarities and differences in the arrangement of governmental facilities in the two locations in class and in their journals.

7. Students should then read about the South China Sea: [South China Sea](http://www.bbc.com/news/world-asia-pacific-13748349)

8. Once divided into equal groups, groups will be assigned to one of the following countries:

* China

* Vietnam

* the Philippines

* Taiwan

* Malaysia

* Brunei

Research the South China Seas claims of their assigned country.  Present the South China Sea claim information to the class.

---
###### If there are any questions, comments or feedback, please Email [TeachOSM](mailto:info@teachosm.org) or Tweet [@TeachOSM](https://twitter.com/teachosm).
---
###### To contribute, please visit the [Contribution page](https://github.com/shawnmgoulet/teachosm-for-school/blob/master/CONTRIBUTING.md) to learn how!
