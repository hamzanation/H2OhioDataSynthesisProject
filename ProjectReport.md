# H2Ohio Data Synthesis Project

##### Rayan Hamza | May 2021- May 2022

## Overview

<p>In this day and age, working with data has become a vital and necessary skill in many career paths, from general industry to academia, and as such, many institutions are transitioning to a more "data driven" methodology.This adapting towards data centered environments drives a need for proper data storage and maintenence. In this case, a state funded initiative revolving around around the collection, analysis, and modeling of data over the various wetlands in the state of Ohio is in need of a storage infrastructure that is robust and scalable for roughly 10 years. </p>
<p>It is clear that a need for proper data infrastructure has been established, and often times the proposed solution often revolves around a hub for data such as a large relational database or a data warehouse. While organizations could consiously choose to simply bundle their data into some cloud and access as needed, proposing a more structured model, in this case a data warehouse with relational database hubs, would prove to be more optimal, as mentioned in the following section.</p>

### Why Data Warehousing?

<img src="https://1.cms.s81c.com/sites/default/files/2021-01-06/ICLH_Diagram_Batch_02_15-DataWarehouse-WHITEBG.png">

<p>The goal of data awrehoising is to create a trove of historical data that can be retrieved and analyzed to provide useful insigght into the organization's operations, as defined by <a href="https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwiywoWJ5sX2AhUSXc0KHSf3AvwQFnoECBcQAw&url=https%3A%2F%2Fwww.investopedia.com%2Fterms%2Fd%2Fdata-warehousing.asp&usg=AOvVaw1JL6iQpJVmWHOaWHNjeSmy">investopedia</a>. Many organizations in enterprise use Data Warehousing for their business intelligence needs, such as JP Morgan Chase and Nationwide Insurance, and their are many benefits to choosing a Data Warehouse architecture, including but not limited to the following:</p>

- Relational databases within data warehouses create meaningful information by joining the tables within appropriately
- Data warehouse structures can have certain data dimentions coupled or decoupled as needed, depending on the design choice
- Data warehouses work really well in modeling and analyzing big data, and are the source of generation for online analytical processing (OLAP)
- Data warehouses are more easily scalable than unstructured data architectures
- Data warehouses optimize desired inquireies from users and stakeholders

## Designing The Infrastructure

<p>Initial decisions for this project were made from the top-down, looking at the big picture of what is needed for project and accounting for the details as we go. Actual implementation of the project is done from the bottom up, one "hub" of data in the project is given attention, and a database is created to house that data, and from there relationships with other "hubs" are then determined.</p>

### Deciding the appropriate overall architecture

<p>Data warehouses come in many different flavors that suit different needs, in this case, there are lots of hydrogeological data products that may relate to each other, but the relationships don't necesarrily have a large factor of dependence towards them. Wetland images and tabular data that isn't metadata of the images would not be directly related for example.</p>

<p>Work in progress, to be continued...</p>
