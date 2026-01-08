# Vivek Muskan

Senior AI / ML Engineer · Applied Machine Learning Systems · Robotics & Perception  
IIT Delhi — Mathematics & Computing

This page is a long-form archive of my technical work across academics, industry, and personal projects.
It is intentionally detailed and not a resume replacement.

---

# Professional Experience

## Senior AI / ML Engineer  
TribolaTech India LLP, Bangalore (Remote) | Apr 2025 – Present

Focus: End-to-end AI/ML systems, document intelligence, PII detection, LLM/VLM-based querying, and DevOps-heavy deployments.

### Scalable Document Processing & Intelligence Platform
- Designed a full document processing pipeline combining OCR (Tesseract) with Vision-Language Models (SmolDocling).
- Extracted structured data from heterogeneous scanned documents (tables, forms, mixed layouts).
- Handled multi-page parallel processing to significantly reduce end-to-end latency.

Tech: Python, FastAPI, Tesseract, SmolDocling, AWS

### Natural Language Query (NLQuery) Systems
- Built multiple generations of NLQuery systems:
  - Table-specific NL → SQL querying
  - Fully generic LLaMA-based querying over arbitrary datasets
- Designed prompt grounding and schema-awareness to reduce hallucinations.
- Benchmarked accuracy, latency, and scalability across variants to guide production trade-offs.

Tech: LLaMA, SQL, Python, AWS Bedrock

### PII Detection & Computer Vision Pipelines
- Fine-tuned YOLO models on biometric datasets for sensitive information detection.
- Implemented parallelized inference for multi-page documents.
- Improved throughput and consistency for large document batches.

Tech: YOLO, OpenCV, Python

### ML DevOps & Infrastructure Automation
- Designed end-to-end CI/CD pipelines for ML training and inference.
- Automated containerization, testing, and deployment to AWS ECS using Terraform.
- Enabled client-isolated deployments (models + infra + storage) in under 10 minutes.
- Integrated EFS-backed persistent storage and multi-service backend architecture.

Tech: Docker, Terraform, AWS ECS, EFS, Git

---

## AI Integration Engineer  
Accenture Japan, Tokyo | Mar 2022 – Mar 2025

Focus: Applied ML, enterprise NLP, and GenAI integration into production systems.

### Retrieval-Augmented Generation (RAG) Platform
- Architected a cloud-deployable RAG system indexing 1GB+ of data from Jira, Confluence, and Slack.
- Integrated OCR-based image tagging for mixed-modal documents.
- Built Knowledge Graphs from Confluence data using Neo4j and NetworkX.
- Re-ranked RAG search results using graph proximity and semantic similarity.
- Implemented security layers including RBAC, input sanitization, and post-processing to mitigate prompt injection.

Tech: FastAPI, Docker, Azure, Vector DB, Neo4j, LangChain

### Slack Message Clustering & Channel Prediction (PoC)
- Designed a clustering pipeline using OpenAI embeddings with Kernel PCA.
- Grouped messages into 20+ meaningful semantic clusters.
- Generated cluster tags using TF-IDF and NLTK.
- Automated channel name and description generation via LLM prompts.

Tech: OpenAI embeddings, Python, NLTK, Scikit-learn

### JIRA Issue Completion Prediction
- Built a stacking ensemble model combining Decision Trees, Random Forests, and Logistic Regression.
- Performed EDA to identify high-impact features such as story points and issue types.
- Applied PCA to retain 80%+ variance.
- Achieved mean absolute error of approximately 2.3 days.
- Packaged and deployed as a Dockerized service with metric tracking.

Tech: Scikit-learn, Docker, Azure

---

# Education

## B.Tech in Mathematics & Computing  
Indian Institute of Technology (IIT), Delhi | 2017 – 2021

### Machine Learning & Data Mining Projects

#### Microsoft Malware Prediction
- Performed EDA, feature engineering, and dimensionality reduction.
- Used K-Means and GMM clustering to generate additional features.
- Compared Decision Trees, Random Forests, Bayesian models, ANN, Bagging, and Boosting.

#### Handwritten Digit Recognition
- Implemented a neural network from scratch using backpropagation.
- Trained on MNIST dataset.
- Achieved approximately 89% test accuracy.

#### Emotion Recognition from Facial Expressions
- Designed a multi-layer CNN trained on FER-2013 dataset.
- Implemented real-time emotion prediction using webcam input.

### Algorithms, Systems & Theory Projects

#### Pattern Searching in Genome Sequences
- Implemented compressed suffix trees in C.
- Enabled fast pattern and common subsequence search.

#### Graph Embedding Study
- Studied word2vec, LINE, and SDNE approaches.
- Analyzed first- and second-order proximity preservation.

#### Computer Architecture
- Designed a 5-stage pipelined SimpleRISC processor.

#### Data Structures Projects
- Publish–subscribe platform using graphs and hash maps.
- Search engine using AVL trees.
- Mobile phone tracking system using hierarchical data structures.

Full academic archive:
https://github.com/vivekmuskan31/Academic-Projects

---

# Internships

## System Developer Intern  
VECROS Pvt. Ltd., Andhra Pradesh | Jun 2020 – Aug 2020

- Engineered live video streaming from drones to server using Raspberry Pi and AWS Kinesis.
- Achieved sub-1-second end-to-end latency.
- Fine-tuned YOLOv3 for real-time object detection with ~20% accuracy improvement.
- Dockerized training and inference workflows.

## Cloud DevOps Intern  
Samsung R&D Institute, Delhi | May 2020 – Jun 2020

- Built boto3-based automation to identify and delete unused AWS resources.
- Managed dependencies across EC2, RDS, Load Balancers, and S3.
- Achieved measurable cloud cost reduction.

---

# Personal Projects & Robotics

## LocalRC Bros | May 2025 – Present
https://localrcbros.com

A long-term initiative to document hands-on robotics, autonomy, and perception projects.

### Target Tracking Reaper (RC Plane)
- Built a lightweight fixed-wing RC aircraft (~1.7 kg).
- Progressed from manual flight testing to Pixhawk-based autonomy.
- Implemented waypoint missions and groundwork for ground-target detection.

### AI Rover Explorer (RC Car)
- Built a 4WD rover with onboard camera and telemetry.
- Implemented gesture-recognition based control.
- Conducted computer vision-based perception experiments.
- Integrated safety fallbacks and control overrides.

### Current Focus
- PX4 SITL with Gazebo
- MAVLink / MAVSDK
- ROS2-based autonomy testbed
- Future direction: SLAM and onboard AI task coordination

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

---

# Skills

Programming: Python, Java, C++, C, JavaScript, MATLAB  
AI / ML: Scikit-learn, Keras, Transformers, Hugging Face, OpenCV, NLTK, LLaMA  
Cloud & DevOps: AWS, Azure, Docker, Terraform, Git, Linux  
Databases & Infra: Postgres, Neo4j, Vector DBs, Splunk  
Robotics: ROS, Gazebo, PX4, MAVSDK, URDF, RViz
