# OnlineShopperClickstreamAnalysis

Goal: 
A) Can we cluster user sessions to help marketing teams? (Using K-Means Sklearn)
B) Can we predict whether a user session will end up in a purchase? (Using Decision Tree and Random Forest Sklearn)

The Target variable Revenue(Binary) or whether a purchase is present: is constantly referred to for each features and clusters relevance to see if we are working towards our goal understand more about user sessions. 

Contents:
1. Datasets:
- Datasets (Original Datasets)
- SMOTE_Files (Containing 10 modidified balanced training datasets)
- Test_Set_File (Contains 1 Test Set)
2. Exploratory_Analysis.ipynb (Exploratory Analysis performed for the literature review along with some calculations to correlate variables )
3. Clustering.ipynb (Used to Cluster the Dataset using K-Means, along with some code looking to find meaning from the clusters)
4. Cross_Validation.ipynb (First used to split training and test set, Second used to split training ds into 10 folds, Thirdly, balances the revenue each fold with SMOTE)
5. Decision_Tree (Function, Function call for each k-fold, and Confusion Matrix)
6. Random_Forest ('' '')

