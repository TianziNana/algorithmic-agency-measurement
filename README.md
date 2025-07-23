# Algorithmic Agency Measurement Framework

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Research Status](https://img.shields.io/badge/status-methodology%20validated-brightgreen.svg)]()

> **A rigorous framework for measuring user agency in algorithmic recommendation systems, resolving critical methodological issues and establishing evidence-based foundations for human-AI interaction research.**

![Project Overview](project_visualizations/project_summary_dashboard.png)

## 🎯 **Research Breakthrough**

This project addresses and **solves critical methodological problems** in measuring user agency within algorithmic systems. Through systematic analysis of **701,528 Amazon Beauty reviews** from **5,028 users**, we establish the first methodologically rigorous framework for behavioral agency measurement.

### **🔬 Key Methodological Innovation**

- **Fixed Circular Reasoning**: Resolved fundamental issues where predictors were incorrectly included as outcomes
- **Choice Diversity Breakthrough**: Improved measurement validity from **0% to 45.1%** through novel calculation framework  
- **Causal Inference Foundation**: Established clear separation enabling valid statistical inference

---

## 📊 **Empirical Findings**

### **🎯 Statistically Significant Results**

| Discovery | Evidence | Significance |
|-----------|----------|--------------|
| **Recommendation Dependence Effect** | ATE = -0.115, p < 0.001 | Strong causal evidence |
| **Agency-Recommendation Correlation** | r = -0.748 | Robust negative relationship |
| **User Persona Classification** | 4 distinct groups, Silhouette = 0.673 | Excellent clustering quality |
| **Predictive Model Performance** | RMSE = 0.030 | High accuracy framework |

### **👥 User Persona Discovery**

1. **Algorithm-Dependent Users (47.5%)**: Low agency (0.159), high recommendation reliance (0.587)
2. **Highly Autonomous Users (38.0%)**: High agency (0.474), low recommendation dependence (0.033)  
3. **Moderate Autonomy Users (8.8%)**: Medium agency (0.326), selective recommendation use
4. **High-Agency Explorers (5.7%)**: Highest agency (0.649), maximum choice diversity (0.986)

---

## 🔧 **Technical Implementation**

### **Phase 1: Data Preprocessing & Feature Engineering**
```python
# Large-scale data processing pipeline
• 701,528 Amazon Beauty reviews processed
• 5,028 users with sufficient activity retained  
• Multi-dimensional agency indicator calculation
• Comprehensive data quality validation
```

### **Phase 2: Exploratory Analysis & User Personas**
```python
# Advanced clustering and persona identification
• K-means clustering with PCA dimensionality reduction
• Silhouette Score: 0.673 (excellent quality)
• 4 distinct user personas identified
• Statistical significance testing across groups
```

### **Phase 3: Causal Inference & Explanatory Modeling**
```python
# Rigorous causal analysis framework
• Treatment effect estimation: ATE = -0.115 (p < 0.001)
• SHAP explainability analysis: RMSE = 0.030
• Counterfactual fairness evaluation
• Evidence-based design recommendations
```

### **Phase 4: Methodology Fixes (Innovation)**
```python
# Critical methodological improvements
• Circular reasoning resolution in agency measurement
• Choice diversity calculation optimization (0% → 45.1%)
• Clear variable separation for causal inference
• Reproducible research framework establishment
```

---

## 📈 **Before vs After: Methodological Impact**

| **Metric** | **Before Fix** | **After Fix** | **Improvement** |
|------------|----------------|---------------|-----------------|
| Choice Diversity Validity | ~0% users | **45.1% users** | ✅ **Fundamental resolution** |
| Agency Measurement | Circular reasoning | **Rigorous framework** | ✅ **Methodologically sound** |
| Causal Analysis | Invalid | **Statistically significant** | ✅ **Research-grade evidence** |
| User Classification | 2 unclear groups | **4 distinct personas** | ✅ **Precise segmentation** |
| Predictive Performance | Unknown | **RMSE = 0.030** | ✅ **High-accuracy models** |

---

## 🛠 **Tech Stack & Dependencies**

```python
# Core Analysis Framework
pandas>=1.5.0          # Data manipulation
numpy>=1.21.0           # Numerical computing
scipy>=1.9.0            # Statistical analysis
scikit-learn>=1.1.0     # Machine learning

# Causal Inference & Explainability  
dowhy>=0.8.0            # Causal inference framework
shap>=0.41.0            # Model explainability

# Visualization & Reporting
matplotlib>=3.5.0       # Static plotting
seaborn>=0.11.0        # Statistical visualization
plotly>=5.0.0          # Interactive dashboards
```

---

## 🚀 **Quick Start**

### **1. Clone and Setup**
```bash
git clone https://github.com/yourusername/algorithmic-agency-measurement.git
cd algorithmic-agency-measurement
pip install -r requirements.txt
```

### **2. Run Complete Analysis Pipeline**
```bash
# Phase 1: Data preprocessing (requires Amazon Beauty dataset)
python src/phase1_preprocessing.py --data_path data/raw/All_Beauty.jsonl

# Phase 4: Apply methodological fixes  
python src/phase4_fixed_analysis.py

# Phase 2-3: Analysis with fixed methodology
python src/robust_phase2_fixed.py
python src/phase3_with_fixed_data.py

# Generate comprehensive visualizations
python src/generate_all_visualizations.py
```

### **3. Explore Results**
```bash
# Key output files
results_fixed/
├── phase2/                     # User persona analysis
├── phase3/                     # Causal inference results  
├── fixed_user_analysis.csv     # Clean dataset
└── reports/                    # Comprehensive reports

project_visualizations/         # All generated plots
├── before_after/              # Methodology comparison
├── agency_analysis/           # Core findings
├── user_personas/             # Persona characteristics
└── project_summary_dashboard.png  # Overview
```

---

## 📊 **Research Validation**

### **Statistical Rigor**
- **Sample Size**: 5,028 users (sufficient statistical power)
- **Effect Size**: ATE = -0.115 (medium-to-large effect)
- **Significance**: p < 0.001 (highly significant)
- **Model Quality**: Silhouette Score = 0.673 (excellent clustering)

### **Methodological Robustness**  
- **Circular Reasoning**: ✅ Resolved through variable separation
- **External Validity**: ✅ Large-scale real-world data
- **Reproducibility**: ✅ Complete open-source pipeline
- **Theoretical Foundation**: ✅ Based on established HCI theory

### **Peer Review Readiness**
- **Complete Documentation**: ✅ All methods fully described
- **Code Availability**: ✅ Full implementation provided
- **Data Quality**: ✅ Comprehensive validation performed
- **Ethical Considerations**: ✅ Public dataset, anonymized users

---

## 🎓 **Academic Contributions**

### **For Human-Computer Interaction Research**
- **First rigorous behavioral agency measurement framework** resolving methodological gaps
- **Evidence-based design recommendations** for algorithm transparency
- **Validated user taxonomy** enabling personalized interface development

### **For Recommendation Systems Research**
- **Causal evidence** of algorithmic impact on user autonomy (ATE = -0.115)
- **Quantitative framework** for measuring choice diversity in algorithmic environments  
- **Fair comparison methodology** across different system designs

### **For Digital Inclusion & Ethics Research**
- **Identification of vulnerable populations** (47.5% algorithm-dependent users)
- **Empirical foundation** for algorithmic accountability policies
- **Tools for measuring** AI system impact on user empowerment

---

## 📁 **Project Structure**

```
algorithmic-agency-measurement/
├── 📂 src/                              # Source code
│   ├── phase1_preprocessing.py          # Data processing pipeline  
│   ├── robust_phase2_fixed.py          # Fixed exploratory analysis
│   ├── phase3_with_fixed_data.py       # Fixed causal inference
│   ├── phase4_fixed_analysis.py        # Methodology corrections
│   ├── choice_diversity_fix.py         # Diversity calculation fixes
│   ├── agency_measurement_fix.py       # Agency framework fixes
│   └── generate_all_visualizations.py  # Comprehensive plotting
├── 📂 data/                            # Data directory
│   ├── raw/                            # Original datasets (not included)
│   └── README.md                       # Data documentation
├── 📂 processed_data/                  # Phase 1 outputs
├── 📂 results_fixed/                   # Fixed analysis results
│   ├── phase2/                         # Persona analysis outputs
│   ├── phase3/                         # Causal inference outputs
│   └── reports/                        # Comprehensive reports
├── 📂 project_visualizations/          # All generated plots
├── 📂 references/                      # Academic literature
├── 📄 requirements.txt                 # Python dependencies
├── 📄 LICENSE                          # MIT license
└── 📄 README.md                        # This file
```

---

## 🔬 **Research Methodology**

### **Theoretical Foundation**
- **Technology Acceptance Model (TAM)**: User-algorithm interaction framework
- **Self-Determination Theory (SDT)**: User autonomy and agency concepts  
- **Causal Inference Theory**: Pearl's causal hierarchy implementation

### **Statistical Methods**
- **Causal Inference**: DoWhy framework with multiple identification strategies
- **Clustering Analysis**: K-means with PCA dimensionality reduction
- **Explainability**: SHAP values for model interpretation
- **Validation**: Cross-validation, silhouette analysis, significance testing

### **Quality Assurance**
- **Methodological Review**: Systematic identification and resolution of circular reasoning
- **Robustness Checks**: Multiple estimation methods and sensitivity analysis  
- **Reproducibility**: Complete code availability and documentation
- **Transparency**: Open methodology and clear limitation discussion

---

## 📊 **Impact & Applications**

### **Immediate Applications**
- **Interface Design**: Evidence-based recommendations for 47.5% of users needing agency enhancement
- **Algorithm Auditing**: Framework for measuring user autonomy impact
- **Policy Development**: Quantitative foundation for algorithmic accountability

### **Future Research Directions**  
- **A/B Testing Framework**: Validate interventions using established personas
- **Cross-Platform Validation**: Apply methodology to other recommendation systems
- **Longitudinal Analysis**: Track agency changes over time with system modifications

### **Industry Impact**
- **E-commerce Platforms**: Optimize recommendation systems for user empowerment
- **Content Platforms**: Balance engagement with user autonomy  
- **AI Ethics**: Practical tools for measuring algorithmic fairness

---

## 📞 **Contact & Collaboration**

- **Author**: Tianzi Liu  
- **Email**: tianziliu99@gmail.com
- **Research Focus**: Fairness-aware AI, Human-AI Interaction, Algorithmic Ethics
- **Institution**: Johns Hopkins Carey Business School

### **How to Cite**
```bibtex
@misc{liu2024agency,
  title={Behavioral Agency Measurement Framework for Algorithmic Systems: 
         Methodological Innovation and Empirical Validation},
  author={Liu, Tianzi},
  year={2024},
  note={Comprehensive analysis of 701,528 user interactions with statistical validation},
  url={https://github.com/yourusername/algorithmic-agency-measurement}
}
```

---

## 📄 **License & Contributing**

This project is licensed under the **MIT License** - see [LICENSE](LICENSE) for details.

**Contributions welcome!** Please read our contributing guidelines and submit pull requests for:
- Additional dataset validation
- Alternative measurement frameworks  
- Cross-platform implementation
- Methodological improvements

---

## 🙏 **Acknowledgments**

- **Amazon Review Dataset**: Public dataset enabling large-scale analysis
- **DoWhy Framework**: Microsoft Research's causal inference library
- **SHAP Library**: Model explainability and interpretation tools
- **Open Source Community**: Python scientific computing ecosystem

---

*This research demonstrates the critical importance of methodological rigor in behavioral data analysis and provides a validated, reproducible framework for measuring user agency in algorithmic systems. The findings have immediate implications for interface design, algorithm auditing, and digital rights protection.*

**⭐ Star this repo if you find it useful for your research!**
