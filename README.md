# Data Visualization with Matplotlib and Seaborn
[![Codespaces Prebuilds](https://github.com/4GeeksAcademy/gperdrizet-visualization-exercises-with-matplot-and-seaborn/actions/workflows/codespaces/create_codespaces_prebuilds/badge.svg)](https://github.com/4GeeksAcademy/gperdrizet-visualization-exercises-with-matplot-and-seaborn/actions/workflows/codespaces/create_codespaces_prebuilds)

A comprehensive data visualization project focused on mastering essential plotting techniques using Python's most popular visualization libraries. This project demonstrates fundamental to advanced visualization concepts through practical exercises with real-world applications.

![Project Preview](assets/preview.png)

## Project Overview

This project provides hands-on experience with data visualization fundamentals using **Matplotlib** and **Seaborn**. Through interactive Jupyter notebooks, you'll learn to create compelling visualizations that effectively communicate data insights and patterns.

The project covers essential visualization techniques including:

- Line plots for continuous data trends
- Bar charts for categorical data comparison
- Pie charts for proportion visualization
- Scatter plots for relationship analysis
- Histograms for distribution exploration
- Heatmaps for correlation matrices
- Box plots for statistical summaries


## Getting Started

### Option 1: GitHub Codespaces (Recommended)

1. **Fork the Repository**
   - Click the "Fork" button on the top right of the GitHub repository page
   - 4Geeks students: set 4GeeksAcademy as the owner - 4Geeks pays for your codespace usage. All others, set yourself as the owner
   - Give the fork a descriptive name. 4Geeks students: I recommend including your GitHub username to help in finding the fork if you loose the link
   - Click "Create fork"
   - 4Geeks students: bookmark or otherwise save the link to your fork

2. **Create a GitHub Codespace**
   - On your forked repository, click the "Code" button
   - Select "Create codespace on main"
   - If the "Create codespace on main" option is grayed out - go to your codespaces list from the three-bar menu at the upper left and delete an old codespace
   - Wait for the environment to load (dependencies are pre-installed)

3. **Start Working**
   - Open `notebooks/assignment.ipynb` in the Jupyter interface
   - Follow the step-by-step instructions in the notebook

### Option 2: Local Development

1. **Prerequisites**
   - Git
   - Python >= 3.10

2. **Fork the repository**
   - Click the "Fork" button on the top right of the GitHub repository page
   - Optional: give the fork a new name and/or description
   - Click "Create fork"

3. **Clone the repository**
   - From your fork of the repository, click the green "Code" button at the upper right
   - From the "Local" tab, select HTTPS and copy the link
   - Run the following commands on your machine, replacing `<LINK>` and `<REPO_NAME>`

   ```bash
   git clone <LINK>
   cd <REPO_NAME>
   ```

4. **Set Up Environment**

   ```bash
   python -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```

5. **Launch Jupyter & start the notebook**
   ```bash
   jupyter notebook notebooks/assignment.ipynb
   ```


## Project Structure

```
├── .devcontainer/         # Codespace/development container configuration
├── assets/                # Images and other files 
│
├── notebooks/             # Interactive Jupyter notebooks
│   ├── assignment.ipynb   # Exercise notebook with challenges
│   └── solution.ipynb     # Solution notebook
│
├── .gitignore             # Files/directories not tracked by git
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
```


## Sample Datasets

The project works with carefully designed datasets including:

- **Linear Motion Data**: Mathematical functions and physical concepts
- **University Enrollment**: Categorical data for educational analysis
- **Iris Flower Measurements**: Classic dataset for multi-variable analysis
- **Generated Distributions**: Controlled data for exploring statistical concepts


## Learning Objectives

- **Matplotlib**: Core plotting functionality and customization
- **Seaborn**: Statistical visualization and aesthetic enhancements
- **Pandas**: Data manipulation for visualization
- **NumPy**: Numerical data generation and processing


## Technologies Used

- **Python 3.11**: Core programming language
- **Matplotlib**: Fundamental plotting library
- **Seaborn**: Statistical data visualization
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing and data generation
- **Jupyter**: Interactive development environment


## Contributing

This is an educational project designed for learning data visualization concepts. Contributions for improving exercises, adding new visualization techniques, or enhancing explanations are welcome:

1. Fork the repository
2. Create a feature branch
3. Make your improvements
4. Submit a pull request
