# t-SNE-using-MNIST-Data-set
This project demonstrates the application of t-SNE (t-Distributed Stochastic Neighbor Embedding) for visualizing high-dimensional data from the MNIST dataset. The MNIST dataset consists of 70,000 grayscale images of handwritten digits (0-9), each represented as a 784-dimensional vector.

Key Features:
Data Preprocessing: The MNIST dataset is loaded, and a subset of 3,000 images is selected for dimensionality reduction.
Dimensionality Reduction: t-SNE is applied to reduce the 784-dimensional image vectors to a 2D space, allowing for visual exploration of the data.
Visualization: The reduced 2D data is plotted to visualize the distribution of handwritten digits, providing insights into how similar digits are clustered together in the reduced space.

Libraries/Technologies Used:
Python: The primary programming language.
Libraries: scikit-learn for t-SNE, matplotlib for plotting, and pandas for data manipulation

How to Use:
Clone the repository.
Install the required libraries (scikit-learn, matplotlib, pandas).
Run the provided script or Jupyter notebook to perform t-SNE on the MNIST dataset and generate visualizations.
This project showcases data preprocessing, dimensionality reduction, and visualization techniques, making it a useful example for understanding complex data analysis workflows.
