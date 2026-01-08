<nav class="side-nav">

### Navigation
- [Current Focus](#current-focus-2025--present)
- [Professional Experience](#professional-experience)
- [Robotics & Autonomous Systems](#independent-robotics--autonomous-systems)
- [Education](#education)
- [Academic Projects](#academic-projects-iit-delhi)
- [Internships](#internships)
- [Certifications](#certifications--specialized-training)
- [Leadership](#leadership--activities)

</nav>

Senior AI / ML Engineer · Applied Machine Learning Systems · Robotics & Autonomy  
IIT Delhi — Mathematics & Computing

This page is a long-form, chronological archive of my work across industry, academics, and independent engineering initiatives.  
It is intentionally detailed and not a resume replacement.

---

## Current Focus (2025 – Present)

- **Senior AI / ML Engineer — TribolaTech India LLP**  
  Building production-grade AI/ML systems for document intelligence, PII detection, and natural language querying.

- **Independent Robotics Initiative — LocalRC Bros**  
  Founder-led robotics and autonomy work focused on RC platforms, perception, and PX4/ROS-based systems.  
  Website: [https://localrcbros.com](https://localrcbros.com)

---

## On this page
- [Professional Experience](#professional-experience)
- [Independent Robotics & Autonomous Systems](#independent-robotics--autonomous-systems)
- [Education](#education)
- [Academic Projects (IIT Delhi)](#academic-projects-iit-delhi)
- [Internships](#internships)
- [Certifications & Specialized Training](#certifications--specialized-training)
- [Leadership & Activities](#leadership--activities)

---

# Professional Experience

## Senior AI / ML Engineer  
TribolaTech India LLP, Bangalore (Remote) | Apr 2025 – Present

Focus: End-to-end AI/ML systems, document intelligence, LLM/VLM-based querying, and DevOps-driven deployments.

### Document Processing & Intelligence Platform
- Designed a scalable document processing pipeline combining OCR (Tesseract) with Vision-Language Models (SmolDocling).
- Extracted structured data from heterogeneous scanned documents including tables, forms, and mixed layouts.
- Implemented parallelized multi-page processing to significantly reduce end-to-end latency.

### Natural Language Query (NLQuery) Systems
- Built multiple generations of NLQuery systems:
  - Table-specific natural language to SQL querying
  - Fully generic LLaMA-based querying over arbitrary datasets
- Focused on prompt grounding, schema-awareness, and reducing hallucinations.
- Designed benchmarking frameworks to compare accuracy, latency, and scalability across variants.

### PII Detection & Computer Vision Pipelines
- Fine-tuned YOLO models on biometric datasets for sensitive information detection.
- Optimized inference pipelines for large document batches using parallel execution.

### ML DevOps & Infrastructure Automation
- Designed end-to-end CI/CD pipelines for ML training and inference.
- Automated containerization, testing, and deployment to AWS ECS using Terraform.
- Enabled fully isolated, client-specific deployments (infra + models + storage) in under 10 minutes.
- Integrated EFS-backed persistent storage and multi-service backend architecture.

---

## AI Integration Engineer  
Accenture Japan, Tokyo | Mar 2022 – Mar 2025

Focus: Applied ML, enterprise NLP, and GenAI integration into production systems.

### Retrieval-Augmented Generation (RAG) Platform
- Architected a cloud-deployable RAG system indexing 1GB+ of data from Jira, Confluence, and Slack.
- Integrated OCR-based image tagging for mixed-modal documents.
- Built Knowledge Graphs from Confluence data using Neo4j and NetworkX to re-rank retrieval results.
- Implemented RBAC, input sanitization, and post-processing to mitigate prompt injection and data leakage.

### Slack Message Clustering & Channel Prediction (PoC)
- Designed a clustering pipeline using OpenAI embeddings with Kernel PCA.
- Grouped messages into 20+ meaningful semantic clusters.
- Generated cluster tags using TF-IDF and NLTK.
- Automated channel name and description generation using LLM prompts.

### JIRA Issue Completion Prediction
- Built a stacking ensemble model using Decision Trees, Random Forests, and Logistic Regression.
- Performed extensive EDA and feature engineering.
- Applied PCA while retaining over 80% variance.
- Achieved mean absolute error of approximately 2.3 days.
- Packaged and deployed as a Dockerized service with metric tracking.

---

# Independent Robotics & Autonomous Systems

## LocalRC Bros — Independent Robotics Initiative  
May 2025 – Present  
Website: [https://localrcbros.com](https://localrcbros.com)

A long-term initiative to design, build, and document hands-on robotics, autonomy, and perception systems.

### Target Tracking Reaper (RC Plane)
- Designed and built a lightweight fixed-wing RC aircraft (~1.7 kg).
- Progressed from manual flight testing to Pixhawk-based autonomy.
- Implemented waypoint missions and groundwork for ground-target detection and tracking.

### AI Rover Explorer (RC Car)
- Built a 4WD rover with onboard camera, telemetry, and control stack.
- Implemented gesture-recognition based control.
- Conducted computer vision-based perception experiments.
- Integrated safety fallbacks and control overrides.

### Current Technical Focus
- PX4 SITL with Gazebo
- MAVLink / MAVSDK
- ROS2-based autonomy testbed
- Future direction: SLAM and onboard AI task coordination

---

# Education

## Indian Institute of Technology (IIT), Delhi  
**B.Tech in Mathematics & Computing** | 2017 – 2021

- Core focus areas: Machine Learning, Data Mining, Algorithms, Linear Algebra, Probability, Statistics
- Graduated with strong emphasis on applied ML and systems-level thinking

## Jawahar Navodaya Vidyalaya (JNV), Bundi, Rajasthan  
**Higher Secondary (CBSE Class XII)** | 2017  
- Scored 95%
- Strong academic performance in Mathematics and Sciences

## Jawahar Navodaya Vidyalaya (JNV), Munger, Bihar  
**Secondary School (CBSE Class X)** | 2015  
- Perfect 10/10 CGPA
- Consistently strong scholastic record

---

# Academic Projects (IIT Delhi)

### Microsoft Malware Prediction
- Performed EDA, feature engineering, and dimensionality reduction.
- Used K-Means and GMM clustering to generate additional features.
- Compared Decision Trees, Random Forests, Bayesian models, ANN, Bagging, and Boosting techniques.

### Handwritten Digit Recognition
- Implemented a neural network from scratch using backpropagation.
- Trained on the MNIST dataset.
- Achieved approximately 89% test accuracy.

### Emotion Recognition from Facial Expressions
- Designed a multi-layer CNN trained on the FER-2013 dataset.
- Implemented real-time emotion prediction using webcam input.

### Algorithms & Systems Projects
- Genome pattern searching using compressed suffix trees in C.
- Graph embedding study covering word2vec, LINE, and SDNE.
- Designed a 5-stage pipelined SimpleRISC processor.
- Built data-structure-heavy systems including a search engine and mobile phone tracking system.

Full academic archive:  
[https://github.com/vivekmuskan31/Academic-Projects](https://github.com/vivekmuskan31/Academic-Projects)

---

# Internships

## System Developer Intern  
VECROS Pvt. Ltd., Andhra Pradesh | Jun 2020 – Aug 2020

- Engineered live video streaming from drones to servers using Raspberry Pi and AWS Kinesis.
- Achieved sub-1-second end-to-end latency.
- Fine-tuned YOLOv3 for real-time object detection with ~20% accuracy improvement.
- Dockerized training and inference workflows.

## Cloud DevOps Intern  
Samsung R&D Institute, Delhi | May 2020 – Jun 2020

- Built boto3-based automation to identify and delete unused AWS resources.
- Managed dependencies across EC2, RDS, Load Balancers, and S3.
- Achieved measurable cloud cost reduction.

---

# Certifications & Specialized Training

## Essentials of Satellite Manufacturing  
**IN-SPACe (Indian National Space Promotion and Authorization Centre) — Department of Space, Government of India**  
In collaboration with **ISRO** | In-person, 1-week intensive program

- Covered satellite manufacturing fundamentals, subsystem integration, and industry-grade space engineering practices.
- Exposure to real-world satellite development workflows and India’s private space ecosystem.

## Cloud & AI Certifications
- Microsoft Certified: Azure AI Engineer Associate
- AWS Certified Developer Associate

---

# Leadership & Activities

## Aeromodelling Club, IIT Delhi

### Overall Coordinator | 2020 – 2021
- Led a 3-tier organization of 30+ members.
- Introduced structured project planning and faculty collaboration.
- Secured INR 2.5 lakh in research funding.

### Admin & Finance Coordinator | 2019 – 2020
- Managed finances for national-level events and competition travel.
- Audited expenses and reimbursements.

### Aviation Executive | 2018 – 2019
- Trained members in RC plane and drone piloting.
