# **Module 8 | Mapping Agricultural and Rural Land Use OSM Map Features**

* * *


## **Overview**

**Module Title:** Module 8 | Mapping Agricultural and Rural Land Use OSM Map Features

**Activity Title:** In this module, students will map road map features associated with agricultural practices and rural areas at location(s) in the world.  Students will explore similarities and differences between the arrangement of these facilities in areas where agricultural practices and rural landscape differs.  In addition, students will use two USDA products, the Census of Agriculture and the USDA CropScape tool to gain a sense about the agricultural industry in location(s) of study.  A suggested implementation is provided.

**Image:** [https://wiki.openstreetmap.org/w/images/e/ef/Landuse%3Dfarmland.jpg](https://wiki.openstreetmap.org/w/images/e/ef/Landuse%3Dfarmland.jpg)

**Image credit:** [Creative Commons Attribution-ShareAlike 2.0 license](https://wiki.openstreetmap.org/wiki/Wiki_content_license) | [https://wiki.openstreetmap.org/wiki/User:Harry_Wood](https://wiki.openstreetmap.org/wiki/User:Harry_Wood)

**Made by:** TeachOSM Contributors

**Educator Prep Time:** Approximately 1 hour

**Module Time:** 50-90 minute class

**Activity** X of Y: 8 of 12

**Read | Write | Participate on the Web**

**21st Century Skills:**

* Collaboration

* Communication

* Creativity

* Problem-solving

**Web Literacy Skills:**

* Search

* Navigate

* Evaluate

* Open Practice

* Contribute

* Share

**Learning Objectives:**

1. Given the list of **[map features](http://wiki.openstreetmap.org/wiki/Map_Features)**, students will be able to identify and compile a list of OSM map features and their associated tags applicable to farm-to-market/agricultural/farm/ranch roads and rural roads in the two areas identified for analysis.

2. Using **[overpass turbo](https://overpass-turbo.eu/)**, students will be able to examine the mapped agricultural and rural roads of the pertinent map features locally and begin to identify and prioritize issue areas where:

    1. possible improper tagging exists

    2. farm-to-market roads exist but are not properly tagged

    3. rural roads exist, but are not properly tagged.

3. Following identification and prioritization of areas where work is needed with **[overpass turbo](https://overpass-turbo.eu/)**, students will work on issue areas either directly within overpass turbo, using the **[id editor](http://ideditor.com/)** or the **[TeachOSM Tasking Manager](http://tasks.teachosm.org/)**.

4. Utilizing the **[USDA Census of Agriculture](https://www.agcensus.usda.gov/)** and the **[USDA CropScape](https://nassgeodata.gmu.edu/)**, students will research the different types of places, and the people that are involved in their operations, that produce agricultural products and crops throughout the United States.

**AP Human Geography Connection:**

* **[Agricultural and Rural Land Use | A - D](https://apstudent.collegeboard.org/apcourse/ap-human-geography/course-details)**

**Audience:**

* Educator Resources: High School Educators

* Module Activities: High School Students

**Materials:**

* Computer

* Internet Connection

* Web Browser (e.g. Mozilla Firefox)

* * *


## **Educator Preparation**

**OSM Work**

1. Explore the **[OSM Wiki | Map Features](https://wiki.openstreetmap.org/wiki/Map_Features)**.

    1. Run a search on the Map Features page.

        1. Examine the map features with the **[highway](https://wiki.openstreetmap.org/wiki/Key:highway)** key.

        2. A subset of the map features with the highway key will be used to explore agricultural roads and rural roads within OSM.

        3. Review the **[highway=service](https://wiki.openstreetmap.org/wiki/Tag:highway%3Dservice)** tag.  Students will use this tag to edit all farm-to-market roads.

        4. Read the **[highway=unclassified](https://wiki.openstreetmap.org/wiki/Tag:highway%3Dunclassified)** tag.  Be sure to cover the *Situations where other tags should be used* subheading.  Notice that it discusses rural roads and agricultural roads.

        5. The motor_vehicle=agricultural tag has been replaced by the **[access=agricultural](https://wiki.openstreetmap.org/wiki/Key:access)** tag.

        **NOTE:**  The access=agricultural key=value tag should only be used if the traffic is restricted to agricultural vehicles.

        6. "Rural roads" fall within different highway tags.  Explore the **[highway=unclassified](http://wiki.openstreetmap.org/wiki/Tag:highway%3Dunclassified)**, **[highway=secondary](https://wiki.openstreetmap.org/wiki/Tag:highway%3Dsecondary), **[highway=tertiary](https://wiki.openstreetmap.org/wiki/Tag:highway%3Dtertiary)** and **[highway=residential](https://wiki.openstreetmap.org/wiki/Tag:highway%3Dresidential)** tags.  These tags are recommended to be explored and subsequently edited as the group of “rural roads” by students as part of this module.

2. Familiarize yourself with these map features and prepare a short presentation to introduce these to the class during a lecture.  Consider just using the map features page and flipping through the key=value tags explained above.  Navigating through the map features page directly provides the students a guide of how they will in turn use the map features page as they work through this module.

    2. Include the definitions of the different map features listed above

    3. Include reviewing a photograph of each map feature

    4. Include examples locally, within the county or regionally of each map feature.

    5. Include examples from some other area where you may wish students to map.

**NOTE:**  It is important for students to see a few examples of any map feature that they will be editing within an area that they are familiar with.  Naturally, whenever possible, local examples seem to work best.

**NOTE:**  It is imperative that you define each key=value tag so students understand that although they will need to use their best judgement in these cases, there is a definition for each map feature to guide their judgement.  There will be cases where roads will fall in the grey area between 2 different tags.  Explain to students that they need to make a decision and choose the "more correct" tag.  Sometimes mapping OSM features is not 100% straightforward and we anticipate that this exercise will certainly highlight this.  This is a part of the process in many areas of open mapping/digital geography.

3. Navigate to **[overpass turbo](https://overpass-turbo.eu/)**.  If you need to familiarize yourself with the overpass turbo open mapping tool, consider using a previous module such as module 7.

    6. Explore the key=value tags previously mentioned locally/somewhere else in your county, state or region to find an area where these tags have been mapped.  If your region does not have rural or agricultural roads, consider moving to another area of your county, state or the United States that does (e.g. midwest).

    7. Take a few screenshots to introduce these areas and the features that are currently mapped to students.  Explain to students that mapped features may have been tagged incorrectly, tagging may be lacking additional tags or features exist that haven’t been tagged properly that need to be updated.

    8. Also, consider highlighting areas where roads exist without tags that might be rural or farm-to-market.

4. Navigate to the id editor within OSM to explore these areas.  Consider taking screenshots and highlighting map features within this open mapping tool as explained above using overpass turbo.

5. If you wish to have students to map an area over the course of greater than or equal to one week, consider opening a task using the TeachOSM Tasking Manager.  If you wish to do this, please reach out to a TeachOSM representative for assistance on creating an account and task.

**OSM-Related Work**

6. Navigate to the **[USDA Census of Agriculture](https://www.agcensus.usda.gov/)** and the **[USDA CropScape](https://nassgeodata.gmu.edu/)**.

    9. Begin by exploring the Census and looking through different tools available.

    10. The [Quick Stats](https://quickstats.nass.usda.gov/?source_desc=CENSUS) tool is a great place to begin to get an understanding either by commodity, by location or temporally.

![USDA National Agricultural Statistics Service | Quick Stats](https://github.com/shawnmgoulet/teachosm-for-school/blob/master/Images/ag-census-quick-stats.png)

    11. The [Web Maps](https://www.agcensus.usda.gov/Publications/2012/Online_Resources/Ag_Census_Web_Maps/Overview/) are a great place to explore the data through a map lense.  Datasets displayed on the map include crops, economics and agricultural business operators, among others.

	![USDA Agricultural Census | Web Maps](https://github.com/shawnmgoulet/teachosm-for-school/blob/master/Images/ag-census-web-map.png)

    12. If you prefer looking at datasets at the state or county level, the [Full Report by State page](https://www.agcensus.usda.gov/Publications/2012/Full_Report/Census_by_State/) is the resource to use.  Here you can also obtain this data from Censuses dating back to 1840.

![USDA Agricultural Census | Publications](https://github.com/shawnmgoulet/teachosm-for-school/blob/master/Images/ag-census-publications.png)

    13. Head over to the CropScape tool.

    14. You will see that your left-hand panel holds the menu of geospatial layers available.

**NOTE:**  Use the panel to turn on and off the different layers such as reviewing the changes in agricultural areas/types over time or exploring the geographic relationship between agricultural practice and surface water body, for instance.

![USDA CropScape | Layers](https://github.com/shawnmgoulet/teachosm-for-school/blob/master/Images/cropscape-layers.png)

    15. Along the banner of buttons at the top of the site, locate the button of the United States filled with an American flag style.  Click on that to launch the *Define an Area of Interest by Geographic Extent* tool.  Walk through the steps of selecting the geographic level you wish to explore and then the region of that level.

![USDA CropScape | Area of Interest](https://github.com/shawnmgoulet/teachosm-for-school/blob/master/Images/cropscape-aoi.png)

    16. There are many other functions of tools available within the CropScape application.  Explore those available, such as creating statistical visualizations of your area of interest or exporting the area of interest’s statistics as a PDF.  Identify those you wish to introduce to your students for them to use to explore.

7. Read **[#TimeToBuild America’s Infrastructure For Agriculture Trade](http://www.globalharvestinitiative.org/index.php/2017/05/timetobuild-americas-ag-trade-infrastructure/)**.  Consider introducing this article to students as a starting point for a discussion.  Then consider introducing the following questions to students for lecture/assignment purpose:

    17. consider touching upon the infrastructure necessary to bring our food to market (e.g. boat, multiple roads, air, train, etc.)

    18. what types of food might use each mode of transportation and why?

    19. what about other countries you may have/are covering - why might the United States differ from them?

    20. what is the role of United States government in getting food to market?  How about the countries you have/are covering?

    21. what is the state of infrastructure in the countries you are covering and is anything/what is being done about it?

    22. what are other countries doing to assist developing nations?

* * *


# In Class Educator Lecture

1. Use the presentation and discussion/questions outlined in the preparation above to present the OSM Map Features students will be editing within this module.

2. Center a discussion around infrastructure necessary to bring food to market locally and within a nation covered in your curriculum.  Consider using the article or some other literature and discussion/questions listed in the preparation above to have a class discussion centered around the topic.

3. Introduce the USDA Census of Agriculture and CropScape tool.  Explain to them how you wish to have them use these resources to gain a deeper understanding of the agricultural practices and industries in the area of study.

4. If necessary, demonstrate to students how they will use overpass turbo, id Editor and/or the TeachOSM Tasking Manager to map these features.  Show examples of these, features and how each open mapping tool would be used to accomplish editing within the area(s) you wish to contribute.



**NOTE:**  If students need a refresher on these tools, please point them to a previous module (e.g. Module 7) where they are covered for them to either begin using or refresh themselves with the tool.

* * *


## **Student Assignment**

*If not already done, students must complete the *_[learnOSM | Getting Started](http://learnosm.org/en/beginner/start-osm/)_ exercises and make their first contributions to the OSM within the High School's municipality prior to starting this exercise.

*With the above, students should have already made their first entry into their journal.*

*Students must continue to contribute to their student journal to describe with text and screenshots of their contributions, issues, questions, etc. when making contributions to OSM.*

*Teachers will create a folder for journals and ask students to save their journals to the folder. (e.g. Google Drive folder or some other place where all have access)*

**_Content produced by the following should be entered into your journal._**

**OSM Work**

1. Research, the map features covered by agricultural and rural roads and understand their definition and examples in the area(s) you will be mapping.

2. Using overpass turbo, examine agricultural and rural roads mapped features in area(s) designated by the teacher.

3. Using overpass turbo, id editor and/or the TeachOSM Tasking Manager, map agricultural and rural road features updating/improving their tagging, adding tags, etc.

4. Wherever possible, compare the network of agricultural roads in different locations and describe their observations in their journals.

    1. How do they differ and why might they differ in the nature that they do?

5. Consider the following issues around the transportation networks of the agricultural products/crops in the area(s) you are working.

    2. Consider different factors that contribute to how the agricultural item is brought to market.

    3. Does the item need to be brought to market in days, weeks, months, etc.?

    4. How might that change the necessary modes of transportation?

    5. What are the modes of transportation available in the area?

    6. Are these applicable modes appropriate for the agricultural product/crop?

**OSM-Related Work**

1. Using the USDA Census of Agriculture and CropScape, search the types of agriculture in the area(s) you are mapping.

    1. Using the USDA Census of Agriculture, consider the following.

        1. what are the demographics of the agricultural products/crops producers in the area that you are working?

        2. Explore the [USDA Census of Agriculture web maps](https://www.agcensus.usda.gov/Publications/2012/Online_Resources/Ag_Census_Web_Maps/index.php), explore the different datasets in the area(s) where you are mapping.

            1. What are the differences between the different areas?

            2. What is the reason behind these differences?

is it historical? | is the government subsidizing the agricultural production?

            3. What is/are the story/stories behind agricultural business(es) and activity(ies) in your area(s)?

    2. Using the USDA CropScape maps, consider the following.

        3. Examine the changes of crop lands over time.

            4. What do the changes tell us about your area(s)?

            5. Is there any evidence of transitions to/from different crops?

        4. Take a look at the relationship between the ‘Cropland Data Layers’ and the ‘Water Layers’.

            6. Are crops in your area(s) concentrated along surface water bodies?

            7. Are there any issues with water quality in these areas?

            8. Might there be/have there been a relationship between water quality impacts and agricultural practices?

1. Coupled with the questions and topic discussed above, choose to either write a one page paper or present to the class your research on agricultural items and existing and the health/state of modes of transportation.  Pair this by reading the **[#TimeToBuild America’s Infrastructure For Agriculture Trade](http://www.globalharvestinitiative.org/index.php/2017/05/timetobuild-americas-ag-trade-infrastructure/)** article.

    1. Consider leading a class discussion around the role of government in the agricultural industry and the transportation networks the industries use.

    2. What about the role of local/national government?

    3. Does government play a role and is it helpful/hurtful?

---
###### If there are any questions, comments or feedback, please Email [TeachOSM](mailto:info@teachosm.org) or Tweet [@TeachOSM](https://twitter.com/teachosm).

---
###### To contribute, please visit the [Contribution page](https://github.com/shawnmgoulet/teachosm-for-school/blob/master/CONTRIBUTING.md) to learn how!
