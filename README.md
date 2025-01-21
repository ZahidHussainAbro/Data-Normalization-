# Data-Normalization-
Python Data Normalization, Standardization, Log Transformation
𝗗𝗼 𝘆𝗼𝘂 𝗸𝗻𝗼𝘄 𝗮𝗯𝗼𝘂𝘁 𝘁𝗵𝗲 𝗺𝗲𝘀𝘀𝘆 𝗯𝗶𝗴 𝗱𝗮𝘁𝗮 𝘁𝗵𝗮𝘁 𝗰𝗮𝗻 𝗿𝘂𝗶𝗻 𝘆𝗼𝘂𝗿 𝗼𝘂𝘁𝗰𝗼𝗺𝗲 𝗼𝗳 𝗮𝗻𝗮𝗹𝘆𝘀𝗶𝘀 𝗶𝗳 𝘁𝗵𝗲 𝗱𝗮𝘁𝗮 𝗶𝘀 𝗻𝗼𝘁 𝗻𝗼𝗿𝗺𝗮𝗹 𝗼𝗿 𝗶𝗻 𝘀𝘁𝗮𝗻𝗱𝗮𝗿𝗱 𝗳𝗼𝗿𝗺𝗮𝘁?

𝗖𝗼𝗺𝗲 𝘄𝗲 𝘂𝗻𝗱𝗲𝗿𝘀𝘁𝗮𝗻𝗱 𝗶𝘁:

Not every time either big data or small, it's suitable for any kind of analysis either Machine learning, or data analytics such as Root, Diagnostic, prediction, or prospective. Data is messy, uncleaned, scattered, skewed, and not normal which can cause conflict or not accurate results, it may contain anomalies or outliers therefore preprocessing through Exploratory Analysis always comes on the mark to understand the data quality and normalization either we log transform, standardize or normalize data etc.

𝟭. 𝗦𝘁𝗮𝗻𝗱𝗮𝗿𝗱𝗶𝘇𝗮𝘁𝗶𝗼𝗻
What it does: Rescales data so that it has a mean of 0 and a standard deviation of 1.
𝗪𝗵𝘆 𝗶𝘁'𝘀 𝘂𝘀𝗲𝗳𝘂𝗹: Standardization ensures that all features contribute equally to the model, especially when their units or ranges differ.
𝗪𝗵𝗲𝗻 𝘁𝗼 𝘂𝘀𝗲:Models sensitive to feature scales, such as Support Vector Machines (SVM), Principal Component Analysis (PCA), and linear regression.
When the data doesn't have significant outliers.

𝟮. 𝗡𝗼𝗿𝗺𝗮𝗹𝗶𝘇𝗮𝘁𝗶𝗼𝗻
𝗪𝗵𝗮𝘁 𝗶𝘁 𝗱𝗼𝗲𝘀: Rescales data to a fixed range, typically [0, 1].
𝗪𝗵𝘆 𝗶𝘁'𝘀 𝘂𝘀𝗲𝗳𝘂𝗹: Normalization ensures that all features are on the same scale, making it ideal for algorithms that rely on distance calculations (like Euclidean distance).
𝗪𝗵𝗲𝗻 𝘁𝗼 𝘂𝘀𝗲: Distance-based algorithms such as k-nearest Neighbors (KNN) or clustering (e.g., k-means).
When feature values need to be constrained to a specific range.

𝟯. 𝗟𝗼𝗴 𝗧𝗿𝗮𝗻𝘀𝗳𝗼𝗿𝗺𝗮𝘁𝗶𝗼𝗻
What it does: Applies a logarithmic function to compress large values and reduce skewness.
𝗪𝗵𝘆 𝗶𝘁'𝘀 𝘂𝘀𝗲𝗳𝘂𝗹: Helps stabilize variance, reduce the effect of outliers, and make distributions more normal-like.
𝗪𝗵𝗲𝗻 𝘁𝗼 𝘂𝘀𝗲: For skewed datasets, such as income or sales data.
When outliers need to be handled without outright removal.
