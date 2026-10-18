# Matplotlib Notebook

A beginner-friendly notebook covering data visualization in Python with **Matplotlib** (plus a little Seaborn and Pandas plotting), using examples like IPL batting data, the tips dataset, the iris dataset and stock prices.

## Topics Covered

- **Types of data** - numerical and categorical
- **2D line plot** - labels, title, colors (hex), linestyle, linewidth, markers, legend, axis limits, grid
- **Scatter plot** - basic, size of points, `plt.plot` as a faster alternative
- **Bar chart** - simple, horizontal, multiple bars, stacked, rotating x-ticks
- **Histogram** - custom bins, logarithmic scale
- **Pie chart** - percentages with `autopct`, colors, explode, shadow
- **Styles** - changing plot styles, saving a figure with `plt.savefig()`
- **Colored scatter plots** - `c`, `cmap`, `alpha`, colorbar
- **Plot size** - `figsize`
- **Annotations** - `plt.text()`, horizontal and vertical lines (`axhline`, `axvline`)
- **Subplots** - `plt.subplots()` and `fig.add_subplot()`
- **3D plots** - 3D scatter, 3D line, 3D surface plots
- **Contour plots** - `contour` and `contourf`
- **Heatmap** - using `imshow()`
- **Pandas `plot()`** - line, scatter, bar, stacked bar, histogram, pie, subplots on Series and DataFrames

## Libraries Used

- NumPy
- Pandas
- Matplotlib
- Seaborn (only to load the `tips` dataset)

## How to Run

1. Clone this repository
   ```bash
   git clone <your-repo-link>
   ```
2. Install the libraries
   ```bash
   pip install numpy pandas matplotlib seaborn jupyter
   ```
3. Open the notebook
   ```bash
   jupyter notebook matplotlib.ipynb
   ```

> **Note:** Some cells read CSV files from a local folder (`C:\Users\acer\Documents\Matplotlib Dataset\`). Download the datasets and change the file paths to your own location before running those cells.

## Author

Vishesh - B.Tech CSE (3rd year)
