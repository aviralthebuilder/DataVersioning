# DataVersioning
This is a documenation of a possible implementation of pachyderm into Jupyter
and see whether we can implement data versioning to a certain extent
let us list the various tasks of the mini project and implement it along the way:
Before going into any details, make sure you have the necessary stuff installed
for this.
1. We create a repo for the initial raw data. We will call it SMSTRAINING. This
   is where we will be putting different versions of input data (since this particular
   data set only has two columns, we will be giving more focus to the amount of data,
   i.e. varying the the number of rows)
2. It is now time to preprocess the data, i.e., clean the data and/or apply some feature engineering to it
   Like the last version, we will have two versions, one where there are less features than the other one
   just to mess around with data a little more.
3. Now that we have access to the preprocessed data it is time to analyze it a bit more by some extensive Feature 
   Engineering methods such as TfIDF and so on.
4. Now that we have done the SMS spam analysis for for one version of rawData and one version of preprocessed
   data, we finally get to try what we have all been waiting for: APPLYING DATA VERSIONING.
   Just for reference purposes, I will be refering to the 4 forms of raw data as RAW1(3000 rows) RAW2(5572 rows)
   RAW3(5000 rows) and RAW4(4000 rows) and I will be refereing to the more advanced preproccesing as PREPROCESS1
   and the lesser preprocessing method as PREPROCESS2. 
   NOTE: THE PREPROCESSING EXAMPLES USED HERE CAN ALSO BE IMPLIED AS AN ANALOGY FOR MODELS. EVERY MODEL CAN BE
   CODED IN SUCH A WAY THAT CERTAIN VERSIONS ARE MORE ADVANCED(for lack of a better word ~ compact maybe?) THAN 
   OTHERS
   I will be providing the results of all of it the end of it all
