# <Homework1 for MEM 679_Ohsung Kwon(14680477)>

## Find your wine(wine finder)

### Basic Concept
***"Make a search tool that helps you quickly find the wine that best suits you through a few surveys."***  
I got inspiration from the MBTI personality test, which is famous in South Korea. This test can categorize individuals into sixteen personality types(a binary value for each of the four categories) through a few survey questions. Similarly, I wanted to develop a wine search tool that could recommend the most suitable wine based on a few surveys about the user's tastes, purpose, or budget.

> Reference - `wine recommender` [link](https://www.onestopwineshop.com/wine-recommender/?srsltid=AfmBOoqlofrrFDlqBY31y_mx_BswQRBDihYQ4eH7eFwTXGoex8vX27la)
![image](https://github.com/user-attachments/assets/1f2c8777-aabf-4fe5-b84b-32809d9b5974)

### Dataset information
Source: [Wine Quality from UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/186/wine+quality)
- **Sample Size**: total 6497 Wines(1599 red wines + 4898 white wines)  
- **Features**: This dataset has 12 features(acid, sugar, pH, alcohol %, etc.) and color feature of red/white.  
- **Accessibility**: Using open sources from the UCI Machine Learning Repository.  
- **Metadata**: Information about red and white wine datasets can be found on the UCI Machine Learning Repository website.

### To do next
- **Assign code number to each wine**: Because the dataset does not include information about wine names, I need to assign a code number to each wine and use it instead of the wine name.
- **Recognize the correlation between data**: For classification, it is necessary to analyze what each data indicator means, the correlation between them, and the data classification processing method in heterogeneous relationships.
- **Set the standard**: For grouping wines(dry/sweet, light-bodied/full-bodied), I need to decide the number of groups and set grouping standards for all categories 
  > In the case of `wine recommender`, they use four levels for grouping color, dryness, and price. 

### Further improvement
- **Collect more data**: We can increase the accuracy of your group segmentation and classification criteria by increasing the amount of data.
- **Secure missing data**: We can provide users with the data they need more by obtaining the wine name and price data.
- **Correlation analysis with other factors**: We will also be able to check the user's purpose(for fine dining/party) when we figure out the correlation with the types of wine used depending on the situation.
