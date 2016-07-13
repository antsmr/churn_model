# Churn Model

## DSCI-6006 (Leadership) Final Project [March 2016]

### Summary

This project works with the ‘[Churn in Telecom](https://bigml.com/user/francisco/gallery/dataset/5163ad540c0b5e5b22000383)’ dataset. The task was to develop a churn model using the dataset and present it to a non-technical audience. I focused on my model’s recall performance for customers who did churn. When creating a churn model, I determined that being accurate in this area (determining which customers will actually churn) is ultimately what could provide the most value to a company.

Algorithms used included gradient boosting and random forests, with somewhat similar results for both. Random forests are often considered the go-to for churn models, but gradient boosting performed better in terms of the above-mentioned churn customer recall.
After completing the project, the model had to be presented to a non-technical audience in a business setting in no more than ten minutes. The deck that accompanied my presentation is included in this repo.

### Technologies Used

* Scikit-Learn
* Pandas
* Matplotlib
* Random Forests
* Gradient Boosting


### Ideas for Improvement

Every project runs up against time constraints, and this one was no exception. If this project were to be re-visited and improved, I would look into normalizing and / or scaling the data. I believe that this could potentially yield better results.
