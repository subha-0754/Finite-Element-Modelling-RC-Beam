# Finite Element Analysis of Reinforced Concrete Beam Under Four-Point Bending Using ABAQUS

## Overview

This project presents the finite element modelling and analysis of a Reinforced Concrete (RC) beam subjected to four-point bending using ABAQUS. The objective was to simulate the flexural behaviour of RC beams and evaluate their structural response under laboratory-representative loading conditions.

A detailed three-dimensional finite element model was developed incorporating concrete, longitudinal reinforcement bars, and stirrups with appropriate material properties, interaction constraints, and boundary conditions. The analysis was performed to investigate stress distribution, displacement response, crack initiation zones, and overall flexural performance.

## Objectives

* Develop a detailed 3D finite element model of an RC beam in ABAQUS.
* Simulate four-point bending test conditions.
* Evaluate flexural behaviour under static loading.
* Analyze stress and strain distribution within concrete and reinforcement.
* Study displacement and deformation characteristics.
* Compare numerical behaviour with expected structural response.

## Software Used

* ABAQUS/CAE
* ABAQUS Standard Solver

## Model Details

### Geometry

* Reinforced Concrete Beam
* Longitudinal Reinforcement Bars
* Shear Reinforcement (Stirrups)

### Material Properties

#### Concrete

* Elastic Properties
* Concrete Damaged Plasticity (CDP) Model

#### Steel Reinforcement

* Elastic-Plastic Material Behaviour
* Yield Strength and Elastic Modulus as per design specifications

### Interactions

* Embedded Region Constraint used to model bond behaviour between concrete and reinforcement.

### Boundary Conditions

* Simply Supported Beam Configuration
* Four-Point Loading Arrangement

## Methodology

1. Creation of beam geometry and reinforcement layout.
2. Assignment of material properties to concrete and steel.
3. Definition of embedded interaction between reinforcement and concrete.
4. Mesh generation using appropriate finite elements.
5. Application of supports and loading conditions.
6. Static analysis execution.
7. Post-processing of stress, strain, displacement, and damage results.

## Results Obtained

The simulation provided:

* Stress distribution within concrete and reinforcement.
* Beam deflection under applied loading.
* Tensile stress concentration in the flexural zone.
* Crack initiation and damage progression regions.
* Load transfer mechanism between concrete and reinforcement.
* Overall structural behaviour under four-point bending.

## Key Engineering Concepts Applied

* Finite Element Analysis (FEA)
* Reinforced Concrete Behaviour
* Flexural Response of RC Members
* Concrete Damaged Plasticity (CDP)
* Structural Modelling and Simulation
* Stress-Strain Analysis
* Numerical Structural Engineering

## Project Outcomes

The developed finite element model successfully replicated the expected flexural behaviour of reinforced concrete beams under four-point loading. The study demonstrated the effectiveness of ABAQUS in predicting structural response and provided a reliable framework for future investigations involving different loading conditions, reinforcement configurations, and material properties.

## Author

Subhalaxmi Baliarsingh,
B.Tech Civil Engineering,
National Institute of Technology, Rourkela

## Keywords

Finite Element Analysis, ABAQUS, Reinforced Concrete Beam, Four-Point Bending, Structural Analysis, Concrete Damaged Plasticity, RC Beam Modelling, Flexural Behaviour, Civil Engineering Simulation.
