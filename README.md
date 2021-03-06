# TinNews
## A Tinder-like News App
![1](https://user-images.githubusercontent.com/63382428/106566170-cc6dc880-64e4-11eb-9f25-69c646d64d44.PNG)

Designed the Instagram flavor News app based on Google Component Architectural MVVM Pattern.

![9](https://user-images.githubusercontent.com/63382428/110220498-ec453300-7e7a-11eb-9cc4-d6f1a7e4b172.PNG)

TinNews Architecture


![5](https://user-images.githubusercontent.com/63382428/110220164-98d1e580-7e78-11eb-82d2-06397c498644.PNG)

Jetpack Navigation Component

![2](https://user-images.githubusercontent.com/63382428/110220158-97082200-7e78-11eb-8d14-93571fbcc1f6.PNG)

Android provides MVVM support built into the ecosystem with Jetpack. 

![3](https://user-images.githubusercontent.com/63382428/110220159-97a0b880-7e78-11eb-865b-58db0db240a5.PNG)

A RecyclerView is used for displaying a large amount of data in the fashion of a list (single column) or a grid (multi-column).

![4](https://user-images.githubusercontent.com/63382428/110220160-97a0b880-7e78-11eb-8439-5ccb4ce83906.PNG)

We need to display the content image of the news for a better experience. We use a library called Picasso to load any given image URL in a single line. Other popular image loading and caching libraries include Glide and Fresco.

![6](https://user-images.githubusercontent.com/63382428/110220349-eac73b00-7e79-11eb-970e-10db77b2f99c.PNG)

We use CardStackView to implement the Tinder’s like and unlike swipe gesture handling

![7](https://user-images.githubusercontent.com/63382428/110220378-2d891300-7e7a-11eb-8996-ac1ea9450180.PNG)

Room has the following concepts:
1. Database contains the database holder and serves as the main access point for the underlying connection to your app’s persisted, relational data.
2. Entity represents a table within the database.
3. DAO contains the methods used for accessing the database.

![8](https://user-images.githubusercontent.com/63382428/110220442-aa1bf180-7e7a-11eb-8410-78c8598f4e58.PNG)

How the database work with the rest of the MVVM architecture

