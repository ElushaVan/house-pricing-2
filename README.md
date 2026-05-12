# house-pricing-2

Dataset source: https://www.kaggle.com/datasets/alyelbadry/house-pricing-dataset

**🏠 The House Price Chronicles:** A Data Science JourneyEvery house has a story, but behind the bricks and mortar lies a complex web of numbers. This project is a narrative of how we turned 21,613 property records into a smart system capable of predicting home values with high precision.

**📖 The Prologue:** The MissionIn a volatile real estate market, "guessing" a price isn't enough. Our mission was to decode the DNA of property value. Why is one house worth a fortune while its neighbor isn't? We set out to build a machine learning model that could see the patterns humans might miss.

**🛠 Chapter 1:** Preparing the ToolkitBefore diving into the data, we assembled our digital workshop. Using the power of Python, we brought in the heavy hitters:Pandas & NumPy: For data manipulation.Matplotlib & Seaborn: To visualize the hidden trends.Scikit-Learn: The engine for our predictive intelligence.

**🔍 Chapter 2:** Understanding the Language of HousesThe data spoke to us through 21 different variables. We discovered that a house isn't just a list of rooms; it's a combination of:Physicality: The living space (sqft_living), the quality of construction (grade), and the view.Geography: The precise location via latitude and longitude.History: When it was built and if it was ever reborn through renovation.The Waterfront Twist: We noticed the "Waterfront" feature was written in text ('Y'/'N'). We translated this into a language the computer understands: 0s and 1s.

**🧪 Chapter 3:** The Mathematical AlchemyRaw prices are often messy and skewed. To help our model learn better, we applied a Log Transformation ($np.log1p$). This balanced the scales, making the "giant" mansion prices and "small" cottage prices easier for the algorithm to compare fairly.

**🤖 Chapter 4:** Training the "Forest"We didn't just use one tree; we planted a forest. We deployed a Random Forest Regressor with 200 individual decision trees working in harmony.By splitting our data—training on 80% and testing on 20%—we ensured our model wasn't just "memorizing" the past, but actually "learning" for the future.

**🏆 The Grand Finale:** The ResultsThe moment of truth arrived when we asked the model to guess the prices of houses it had never seen before.The Verdict: The model achieved a staggering 88.52% accuracy.The Visualization: Our Residual Plot showed that most of our "guesses" were remarkably close to the actual sales prices, with the errors scattered evenly around the zero-line.
