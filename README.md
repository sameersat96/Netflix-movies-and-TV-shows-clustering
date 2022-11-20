# Netflix-movies-and-TV-shows-clustering

![image](https://user-images.githubusercontent.com/95841292/181676154-4c6e72ed-ae2d-4ae1-91c6-7c450768fb4e.png)


# 📖 **Introduction**

Netflix,Inc. American subscription streamigservice and production company. Launched on August 29, 1997, it offers a film and television series library through distribution deals as well as its own productions, known as Originals.
It is the second largest entertainment/media company by market capitalization.



![image](https://user-images.githubusercontent.com/95841292/182011305-1c804efe-9688-4e5c-a787-9e86d1a2af38.png)



# 📖**Problem statement**

This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.

In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.


# 📖**Dataset features**

1.	 Show id: Unique ID for every Movie / TV Show 
2.	 type – Identifier - A Movie or TV Show 
3.	 title – Title of the Movie / TV Show
4.	 director-director of the content 
5.	cast –Actors involved in the movie / show 
6.	 country – Country where the movie / show was produced 
7.	 date_added – Date it was added on Netflix 
8.	 release_year – Actual Release year of the movie / show
9.	 rating – TV Rating of the movie / show 
10.	 duration – Total Duration - in minutes or number of seasons 
11.	 listed_in – genre 
12.	description – The Summary description

# 📖 Visualization 

![image](https://user-images.githubusercontent.com/95841292/202914096-ce821c94-d81b-430c-a794-fe7491fc02d1.png)








# 📖**Conclusion**
1.	Netflix has 69% of its content as movies, so movies are  more popular on Netflix than TV shows.
2.	United States has the most number of movies and shows followed by India and United Kingdom.
3.	TV-MA rated content is maximum in number in the dataset. This rating indicates that the content is for mature and adult audience above the age of 17.
4.	There is an exponential raise in the number of TV shows and movies distributed by Netflix in the recent years.
5.	Text cleaning and vectorization was done on the combined features of the dataset which includes origin country, leading cast member, rating type, content type and description for clustering analysis.
6.	Optimal number of clusters were found out to be 5 with silhouette coefficient value of 0.362

7.	Principal component analysis was performed in order to reduce the higher dimensionality which improved the silhouette coefficient to 0.42. Even though there's improvement in the silhouette score, these cannot be compared as these are two different method of pre processing is involved.
8.	Recommendation based on cosine similarity is also done on the same transformed data.



# 📋 Execution Instruction

The given IPython Notebook can be either downloaded to be run on your local Jupyter Notebook or can be directly run on Google Colab.


# 📜 Credits

Sameer Satpute | Data Scientist | Machine Learning Engineer | Deep Learning enthusiast

special thanks to Mahima Phalkey

Contact me for Data Science Project Collaborations

[![image](https://user-images.githubusercontent.com/95841292/202914376-d5a83f3d-110a-4476-896e-1da078b185dc.png)](https://www.linkedin.com/in/sameersatpute/)
[![image](https://user-images.githubusercontent.com/95841292/202914715-787f6ae3-d9f6-491c-9cae-c717131ddebd.png)](https://github.com/sameersat96)
[![image](https://user-images.githubusercontent.com/95841292/202914883-bce71634-6c2b-4305-8020-4b240cb76e41.png)](https://medium.com/@sameersatpute)
![image](https://user-images.githubusercontent.com/95841292/202914940-5d5eba71-e45d-4e95-8dfe-65e45d255aec.png)




# 📚 References
