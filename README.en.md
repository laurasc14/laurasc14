# Laura Solé Català

<p align="center">
  <strong>Data Engineer</strong> · Python · Spark · Kafka · SQL
</p>

<p align="center">
  <strong>🌐 Languages</strong><br />
  <a href="README.en.md"><img alt="Read in English" src="https://img.shields.io/badge/ENGLISH-0A66C2?style=for-the-badge" /></a>
  <a href="README.md"><img alt="Leer en español" src="https://img.shields.io/badge/ESPA%C3%91OL-2E8B57?style=for-the-badge" /></a>
</p>

<p align="center">
  <strong>✉️ Contact</strong><br />
  <a href="https://www.linkedin.com/in/laura-sol%C3%A9-catal%C3%A0-b7851083/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Profile-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:lsolecatala@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-lsolecatala@gmail.com-6C757D?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

## About me

Computer engineer with a master's degree in Big Data and Data Engineering. I build streaming pipelines that take data from the source all the way to a dashboard. I also work as a teacher: I enjoy sharing what I learn and learning from others.

## What I've built

- End-to-end streaming pipeline: Riot Games API → Kafka → Spark Structured Streaming → MongoDB → Streamlit
- Ingestion from an external, rate-limited API
- Reproducible deployment with Docker and Docker Compose

## Technologies

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" alt="Apache Kafka" />
  <img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" alt="Apache Spark" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
</p>

## Featured project

### [LoL RealTime Analytics](https://github.com/laurasc14/TFM-LoL-RealTime-Analytics)

Real-time analytics platform for League of Legends matches. Master's thesis at Universidad Complutense de Madrid (2025).

```mermaid
flowchart LR
    A[Riot Games API] --> B[Kafka]
    B --> C[Spark Structured Streaming]
    C --> D[(MongoDB)]
    D --> E[Streamlit Dashboard]
```

- **Throughput:** over 200 events per second in local tests
- **Average latency:** ~1.8 seconds end to end
- **Features:** summoner search, aggregated champion statistics and match history
- **Next step:** cloud deployment (GCP/AWS/Azure) to validate scalability

## Education

- **Master's Degree in Big Data and Data Engineering**: Universidad Complutense de Madrid, 2024–2025
- **Bachelor's Degree in Computer Engineering**: Universitat Oberta de Catalunya, 2020–2025
- **Master's Degree in Teacher Training**: UTAMED, in progress

---

<p align="center"><em>Data helps us understand the present; curiosity helps us imagine what comes next.</em></p>
