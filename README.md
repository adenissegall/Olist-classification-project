# Olist classification project
Data App created for this project: https://share.streamlit.io/streamlitstack/olist_stack/main/app.py<br><br>
This is an end to end Machine Learning project to solve the following business problem: <b>high number of sellers stop selling with Olist in the first months of operation.</b><br><br>
Here i make some data analysis to understand what drives the company's revenue and the sellers behavior, wich brings me to the business problem. With these informations, i made a classification model to find the sellers with high probability to stop selling for more than 90 days, giving a label to this ones and its probability.<br><br> 
In order to make the company's actions more efficient, i provide a clustering analysis using K-means to separate sellers groups and understand wich one is more important to the company. So, with these two informations together (sellers with probability to stop selling and wich cluster that seller is), Olist can make some actions trying to retain the seller and also create different actions to different groups of sellers.<br><br>
Here you'll find:<br>
-A jupyter notebook with the analysis and algorithms code (i'm cleaning this jupyter notebook to provide it here, so its is not here yet);<br>
-The presentation of results (pdf);<br>
-A python file created for the Data App to generate the prediction, the clustering and to download the csv file with all the informations about each seller (including cluster, label if the seller have high probabilty to stop selling and the probability itself).<br><br>
-A python file created to acess the azure datalake to input or get files<br><br>
The main idea with this project is to help the CRM team of Olist to make retention actions to the sellers, providing strategic information and data.
