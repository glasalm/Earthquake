# Earthquake Prediction using LSTM

This project leverages Long Short-Term Memory (LSTM) neural networks to predict earthquake magnitudes and times based on historical seismic data. The primary objective is to develop a model capable of providing insights into future earthquake occurrences by analyzing past patterns and characteristics of seismic activities.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Results](#results)

## Introduction

Predicting earthquakes is a challenging task due to the complexity and randomness of seismic events. This project aims to utilize LSTM neural networks, a type of recurrent neural network (RNN) particularly well-suited for time series data, to forecast the magnitude and time of future earthquakes. By training the model on historical earthquake data, we aim to identify patterns that could help in anticipating future seismic activities.

## Dataset

The dataset used in this project is sourced from seismic records of earthquakes in India from 2019 to 2021. The dataset includes several important features such as:
- **Latitude**: Geographical coordinate specifying the north-south position.
- **Longitude**: Geographical coordinate specifying the east-west position.
- **Depth**: Depth at which the earthquake occurred.
- **Origin Time**: The exact time when the earthquake occurred.
- **Magnitude**: The magnitude of the earthquake on the Richter scale.

## Project Structure
earthquake_prediction.py: The main script that preprocesses the data, builds, trains, and evaluates the LSTM models for earthquake prediction.

requirements.txt: A list of Python libraries required to run the project.

## Results 
Next predicted earthquake magnitude: 3.3

Next predicted earthquake time: 2021-05-15 05:29:44



