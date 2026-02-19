# Visualizing My LinkedIn Network

A comprehensive analysis and visualization of my LinkedIn network using Python, Jupyter, and Plotly. This project evolved from simple network visualization to include advanced business development analytics for identifying key decision-makers and prospects.

## Overview

- **Tech Stack**: Python, Pandas, Plotly, NetworkX, PyVis
- **Data Source**: LinkedIn Connections (.csv export)
- **Interactive Notebook**: [VisualizingMyLinkedinNetwork.ipynb](VisualizingMyLinkedinNetwork.ipynb)

## 📊 Features

### Core Visualizations
- **Company Distribution**: Treemap showing where colleagues work
- **Role Distribution**: Hierarchical view of job titles across network
- **Interactive Network Graph**: Company relationships based on shared position types

### Business Development Analytics (NEW)
- **Decision-Maker Identification**: Finds VP+ level contacts in data/engineering roles
- **Tiered Prospect Segmentation**:
  - **Tier 1**: VP+ in Data/Engineering (22 prospects)
  - **Tier 2**: Senior/Manager level in target roles (301 prospects)
  - **Tier 3**: All data/engineering roles (1,254+ prospects)
- **Interactive DataFrames**: Explore prospects directly in the notebook

## 🚀 Getting Started

### Option 1: View on GitHub
Open [VisualizingMyLinkedinNetwork.ipynb](VisualizingMyLinkedinNetwork.ipynb) directly in GitHub to see static renders of all analyses and datasets.

### Option 2: Run Locally
```bash
# Clone the repository
git clone https://github.com/TuckerRasbury/02_VisualizingMyLinkedinNetwork.git
cd 02_VisualizingMyLinkedinNetwork

# Install dependencies
pip install pandas plotly networkx pyvis nbformat

# Open the notebook
jupyter notebook VisualizingMyLinkedinNetwork.ipynb
```

### Option 3: Interactive Online (Binder)
Click the badge below to run the notebook interactively online:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/TuckerRasbury/02_VisualizingMyLinkedinNetwork/improve/best-practices?filepath=VisualizingMyLinkedinNetwork.ipynb) 


## 📈 Insights & Use Cases

### For Network Analysis
Discover where your professional community is concentrated and identify key industry hubs and talent pools within your network.

### For Business Development
Rapidly identify decision-makers and influencers in your target functional areas (Data, Engineering, Analytics). The tiered approach allows you to customize outreach strategies:
- Executive engagement for Tier 1 (VPs and above)
- Technical conversations with Tier 2 (Managers and Senior roles)
- Broad awareness campaigns for Tier 3 (all roles)

### Data-Driven Insights
- Understand role distribution across your network
- Identify underrepresented functional areas
- Track connection trends over time (via "Connected On" dates)

## 📝 What's New (Recent Updates)

### Code Quality Improvements
- ✅ Removed unused imports and dependencies
- ✅ Extracted magic numbers into constants for maintainability
- ✅ Avoided `inplace=True` patterns in favor of reassignment
- ✅ Added `.gitignore` for generated files

### Business Development Analytics
- ✅ Decision-maker filtering with customizable criteria
- ✅ Tiered prospect segmentation (VP+, Senior/Manager, All roles)
- ✅ Interactive DataFrames for exploring results
- ✅ Summary statistics for each analysis tier

### Data Visualization
- ✅ Interactive treemaps showing company and role distribution
- ✅ Responsive Plotly visualizations for exploration

## 🛠️ Technical Stack

- **pandas**: Data manipulation and analysis
- **plotly**: Interactive visualizations
- **networkx**: Network analysis
- **pyvis**: Interactive network graphs
- **pathlib**: Cross-platform file handling
- **jupyter**: Interactive notebook environment

## 📚 References

- Original inspiration: [_"Visualizing My Linkedin Network"_ | Medium | Tavish Gobindram Software Engineer](https://towardsdatascience.com/visualizing-my-linkedin-network-c4b232ab2ad0)
- LinkedIn Data Privacy: [LinkedIn Connection Data Export Guide](https://www.linkedin.com/help/linkedin/answer/50191)
