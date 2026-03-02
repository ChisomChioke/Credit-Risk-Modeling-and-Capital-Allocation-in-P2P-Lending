# Credit-Risk-Modeling-and-Capital-Allocation-in-P2P-Lending

## Project Background

Peer-to-peer lending platforms deploy over $150 billion globally but struggle with a fundamental trade-off: expanding loan origination while controlling credit risk. Unlike traditional banks, P2P platforms operate under explicit capital constraints, making efficient capital deployment as critical as accurate default prediction.

This project analyzes ~410,000 historical consumer loans (2009–2024) to develop a machine-learning–driven credit risk framework that goes beyond classification accuracy and directly optimizes portfolio-level financial outcomes. The analysis demonstrates how predictive models can be translated into expected returns, capital allocation decisions, and realized profitability under realistic business constraints.

The project is designed to mirror how credit models are evaluated and deployed in professional lending environments: beginning with interpretable baselines, progressing to advanced ensemble models, and ultimately embedding predictions into decision strategies that maximize return on capital.

## Objectives

The analysis addresses three core business questions:

**1. Prediction:** Can machine learning models meaningfully improve default prediction over interpretable baselines?

**2. Decision-making:** How should predicted default probabilities be translated into loan approval decisions?

**3. Capital allocation:** Given limited capital, which deployment strategies maximize portfolio-level returns?

## Executive Summary

![Capital Allocation Efficiency Frontier](images/capital_allocation_efficiency.png)
_Under binding capital constraints, ranking loans by expected value per euro invested consistently dominates both fixed probability thresholds and absolute expected value selection across all tested budget levels (€25M–€100M)._
