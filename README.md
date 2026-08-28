# AI-Enhanced Blockchain-Based Secure Log Management

## Overview

This project develops a privacy-preserving security platform for real-time cyberattack detection and trustworthy log management. It combines artificial intelligence, federated learning, cryptographic evidence, and blockchain technology to make security logs more useful, verifiable, and resilient against tampering.

## Problem

Traditional log-management systems may expose sensitive data, rely on a central server, and make it difficult to prove whether a log or alert was changed after collection. Security teams also need faster ways to identify suspicious activity from large volumes of log data.

## Proposed Solution

The system collects logs from multiple sites, protects them with encryption and cryptographic hashes, and detects suspicious behaviour in real time. Each site can train the AI model locally, sharing model updates instead of raw logs. Important log-batch proofs and AI-alert evidence are anchored on blockchain for independent verification.

## Key Features

- Secure log collection, encryption, hashing, and tamper verification
- AI-based anomaly detection for suspicious cyber activity
- Federated learning that keeps raw logs at their original sites
- Explainable alerts that show why an event was considered suspicious
- Blockchain-backed, tamper-evident evidence for log batches and alerts
- Dashboard for monitoring alerts, verification results, and model status

## Technology Stack

- Python and FastAPI
- PostgreSQL and encrypted object storage
- Machine learning and federated learning
- Solidity with a local blockchain network
- React or Streamlit dashboard
- Docker for local deployment

## Project Status

Initial project setup in progress.
