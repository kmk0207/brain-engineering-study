현재 GitHub Repository `brain-engineering-study`의 루트에 `README.md`가 존재한다.

기존 README의 내용을 먼저 확인한 뒤, 중요한 기존 내용은 최대한 유지하면서 Repository 구조와 학습 Roadmap을 아래의 새로운 구조에 맞게 수정해줘.

# Repository 목적

이 Repository는 Computer Engineering 전공자가 Brain & Cognitive Engineering 연구를 준비하면서 공부한 내용을 기록하기 위한 학습 Repository이다.

전체 학습 흐름은 다음과 같다.

```text
Programming
↓
Machine Learning
↓
Signal Processing
↓
EEG
↓
EEG + Machine Learning
↓
EEG Cognitive State Classification Project
```

Programming 단계에서는 Python, NumPy, Pandas, Matplotlib을 하나의 STEP으로 묶어서 공부한다.

---

# README 제목

```markdown
# 🧠 Brain Engineering Study
```

---

# Introduction

다음 내용을 자연스럽게 작성한다.

Computer Engineering 기반으로

* Programming
* Machine Learning
* Signal Processing
* EEG
* Cognitive Engineering

을 단계적으로 공부하기 위한 Repository이다.

최종적으로 EEG 데이터를 직접 처리하고 Machine Learning을 이용하여 Cognitive State Classification을 구현하는 것을 목표로 한다.

---

# 🎯 Goal

다음 학습 흐름을 표시한다.

```text
Computer Engineering

↓

Programming
Python / NumPy / Pandas / Matplotlib

↓

Machine Learning

↓

Signal Processing

↓

EEG

↓

EEG + Machine Learning

↓

Cognitive Engineering

↓

EEG Cognitive State Classification
```

---

# 📚 Study Roadmap

## STEP 1. 💻 Programming

Python 기반 데이터 분석 능력을 만든다.

### Python

* [ ] Variables / Data Types
* [ ] List / Tuple
* [ ] Dictionary / Set
* [ ] Condition / Loop
* [ ] Function
* [ ] File I/O
* [ ] Class Basic

### NumPy

* [ ] ndarray
* [ ] shape / reshape
* [ ] indexing / slicing
* [ ] axis
* [ ] mean / std
* [ ] broadcasting
* [ ] EEG-style multidimensional array

### Pandas

* [ ] Series
* [ ] DataFrame
* [ ] CSV
* [ ] column / row selection
* [ ] filtering
* [ ] missing values
* [ ] groupby
* [ ] describe

### Matplotlib

* [ ] plot
* [ ] scatter
* [ ] histogram
* [ ] signal visualization
* [ ] multi-channel visualization

Programming의 최종 목표는 다음과 같다.

```text
Python Basic
↓
Numerical Data Processing
↓
Experimental Data Management
↓
Signal Visualization
↓
Ready for Machine Learning / EEG
```

---

## STEP 2. 🤖 Machine Learning

* [ ] Machine Learning Fundamentals
* [ ] Linear Regression
* [ ] Logistic Regression
* [ ] KNN
* [ ] Decision Tree
* [ ] SVM
* [ ] Model Evaluation
* [ ] Cross Validation
* [ ] PCA

목표:

```text
Data
↓
Feature
↓
Machine Learning
↓
Prediction
↓
Evaluation
```

---

## STEP 3. 📡 Signal Processing

* [ ] Signal Basics
* [ ] Sampling
* [ ] Fourier Transform
* [ ] FFT
* [ ] Filtering
* [ ] Power Spectral Density

목표:

```text
Time-domain Signal
↓
Signal Processing
↓
Frequency-domain Analysis
```

---

## STEP 4. 🧠 EEG

* [ ] EEG Basics
* [ ] EEG Frequency Bands
* [ ] EEG Preprocessing
* [ ] ERP
* [ ] Feature Extraction

목표:

```text
Raw EEG
↓
Preprocessing
↓
Epoching
↓
Feature Extraction
↓
Clean EEG Features
```

---

## STEP 5. 🧠🤖 EEG + Machine Learning

* [ ] EEG Dataset
* [ ] Preprocessing
* [ ] Feature Extraction
* [ ] Band Power
* [ ] Classification
* [ ] Cross Validation
* [ ] Model Evaluation

목표:

```text
EEG
↓
Preprocessing
↓
Feature Extraction
↓
Machine Learning
↓
Cognitive State Prediction
```

---

# 🔬 Final Project

## EEG Cognitive State Classification

최종 프로젝트 목표는 공개 EEG Dataset을 이용하여 전체 EEG + ML Pipeline을 구현하는 것이다.

```text
EEG Dataset
↓
Preprocessing
↓
Filtering
↓
Epoching
↓
Feature Extraction
↓
PSD / Band Power
↓
Machine Learning
↓
Classification
↓
Evaluation
```

사용할 기본 ML Model:

* Logistic Regression
* KNN
* SVM

Evaluation:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix
* Cross Validation

---

# 📂 Repository Structure

README에 다음 구조를 표시한다.

```text
brain-engineering-study/

├── README.md
│
├── 01_programming/
│   ├── README.md
│
├── 02_machine_learning/
│   └── README.md
│
├── 03_signal_processing/
│   └── README.md
│
├── 04_eeg/
│   └── README.md
│
├── 05_eeg_machine_learning/
│   └── README.md
│
└── projects/
    └── eeg_cognitive_state_classification/
        └── README.md
```

---

# 🏁 Long-Term Goal

마지막에는 다음 내용을 간략하게 작성한다.

이 Repository의 목적은 단순히 Python이나 Machine Learning 문법을 공부하는 것이 아니다.

Computer Engineering에서 배운 Programming과 데이터 처리 능력을 기반으로

```text
Computer Engineering
↓
Machine Learning
↓
Signal Processing
↓
EEG
↓
Brain & Cognitive Engineering
```

으로 연구 역량을 확장하는 것이 목표이다.

---

# 작업 규칙

1. 기존 README를 먼저 읽는다.
2. 기존에 의미 있는 내용이 있으면 무조건 삭제하지 않는다.
3. 위 Roadmap과 충돌하는 기존 구조만 새로운 구조에 맞게 수정한다.
4. Python / NumPy / Pandas / Matplotlib을 각각 STEP으로 만들지 않는다.
5. 네 분야는 모두 `STEP 1. Programming` 안에 포함한다.
6. Markdown 형식을 깔끔하게 작성한다.
7. 설명은 한국어 중심으로 작성하되 기술 용어는 영어를 사용해도 된다.
8. 과도하게 긴 이론 설명은 작성하지 않는다.
9. 학습 진행 상황을 확인할 수 있도록 checkbox를 유지한다.
10. 수정 완료 후 변경한 내용을 간단하게 요약한다.
