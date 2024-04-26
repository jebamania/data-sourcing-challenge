# data-sourcing-challenge

## Outline
Part 1: Access the New York Times API.

Part 2: Access The Movie Database API.

Part 3: Merge and Clean the Data for Export.

## Part 1: Access the New York Times API

In this section I connected to the NYT api to collect articles about movies.

I needed to get the title of the movies, but I did not use the given method to find that information and did it my own way, still using the apply() method.

The given method `lambda st: st[st.find("\u2018")+1:st.find("\u2019 Review")]`

I was not aware of the find method as that had not been taught to us and google did not show me this method when I was troubleshooting. This way is probably more effective but my way is my own.

We then build a list from the new 'Title' column.

## Part 2: Access The Movie Database API.

## Part 3: Merge and Clean the Data for Export.