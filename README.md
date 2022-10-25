# Project 2 - Ames Housing Data and Kaggle Challenge

**Overview:**
Ames is centrally located in the heart of Midwest and lowa. It also houses the world-renowned lowa State University. Iowa State University of Science and Technology's ranking in the 2022-2023 edition of Best Colleges is National Universities, #127.

Houses Prices are affected by many factors. It is hard to identify and understand how much factor willl influence Sale Price more than another factor. Everyone has a budget, but the issue is about maximising what is important based on your budget. 

## The Problem Statement

As a student who has enrolled in Iowa State University, choosing a house that meets your need and budget is very important. This model is built to help students choose a house within their budget, which means their requirements or preferred features. 

## Brief summary of your analysis

1a_EDA (train set): Understanding and Cleaning Up of Train Set
   - Cleaning of data

1b_EDA (test set): Understanding and Cleaning Up of Test Set
   - Cleaning of data

2_Preprocessing_Model_Kaggle Submission
   - Encode data, Scale Data
   - Train Data
   - Models: Linear Regression, Lasso, Ridge
   - Conclude Model to be used
   - Conclusions and Recommendations


## Conclusions/recommendations
The model could be used to provide students some insights to help them choose an ideal house within their limited budgets.
With the model, students can decide which features to prioritise and spend their budget on. 

For example, gr_liv_area (Above Ground Living Area) affects Sale Price greatly. Holding everything else constant, every unit increase in Above Ground Living Area, increases Sale Price by 28263.87. A student would have to consider if Above Ground Living Area is critical enough for them to pay this much.

Similarly, a student with tight budget might want to choose to stay in Edwards as it affects Sale Price negatively (holding all other features constant).

Top 10 Features that positively affect Sale Price:
|       Features       |                         Features Descriptions                        | Coefficients |
|:--------------------:|:--------------------------------------------------------------------:|:------------:|
|      gr_liv_area     |             Above grade (ground) living area square feet             | 28263.871326 |
| neighborhood_StoneBr |                              Stone Brook                             | 22585.339752 |
| neighborhood_NridgHt |                          Northridge Heights                          | 21927.939059 |
|     overall_qual     |          Rates the overall material and finish of the house          | 16034.068450 |
| exterior_1st_BrkFace |                Exterior covering on house: Brick Face                | 13996.772863 |
|      year_built      |                      Original construction date                      | 12529.585894 |
|     total_bsmt_sf    |                  Total square feet of basement area                  | 11556.686463 |
|   condition_1_PosN   | Proximity to various conditions: Near positive off-site feature park | 10733.989735 |
|   land_contour_HLS   |                  Flatness of the property: Highlands                 | 10274.034374 |
|    garage_qual_Gd    |                         Garage quality: Good                         | 10177.460750 |


Top 10 Features that negatively affect Sale Price:
|       Features       |                     Features Descriptions                    | Coefficients |
|:--------------------:|:------------------------------------------------------------:|:------------:|
|   ms_zoning_C (all)  |     General zoning classification of the sale: Commercial    | -7134.645512 |
|  neighborhood_NWAmes |                        Northwest Ames                        | -7447.899266 |
|  condition_1_Artery  | Proximity to various conditions: Adjacent to arterial street | -7598.496644 |
|    garage_qual_TA    |                Garage quality: Typical/Average               | -7607.950064 |
| neighborhood_CollgCr |                         College Creek                        | -8449.340964 |
| neighborhood_SawyerW |                          Sawyer West                         | -8840.947331 |
| neighborhood_Gilbert |                            Gilbert                           | -9232.093887 |
|     sale_type_COD    |            Type of sale: Court Officer Deed/Estate           | -9543.284024 |
| neighborhood_Edwards |                            Edwards                           | -9548.504447 |
|  roof_style_Mansard  |                     Type of roof: Mansard                    | -9975.944202 |
