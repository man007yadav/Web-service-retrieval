Web\_Service\_Retrieval
=====================

A basic automatic web service retrieval mechanism based on co-sine similarity.

This project was done as a part of _Web Technologies and Applications_ course in V<sup>th</sup> semester B.Tech program in Department of Information Technology, National Institute of Technology Karnataka, Surathkal during the academic year 2014.

Methodology
===========

We have used the service interfaces to search for similar services. We extract the &lt;&lt;__profile:hasinput__&gt;&gt; and &lt;&lt;__profile:hasoutput__&gt;&gt; of 1000+ OWL document, each of which correspond to a particular web service.

We have chosen 7 categories for web services which are : Communication, Economy, Education, Food, Medical, Travel and Weapon. We have considered a 7-dimension vector space where each of these mentioned category represents a dimension. After extracting the service interfaces from their corresponding OWL document we construct an input as well as output vector for the service.

We indexed all the services in our dataset using the same technique. After indexing we process the user's request by contructing an equivalent vector representation of the query and then using co-sine similarity to find out similar web services.

The phase two of the project incorporates semantic search based on wordnet.

More details about the implementation techniques can be found in our project report.

Installation
============

__Pre-requisites__ : Linux, Apache Server, Python

__Getting Started__ : The indexation is already done. To quickly run the system on Linux, one just needs to host the owls folder and access the search.php file.


