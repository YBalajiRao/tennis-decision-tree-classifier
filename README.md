# Tennis Decision Tree Classifier

This project explores building a decision tree classifier to predict whether to play tennis based on weather conditions. The dataset used in this project contains information about outlook, temperature, humidity, windiness, and the decision to play tennis.

## Dataset
The dataset used in this project is stored in [tennis.csv](https://github.com/YBalajiRao/tennis-decision-tree-classifier/blob/main/tennis.csv), which contains the following columns:
- Outlook: Weather outlook (sunny, overcast, rainy)
- Temp: Temperature (hot, mild, cool)
- Humidity: Humidity level (high, normal)
- Windy: Windiness (True, False)
- Play: Decision to play tennis (yes, no)

## Steps
1. **Data Preprocessing**: 
    - Used label encoding to convert categorical variables into numerical values.
    - Split the dataset into features (X) and the target variable (y).
    - Split the data into training and testing sets.
    
2. **Model Building**:
    - Implemented a decision tree classifier using scikit-learn.
    - Trained the model on the training data.
    - Evaluated the model's accuracy on the testing data.
    
3. **Visualization**:
    - Visualized the dataset using matplotlib and seaborn.
    - Created bar plots and scatter plots to explore relationships between variables.
    
## Usage
1. Clone the repository:
    ```
    git clone <repository_url>
    ```
2. Navigate to the project directory:
    ```
    cd tennis-decision-tree
    ```
3. Install the required dependencies:
    ```
    pip install -r requirements.txt
    ```
4. Run the Jupyter Notebook to see the code and visualizations:
    ```
    jupyter notebook
    ```

## Requirements
- Python 3.x
- Jupyter Notebook
- scikit-learn
- pandas
- matplotlib
- seaborn

## Author
[Yadhav Balaji Rao]

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
