# Star Wars Sentiment Analysis 🌟

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![R](https://img.shields.io/badge/R-4.0.0-blue.svg)](https://www.r-project.org/)
[![Contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](https://github.com/AndreChuabio/Star-Wars-Sentiment-Analysis/issues)

## 📊 Overview
This project conducts a comprehensive sentiment analysis of Star Wars movie scripts using Natural Language Processing (NLP) techniques. By analyzing dialogue patterns and emotional content, we uncover insights into character development and narrative arcs across the original trilogy.

![Star Wars Analysis](https://img.shields.io/badge/Star%20Wars-Sentiment%20Analysis-red)

## ✨ Features
- **Sentiment Analysis**: Deep dive into emotional patterns in movie dialogues
- **Character Tracking**: Individual character sentiment progression
- **Visual Analytics**: Dynamic visualizations of emotional patterns
- **Cross-Episode Analysis**: Comparative study across different movies

## 📚 Data Sources
The analysis covers the original Star Wars trilogy (Episodes IV, V, and VI). Due to size limitations, data files are stored separately. Access the source data here:
- [Original Project Repository](https://github.com/samrea5/Project-1-Star-Wars-Sentiment-analysis)

## 🗂 Project Structure
```bash
Star-Wars-Sentiment-Analysis/
├── 📁 DATA/                  # Data directory
│   ├── 📄 Preprocessing/    # Raw movie scripts
│   └── 📄 Processed/       # Processed dialogue files
├── 📁 Scripts/              # Analysis scripts
│   ├── 📊 Analysis/        # Main analysis
│   └── 🔧 Preprocessing/   # Data preparation
└── 📈 Output/              # Results and visualizations
```

## 🚀 Getting Started

### Prerequisites
- R (version 4.0.0 or higher)
- RStudio (recommended)
- Required R packages:
  ```r
  install.packages(c("tidyverse", "tidytext", "ggplot2", "dplyr", "stringr"))
  ```

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/AndreChuabio/Star-Wars-Sentiment-Analysis.git
   cd Star-Wars-Sentiment-Analysis
   ```
2. Download data files from the original repository
3. Place data files in appropriate `DATA/` subdirectories
4. Open the R project in RStudio

### Running the Analysis
1. Execute preprocessing scripts in order:
   - `Scripts/Preprocessing/Star Wars 4- Preprocessing.Rmd`
   - `Scripts/Preprocessing/Star Wars 5- Preprocessing.Rmd`
   - `Scripts/Preprocessing/Star Wars 6- Preprocessing.Rmd`
2. Run the main analysis:
   - `Scripts/Analysis/Analysis of Star Wars.Rmd`

## 🔬 Analysis Methods
Our analytical approach includes:
- **Lexicon-Based Sentiment Analysis**: Using the NRC emotion lexicon
- **Character-Level Analysis**: Tracking individual character emotional arcs
- **Temporal Analysis**: Time-series sentiment tracking
- **Statistical Testing**: Chi-squared tests for emotional differences
- **Cross-Episode Comparison**: Comparative analysis between movies

## 📈 Key Findings
The analysis reveals fascinating patterns in Star Wars dialogues:
- **Character Development**: Emotional evolution of key characters
- **Narrative Structure**: Sentiment patterns matching story arcs
- **Episode Comparisons**: Distinct emotional signatures per film
- **Key Moments**: Identification of emotional turning points

## 🤝 Contributing
We welcome contributions! Here's how you can help:

1. Fork the repository
2. Create your feature branch:
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature/AmazingFeature
   ```
5. Open a Pull Request

## 📝 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments
- Original concept and data from [Star Wars Sentiment Analysis Project](https://github.com/samrea5/Project-1-Star-Wars-Sentiment-analysis)
- Star Wars scripts from various online sources
- R community and package maintainers

## 📬 Contact
Andre Chuabio - [GitHub](https://github.com/AndreChuabio)

Project Link: [https://github.com/AndreChuabio/Star-Wars-Sentiment-Analysis](https://github.com/AndreChuabio/Star-Wars-Sentiment-Analysis)

---
⭐️ If you find this project interesting, please consider giving it a star!
