# PCA-and-data-visualization
# 🧠 PCA and Data Visualization

A simple yet powerful project demonstrating **Principal Component Analysis (PCA)** for dimensionality reduction and how to visualize high-dimensional datasets using Python libraries like `scikit-learn`, `matplotlib`, and `seaborn`.

## 📊 Features

- Load and preprocess datasets
- Perform PCA to reduce dimensions
- Visualize original and reduced data in 2D and 3D
- Supports custom datasets (CSV format)

## 🛠️ Tech Stack

- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## 📁 Project Structure

```

PCA-and-data-visualization/
├── data/                    # Sample datasets
│   └── your\_dataset.csv
├── src/
│   ├── pca\_visualizer.py   # Main PCA logic and visualization
│   └── utils.py            # Helper functions (scaling, loading, etc.)
├── README.md
└── requirements.txt

````

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/your-username/PCA-and-data-visualization.git
cd PCA-and-data-visualization
````

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the PCA script

```bash
python src/pca_visualizer.py
```

### 4. Use your own dataset (optional)

Place your `.csv` file in the `data/` folder and update the file path in `pca_visualizer.py`.

## 📷 Example Outputs

| Original Data (Before PCA)       | PCA Reduced (2D)         | PCA Reduced (3D)         |
| -------------------------------- | ------------------------ | ------------------------ |
| ![original](images/original.png) | ![2d](images/pca_2d.png) | ![3d](images/pca_3d.png) |

## 📚 Concepts Covered

* Standardization of data
* Covariance matrix and eigen decomposition
* Explained variance ratio
* Scatter plots and 3D visualizations

## ✅ To-Do

* [ ] Add support for more visualization types
* [ ] Create a Streamlit or Gradio web app
* [ ] Add unit tests

## 🙌 Contributing

Contributions are welcome! Fork this repo and submit a pull request.

## 📄 License

This project is licensed under the MIT License.
