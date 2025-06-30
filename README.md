# Data Visualization with Matplotlib and Seaborn

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

## Learning Objectives

### Core Visualization Concepts
- Understanding when to use different chart types
- Creating clear, informative plots with proper labeling
- Customizing visual elements for better communication
- Exploring data distributions and relationships

### Technical Skills
- **Matplotlib**: Core plotting functionality and customization
- **Seaborn**: Statistical visualization and aesthetic enhancements
- **Pandas**: Data manipulation for visualization
- **NumPy**: Numerical data generation and processing

## Getting Started

### Using GitHub Codespaces (Recommended)

Launch this project instantly in a fully configured cloud development environment:

1. Click the green "Code" button on the GitHub repository
2. Select "Codespaces" tab
3. Click "Create codespace on main"
4. Wait for the environment to initialize (all dependencies will be installed automatically)
5. Open `notebook/problems.ipynb` to start the exercises

GitHub Codespaces provides a complete VS Code environment in your browser with all required extensions and packages pre-installed.


### Local installation

#### Prerequisites

- Python 3.11+
- Jupyter Notebook or VS Code with Jupyter extension

#### Steps

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd 02-matplotlib
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Open the project**:
   ```bash
   jupyter notebook notebook/problems.ipynb
   ```
   
   Or open the notebook files in VS Code with the Jupyter extension.


## Project Structure

```
├── .devcontainer/          # Development container configuration
├── assets/                 # Resources and preview images
│   └── preview.png        # Project preview image
├── notebook/              # Interactive Jupyter notebooks
│   ├── problems.ipynb     # Exercise notebook with challenges
│   └── solutions.ipynb    # Complete solutions and examples
├── requirements.txt       # Python dependencies
└── README.md             # Project documentation
```

## Exercises Overview

### Exercise 1: Simple Line Plot
- **Concept**: Linear functions and continuous data
- **Skills**: Basic plotting, axis labeling, mathematical visualization
- **Application**: Walking speed analysis using distance vs. time

### Exercise 2: Categorical Data Visualization
- **Concept**: Representing categorical information
- **Skills**: Bar charts (vertical and horizontal), proper labeling
- **Application**: University enrollment analysis by major

### Exercise 3: Proportion Visualization
- **Concept**: Part-to-whole relationships
- **Skills**: Pie charts, percentage display, effective labeling
- **Application**: Student distribution across academic programs

### Exercise 4: Relationship Analysis
- **Concept**: Correlation between numerical variables
- **Skills**: Scatter plots, color coding, legend management
- **Application**: Iris flower measurements analysis

### Exercise 5: Distribution Exploration
- **Concept**: Understanding data distributions
- **Skills**: Histograms, bin optimization, multiple distributions
- **Application**: Flower characteristic distribution patterns

### Exercise 6: Correlation Visualization
- **Concept**: Variable relationships and correlation strength
- **Skills**: Heatmaps, correlation matrices, annotation
- **Application**: Multi-variable relationship analysis

### Exercise 7: Statistical Summaries
- **Concept**: Distribution comparison across categories
- **Skills**: Box plots, quartile visualization, outlier detection
- **Application**: Species-based characteristic comparison

## Key Concepts Covered

### Visualization Best Practices
- **Clarity**: Clear axis labels, titles, and legends
- **Appropriateness**: Choosing the right chart type for your data
- **Aesthetics**: Effective use of color, size, and styling
- **Communication**: Making data insights accessible and understandable

### Technical Proficiency
- **Matplotlib Fundamentals**: Core plotting functions and customization
- **Seaborn Enhancements**: Statistical plotting and improved aesthetics
- **Data Integration**: Working with Pandas DataFrames and NumPy arrays
- **Interactive Development**: Jupyter notebook best practices

## Sample Datasets

The project works with carefully designed datasets including:

- **Linear Motion Data**: Mathematical functions and physical concepts
- **University Enrollment**: Categorical data for educational analysis
- **Iris Flower Measurements**: Classic dataset for multi-variable analysis
- **Generated Distributions**: Controlled data for exploring statistical concepts

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

## Educational Value

This project is structured to provide:

- **Progressive Learning**: Exercises build from simple to complex concepts
- **Practical Application**: Real-world scenarios and relevant datasets
- **Best Practices**: Industry-standard visualization techniques
- **Interactive Exploration**: Hands-on experimentation with parameters and styles

Perfect for data science students, analysts, and anyone looking to improve their data visualization skills with Python's most popular libraries.
