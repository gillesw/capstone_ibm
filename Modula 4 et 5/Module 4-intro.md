# Opening a new japanese restaurant in Paris

**April 2020**

## Applied Data Science Capstone by IBM - Coursera MOOC


!["Paris"](Tour_Eiffel_360_Panorama.jpg)

## Paris

Paris is the capital of France:
- 105 $km^2$
- 2.150 millions of people
- About 11700 restaurants

For many people, Paris is the most beatiful city of the World. At least, it's the most visited one. If museum, art gallery and historical buildings are the real reasons to visit, everyone has to lunch.

Moreover, Paris is the economical heart of France and about 10% of French people are working in Paris or around. And they have to lunch.

## Japanese Food

France is well known for its cooking traditions. A lot of French restaurants are opened in Paris.

But Japanese food is becoming increasingly popular. So my projectt is to find the best place in Paris to install a new japanese restaurant.

## Data and Process

- Download the position of each of the 20 boroughs of Paris
- Download the 100 first venues in the 500m around the position of each borough
- Make some analysis on the datas
- Use *K-Means Clustering* to classify
- Find the right cluster to install the new restaurant :
    - not too much japanese restaurants
    - some restaurants to define a cluster where people are going to restaurants.

Let's consult the [Jupyter Notebook](https://github.com/gillesw/capstone_ibm/blob/master/Modula%204%20et%205/Module4-intro.ipynb) 

## Results

!['Results'](cluster4.png)

The right cluster seems to be the $4^{th}$ one, so one of this 3 boroughs :

- $7^{th}$ arrondissement : **Palais-Bourbon**
- $14^{th}$ arrondissement : **Observatoire**
- $8^{th}$ arrondissement : **Elysée**