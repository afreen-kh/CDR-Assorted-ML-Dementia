# A Systematic Analysis of Assorted Machine Learning Classifiers to Assess Their Potential in Accurate Prediction of Dementia

**Afreen Khan**, Swaleha Zubair, Samreen Khan  
*Arab Gulf Journal of Scientific Research*, 2022  

🔗 **Paper (PDF):** https://www.emerald.com/agjsr/article-split/40/1/2/59850/A-systematic-analysis-of-assorted-machine-learning

## Repository Purpose

This repository serves as a research companion to the published article titled *“A Systematic Analysis of Assorted Machine Learning Classifiers to Assess Their Potential in Accurate Prediction of Dementia”*.

The study presents a systematic evaluation of multiple machine learning classifiers to assess their effectiveness in dementia prediction using MRI-derived features, with a particular focus on the **Clinical Dementia Rating (CDR)** scale as a clinically significant prognostic indicator.

This repository documents the comparative analysis, evaluation protocol, and clinical interpretation reported in the paper. It does not provide a full implementation or reproducibility package.

## Dataset Context

The experimental analysis reported in this study is based on neuroimaging and clinical data derived from the **Open Access Series of Imaging Studies (OASIS)**. The dataset comprises MRI-derived structural features along with associated clinical annotations used for dementia assessment.

A key clinical variable examined in this work is the **Clinical Dementia Rating (CDR)** scale, which provides a standardized measure of dementia severity and progression. The inclusion of CDR enables clinically meaningful interpretation of model predictions beyond purely data-driven performance metrics.

All analyses were conducted in compliance with the data usage policies governing the OASIS dataset. No raw MRI scans, extracted features, or subject-level records are distributed through this repository.

## Evaluation Protocol

The study adopts a systematic comparative framework to evaluate the predictive capability of **twenty distinct machine learning classifiers** for dementia prediction. The classifiers span multiple learning paradigms, including linear models, instance-based learners, probabilistic methods, tree-based approaches, and ensemble techniques.

Model evaluation was performed using standard classification metrics commonly employed in clinical machine learning studies. Comparative performance analysis focused on identifying consistent trends across classifiers rather than optimizing a single model.

Special emphasis was placed on assessing the statistical and clinical relevance of the **Clinical Dementia Rating (CDR)** variable across models, enabling interpretation of its contribution to dementia prognosis within diverse algorithmic settings.

## Results Summary

The systematic evaluation of various machine learning classifiers revealed clear performance variability across algorithmic families when applied to dementia prediction using MRI-derived features. Ensemble-based and hybrid learning approaches consistently demonstrated superior predictive performance compared to single linear or probabilistic classifiers.

Among the evaluated models, boosting- and tree-based ensemble methods achieved the highest classification accuracy, with peak performance reaching approximately **93.67%**, indicating their strong capacity to capture complex, non-linear relationships in neuroimaging-derived feature spaces. In contrast, simpler probabilistic models exhibited comparatively lower accuracy, highlighting the importance of model expressiveness for dementia classification tasks.

Further analysis focusing on the **Clinical Dementia Rating (CDR)** scale confirmed its clinical and statistical relevance. Precision–recall evaluation across three diagnostic classes—normal cognition, very mild dementia, and moderate dementia—demonstrated consistently high predictive reliability for the normal class, with precision approaching **98%** and recall exceeding **95%**. Although performance decreased for more subtle dementia stages, CDR remained a stable and informative predictor across all classes.

These findings reinforce that classifier performance alone does not dictate diagnostic reliability. Instead, the integration of clinically grounded variables such as CDR plays a pivotal role in enabling robust dementia prognosis across diverse machine learning paradigms. The results collectively support the clinical interpretability and prognostic value of CDR-informed machine learning models in dementia prediction.

## Citation

If you use or reference this work, please cite the following article:

```bibtex
@article{khan2022systematic,
  title={A Systematic Analysis of Assorted Machine Learning Classifiers to Assess Their Potential in Accurate Prediction of Dementia},
  author={Khan, Afreen and Zubair, Swaleha and Khan, Samreen},
  journal={Arab Gulf Journal of Scientific Research},
  year={2022}
}







