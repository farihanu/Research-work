
# Development and Validation of an Explainable Machine Learning Model for Predicting Early Clinical Deterioration in Guillain–Barré Syndrome Using Pretreatment Clinical Data

---

# Topic Exploration

Selecting a suitable research topic required a systematic literature exploration rather than choosing a problem directly. The objective was to identify clinically meaningful research problems in Guillain–Barré Syndrome (GBS), understand the current state of research, evaluate existing Artificial Intelligence (AI) applications, and identify potential research gaps suitable for an undergraduate Computer Science and Engineering research project.

The exploration began with a broad review of AI and machine learning applications in GBS. As the literature review progressed, the search was gradually refined into several focused research categories, including diagnostic delay, emergency department presentation, clinical decision support systems, explainable AI, and traditional clinical prediction studies. This iterative process helped narrow the research scope and ultimately led to the selection of the final research topic.

---

# Literature Search Strategy

The literature search was conducted using the following academic databases:

- Google Scholar
- PubMed
- IEEE Xplore

To ensure comprehensive coverage, the search was divided into five major research categories.

---

## Category 1: Diagnostic Delay

### Objective

- Identify causes of delayed diagnosis
- Understand early recognition challenges
- Explore factors contributing to diagnostic delay

### Search Queries

```
("Guillain-Barre syndrome" OR GBS)
AND
("diagnostic delay" OR "delayed diagnosis")
```

```
("Guillain-Barre syndrome" OR GBS)
AND
(misdiagnosis OR "incorrect diagnosis")
```

```
("Guillain-Barre syndrome" OR GBS)
AND
("early diagnosis" OR "early recognition")
```

---

## Category 2: Emergency Department / First Clinical Presentation

### Objective

- Identify common first symptoms
- Study referral pathways
- Understand emergency physician challenges

### Search Queries

```
("Guillain-Barre syndrome" OR GBS)
AND
("emergency department" OR emergency)
```

```
("Guillain-Barre syndrome" OR GBS)
AND
("first presentation" OR "initial presentation")
```

```
("Guillain-Barre syndrome" OR GBS)
AND
(triage OR referral)
```

---

## Category 3: Clinical Decision Support

### Objective

- Review existing clinical decision-support tools
- Study clinical workflow improvements
- Explore AI-assisted decision making

### Search Queries

```
("Guillain-Barre syndrome" OR GBS)
AND
("clinical decision support" OR CDSS)
```

```
("Guillain-Barre syndrome" OR GBS)
AND
("decision support system")
```

```
("Guillain-Barre syndrome" OR GBS)
AND
(clinical workflow OR "clinical pathway")
```

---

## Category 4: Artificial Intelligence / Machine Learning

### Objective

- Review existing AI models
- Explore machine learning techniques
- Investigate Explainable AI approaches

### Search Queries

```
("Guillain-Barre syndrome" OR GBS)
AND
("machine learning" OR "artificial intelligence")
```

```
("Guillain-Barre syndrome" OR GBS)
AND
("predictive model" OR prediction)
```

```
("Guillain-Barre syndrome" OR GBS)
AND
("explainable AI" OR SHAP OR LIME OR XAI)
```

---

## Category 5: Traditional Clinical Studies

### Objective

- Identify established clinical predictors
- Review prognostic studies
- Understand commonly reported clinical features

### Search Queries

```
("Guillain-Barre syndrome" OR GBS)
AND
("clinical predictors" OR "risk factors")
```

```
("Guillain-Barre syndrome" OR GBS)
AND
(prognosis OR "outcome predictors")
```

```
("Guillain-Barre syndrome" OR GBS)
AND
("clinical features" OR symptoms)
```

---

# 4. Literature Collection

Using the above search strategy, a comprehensive collection of research papers was gathered from different research domains. Instead of selecting papers from only one category, studies were collected across multiple perspectives, including diagnostic delay, emergency medicine, clinical decision support, machine learning, explainable artificial intelligence, and traditional clinical prediction studies.

The collected paper abstracts and detailed summaries are organized separately in the **Literature Review** section of this repository to maintain a clear separation between topic exploration and detailed literature analysis.

---

# 5. Next Step

After completing the literature collection, each selected paper was reviewed and categorized to identify research trends, existing prediction models, current limitations, and potential research gaps. The complete collection of reviewed papers, along with their abstracts, has been organized in the literature/ folder of this repository under their respective research categories. These findings ultimately guided the selection of the final research topic, which is discussed in the following sections.
# 6. Evolution of the Research Topic

The research topic was not selected immediately. Instead, it evolved through multiple stages of literature exploration, critical analysis, and continuous refinement. The objective throughout this process was to identify a research problem that is clinically meaningful, technically feasible for an undergraduate Computer Science and Engineering (CSE) research project, and capable of making a practical contribution.

## Stage 1: Initial Research Exploration

The exploration began with a broad interest in applying Artificial Intelligence (AI) and Machine Learning (ML) to healthcare problems. Since Guillain–Barré Syndrome (GBS) is a rapidly progressing neurological disorder with potentially severe outcomes, it was selected as the disease of interest.

The first objective was to understand the existing applications of AI and ML in GBS. Literature searches focused on identifying current prediction models, machine learning techniques, and clinical applications related to the disease.

During this stage, it became evident that several studies had already explored prognosis prediction, severity assessment, and respiratory failure prediction using both traditional statistical approaches and machine learning methods.

---

## Stage 2: Exploring Existing Clinical Prediction Studies

After understanding the general research landscape, the literature review was expanded to investigate traditional clinical studies.

The objectives of this stage were to identify:

- Common clinical predictors used in previous studies
- Existing clinical scoring systems
- Frequently reported risk factors
- Outcome prediction methods

The review revealed that several established scoring systems, such as mEGOS and mEGRIS, are widely used to estimate disease severity and respiratory failure risk.

Although these models provide valuable clinical guidance, many studies rely on traditional statistical techniques and are designed for specific clinical outcomes.

---

## Stage 3: Investigating Clinical Challenges

Recognizing that prediction models already existed, the exploration shifted toward understanding the practical challenges faced by clinicians during the early stages of patient management.

To achieve this, literature searches focused on:

- Diagnostic delay
- Misdiagnosis
- Emergency department management
- First clinical presentation
- Referral pathways

These studies highlighted that early diagnosis of GBS remains difficult because the disease often begins with nonspecific symptoms such as tingling, mild weakness, or sensory disturbances. Such symptoms can easily be mistaken for other neurological or musculoskeletal conditions, resulting in delayed diagnosis and treatment.

This stage emphasized the importance of supporting clinicians during the earliest phase of patient assessment.

---

## Stage 4: Clinical Decision Support Systems

Based on the findings from diagnostic delay studies, the next stage explored Clinical Decision Support Systems (CDSS).

The objective was to determine whether AI-based decision-support tools already existed for assisting clinicians in the early identification and risk assessment of GBS patients.

Although decision-support systems have become increasingly common in healthcare, relatively few studies specifically addressed explainable clinical decision support for GBS using only pretreatment clinical information.

This indicated an opportunity to investigate a clinically useful decision-support framework.

---

## Stage 5: Explainable Artificial Intelligence

Another important consideration was model interpretability.

Many machine learning models provide accurate predictions but operate as "black boxes," making it difficult for clinicians to understand the reasoning behind the predictions.

Therefore, the literature review was extended to Explainable Artificial Intelligence (XAI), including techniques such as SHAP and LIME.

These studies demonstrated that explainability is becoming increasingly important in medical AI because clinicians need transparent evidence to trust model predictions.

This finding strongly influenced the decision to incorporate Explainable AI into the proposed research.

---

## Stage 6: Identifying the Research Gap

After reviewing studies from multiple perspectives, several observations became clear:

- Numerous studies predict long-term prognosis or disease severity.
- Existing clinical scoring systems are widely used but are based on predefined statistical models.
- Machine learning studies often focus on prediction accuracy while providing limited interpretability.
- Only a limited number of studies investigate explainable machine learning models using pretreatment clinical data for early clinical deterioration prediction.

These observations suggested that there remains an opportunity to develop a transparent machine learning model capable of assisting clinicians during the earliest stage of patient management.

---

## Stage 7: Refinement of the Research Problem

Several possible research directions were considered throughout the exploration process, including:

- Severity prediction
- Respiratory failure prediction
- Diagnostic delay analysis
- Clinical decision support systems
- Explainable AI for healthcare
- Early risk stratification

Each potential topic was evaluated based on:

- Clinical importance
- Novelty
- Availability of hospital data
- Feasibility within the research timeline
- Suitability for a Computer Science and Engineering research project
- Potential for publication

Following this evaluation, the focus gradually shifted toward predicting **early clinical deterioration** using only pretreatment clinical data collected at hospital admission.

This direction combines clinical relevance, explainable machine learning, and practical feasibility while addressing an important stage of patient management.

---

## Final Selected Research Topic

**Development and Validation of an Explainable Machine Learning Model for Predicting Early Clinical Deterioration in Guillain–Barré Syndrome Using Pretreatment Clinical Data**

The proposed study aims to develop an explainable machine learning-based clinical decision support system that predicts the risk of early clinical deterioration in newly diagnosed GBS patients using only clinical information available before treatment begins.

By integrating machine learning with explainable artificial intelligence techniques, the proposed framework seeks to support early clinical decision-making while maintaining transparency and interpretability for healthcare professionals.

---

## Reflection

The topic selection process involved a systematic review of multiple research domains rather than choosing a problem based on assumptions. Each stage of the exploration refined the research direction by identifying what had already been studied, recognizing existing limitations, and evaluating practical feasibility. This iterative process ensured that the final topic was selected through evidence-based analysis and aligns with both current clinical needs and the research objectives of this project.
