# PCA_using_iris_data
The code begins by importing necessary libraries, including NumPy, Pandas, Matplotlib, and functions from scikit-learn.

It loads the Iris dataset using load_iris() from scikit-learn's datasets module and assigns it to the variable wine_data.

The code prints the contents of wine_data, which includes features, labels, target names, and other dataset information.

It separates the features into the variable x and the target labels into y.

A scatter plot is created using Matplotlib, displaying the first and third columns of the feature data (x[:,0] and x[:,2]) with colors corresponding to the target labels (c=y). A legend is added to the plot.

The code then proceeds to perform Principal Component Analysis (PCA) with 3 components on the original feature data (x). The transformed data is stored in x_transform.

It prints the transformed data and its shape to the console.

Standardization of the feature data is performed using scikit-learn's StandardScaler. The scaled data is stored in x_normalised.

PCA is applied again to the standardized data, and the transformed data is stored in x_transform.

Finally, another scatter plot is created, this time showing the first and third components of the transformed data (x_transform[:,0] and x_transform[:,2]) colored by the target labels. A legend is added to this plot as well, allowing for visual comparison with the initial scatter plot.

This code demonstrates the application of PCA for dimensionality reduction and visualization of the Iris dataset, both before and after standardization.
