# Overview of the analysis:


To improve Dana’s webpage and dynamic table, filters for multiple criteria were added using javascript. Users can now filter for UFO sitings by filtering any combination of the city, state, country, and shape.


## Results:

To perform a search users can select one or multiple criteria. Users have the ability to search by a particular date to see 

For instance, A user wants to know how many  "Unknown" shapes there were on 1/1/2010. The users selects "unknown" in the shaps drop down, click the filter table button and the following data will appear:

![selection of_unknown shape](https://user-images.githubusercontent.com/74462990/125225061-39576c80-e294-11eb-9b6e-a5c5f9e842bc.PNG)

The search can be further refined by adding additional filter criteria such as "state". In this case, it 

![refined_search](https://user-images.githubusercontent.com/74462990/125225183-70c61900-e294-11eb-9f21-583d0c950df3.PNG)

Clicking on Filter Search will clear the table data


## Summary:


There are several drawbacks to the website. 

One draw back of the design is that when one enters a search by a particular date, the incidents appear in chronological order, sorted by the date requested. 

![date search](https://user-images.githubusercontent.com/74462990/125225941-bdf6ba80-e295-11eb-8028-ea9f59b7fe63.PNG)


Another drawback is that the date field is required in order to perform a search. If the date is blank, and a user clicks on "filter table" no results populate in the table.

Suggest rewriting the javascript to 
1. The amount of data that could potentially be returned may be really large. To give users who may want to look a certian period of time, make changes to the date field to provide "date range" selection (i.e. bewtween xxx and yyy)
3. Make coding changes to date filter to only populate the table with data for the requested date


