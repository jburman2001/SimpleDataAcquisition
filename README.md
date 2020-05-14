# SimpleDataAcquisition
Data Acquisition using Simple Webscraping Techniques

## Introduction
This small project is meant to demonstrate how to perform a simple webscrape using Python. 
Webscraping, when done ethically, is a very useful tool to collect data from the Internet. 

I scraped the data from a shopping website called Flipkart. 
Specifically, I obtained the names of the product (including their specs), the prices of the product, and the ratings of the product. 
Afterward, I made the script generate a .csv file which includes all of the information there. 
With the given information, I as a consumer can use this to compare products and find the best one based on these metrics.

## The Process
Wepages are created with HTML files, and the information users see on the webpage are typically stored in containers within the HTML. 
For many reasons, shopping companies group these containers and give them their own ID. 

For instance, there is a container that holds other containers such as the price, the rating, and the name of the device. 
That overall container (for this case I will call a product container) has an ID attached to it. 
For this script to work, it tries to identify all the containers on the webpage by comparing the IDs.
Once the program can find the container, it looks in the contents to identify more containers with their own individual components. 
After identifying those containers, the program looks into the contents and gathers the information from them.
At the end, the program organizes the data collected into a .csv file for use.

## Effects of the Process
As previously mentioned, webscraping is an effective tool for data retrieval.
In a world where information is constantly generated, it is very difficult (maybe even merely impossible) for a person to collect enough data for processing by hand.
With webscraping technologies, this makes data collection painless and effective; however, there are illegal implications.

It is important to note that while webscraping is useful, it must be done in an ethical manner. 
One may not use this data for financial gain nor should use it as a weapon against another side. 
If one chooses to do so, legal actions can and possibly will take place such as lawsuits and charges.
