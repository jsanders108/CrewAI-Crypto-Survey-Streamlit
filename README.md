# CrewAI Survey Analysis on Railway

This repository contains the **Survey Analysis with CrewAI** project, deployed on **Railway** with a **Streamlit** user interface and a **FastAPI** backend. The project enables users to upload survey data in CSV format and run CrewAI-based analysis in the cloud.

## 🚀 Project Overview

This project migrates the **CrewAI** survey analysis pipeline to Railway, making it accessible via a **web-based Streamlit UI**. The system is built with:

- **Streamlit**: Provides a user-friendly interface for CSV upload and results visualization.
- **FastAPI**: Handles the processing of survey data and calls CrewAI for analysis.
- **CrewAI**: Orchestrates the survey analysis process.
- **Railway**: Cloud platform used for deployment.

## 🎯 Features

✅ Upload survey data in CSV format  
✅ View a preview of the uploaded data  
✅ Process survey data using CrewAI with a single click  
✅ Receive analysis results in real-time  

## 🔧 Deployment Details

The system is split into **two repositories**: one for the Streamlit frontend and one for the FastAPI backend.

- The **Streamlit app** serves as the user interface.
- The **FastAPI backend** receives data, processes it with CrewAI, and returns the results.

Both services are deployed on **Railway**, with public networking enabled.

