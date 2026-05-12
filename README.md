![Portfolio Summary Banner](00_Resources/portfolio_banner.png)

<br>

**I walk into broken, expensive, manual processes and automate them out of existence.**

Analytics & Automation Engineer with a track record of delivering production-grade 
automation and AI pipelines inside highly regulated government environments.

This portfolio documents that work — real problems, real outcomes, and the analytical 
depth that makes the automation meaningful.

<br>

## Automation & AI Pipelines  

**Production deployments. Real environments. Measurable outcomes.**

### WhisperX Transcription Pipeline

*What do you do when 3,500 call recordings need transcribing and no approved tool exists?*

[<img src="00_Resources/transcription_image.jpg" alt="Transcription image" height="200px">](https://github.com/DataDaneHQ/whisperx-transcription-pipeline)

[View Project →](https://github.com/DataDaneHQ/whisperx-transcription-pipeline)

#### The Problem

An enforcement team needed ~3,500 call recordings transcribed at scale — fast, accurately, and without sensitive audio ever leaving the team's infrastructure. No approved commercial tool existed. Procurement was too slow.

#### How It Was Solved

Built and deployed an in-house pipeline using WhisperX and three Pyannote neural models for speaker diarisation, orchestrated through R and connected to SharePoint. Distributed across six analyst machines with privacy-by-design controls built in from the ground up.

#### The Result

~3,500 calls transcribed — speaker-labelled, timestamped, and delivered in the format investigators needed. Sensitive audio never left the team's infrastructure. The organisation's first locally-deployed, multi-model AI pipeline.

**Tools:** R · WhisperX · Pyannote · Reticulate · Shiny · SharePoint · Microsoft365R

---

<br>

### RStudio & GitHub Guide

*How do you uplift a team's analytical capability without a training budget?*

[<img src="00_Resources/rstudio_guide_image.jpg" alt="RStudio Guide image" height="200px">](https://github.com/DataDaneHQ/rstudio-guide)

[View Project →](https://github.com/DataDaneHQ/rstudio-guide)

#### The Problem

Analysts needed a practical, reliable reference for working with R and GitHub together — something they could use independently without needing to ask for help every time.

#### How It Was Solved

Built a comprehensive, self-service guide covering environment setup, GitHub integration, R Markdown, Quarto, and CSS styling — documented to production standard with working examples throughout.

#### The Result

A reusable, public resource that removes the dependency on tribal knowledge and lets analysts get productive faster — independently.

**Tools:** R · RStudio · GitHub · R Markdown · Quarto · CSS

---

<br>

### Salifort Motors — Employee Attrition Prediction

*Can you predict who's about to quit before they do?*

[<img src="00_Resources/salifort_motors_cover_image.jpg" alt="Salifort Motors" height="200px">](https://github.com/DataDaneHQ/Salifort_Motors_Attrition_Analysis/blob/main/README.md)

[View Project →](https://github.com/DataDaneHQ/Salifort_Motors_Attrition_Analysis/blob/main/README.md)

#### The Problem

Employee turnover is expensive and largely predictable — if you have the right model. Salifort Motors needed to identify attrition risk before it became a resignation letter.

#### How It Was Solved

Tested Decision Tree, Random Forest, and XGBoost models against workforce data. XGBoost emerged as the clear winner. Key drivers of attrition were isolated and translated into actionable HR recommendations.

#### The Result

96.7% AUC-ROC — a highly reliable early warning system for HR decision-making, with specific recommendations on workload, career development, and compensation gaps.

**Tools:** Python · XGBoost · Scikit-Learn · Seaborn · Jupyter Notebook