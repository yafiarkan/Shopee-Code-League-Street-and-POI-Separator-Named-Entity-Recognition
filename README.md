# Shopee-Code-League-Street-and-POI-Separator-Named-Entity-Recognition
Shopee Code League is a competitions held by Shopee in 2021. My team and I are in the top 250 out of 1000+ teams throughout Southeast Asia and China. This project is about separator between street names and place names with complex datasets, where the dataset has an indeterminate format and unnecessary special characters. The model created has an accuracy of 50% for the test data.

# Background
At Shopee, we strive to ensure our customers' highest satisfaction for their shopping and delivery experience - fast and accurate delivery of goods. This can be better achieved if we have key address elements for each user address which allows us to accurately geocode it to obtain geographic coordinates to ship the parcel to our customers. These key address elements include Point of Interest (POI) Names and Street Names. However, most addresses that Shopee receives are unstructured and in free text format, not following a certain pattern. Thus it is important for us to develop a model to precisely extract the key address elements from it.

# Methodology
We made two different models, that is to distinguish specifically for street names and specifically for place names. The street name's model has two classes, street name and not street name, the places model has two classes, place name and not place name. Both models use the same dataset but different configurations. The results of the two models are combined and produce complete results.

# Result
The results obtained are that it can be used to predict special characters as street names and place names with 50% accuracy.
