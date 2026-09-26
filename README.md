# QuantumCognitionMLEnhancedCQDBioSensors
This project presents a Quantum Cognition Machine Learning-enhanced Carbon Quantum Dot (CQD) biosensing framework for intelligent detection of antibiotic residues in aquatic ecosystems.
# Quantum Cognition Machine Learning-Enhanced Carbon Quantum Dot Biosensors for Antibiotic Residue Detection in Aquatic Ecosystems

![Quantum Machine Learning](https://img.shields.io/badge/Quantum%20Machine%20Learning-QML-blueviolet)
![Carbon Quantum Dots](https://img.shields.io/badge/Carbon%20Quantum%20Dots-CQD-green)
![Biosensor](https://img.shields.io/badge/Biosensor-Aquatic%20Monitoring-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-SVM-orange)
![Environmental AI](https://img.shields.io/badge/Environmental-AI-success)
![Python](https://img.shields.io/badge/Python-3.x-yellow)

## 📌 Overview

This project presents a **Quantum Cognition Machine Learning-enhanced Carbon Quantum Dot (CQD) biosensing framework for intelligent detection of antibiotic residues in aquatic ecosystems**.

Antibiotic contamination in aquatic environments can originate from pharmaceutical discharge, wastewater, agricultural runoff, aquaculture, livestock operations, and improper disposal. Detecting low-level antibiotic residues is challenging because aquatic samples contain complex chemical and environmental backgrounds.

The proposed framework integrates:

* **Carbon Quantum Dot (CQD) biosensors**
* **Fluorescence sensing**
* **Electrochemical sensing**
* **Environmental parameters**
* **Quantum feature mapping**
* **Quantum-enhanced Support Vector Classification (QSV)**
* **Barber Optimization (BO)**
* **Machine-learning-based signal interpretation**
* **Multi-antibiotic classification**
* **Noise- and environment-aware detection**

The published study develops a **Quantum-enhanced Support Vector Classifier with Barber Optimization (QSV-BO)** and reports classification accuracies of **97.1% for ciprofloxacin, 96.3% for amoxicillin, 95.4% for erythromycin, and 96.6% for tetracycline**.

---

# 🎯 Research Objectives

The primary objectives are:

1. Develop an intelligent CQD-based biosensing framework.
2. Detect antibiotic residues in aquatic environments.
3. Integrate fluorescence and electrochemical sensor responses.
4. Incorporate environmental conditions into the detection model.
5. Apply quantum feature mapping for nonlinear feature representation.
6. Develop a quantum-enhanced Support Vector Classifier.
7. Optimize model and quantum-kernel parameters using Barber Optimization.
8. Improve classification robustness under environmental variability.
9. Distinguish multiple antibiotic residues.
10. Develop a foundation for intelligent and scalable aquatic pollution monitoring.

---

# 🌊 Problem Statement

Traditional laboratory-based antibiotic detection can require sophisticated instrumentation, sample preparation, and centralized analysis.

The project addresses the following challenges:

```text
Aquatic Sample
      │
      ├── Complex Chemical Matrix
      ├── Low Antibiotic Concentration
      ├── Environmental Noise
      ├── pH Variation
      ├── Temperature Variation
      ├── Ionic Interference
      └── Multiple Antibiotic Classes
                │
                ▼
       Difficult Signal Interpretation
                │
                ▼
      Need for Intelligent Detection
```

The proposed approach combines nanoscale sensing with quantum-enhanced machine learning to improve interpretation of complex sensor signals.

---

# 🧬 Carbon Quantum Dot Biosensor

Carbon Quantum Dots are nanoscale carbon-based materials with useful optical and surface properties for sensing applications.

The framework exploits CQDs for generating measurable responses to target antibiotic residues.

```text
              Aquatic Sample
                    │
                    ▼
           ┌────────────────┐
           │ Target Antibiotic│
           └───────┬────────┘
                   │
                   ▼
        ┌──────────────────────┐
        │ Carbon Quantum Dots  │
        │       (CQDs)         │
        └──────────┬───────────┘
                   │
          Molecular Interaction
                   │
          ┌────────┴────────┐
          ▼                 ▼
     Fluorescence       Electrochemical
       Response            Response
          │                 │
          └────────┬────────┘
                   ▼
             Sensor Features
```

CQDs are attractive for biosensing because their optical and surface properties can support sensitive detection and functionalization. The published work specifically integrates fluorescence and electrochemical sensing information.

---

# 🔬 Multimodal Biosensing

A key component of the framework is the combination of multiple signal sources.

## 1. Fluorescence Signals

Fluorescence measurements can capture changes associated with interactions between CQDs and target analytes.

Example features:

* Fluorescence intensity
* Emission characteristics
* Peak position
* Quenching response
* Spectral characteristics

## 2. Electrochemical Signals

Electrochemical measurements provide complementary information.

Possible features include:

* Current response
* Potential
* Impedance-related features
* Peak characteristics
* Charge-transfer response

## 3. Environmental Signals

Environmental conditions are incorporated to improve robustness.

Examples:

* Temperature
* pH
* Conductivity
* Ionic conditions
* Water-quality parameters

---

# 🏗️ Proposed System Architecture

```text
┌──────────────────────────────────────────────────────────┐
│                 AQUATIC ECOSYSTEM                        │
│                                                          │
│ Rivers │ Lakes │ Groundwater │ Wastewater │ Aquaculture │
└──────────────────────────┬───────────────────────────────┘
                           │
                           ▼
                 ┌──────────────────┐
                 │ Water Sampling   │
                 └────────┬─────────┘
                          │
                          ▼
              ┌──────────────────────┐
              │ CQD Biosensing Unit  │
              └──────────┬───────────┘
                         │
             ┌───────────┴────────────┐
             │                        │
             ▼                        ▼
      Fluorescence              Electrochemical
         Signal                     Signal
             │                        │
             └───────────┬────────────┘
                         │
                         ▼
              Environmental Features
                         │
                         ▼
              ┌──────────────────────┐
              │ Data Preprocessing   │
              │ Min-Max Normalization│
              └──────────┬───────────┘
                         │
                         ▼
              ┌──────────────────────┐
              │ Quantum Feature      │
              │ Mapping / Encoding   │
              └──────────┬───────────┘
                         │
                         ▼
              ┌──────────────────────┐
              │ Quantum Kernel       │
              │ Computation          │
              └──────────┬───────────┘
                         │
                         ▼
              ┌──────────────────────┐
              │ Quantum-Enhanced     │
              │ Support Vector       │
              │ Classifier (QSV)     │
              └──────────┬───────────┘
                         │
                         ▼
              ┌──────────────────────┐
              │ Barber Optimization  │
              │ Hyperparameter Tuning│
              └──────────┬───────────┘
                         │
                         ▼
              ┌──────────────────────┐
              │ Antibiotic Detection │
              └──────────┬───────────┘
                         │
        ┌────────────────┼─────────────────┐
        ▼                ▼                 ▼
  Ciprofloxacin     Amoxicillin      Erythromycin
                                           │
                                           ▼
                                      Tetracycline
```

---

# 🧠 Quantum Machine Learning Layer

The quantum learning component transforms normalized classical sensor data into a quantum feature representation.

Conceptually:

$$
x \rightarrow \text{Quantum Feature Map}(x)
\rightarrow |\phi(x)\rangle
$$

The resulting quantum representation is used to construct a kernel:

$$
K(x_i,x_j)
=
|\langle\phi(x_i)|\phi(x_j)\rangle|^2
$$

This kernel enables the classifier to evaluate relationships between samples in a transformed feature space.

---

# ⚛️ Quantum Feature Mapping

The proposed workflow uses quantum encoding to represent normalized sensor features.

```text
Classical Sensor Features
          │
          ▼
   Min-Max Scaling
          │
          ▼
   Feature Vector
          │
          ▼
 ┌───────────────────┐
 │ Quantum Encoding  │
 │                   │
 │ Amplitude / Angle │
 │ Based Mapping     │
 └─────────┬─────────┘
           │
           ▼
     Quantum State
           │
           ▼
     Quantum Kernel
           │
           ▼
      QSV Classifier
```

Quantum feature mapping is used to enhance representation of nonlinear relationships in multidimensional sensor data.

---

# 🤖 Quantum-Enhanced Support Vector Classifier

The classification layer uses a quantum-enhanced Support Vector approach.

A conventional SVM attempts to determine an optimal decision boundary:

$$
f(x)=w^T\phi(x)+b
$$

The quantum-kernel version instead uses:

$$
K(x_i,x_j)
=
\langle\phi(x_i)|\phi(x_j)\rangle
$$

The resulting kernel matrix is used by the Support Vector Classifier.

```text
Sensor Feature Vector
        │
        ▼
Quantum Feature Map
        │
        ▼
Quantum Kernel
        │
        ▼
Kernel Matrix
        │
        ▼
Support Vector Classifier
        │
        ▼
Antibiotic Class
```

---

# 🧪 Antibiotic Classification

The framework focuses on multiple antibiotic residues, including:

```text
                 QSV-BO
                   │
       ┌───────────┼────────────┐
       │           │            │
       ▼           ▼            ▼
 Ciprofloxacin  Amoxicillin  Erythromycin
       │           │            │
       └───────────┼────────────┘
                   │
                   ▼
              Tetracycline
```

The reported test accuracies are:

| Antibiotic    | Reported Accuracy |
| ------------- | ----------------: |
| Ciprofloxacin |             97.1% |
| Amoxicillin   |             96.3% |
| Erythromycin  |             95.4% |
| Tetracycline  |             96.6% |

These values are the experimental results reported in the publication and are not guarantees for independent sensor deployments.

---

# 🧮 Min-Max Normalization

Sensor modalities can have substantially different numerical ranges.

Min-Max normalization is therefore applied:

$$
x'=
\frac{x-x_{min}}
{x_{max}-x_{min}}
$$

This maps features to a common range and provides a standardized input representation for subsequent quantum feature mapping and classification.

```text
Raw Sensor Data
      │
      ├── Fluorescence
      ├── Electrochemical
      └── Environmental
              │
              ▼
       Min-Max Scaling
              │
              ▼
     Normalized Feature Vector
```

The published methodology explicitly uses Min-Max normalization before quantum processing.

---

# 🪒 Barber Optimization

**Barber Optimization (BO)** is incorporated as the optimization mechanism for tuning parameters associated with the quantum-enhanced classifier.

Conceptually:

```text
              Candidate Parameters
                       │
                       ▼
              ┌────────────────┐
              │ Barber         │
              │ Optimization   │
              └───────┬────────┘
                      │
             Generate Candidates
                      │
                      ▼
               Evaluate Fitness
                      │
                      ▼
              Update Parameters
                      │
                      ▼
             Best Configuration
                      │
                      ▼
                 QSV Model
```

The optimization objective can be expressed as:

$$
\theta^*=
\arg\min_{\theta} L(\theta)
$$

where:

* \(\theta\) = model/quantum parameters
* \(L\) = classification loss or optimization objective

The published QSV-BO framework uses Barber Optimization to tune support-vector and quantum-circuit-related parameters.

---

# 🔄 Complete Methodology

```text
Step 1
Aquatic Sample Collection
        ↓
Step 2
CQD-Based Sensing
        ↓
Step 3
Fluorescence Signal Acquisition
        ↓
Step 4
Electrochemical Signal Acquisition
        ↓
Step 5
Environmental Parameter Collection
        ↓
Step 6
Multimodal Data Integration
        ↓
Step 7
Noise / Quality Processing
        ↓
Step 8
Min-Max Normalization
        ↓
Step 9
Quantum Feature Encoding
        ↓
Step 10
Quantum Kernel Generation
        ↓
Step 11
QSV Classification
        ↓
Step 12
Barber Optimization
        ↓
Step 13
Optimized QSV-BO Model
        ↓
Step 14
Antibiotic Classification
        ↓
Step 15
Performance Evaluation
```

---

# 🧩 Hybrid Dataset

The proposed framework integrates multiple types of information.

```text
                 Hybrid Dataset
                      │
       ┌──────────────┼──────────────┐
       │              │              │
       ▼              ▼              ▼
 Fluorescence    Electrochemical  Environmental
    Data             Data             Data
       │              │              │
       └──────────────┼──────────────┘
                      ▼
             Unified Feature Space
                      │
                      ▼
                QSV-BO Model
```

The study combines systematic signal variations across concentrations and environmental conditions with limited real sensor data to improve model robustness.

---

# 🌡️ Environmental Robustness

Aquatic sensor signals can change under different environmental conditions.

```text
                  Environmental Factors
                           │
       ┌───────────────────┼───────────────────┐
       ▼                   ▼                   ▼
      pH              Temperature          Water Matrix
       │                   │                   │
       └───────────────────┼───────────────────┘
                           ▼
                    Sensor Response
                           │
                           ▼
                  Quantum ML Analysis
                           │
                           ▼
                  Robust Classification
```

The framework is designed to incorporate environmental variability rather than treating the sensor response as independent of the surrounding aquatic conditions.

---

# 📊 Performance Evaluation

The model can be evaluated using:

## Classification Metrics

### Accuracy

$$
Accuracy=
\frac{TP+TN}
{TP+TN+FP+FN}
$$

### Precision

$$
Precision=
\frac{TP}{TP+FP}
$$

### Recall

$$
Recall=
\frac{TP}{TP+FN}
$$

### F1-Score

$$
F1=
2\frac{Precision\times Recall}
{Precision+Recall}
$$

---

## Regression / Signal Metrics

Where concentration prediction is evaluated, the framework can use:

### RMSE

$$
RMSE=
\sqrt{
\frac{1}{n}
\sum_{i=1}^{n}(y_i-\hat y_i)^2
}
$$

### \(R^2\)

$$
R^2=
1-
\frac{\sum(y_i-\hat y_i)^2}
{\sum(y_i-\bar y)^2}
$$

The publication discusses classification and regression-quality validation using measures including RMSE, \(R^2\), and F1-score.

---

# 🧪 Experimental Workflow

```text
                 Experimental Data
                         │
                         ▼
              Data Quality Checking
                         │
                         ▼
                Feature Engineering
                         │
                         ▼
                Min-Max Normalization
                         │
                         ▼
              Train / Validation / Test
                         │
                         ▼
                Quantum Encoding
                         │
                         ▼
                 Kernel Generation
                         │
                         ▼
                 QSV Classification
                         │
                         ▼
                 Barber Optimization
                         │
                         ▼
                 Optimized QSV-BO
                         │
                         ▼
                Independent Testing
                         │
                         ▼
                  Metric Analysis
```

---

# 🆚 Baseline Models

For reproducible research, QSV-BO can be compared with:

* Conventional SVM
* RBF-SVM
* Logistic Regression
* Random Forest
* K-Nearest Neighbors
* Decision Tree
* Artificial Neural Network
* Classical optimized SVM
* Quantum Support Vector Machine without optimization
* QSV with alternative optimization algorithms

A suitable comparison should keep preprocessing, train/test partitions, and evaluation criteria consistent.

---

# 📈 Result Visualization

Recommended visualizations include:

### 1. Antibiotic Classification Accuracy

```text
Accuracy
   │
100│
 95│       █
 90│       █     █     █     █
 85│       █     █     █     █
   └────────────────────────────
       CIP   AMX   ERY   TET
```

### 2. Confusion Matrix

```text
                 Predicted
             CIP AMX ERY TET
Actual CIP   ██  ░   ░   ░
       AMX   ░   ██  ░   ░
       ERY   ░   ░   ██  ░
       TET   ░   ░   ░   ██
```

### 3. Quantum Kernel Similarity

Visualize:

* Inter-class similarity
* Intra-class similarity
* Kernel separability
* Feature-space structure

### 4. Optimization Convergence

Plot:

$$
Fitness\ Value \; vs.\; Iteration
$$

to evaluate Barber Optimization convergence.

---

# 🛠️ Technology Stack

## Programming

* Python 3.x
* NumPy
* Pandas
* SciPy
* Matplotlib

## Machine Learning

* Scikit-learn
* Support Vector Machines
* Classification algorithms
* Feature engineering
* Model evaluation

## Quantum Machine Learning

Possible implementation technologies include:

* Qiskit
* PennyLane
* Quantum kernel methods
* Quantum feature maps
* Parameterized quantum circuits

## Deep Learning / Scientific Computing

* TensorFlow
* Scientific Python ecosystem

The published work identifies Python and TensorFlow for data processing, modeling, and evaluation.

---

# 📁 Suggested Project Structure

```text
quantum-cqd-antibiotic-detection/
│
├── README.md
├── requirements.txt
├── LICENSE
│
├── data/
│   ├── raw/
│   │   ├── fluorescence/
│   │   ├── electrochemical/
│   │   └── environmental/
│   │
│   ├── processed/
│   └── metadata/
│
├── src/
│   │
│   ├── preprocessing/
│   │   ├── cleaning.py
│   │   ├── normalization.py
│   │   └── feature_engineering.py
│   │
│   ├── sensing/
│   │   ├── cqd_processing.py
│   │   ├── fluorescence.py
│   │   └── electrochemical.py
│   │
│   ├── quantum/
│   │   ├── feature_mapping.py
│   │   ├── quantum_kernel.py
│   │   └── quantum_circuit.py
│   │
│   ├── models/
│   │   ├── svm.py
│   │   ├── qsv.py
│   │   └── qsv_bo.py
│   │
│   ├── optimization/
│   │   └── barber_optimization.py
│   │
│   ├── evaluation/
│   │   ├── metrics.py
│   │   ├── confusion_matrix.py
│   │   └── visualization.py
│   │
│   └── utils/
│       └── config.py
│
├── notebooks/
│   ├── data_analysis.ipynb
│   ├── quantum_features.ipynb
│   ├── qsv_training.ipynb
│   └── result_analysis.ipynb
│
├── experiments/
│   ├── baseline/
│   ├── qsv/
│   └── qsv_bo/
│
├── results/
│   ├── metrics/
│   ├── figures/
│   └── models/
│
└── tests/
    ├── test_preprocessing.py
    ├── test_quantum_kernel.py
    └── test_models.py
```

---

# ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/quantum-cqd-antibiotic-detection.git
cd quantum-cqd-antibiotic-detection
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

Linux/macOS:

```bash
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# 📦 Example Requirements

```text
numpy
pandas
scipy
scikit-learn
matplotlib
seaborn
tensorflow
qiskit
qiskit-machine-learning
pennylane
jupyter
```

---

# ▶️ Example Execution

### Step 1 — Preprocess data

```bash
python src/preprocessing/normalization.py
```

### Step 2 — Generate quantum features

```bash
python src/quantum/feature_mapping.py
```

### Step 3 — Generate quantum kernel

```bash
python src/quantum/quantum_kernel.py
```

### Step 4 — Train QSV

```bash
python src/models/qsv.py
```

### Step 5 — Optimize using Barber Optimization

```bash
python src/optimization/barber_optimization.py
```

### Step 6 — Run complete QSV-BO experiment

```bash
python src/models/qsv_bo.py
```

### Step 7 — Generate evaluation results

```bash
python src/evaluation/metrics.py
```

---

# 🔬 Algorithmic Workflow

```text
INPUT:
    Fluorescence Signals
    Electrochemical Signals
    Environmental Parameters

              │
              ▼

       Data Integration

              │
              ▼

      Min-Max Normalization

              │
              ▼

       Feature Vector X

              │
              ▼

     Quantum Feature Mapping

              │
              ▼

        Quantum Kernel K

              │
              ▼

       QSV Classification

              │
              ▼

     Barber Optimization
       ┌───────────────┐
       │ Tune Parameters│
       │ Evaluate Model │
       │ Update Search  │
       └───────────────┘

              │
              ▼

         Optimized QSV

              │
              ▼

     Antibiotic Prediction

              │
       ┌──────┼───────────┐
       ▼      ▼           ▼
      CIP    AMX         ERY
                    └──── TET
```

---

# 🌱 Environmental Monitoring Applications

The architecture can potentially support:

* River-water monitoring
* Lake-water monitoring
* Wastewater surveillance
* Aquaculture monitoring
* Agricultural runoff monitoring
* Pharmaceutical effluent monitoring
* Groundwater assessment
* Smart water-quality systems
* Environmental IoT platforms
* Early-warning pollution systems

---

# 🌐 Smart Aquatic Monitoring Architecture

The research can be extended into an IoT-enabled environmental monitoring system:

```text
┌──────────────────────────────────────────┐
│             Aquatic Environment          │
│                                          │
│ Antibiotics │ pH │ Temp │ Conductivity   │
└────────────────────┬─────────────────────┘
                     │
                     ▼
             ┌──────────────┐
             │ CQD Sensor   │
             └──────┬───────┘
                    │
                    ▼
             ┌──────────────┐
             │ Edge Device  │
             └──────┬───────┘
                    │
                    ▼
             Quantum ML Model
                    │
                    ▼
             Antibiotic Alert
                    │
                    ▼
             Cloud Dashboard
                    │
                    ▼
            Environmental
             Monitoring
```

---

# 🚀 Future Research Directions

Potential extensions include:

### Quantum Hardware Deployment

Move from simulated quantum kernels toward execution on available quantum hardware.

### Edge Quantum-Classical AI

Develop lightweight hybrid quantum-classical models for edge-based environmental monitoring.

### Real-Time Detection

Integrate continuous CQD sensor streams with online classification.

### Multi-Analyte Detection

Extend the framework to simultaneously identify:

* Antibiotics
* Pesticides
* Heavy metals
* Pharmaceutical residues
* Organic pollutants

### Explainable Quantum Machine Learning

Develop interpretable methods for understanding:

* Sensor-feature importance
* Quantum-kernel behavior
* Classification boundaries
* Environmental factors affecting detection

### Quantum IoT

Integrate:

```text
CQD Sensors
     ↓
IoT Gateway
     ↓
Edge AI
     ↓
Quantum ML
     ↓
Cloud Environmental Intelligence
```

### Federated Quantum Learning

A future extension could combine the sensing framework with federated learning across geographically distributed aquatic monitoring stations.

---

# 🔬 Research Contributions

The framework brings together four major research domains:

```text
             Environmental Science
                     │
                     ▼
              CQD Biosensing
                     │
                     ▼
           Multimodal Sensor Data
                     │
                     ▼
        Quantum Machine Learning
                     │
                     ▼
             QSV Classification
                     │
                     ▼
          Barber Optimization
                     │
                     ▼
        Intelligent Antibiotic
              Detection
```

### Core Contributions

1. **CQD-based multimodal biosensing**
2. **Quantum feature representation**
3. **Quantum-enhanced Support Vector Classification**
4. **Barber Optimization-based parameter tuning**
5. **Environmental-condition-aware detection**
6. **Multi-antibiotic classification**
7. **Hybrid synthetic and real sensor-data evaluation**
8. **Intelligent aquatic pollution monitoring**

These components correspond to the methodology and contributions described in the published study.

---

# 📚 Publication

**Jayakumar, Aarav Kannan; Rajalakshmi, R. (2026).**

**“Quantum cognition machine learning-enhanced carbon quantum dot biosensors for antibiotic residue detection in aquatic ecosystems.”**

*Microchemical Journal*, **Volume 224**, Article **117498**.

**DOI:** `10.1016/j.microc.2026.117498`

The article is indexed in Scopus and Web of Science according to the bibliographic record.

---

# 📖 Citation

```bibtex
@article{jayakumar2026quantum,
  title={Quantum cognition machine learning-enhanced carbon quantum dot
         biosensors for antibiotic residue detection in aquatic ecosystems},
  author={Jayakumar, Aarav Kannan and Rajalakshmi, R.},
  journal={Microchemical Journal},
  volume={224},
  pages={117498},
  year={2026},
  doi={10.1016/j.microc.2026.117498}
}
```

---

# 👩‍🔬 Research Profile

**R. Rajalakshmi**
Department of Computer Science and Engineering
Sathyabama Institute of Science and Technology
Chennai, Tamil Nadu, India

### Research Areas

* Artificial Intelligence
* Machine Learning
* Quantum Machine Learning
* Environmental AI
* Biosensor Intelligence
* Carbon Quantum Dots
* IoT and Smart Environmental Monitoring
* Cybersecurity
* Edge AI
* Neuro-Symbolic AI
* Healthcare AI
* Intelligent Sensing


