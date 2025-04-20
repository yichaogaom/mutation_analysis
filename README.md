# mutation_analysis
# Mutation Impact Analysis

This project analyzes the biological impact of 49 gene mutations by quantifying changes in mRNA, protein expression, and cell viability. Python-based tools were used to preprocess data, classify mutation types and regions, compute composite scores, and generate visualizations.

## 📁 Project Structure

- `analysis.ipynb`: Main Jupyter notebook with data processing and visualizations.
- `top5_mutations.csv`: Table of the top 5 high-impact mutations.
- `fig_1_mutation_type_vs_score.png`: Boxplot of mutation type vs score.
- `fig_2_mRNA_vs_viability.png`: Scatterplot of mRNA change vs viability.
- `fig_3_protein_change_hist.png`: Histogram of protein expression change.
- `report.pdf`: Full written report (~2000 words).
- `data/`: Folder containing original `.txt` gene data files.

## 🔬 Methods Summary

- **Mutation Classification**: Substitution, insertion, or deletion.
- **Region Classification**: Promoter region (first 1000 bp) vs coding region.
- **Expression Change Analysis**: Calculated average change from replicate data.
- **Scoring System**:  
  `Score = |mRNA_change| + |Protein_change| + |Viability_change|`
- **Visualization**: Created using `matplotlib` and `seaborn`.

## 🧪 Key Results

- Identified top 5 mutations based on combined expression impact.
- Insertion and deletion mutations in coding regions were most disruptive.
- Visual patterns supported scoring system logic.

## 🤖 AI Tools Acknowledgement

This project was supported by OpenAI ChatGPT (GPT-4), which assisted with:
- Code writing and logic clarification
- Report structure and content suggestions

All interpretations and final outputs were verified and written by the student.

## 👤 Author

**Student Name**: [Yichao Gao]  
**Student ID**: [52428004]  
**Course**: [BT5511]  
**Date**: 20th April 2025 
