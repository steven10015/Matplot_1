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
├── .devcontainer/         # Development container configuration
├── assets/                # Resources and preview images
│   └── preview.png        # Project preview image
├── notebook/              # Interactive Jupyter notebooks
│   ├── problems.ipynb     # Exercise notebook with challenges
│   └── solutions.ipynb    # Complete solutions and examples
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
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
