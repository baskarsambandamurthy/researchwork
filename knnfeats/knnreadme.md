# KNN Feats Generation
> Note: It uses inner train and test datasets

with knn feats score improved from 0.39 to 0.43 <br> 
but without knn feats and with target encoding score improved from 0.39 to 0.41

##### pending issues
1. Test don't have some knn generated columns
2. Minimum proportion columns, standard deviation columns are not renamed properly. The code has been updated, but not executed
3. euclidean distance not tried out. In order to do that, either user_id, video_id and category_id originals have to be removed or one hot encoded to keep them.
