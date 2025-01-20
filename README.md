# Credit Card Clustering with Machine Learning

## Overview

This project aims to perform clustering on credit card data using various machine learning algorithms. The goal is to identify distinct groups of credit card users based on their spending behavior and other relevant features.

## Features

- Data preprocessing and cleaning
- Exploratory data analysis (EDA)
- Feature engineering
- Clustering using K-Means, DBSCAN, and Hierarchical Clustering
- Evaluation of clustering results
- Visualization of clusters

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/mrrezamo/Credit-Card-Clustering-with-Machine-Learning.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Credit-Card-Clustering-with-Machine-Learning
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Prepare your dataset and place it in the `data/` directory.
2. Run the preprocessing script:
   ```bash
   python preprocess.py
   ```
3. Perform clustering:
   ```bash
   python cluster.py
   ```
4. Visualize the results:
   ```bash
   python visualize.py
   ```

## Project Structure

- `data/`: Directory to store the dataset.
- `notebooks/`: Jupyter notebooks for EDA and experimentation.
- `scripts/`: Python scripts for preprocessing, clustering, and visualization.
- `requirements.txt`: List of dependencies.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

## Contact

For any questions or suggestions, please contact mr.sharififarid@gmail.com.

## Results

### Cluster Profiles:

| Cluster   | BALANCE | PURCHASES | CREDIT_LIMIT | PAYMENTS | CASH_ADVANCE |
| --------- | ------- | --------- | ------------ | -------- | ------------ |
| Cluster 1 | 743.22  | 1455.81   | 6350.48      | 1571.05  | 1655.51      |
| Cluster 2 | 807.23  | 556.12    | 2084.35      | 1578.12  | 296.58       |
| Cluster 3 | 8297.18 | 2486.38   | 12512.34     | 5503.89  | 2143.51      |
| Cluster 4 | 4201.29 | 1056.15   | 6717.37      | 1426.13  | 730.36       |
| Cluster 5 | 1223.68 | 3371.34   | 12703.54     | 4379.10  | 500.42       |

### Key Insights:

- **Cluster 1 (Moderate Users):**
  - Low balances with medium purchases and credit limits.
  - **Action:** Offer promotions to encourage higher spending.
- **Cluster 2 (Low Value):**
  - Low balances, purchases, and credit limits.
  - **Action:** Reactivate with cashback offers or incentives.
- **Cluster 3 (Premium Customers):**
  - High balances, purchases, and credit limits.
  - **Action:** Retain with loyalty programs or exclusive offers.
- **Cluster 4 (Occasional Users):**
  - Medium balances and low purchases.
  - **Action:** Encourage more usage through education or rewards.
- **Cluster 5 (Engaged Users):**
  - Medium balances and high purchases with significant credit limits.
  - **Action:** Offer rewards or credit upgrades to increase engagement.

## Conclusion

This segmentation successfully grouped customers into distinct categories, providing actionable insights for targeted marketing, customer engagement, and retention strategies.
