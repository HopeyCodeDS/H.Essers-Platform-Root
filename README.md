# H.Essers - Automated Label Detection and Matching Platform

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/PaddleOCR-100000?style=for-the-badge&logo=paddlepaddle&logoColor=white" alt="PaddleOCR" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/React_Native-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React Native" />
  <img src="https://img.shields.io/badge/Azure-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white" alt="Azure" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
</p>

This is the orchestration and multi-service parent repository for the H.Essers Automated Label Detection and Matching system. It integrates the frontend, backend core API, and OCR microservice using Git Submodules.

## Architecture Overview

*   **`backend/`**: Core API handling business logic and request coordination ([Repository link](https://github.com/HopeyCodeDS/automated-label-detection-and-matching-backend))
*   **`ocr-service/`**: Python-based service responsible for computer vision and OCR processing ([Repository link](https://github.com/HopeyCodeDS/automated-label-detection-and-matching-OCRservice))
*   **`frontend/`**: User interface for managing and viewing label matches ([Repository link](https://github.com/HopeyCodeDS/automated-label-detection-and-matching-frontend))

---

## Getting Started

### 1. Cloning the Repository
Because this project utilizes Git submodules, you must clone it with the recursive flag:

```bash
git clone --recurse-submodules [https://github.com/HopeyCodeDS/H.Essers-Platform-Root.git](https://github.com/HopeyCodeDS/H.Essers-Platform-Root.git)
