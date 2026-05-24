
# ANYA: A Noteworthy Youth Annotation Dataset

**ANYA (A Noteworthy Youth Annotation Dataset)** is a specialized, expert-annotated dataset designed to train machine learning models for ergonomic posture analysis among secondary school students. The framework addresses critical gaps in adolescent posture monitoring by enabling real-time, webcam-based health tracking within everyday classroom environments.

![ANYA Adolescent Posture Analysis Pipeline](ANYA_Adolescent_Posture_Analysis_Pipeline.png)

*Figure: Overview of the ANYA adolescent posture analysis and machine learning pipeline.*

---

# Key Features of the ANYA Dataset

## Adolescent-Centered Design

Unlike traditional ergonomic datasets that primarily focus on adults or workplace environments, ANYA specifically targets the unique ergonomic characteristics and sitting behaviors of adolescents in classroom settings.

This adolescent-centered approach improves the relevance and accuracy of posture analysis for secondary school students.

---

## Semi-Supervised Learning Framework

The dataset employs a semi-supervised annotation strategy to reduce manual labeling effort.

Key techniques include:

- Manual annotation from only **10 labeled instances**
- Expert-guided clustering
- Pseudo-label generation
- Automated dataset expansion

This significantly reduces the cost and time required for large-scale ergonomic dataset creation.

---

## Strong Generalizability

Models trained using the ANYA dataset demonstrate strong robustness across:

- Different student body postures
- Multiple camera viewpoints
- Natural classroom variations
- Real-world sitting conditions

This improves deployment reliability in practical educational environments.

---

# Machine Learning Performance

The study evaluated multiple machine learning models, including:

- XGBoost (XGB)
- LightGBM (LGBM)
- Random Forest (RF)
- Artificial Neural Networks (ANN)

## LightGBM: Best Overall Performance

LightGBM emerged as the most practical solution by balancing predictive accuracy and computational efficiency.

### Performance Highlights

- **F1-score:** 0.9805
- Fastest training duration
- Suitable for real-time classroom deployment
- Low computational overhead

This makes LightGBM highly effective for continuous posture monitoring systems running on low-resource devices.

---

## Random Forest: Highest Accuracy but Higher Cost

Random Forest achieved the highest predictive accuracy:

- **F1-score:** 0.9856

However, its significantly longer training time reduced its practicality for real-time classroom applications.

---

# Practical Applications

By deploying posture-analysis models trained on the ANYA dataset through standard classroom webcams, schools can:

- Continuously monitor student posture
- Detect unhealthy sitting behaviors early
- Reduce ergonomic risks
- Support healthier digital learning environments
- Prevent long-term musculoskeletal disorders

Importantly, the framework operates using low-cost hardware already available in many schools.

---

# Why ANYA Matters

ANYA demonstrates that advanced ergonomic monitoring does not require expensive sensors or specialized medical equipment.

Instead, the framework shows that:

- standard webcams,
- lightweight machine learning models, and
- intelligent annotation strategies

can together provide scalable and affordable student health monitoring systems.

This represents a promising direction for future AI-assisted educational health technologies.

---

# Additional Resources

## Technical Publication

Read the original IEEE publication for detailed methodology, evaluation metrics, and experimental analysis.

Jandaeng, C., Kongkwamcharoen, C., Jaiwang, T., Koad, P., & Thu, M. (2025). ANYA: A noteworthy youth annotation dataset for machine learning-based ergonomic posture analysis. *IEEE Access, 13*, 199665–199682. https://doi.org/10.1109/ACCESS.2025.3633624


```bibtex
@ARTICLE{11250615,
  author={Jandaeng, Chanankorn and Kongkwamcharoen, Chonthicha and Jaiwang, Trakan and Koad, Peeravit and Thu, May},
  journal={IEEE Access}, 
  title={ANYA: A Noteworthy Youth Annotation Dataset for Machine Learning-Based Ergonomic Posture Analysis}, 
  year={2025},
  volume={13},
  number={},
  pages={199665-199682},
  keywords={Ergonomics;Accuracy;Sensors;Monitoring;Computer vision;Semisupervised learning;Machine learning;Hardware;Annotations;Real-time systems;Ergonomic posture assessment;semi-supervised learning framework;webcam-based human pose recognition;adolescent health monitoring;resource-constrained educational settings;low-cost classroom technologies},
  doi={10.1109/ACCESS.2025.3633624}}


```

---

## Dataset Access

Access the dataset directly to develop and evaluate your own posture analysis models.

- Kaggle Dataset Repository (https://www.kaggle.com/datasets/chanankornjandaeng/anya-a-dataset-for-ergonomic-posture-analysis)