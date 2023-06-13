# Movie Recommender
<h2>Recommendation system using Machine Learning Techniques</h2> 
<br>
<br>
<h2>------------------------------------Content Based Filtering----------------------------------</h2>

<h2>NumPy (Numerical Python)</h2>
(arrays and functions on arrays) 
NumPy is a library for python language which adds support for large, multi-dimensional arrays and matrices, along with large collection of high-level mathematical functions to operate on these arrays.
 <br>
Example:  <br>
data.toarray()	converts the data to an array

<h2>Pandas</h2>
Pandas is a library for python language mainly for data manipulation and analysis. 
It provides data structures and operations for manipulating numerical tables and datasets. <br>
Example:  <br>
Df = pd.DataFrame(data)	create a dataframe from data(array) <br>
movies = pd.read_csv(‘location/dataset’)	read dataset as a dataframe <br>
dataframe.head()	shows first 5 rows of dataframe <br>
dataframe.head(1)	shows first row <br>
df1.merge(df2, on=’column’)	merge 2 dataframes based on specified column <br>
dataframe.shape	shows shape of dataframe (rows x cols) <br>
dataframe.iloc[0]	list 0th row from the dataframe <br>

<h2>AST (Abstract syntax tree)</h2> <br>
Example: <br>
ast.literal_eval(string object)	It converts string object to list

<h2>Scikit-learn</h2>
Sklearn is a machine learning library which provides support for various machine learning tools like vector, etc. <br>
Example: <br>
countVectorizer class :	get vector for words occurring in each tag out of 5000 words (0=no, 1=yes) <br>
cv = countVectorizer(max_features=5000,  stop_words=’english’)<br>
cv.fit_transform(tags column).toarray()	 <br>
cosine_similarity class :		get distance of each vector with every other vector<br>
cosine_similarity(vectors) 

<h2>NLTK	(Natural Language Toolkit)</h2>
Python library to process English language.  <br>
Example: <br>
PorterStemmer class :	remove similar words, convert them to standard (love, loving, loved=love)<br>
ps = PorterStemmer()

<h2>Pickle</h2>
Python pickle module is used for serializing and de-serializing python object structures.
pickle.dump(dataset.to_dict(), open('dataset.pkl','wb'))		send dataset to folder as dictionary
<br>
<h2>--------------------------------------------------------------------------------------------</h2>
<br><br>
<h2>-------------------------------Collaborative Based Filtering--------------------------------</h2>
