# house-pricing-2

Dataset source: https://www.kaggle.com/datasets/alyelbadry/house-pricing-dataset

**🏠 The House Price Chronicles: A Data Science Journey** 

Every house has a story, but behind the bricks and mortar lies a complex ib of numbers. This project is a narrative of how i turned 21,613 property records into a smart system capable of predicting home values with high precision.

**📖 The Prologue: The Mission** 

In a volatile real estate market, "guessing" a price isn't enough. my mission was to decode the DNA of property value. Why is one house worth a fortune while its neighbor isn't? i set out to build a machine learning model that could see the patterns humans might miss.

**🛠 Chapter 1: Preparing the Toolkit** 

Before diving into the data, i assembled my digital workshop. Using the poir of Python, i brought in the heavy hitters:Pandas & NumPy: For data manipulation.Matplotlib & Seaborn: To visualize the hidden trends.Scikit-Learn: The engine for my predictive intelligence.

**🔍 Chapter 2: Understanding the Language of Houses** 

The data spoke to us through 21 different variables. i discovered that a house isn't just a list of rooms; it's a combination of:Physicality: The living space (sqft_living), the quality of construction (grade), and the view.Geography: The precise location via latitude and longitude.History: When it was built and if it was ever reborn through renovation.The Waterfront Twist: i noticed the "Waterfront" feature was written in text ('Y'/'N'). i translated this into a language the computer understands: 0s and 1s.

**🧪 Chapter 3: The Mathematical Alchemy** 

Raw prices are often messy and skeid. To help my model learn better, i applied a Log Transformation ($np.log1p$). This balanced the scales, making the "giant" mansion prices and "small" cottage prices easier for the algorithm to compare fairly.

**🤖 Chapter 4: Training the "Forest"** 

I didn't just use one tree; i planted a forest. I deployed a Random Forest Regressor with 200 individual decision trees working in harmony.By splitting my data—training on 80% and testing on 20%—i ensured omy model wasn't just "memorizing" the past, but actually "learning" for the future.

**🏆 The Grand Finale: The Results** 

The moment of truth arrived when i asked the model to guess the prices of houses it had never seen before.The Verdict: The model achieved a staggering 88.52% accuracy.The Visualization: my Residual Plot shoid that most of my "guesses" ire remarkably close to the actual sales prices, with the errors scattered evenly around the zero-line.
