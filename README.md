# H.Essers - Automated Label Detection and Matching Platform

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
