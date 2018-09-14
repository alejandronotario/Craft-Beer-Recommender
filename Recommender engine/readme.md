

# Recommender Engine Folder
<br>
<hr>

_This folder contains different engines tested. It has been consulted different knowledge resources to try with this repository data target_

## The notebooks:

__1."collaborative_filtering_KNN_&_Item_based(RMSE).ipynb"__

It has a collaborative filtering and an item based engines. It has been got the RMSE in both cases and a clear idea of the final dataset structure in which it can be seen a low sparsity. Maybe to make good predictions it is needed more historical data to try filters and reduce zeros.

__2."kneighbors_test_using_beers.ipynb"__

This contains a KNN classifier taking 20 neighbors by beers, gets predictions and accuracy, low

__3."kneighbors_test_using_users.ipynb"__

This contains a KNN classifier taking 20 neighbors by users, gets predictions and accuracy, low, but quite higher than using beers as "y"

__4."collaborative_filtering_recommender.ipynb"__

This recommender allows to select a USER at a drop down list. It would be the case of a person who is already a user of a kind of beers ratings website and get top k beers for every registered user. It is based on Pearson correlation  coefficients sum from its correlation coefficient matrix. The list is sorted by values and it can be taken k  top values. It does not have neither accuracy score nor error evaluation.

__5."recommender_beer_input.ipynb"__

This recommender allows to select a BEER at a drop down list. It would be the case of a person who knows something about beers, visits the website and starts giving information about specific beers she/he knows and get the top k similar beers. It is based in Pearson coefficient from its correlation coefficiente matrix (Beers/Beers). The list is sorted by values. It does not have neither accuracy score nor error evaluation.

__6."recommender_input_style.ipynb"__

This recommender allows to select a STYLE at a drop down list. It would be the case of a person who likes beer but does not know too much about specific brands besides styles. It is based on Pearson correlation coefficients sum from its correlation coefficient matrix (Styles/Beers). The list is sorted by values and it can be taken k top values. It does not have neither accuracy score nor error evaluat"ion.

__7."Recommender_Systems_with_Metrics.ipynb"__

This notebook includes different recommenders.It runs with "df_clean.csv" comming from "Dataset structure.ipynb" included in Data Folder of this repository. The dataset was splitted into train and test sets to calculate few metrics such as the recall and the MAP in order to evaluate the model.  

## File:

_df_to_recommender.csv_
This file comes from /Data notebooks. It can be gererated different files to tests the recommender engines (except 7.)


