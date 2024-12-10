# FacebookMetrics
# Linear Regression Model🧮🖇️

## Introduction📝
In this project, we developed a linear regression model on a Facebook metric dataset. During this process, we avoided using pre-built linear regression functions and instead created our own by writing cost function and weight update functions. Our focus was on the mathematical foundations of linear regression, specifically evaluating the model's performance through the cost function and improving it by adjusting the weights with the weight update function. This approach allowed us to model relationships within the dataset and adjust the model parameters for accurate future predictions.

## Methodology📉

### 2.1 Data Set Understanding
The dataset contains various Facebook post metrics, including:

- **Page Total Likes**: Total number of likes for a Facebook page.
- **Type**: The type of post (Photo, Status, Link, Video).
- **Category**: A numerical category related to the post.
- **Post Month, Weekday, Hour**: Information on the time of the post.
- **Paid**: Indicates whether the post is paid (1) or unpaid (0).
- **Lifetime Post Total Reach**: Total number of unique users who saw the post.
- **Lifetime Post Total Impressions**: Total number of times the post was viewed.
- **Lifetime Engaged Users**: Users interacting with the post (likes, shares, comments).
- **Lifetime Post Consumers**: Users who clicked or consumed the post content.
- **Lifetime Post Consumptions**: Total number of clicks on the post.
- **Lifetime Post Impressions by People Who Have Liked Your Page**: Impressions from people who liked the page.
- **Lifetime Post Reach by People Who Like Your Page**: Reach from people who liked the page.
- **Lifetime People Who Have Liked Your Page and Engaged with Your Post**: People who liked the page and engaged with the post.
- **Comment, Like, Share**: Counts of comments, likes, and shares on the post.
- **Total Interactions**: Sum of the interactions (comments, likes, and shares).

### 2.2 Data Processing (Feature Engineering)
Feature engineering was applied to manipulate the dataset for better results in machine learning models. This included converting categorical variables to numerical ones, handling missing data, removing outliers, and appropriately filling or processing missing values. These adjustments improved the quality of the dataset and helped the model generalize better.

### 2.3 Data Visualization📊📉📉🔄
- **Figure 1**: Gradient descent function  
  ![Figure 1](https://github.com/user-attachments/assets/e0a9eca9-41a4-4266-89dd-d2dd637f4bde)

- **Figure 2**: Bar graph showing total reactions by month  
  ![Figure 2](https://github.com/user-attachments/assets/c53bfb39-eed4-4c92-8599-00c4f9af0372)

- **Figure 3**: Bar graph showing reaction counts by weekday  
  ![Figure 3](https://github.com/user-attachments/assets/dbf5147c-ade5-4aad-a45a-7ce7e6d5e033)

- **Figure 4**: Bar graph showing total reactions by hour  
  ![Figure 4](https://github.com/user-attachments/assets/d9be22ab-2ca9-4612-8d6e-3625f2f95ccd)

- **Figure 5**: Histogram of likes distribution per post  
  ![Figure 5](https://github.com/user-attachments/assets/ad8e29ec-e5ab-4a0a-866a-bb3724523cdf)

- **Figure 6**: Graph showing whether total likes are from paid or unpaid posts  
  ![Figure 6](https://github.com/user-attachments/assets/4a3c08b3-ffeb-441c-a1c3-7c061f856e16)

- **Figure 7**: Heatmap of correlation  
  ![Figure 7](https://github.com/user-attachments/assets/2b7be45f-8c94-4831-9087-b09022274fe2)

- **Figure 8**: Outliers in post categories  
  ![Figure 8](https://github.com/user-attachments/assets/c239fd09-9350-4034-833b-1ae5fdc1f2fe)

- **Figure 9**: Outliers and their removal in dependent variables  
  ![Figure 9](https://github.com/user-attachments/assets/04f9763b-5521-4986-b8a9-3f6e7a361f1a)

### 2.4 Linear Regression Model Creation
The cost function (SSE, Sum of Squared Errors) is used to calculate the model's error by comparing predicted and actual values for each data point. This function performs one step of the gradient descent algorithm, where weight updates are made based on the error's gradient. The update_weights function helps minimize this error and iteratively updates the model’s weights. These components are fundamental in training a basic linear regression model.

### 2.5 Model Training and Testing
During training, the differences between the model’s predictions and actual values were visualized using bar charts. These graphs helped assess the model's performance and identify where it made the most errors. By examining this visualization, we were able to identify specific areas where the model performed better or worse, allowing us to improve the model further.

![Training Results](https://github.com/user-attachments/assets/cd15859d-69cb-4f8e-a7dc-0447ad22564e)

## Findings and Discussion
The analysis of the data led to the following findings, which were presented through tables, figures, and graphs. The model's error analysis helped identify its strengths and weaknesses, providing insights for further improvement.

## Conclusion
![Conclusion](https://github.com/user-attachments/assets/b5dface9-ea3d-4f7b-b703-5e3df99f586d)

The results indicate that the linear regression model was successful in predicting the performance of Facebook posts. The model learned effectively from the dataset and was able to make reliable predictions. The weights and bias values obtained helped us understand which features were more important in predicting post performance. The error analysis provided further insights into areas of improvement for the model. 📊📈

## References
- Korkmaz, M. (2021). A study over the general formula of regression sum of squares in multiple linear regression. *Numerical Methods for Partial Differential Equations*, 37(1), 406-421.
- James, G., Witten, D., Hastie, T., Tibshirani, R., & Taylor, J. (2023). Linear regression. In *An Introduction to Statistical Learning: With Applications in Python* (pp. 69-134). Cham: Springer International Publishing.
- Yao, W., & Li, L. (2014). A new regression model: modal linear regression. *Scandinavian Journal of Statistics*, 41(3), 656-671.
