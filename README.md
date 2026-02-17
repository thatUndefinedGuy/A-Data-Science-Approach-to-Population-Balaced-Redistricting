# Population-Balanced Redistricting

An independent data science project exploring whether clustering algorithms can generate voting districts with more balanced populations.

## Motivation

Gerrymandering affects political representation in the U.S. I wanted to explore whether basic machine learning techniques could produce alternative district maps with lower population variance.

This project was built independently as a learning exercise.

## Approach

- Used census population data
- Applied K-Means clustering to form districts
- Used gradient descent to reduce population imbalance
- Implemented in Python with basic visualization

## Results

The model produces districts with lower population variance compared to existing maps.

## What I Learned

- How clustering behaves on geographic data
- Limitations of K-Means for political boundaries
- Practical optimization techniques
- Data cleaning and visualization workflows

## Limitations

- Does not include legal redistricting constraints
- Geometry is simplified
- More advanced methods could improve results
- Computationally expensive for larger states

## How to Run

pip install -r requirements.txt  
python main.py

## Future Improvements

- Add legal constraints
- Try alternative clustering methods
- Improve visualization
