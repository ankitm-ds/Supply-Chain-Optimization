# Sustainable Supply Chain Optimization

## Introduction

DHL Supply Chain, a division of Deutsche Post DHL, acknowledges environmental responsibility as both a duty and a business opportunity. The company aims to improve carbon efficiency across its global operations by 30% compared to a 2007 baseline. The project aligns with DHL's commitment to sustainability and innovation in the logistics industry.

This project revolves around optimizing the supply chain for a consumer electronics company (CEC) dealing with LCD TV sets. The objective is to meet production and shipping requirements while considering budget constraints and minimizing CO2 emissions.

## Problem Statement

The logistics and transport sector contributes significantly to greenhouse gas emissions, prompting the need for sustainable practices. DHL Supply Chain aims to address this challenge by optimizing the supply chain for a CEC, focusing on reducing CO2 emissions while fulfilling production and shipping requirements within budgetary constraints.

## Approach

The project utilizes linear Programming optimization techniques to configure an optimal supply chain for the CEC's LCD TV sets. 
Key considerations include:
- Identifying original design manufacturers (ODMs) for production.
- Selecting transportation modes based on cost and carbon emissions.
- Meeting production and shipping requirements while adhering to budget constraints.

## Implementation

The project utilizes Python and the following libraries:

- pandas: For data manipulation and analysis.
- pulp: For linear programming optimization.
- numpy: For numerical computations.

The optimization algorithm considers various constraints such as production capacities, shipping times, and customer order cycle times to generate an optimal solution.

## Usage

To reproduce the results:

1. Clone the repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the main script to execute the optimization algorithm.
4. View the results and analysis to understand the optimized supply chain configuration.

## Results

With a given budget of CNY 4 billion, the simulation exercise suggests:

- Manufacturing LCD 42" in ODM3, ODM4, ODM5, ODM6, and ODM7.
- Manufacturing LCD 32" in ODM1 and ODM2.
- Shipping mostly via water to minimize CO2 emissions.

The optimized solution reduces CO2 emissions to 3416.50 metric tons (3416507.16 kg).

Integrating environmental considerations into supply chain management promotes sustainability. Companies like DHL Supply Chain can mitigate carbon emissions while achieving operational efficiency and cost-effectiveness.
