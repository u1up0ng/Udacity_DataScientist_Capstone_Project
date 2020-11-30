![ulupong](ulupong_clip.png?raw=true "ulupong")

<h1><center>Data Scientist: Capstone Project</center></h1>


### Project: Sparkify

### Table of Contents
1. [Project Motivation](#pm)
2. [Project Goal](#goal)
3. [Notes](#notes)
4. [Data](#data)
5. [Install](#install)
6. [Contents](#contents)
7. [Related Blogs](#blog)

#### Project Motivation<a name="pm"></a>
 As the final step to complete Udacity's Data Scientist nano-degree, I chose to learn Spark to gain an additional language in my programming and data-analytics skills. Spark turned out to be much better than I expected. The platform provided the capability of data analysis and machine learning; a very good choice indeed for the nano-degree capstone.

#### What is this project trying to achieve?<a name="goal"></a>
The goal is to learn how to use Spark MLlib for the efficient analysis and manipulation of datasets, engineer relevant features, and deploy machine learning models for predicting churn. The difference in approach to our usual machine-learning codes lies in the use of PySpark to manipulate very large and realistic datasets, that would make non-distributed technologies like scikit-learn crawl.

#### Notes<a name="notes"></a>
This project has a view of being deployed on **AWS** using a full dataset of **12GB**. Users have been pre-warned; use of AWS this will place additional cost on the user. This could also be deployed via **IBM Cloud**. This is supposedly free, so I took this route as it will give me the possibility to deploy the medium size dataset of **256MB**.  What I failed to read was, it is free until certain limits are reached. Unfortunately, my free-limits have been reached less than one-third of the project. <br>
I must turn my efforts on using the **128MB** dataset, housed on **Udacity**. This worked out well until the machine learning portion. Machine learning on Udacity's platform needs an overnight run and I would return to a disconnected or a paused the workspace. Calculation are usually not completed.<br>
At the end, I finally have to build a Spark platform on my **local machine** due to time-constraints on completing my course. I ran both the **mini-dataset** (128MB) and **medium-dataset** (256MB) for this project, and can be found on this git. Though both codes are similar, *I advise the use of the medium dataset* as it provides better insights to how the code might behave on much larger datasets. Please find related blog on Medium.

#### Data <a name="data"></a>
As implied earlier, there are 2 json datsets attached for this project. One of the file holds about 128MB of data and is reffered to as `mini_sparkify_event_data.json`. The other file holds about 256MB of data and is reffered to as `medium-sparkify-event-data.json`. The mini-data was exported directly from Udacity's workspace, and the medium data was exported from Udacity IBM Starter Code page. More information on the data are embedded in the Jupyter Notebook file.

#### Install<a name="install"></a>
This project requires Python and the following Python libraries installed:

- NumPy
- Pandas
- matplotlib
- seaborn
- scikit-learn
- pyspark
- findspark
- itertools
- datetime
- warnings


You will also need to have software installed to run and execute a Jupyter Notebook.<br>
If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more include.

#### Content<a name="contents"></a>
The archive submission includes the following files:<br>
1. A Jupyter Notebook file that contains the main project code (`Sparkify.ipynb`); same notebook as the mini-dataset file below<br>
2. A Jupyter Notebook file that runs the 'mini-dataset' project code (`Sparkify_mini_data.ipynb`)<br>
3. A Jupyter Notebook file that runs the 'medium-dataset' project code (`Sparkify_medium_data.ipynb`)<br>
4. A zip file of the 128MB json file that contains the 'mini-dataset' (`mini_sparkify_event_data.7z`)<br>
5. A zip file of the 256MB json file that contains the 'medium-dataset' (`medium-sparkify-event-data.7z`)<br>
6. Icon image file (`u1up0ng_clip.png`)
7. This `README.md` file


#### Related Blog<a name="blog"></a>
Please find link to the blog related to this project: [Udacity Data Scientist Nano-Degree Capstone Project](https://u1upong.medium.com/udacity-data-scientist-nano-degree-capstone-project-7bad950798e4). Article is best viewed using Chrome or Firefox. IE dow not display the article properly.

**u1up0ng 2020/11/29**