# Mildew Detection in Cherry Leaves


## Dataset Content

- The dataset is sourced from [Kaggle](https://www.kaggle.com/codeinstitute/cherry-leaves). We then created a fictitious user story where predictive analytics can be applied in a real project in the workplace.
- The dataset contains +4 thousand images taken from the client's crop fields. The images show healthy cherry leaves and cherry leaves that have powdery mildew, a fungal disease that affects many plant species. The cherry plantation crop is one of the finest products in their portfolio, and the company is concerned about supplying the market with a compromised quality product.

## Business Requirements

The cherry plantation crop from Farmy & Foods is facing a challenge where their cherry plantations have been presenting powdery mildew. Currently, the process is manual verification if a given cherry tree contains powdery mildew. An employee spends around 30 minutes in each tree, taking a few samples of tree leaves and verifying visually if the leaf tree is healthy or has powdery mildew. If there is powdery mildew, the employee applies a specific compound to kill the fungus. The time spent applying this compound is 1 minute. The company has thousands of cherry trees located on multiple farms across the country. As a result, this manual process is not scalable due to the time spent in the manual process inspection.

To save time in this process, the IT team suggested an ML system that detects instantly, using a leaf tree image, if it is healthy or has powdery mildew. A similar manual process is in place for other crops for detecting pests, and if this initiative is successful, there is a realistic chance to replicate this project for all other crops. The dataset is a collection of cherry leaf images provided by Farmy & Foods, taken from their crops.

- 1 - The client is interested in conducting a study to visually differentiate a healthy cherry leaf from one with powdery mildew.
- 2 - The client is interested in predicting if a cherry leaf is healthy or contains powdery mildew.

## Hypothesis and how to validate?

 ### Hypothesis 1:
Healthy cherry leaves and those affected by powdery mildew show distinct visual differences that can be identified through image analysis.

 ### Validation:
To confirm this, a visual inspection study will be performed by examining a representative sample of images from both categories. The goal is to assess whether the differences are consistently noticeable to the human eye, which would justify the use of image-based machine learning for automated detection.

 ### Hypothesis 2:
A machine learning model can be trained to classify cherry leaves as either healthy or infected with powdery mildew, achieving an accuracy rate of at least 97%.

 ### Validation:
This hypothesis will be tested by training a model using labeled image data and evaluating its performance on a separate, unseen validation set. If the model reaches or exceeds the target accuracy, the hypothesis will be considered valid, demonstrating its potential for real-world deployment on cherry farms.

## The rationale to map the business requirements to the Data Visualisations and ML tasks

 ### Business Requirement 1

 - The client is interested in conducting a study to visually differentiate a healthy cherry leaf from one affected by powdery mildew.

 #### Rationale for Data Visualisation Tasks
 
 ##### Average Image Calculation:
   - Generate an average image for each class (healthy and powdery mildew) to highlight the typical appearance and structure of leaves in both categories.

 ##### Image Variability Analysis:
   - Create variability (standard deviation) images for each class to visualize the range of differences within the same category, helping to identify consistent features and outliers.

 ##### Difference Image Comparison:
   - Compute and display a difference image between the average healthy leaf and the average powdery mildew-infected leaf. This will provide a direct visual representation of class distinctions.

 ##### Image Montage Creation:
   - Display montages of sample images for both healthy and mildew-infected leaves to give a quick visual overview and support human intuition about the dataset.
 
 These visual tools will allow both technical and non-technical stakeholders to better understand the feasibility of automating the detection process and highlight the visual basis for model training.

## ML Business Case

- In the previous bullet, you potentially visualised an ML task to answer a business requirement. You should frame the business case using the method we covered in the course.

## Dashboard Design

- List all dashboard pages and their content, either blocks of information or widgets, like buttons, checkboxes, images, or any other items, that your dashboard library supports.
- Finally, during the project development, you may revisit your dashboard plan to update a given feature (for example, at the beginning of the project, you were confident you would use a given plot to display an insight, but later, you chose another plot type).

## Unfixed Bugs

- You will need to mention unfixed bugs and why they were unfixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a significant variable for consideration, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed.

## Deployment

### Heroku

- The App live link is: `https://YOUR_APP_NAME.herokuapp.com/`
- Set the runtime.txt Python version to a [Heroku-20](https://devcenter.heroku.com/articles/python-support#supported-runtimes) stack currently supported version.
- The project was deployed to Heroku using the following steps.

1. Log in to Heroku and create an App
2. At the Deploy tab, select GitHub as the deployment method.
3. Select your repository name and click Search. Once it is found, click Connect.
4. Select the branch you want to deploy, then click Deploy Branch.
5. The deployment process should happen smoothly if all deployment files are fully functional. Click the button Open App on the top of the page to access your App.
6. If the slug size is too large, then add large files not required for the app to the .slugignore file.

## Main Data Analysis and Machine Learning Libraries

- Here, you should list the libraries used in the project and provide an example(s) of how you used these libraries.

## Credits

- In this section, you need to reference where you got your content, media and from where you got extra help. It is common practice to use code from other repositories and tutorials. However, it is necessary to be very specific about these sources to avoid plagiarism.
- You can break the credits section up into Content and Media, depending on what you have included in your project.

### Content

- The text for the Home page was taken from Wikipedia Article A.
- Instructions on how to implement form validation on the Sign-Up page were taken from [Specific YouTube Tutorial](https://www.youtube.com/).
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/).

### Media

- The photos used on the home and sign-up page are from This Open-Source site.
- The images used for the gallery page were taken from this other open-source site.

## Acknowledgements (optional)

- Thank the people who provided support throughout this project.
