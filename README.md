# Coursera_Final_Project
## Opening a Mexican Restaurant in Hong Kong

### Introduction/Business Problem
Hong Kong - also known as the “Fragrant Harbour” - has been dubbed the Financial Hub of the East. The city’s established financial status has attracted tens of thousands of foreigners to conduct businesses here, which has in turn contributed to its diverse culinary scene. Although an eclectic mix of restaurants hailing from all of Asia, Europe, and the United States can easily be spotted on the streets of Hong Kong, the city seemed to be lacking in options for authentic Mexican cuisines. In this capstone project, we will be exploring the neighborhoods of Hong Kong to help **potential Mexican restaurant owners** select the prime location to kick start their businesses. Given Hong Kong’s packed and fast-paced nature, I believe this report would be a useful starter guide for potential Mexican restaurant owners to narrow down their location options.

Target Audience: Potential mexican restaurant owners  

### Data Description
The dataset - “District Offices and Sub-offices in Hong Kong” - is originated from ArcGIS Hub. It contains district offices and sub-offices spanning across the 18 districts in Hong Kong. Coordinates of the offices are included as well. Though I could simply use the dataset comprising only the 18 districts in Hong Kong, I figured that might not be the most accurate way to represent the neighborhoods in Hong Kong, since each district is different in size and population. Hence, I’ve decided to use the “District Offices and Sub-offices” dataset to better represent the proportion of each district - as bigger and more populous districts tend to have more offices.

In total, the dataset contains data of 36 district offices or sub-offices. Since a lot of unnecessary features were included in the original dataset, I will be creating a new dataset containing only vital information for this project. They include **office name, address, district, latitude, and longitude.** 

Using Foursquare data, we can seek out districts that are lacking in Mexican restaurants and would serve as a good business opportunity. Additionally, in order to select a good district, I will also be looking at the types of venues within the 18 districts via exploring the **most common venues in each district.** The prime locations would be ones that are near entertainment venues with a vibrant nightlife. Using the clustering method, we will seek out the most appropriate cluster of districts as a starter reference for potential Mexican restaurant owners. However, information on property prices and rental prices will not be considered or analyzed in this project.
