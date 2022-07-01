
# Importing dataset into Sagemaker
Following steps outline how to import data into Sagemaker to be consumed by Datawrangler


* Initialize SageMaker Data Wrangler via SageMaker Studio UI.
    * There are three ways that you can do this, either from the Launcher screen as depicted here:
    ![image](./img/image-1.png)
    * Or from the SageMaker resources menu on the left, selecting Data Wrangler, and new flow
    ![image](./img/image-1-1.png)
    ![image](./img/image-1-2.png)
    * You can also use the File -> New -> DataWrangler option as shown here
    ![image](./img/image-1-4.png)
* It takes a few minutes to load.
![image](./img/image-2.png)
* Once Data Wrangler is loaded, you should be able to see it under running instances and apps as shown below.
![image](./img/image-3.png)
* Once Data Wrangler is up and running, you can see the following data flow interface with options for import, creating data flows and export as shown below.
![image](./img/image-4.png)
* Make sure to rename the untitled.flow to your preference (for e.g., join.flow)
* Paste the S3 URL for the tracks.csv file into the search box below and hit go.
![image](./img/image-5.png)
* Select the CSV file from the drop down results. On the right pane, make sure COMMA is chosen as the delimiter and Sampling is *None*. Hit *import* to import this dataset to Data Wrangler.
![image](./img/image-6.png)
* Once the dataset is imported, the Data flow interface looks as shown below.
![image](./img/image-7.png)
* Since currently you are in the data flow tab, hit the import tab (left of data flow tab) as seen in the above image.
* Import the second part file (ratings.csv) following the same set of instructions as noted previously.
![image](./img/image-8.png)
