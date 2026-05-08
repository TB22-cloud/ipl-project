# IPL Auction Analysis: Are Franchises Paying for Performance?

## Project Overview
This project analyses whether IPL franchise auction spending reflects 
player performance. Using ball-by-ball match data and auction price data 
spanning 2013-2022, it investigates the relationship between what teams 
pay at auction and what they get in return on the field.

## Blog Post
The full blog post and analysis can be found in `IPL-blog.ipynb`

## Data Sources
- **Auction data**: `IPLPlayerAuctionData.csv` (included in this repository)
- **Match delivery data**: Download `deliveries.csv` from:
  https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020
  and place it in the same folder as the notebook

## Requirements
Install the required Python libraries by running:

## How to Replicate
1. Clone this repository
2. Download `deliveries.csv` from the Kaggle link above
3. Place `deliveries.csv` in the same folder as `IPL-blog.ipynb`
4. Open `IPL-blog.ipynb` in Jupyter Notebook
5. Run `Kernel → Restart & Run All`

## Libraries Used
- `pandas` — data loading and cleaning
- `matplotlib` — visualisations
- `scikit-learn` — regression modelling
- `numpy` — numerical operations
