# GSoC-2023
This repository contains the project proposal and my acceptance letter. More updates about the project will be provided as the coding period begins.

# Knowledge Graph aware Recommendation System with DBpedia (Abstract)
DBpedia proves to be a way of "Bringing Order to the Web" with structured information as Open Knowledge Graph, contributing towards making quality data more accessible.
The main goal of this project is to explore DBpedia's potential at enriching the data provided to Recommender Systems (RS) on different standard datasets, such as MovieLens and LastFM. A framework will be implemented for running reproducible experiments with only the model implementation and a simple .yaml configuration file.  Through the framework, this project allows practitioners to easily evaluate and compare their proposed RS algorithms with existing approaches, enabling future benchmarks on enriched and non-enriched datasets. With access to enriched standard RS datasets sourced primarily from DBpedia, this project aims to demonstrate DBpedia's applicability to RS area and other ML areas, potentially promoting DBpedia's adoption and increasing its active community. The main steps of the project are:
- **Entity Linking**: between DBpedia and standard RS datasets.
- **Data Enriching**: Build SPARQL queries to enrich RS datasets with useful DBpedia's properties.
- **Framework Implementation**: for reproducible experiments.
