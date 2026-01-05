---
layout: page
title: Arxiv Ideate
description: Research navigation using semantic embeddings and clustering
img: assets/img/projects/arxiv-ideate.jpg
importance: 2
category:
---

## Overview

Research discovery tool for navigating academic papers, identifying gaps, and synthesizing ideas.

Uses semantic embeddings and clustering to map research landscapes.

## Problem

Researchers struggle to navigate large volumes of papers, identify research gaps, and synthesize connections across work. Traditional keyword search misses semantic relationships.

## Technical Approach

**Core System:**
- Sentence transformers for semantic embeddings
- Clustering algorithms for topic discovery
- Interactive visualization of research space

**Pipeline:**
1. Paper ingestion from arXiv
2. Semantic embedding generation
3. Clustering and relationship mapping
4. Gap identification through density analysis

**Features:**
- Semantic search (beyond keywords)
- Research gap detection
- Citation network analysis
- Topic clustering

## System Design

Built for researchers who need to:
- Understand a new research area quickly
- Find unexplored directions
- Synthesize across multiple papers

## Outcome

Functional tool demonstrating:
- Effective semantic search
- Research gap identification
- Practical application of embeddings
- User-focused design

## Technical Stack

- **ML Models:** Sentence transformers, BERT-based embeddings
- **Clustering:** HDBSCAN, UMAP for dimensionality reduction
- **Backend:** Python, FastAPI
- **Frontend:** Streamlit
- **Data:** arXiv API

---

*Focus: Information retrieval, semantic search, research tooling*
