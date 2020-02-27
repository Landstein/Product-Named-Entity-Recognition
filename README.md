# Product-Named-Entity-Recognition

[Indepth Blog on the Project][1]

[1]:https://medium.com/@eric_landstein/build-a-custom-named-entity-recognition-model-ussing-spacy-950bd4c6449f

Train a model to find the names of products in text

Goal is to identify products, locations, conditions, price and other relevant information in text about products.  

### Example of Early Stages of the Model:

Takes in the following text:


![](https://github.com/Landstein/Product-Named-Entity-Recognition/blob/master/Images/Screen%20Shot%202020-02-18%20at%2010.16.28%20PM.png)


Outputs the correct Tagged words using Named Entity Recognition: 

![](https://github.com/Landstein/Product-Named-Entity-Recognition/blob/master/Images/Screen%20Shot%202020-02-18%20at%2010.16.44%20PM.png)

### Product Trending 
#### Goals
- Determine Price Trends
- Determine average price for product
- Identify good deals as soon as they come onto the market place 

Once the entites have been labeled using the NER model, rows in the dataframe can be filtered for a specific product.  In the below example I filter for iPhone X.  Using this tool I can identify good deals quickly based on market history.  Using the data on the iPhone X i would be looking to buy below 480 as that has been the mean sale price from December 2019 - February 2020.  

![](https://github.com/Landstein/Product-Named-Entity-Recognition/blob/master/Images/Screen%20Shot%202020-02-24%20at%209.16.34%20AM.png)


### Listing Location's 
#### 12/20/2019 - 2/26/2020

![](https://github.com/Landstein/Product-Named-Entity-Recognition/blob/master/Images/Country%20Map.png)

