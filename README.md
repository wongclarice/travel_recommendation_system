# Tourism Recommendation Model using Geotagged Data and Matrix Factorization

Tourism research has increasingly benefited from the widespread use of social networking services worldwide. 
People now rely more on internet resources to plan vacations, leading to the development of sophisticated travel recommendation systems. 
The availability and popularity of geotagged data have significantly influenced destination decisions. However, current research primarily focuses on reviews and textual information for recommendation models.

## Proposed Approach

The proposed travel recommendation model aims to leverage geotagged data and user behavior analysis for personalized suggestions:

1. **Data Preprocessing:**
   - Geotagged data are clustered to create representative location points.
   - A location database is constructed based on visit frequency, creating a user-location rating table.

2. **Model Construction:**
   - Transform the user-location rating table into a matrix format.
   - Utilize matrix factorization, a form of collaborative filtering, to compute user similarities and generate predictions.

3. **Evaluation:**
   - Assess model performance using evaluation metrics such as Root Mean Square Error (RMSE) and Mean Absolute Error (MAE).
   - Compare against baseline models (popularity and random models) using test datasets.

## Results

The findings suggest that the proposed matrix factorization model performs effectively in providing personalized travel recommendations based on user visit history.

### Performance Metrics
- **RMSE:** 1.36
- **MAE:** 1.24

### Conclusion

The proposed model demonstrates higher effectiveness in personalized recommendation compared to baseline models. It leverages geotagged data and matrix factorization techniques to enhance the accuracy of travel destination suggestions.

