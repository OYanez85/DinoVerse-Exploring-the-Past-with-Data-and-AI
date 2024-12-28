# DinoVerse-Exploring-the-Past-with-Data-and-AI
Jurassic Park - The Exhaustive Dinosaur Dataset

# Dinosaur Dataset Analysis

This project focuses on exploring and analyzing a dataset of dinosaurs to uncover insights related to their length, taxonomy, diet, and other characteristics. Machine learning techniques are applied to classify dinosaurs based on their features.

## Dataset Description

The dataset contains information about various dinosaurs, including:

- **Name**: The name of the dinosaur.
- **Diet**: The dietary classification (e.g., carnivorous, herbivorous).
- **Period**: The geological period when the dinosaur existed.
- **Lived In**: The location where fossils were found.
- **Type**: The type of dinosaur (e.g., theropod, sauropod).
- **Length**: The length of the dinosaur in meters.
- **Taxonomy**: The taxonomy hierarchy of the dinosaur.
- **Named By**: The paleontologist(s) who named the dinosaur.
- **Species**: The species name.
- **Link**: A link to more information.

## Project Structure

- **Data Cleaning**: Handling missing values, converting non-numeric columns, and extracting additional features like `period_start_year` and `taxonomy_depth`.
- **Exploratory Data Analysis (EDA)**:
  - Taxonomy depth trends over time.
  - Dinosaur length distribution by type and diet.
  - Outliers in dinosaur lengths.
  - Heatmaps to visualize average lengths by type and period.
- **Machine Learning**:
  - Random Forest Classifier to classify dinosaur types based on features like length, taxonomy depth, period, and diet.
  - Feature importance analysis to understand the most influential features for classification.

## Key Insights

- Sauropods tend to be the largest dinosaur type, while small theropods are the smallest.
- Taxonomy depth shows a general trend of decreasing complexity over geological periods.
- Diet and length are significant factors in determining the type of dinosaur.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd dinosaur-dataset-analysis
   ```
2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook or Python script:
   ```bash
   jupyter notebook dinosaur_analysis.ipynb
   ```

## Dependencies

- Python 3.8+
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Numpy

## Example Visualizations

### Taxonomy Depth Over Time
Scatterplot showing the complexity of taxonomy over geological periods.

### Dinosaur Length by Type
Boxplot comparing the length distributions among different types of dinosaurs.

### Feature Importance in Classification
Bar plot highlighting the most important features for predicting dinosaur types.

## Future Work

- Expand the dataset with more features such as weight or fossil discovery year.
- Apply additional machine learning algorithms for classification and regression tasks.
- Explore clustering techniques to identify patterns in dinosaur characteristics.

## License

This project is licensed under the Creative Commons License.

## Author

[Oscar Yanez-Feijoo] - [(https://github.com/OYanez85)]
