
# UX/HF Data Analysis Project

This project is all about analyzing UX and Human Factors (HF) data using R Markdown. It’s designed to help researchers quickly explore, clean, and visualize their datasets while performing some basic analyses, like bootstrapping.

---

## What’s Included

1. **`ux_hf_sample_data.csv`**  
   - A sample dataset with participant data (e.g., task completion time, accuracy, stress levels, and more).  

2. **`ux_hf_analysis.Rmd`**  
   - The R Markdown file where all the analysis happens.  
   - Includes data cleaning, summary statistics, visualizations, and bootstrap confidence intervals.  

---

## How to Use This

1. **Clone this repository**:  
   Download the files to your computer.  
   ```bash
   git clone https://github.com/mohsen-rafiei/Bootstrapping.git
   cd Bootstrapping
   ```

2. **Open the R Markdown file**:  
   Open `ux_hf_analysis.Rmd` in RStudio or your favorite R editor.  

3. **Run the code**:  
   Knit the document into an HTML file (or Word/PDF, if you prefer).  

4. **Explore the results**:  
   - Summary statistics like averages of task completion time, accuracy, and stress levels.  
   - Visualizations:  
     - Task Completion Time Distribution  
     - Accuracy vs. Stress Level  
     - Bootstrap Distribution of Task Completion Time  
   - Bootstrap confidence intervals for task completion time.  

---

## Purpose

This project is meant to serve as a quick-start framework for UX and HF researchers to analyze their data. It’s lightweight, customizable, and easy to adapt for your own datasets.

---

## Requirements

- **R** (version 4.0 or higher recommended)  
- The following R packages:  
  - `tidyverse`  
  - `ggplot2`  

Install them with:  
```R
install.packages(c("tidyverse", "ggplot2"))
```

---

## Contributing

Found a bug or have a suggestion? Feel free to open an issue or submit a pull request. Contributions are welcome!

---

## License

This project is open-source under the [MIT License](LICENSE). Use it, modify it, and share it—just give credit where it’s due.
