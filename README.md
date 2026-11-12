# Laura Solé Català

<p align="center">
  <strongData Analyst</strong> · SQL · Python · Power BI · R · Spark · Kafka
</p>

<p align="center">
  <strong>🌐 Idiomas</strong><br />
  <a href="README.en.md"><img alt="Read in English" src="https://img.shields.io/badge/ENGLISH-0A66C2?style=for-the-badge" /></a>
  <a href="README.md"><img alt="Leer en español" src="https://img.shields.io/badge/ESPA%C3%91OL-2E8B57?style=for-the-badge" /></a>
</p>

<p align="center">
  <strong>✉️ Contacto</strong><br />
  <a href="https://www.linkedin.com/in/laura-sol%C3%A9-catal%C3%A0-b7851083/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Perfil-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:lsolecatala@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-lsolecatala@gmail.com-6C757D?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

## Sobre mí

Ingeniera informática con máster en Big Data y Data Engineering. Construyo pipelines de streaming que llevan datos desde la fuente hasta un dashboard. También trabajo como docente, así que documento y explico lo que construyo para que otra persona pueda mantenerlo.

## Qué he construido

- Pipeline de streaming de extremo a extremo: Riot Games API → Kafka → Spark Structured Streaming → MongoDB → Streamlit
- Ingesta desde una API externa con límites de peticiones
- Despliegue reproducible con Docker y Docker Compose

## Tecnologías

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" alt="Apache Kafka" />
  <img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" alt="Apache Spark" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
</p>

## Proyecto destacado

### [LoL RealTime Analytics](https://github.com/laurasc14/TFM-LoL-RealTime-Analytics)

Plataforma de analítica en tiempo real sobre partidas de League of Legends. Trabajo de Fin de Máster en la Universidad Complutense de Madrid (2025).

```mermaid
flowchart LR
    A[Riot Games API] --> B[Kafka]
    B --> C[Spark Structured Streaming]
    C --> D[(MongoDB)]
    D --> E[Streamlit Dashboard]
```

- **Throughput:** más de 200 eventos por segundo en pruebas locales
- **Latencia media:** ~1,8 segundos de extremo a extremo
- **Funcionalidades:** búsqueda de invocadores, estadísticas agregadas de campeones e historial de partidas
- **Siguiente paso:** despliegue en la nube (GCP/AWS/Azure) para validar la escalabilidad

## Formación

- **Máster en Big Data y Data Engineering**: Universidad Complutense de Madrid, 2024–2025
- **Grado en Ingeniería Informática**: Universitat Oberta de Catalunya, 2020–2025
- **Máster de Formación del Profesorado**: UTAMED, en curso

---

<p align="center"><em>Los datos nos ayudan a entender el presente; la curiosidad, a imaginar lo que viene.</em></p>
