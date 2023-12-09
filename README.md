# Azure-Databricks-Game-Analytics
Explore the world of game development data with Azure Databricks and Apache Spark. This project leverages Databricks to process large-scale datasets from Kaggle, utilizing Spark for efficient data handling. The pipeline includes the creation of a robust data lake object, enabling seamless storage and retrieval of gaming data. Through powerful visualizations and insightful analytics, gain a deeper understanding of the gaming dataset, uncover trends, and extract valuable insights for game developers and enthusiasts alike. Welcome to the intersection of Azure, Databricks, Spark, and the exciting realm of game analytics.

## Data Overview
* The dataset comprises more than 38 million refined and processed user recommendations (reviews) sourced from the Steam Store, a prominent online platform for acquiring and downloading video games, DLC, and other gaming-related content, accompanied by comprehensive details about games and add-ons.
* Source: Anton Kozyriev. (2023). <i>Game Recommendations on Steam</i> [Data set]. Kaggle. (https://doi.org/10.34740/KAGGLE/DS/2871694)

## Step 1: Establish a code repository in Azure Databricks
Utilizing Databricks' workflow capabilities, a repository can be created, linking either to an existing GitHub repository. This connection involves associating Databricks with a GitHub account or incorporating a GitHub access token. By generating a GitHub token with limited access to only the relevant repository, changes can be tracked within the Databricks repository, changes can synchronize with the GitHub repository.
![image](https://github.com/lisawym/Azure-Databricks-Game-Analytics/assets/46847817/da361a6a-b08d-477f-b2f7-d269eb1b5110)

## Step 2: Extraction: Integrate Data into Databricks
Databricks exhibits the advantage of directly accessing large datasets, in contrast to [GitHub's limitations on file size uploads](https://docs.github.com/en/repositories/working-with-files/managing-large-files/about-large-files-on-github ). GitHub restricts file uploads to 100 MiB, with a recommended maximum of 50 MiB, emphasizing its primary purpose for code hosting rather than data storage. Databricks, on the other hand, efficiently handles substantial datasets, providing convenient interaction through notebooks. 
Various methods, such as uploading local files, integrating with Azure storage services, or utilizing marketplace datasets, can be employed to add data to a Databricks workspace. In this project, the dataset was uploaded locally, considering its static nature. Although alternative options, such as linking to a Kaggle dataset via API, were feasible, the decision was made to download from Kaggle and upload to Databricks DBFS. The data is then read, and a table is created within the Jupyter notebook.
![image](https://github.com/lisawym/Azure-Databricks-Game-Analytics/assets/46847817/695ad335-b2be-464b-bb2b-6b4097db419e)


## Step 3: Transformation: Data Table Integration
To extract the desired information, three data tables were merged.

## Step 4: Loading

## Step 5: Analysis and Visualization

## Step 6: Establishing the Pipeline
