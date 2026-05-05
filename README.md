# DehazingEcho2025-Challenge

The first benchmark and grand challenge for reverberation-induced near-field haze suppression in transthoracic echocardiography. Organized by Fudan University and VINNO Technology (Suzhou), in conjunction with MICCAI 2025.

## Overview

The DehazingEcho 2025 Grand Challenge focuses on clinically meaningful haze suppression in transthoracic echocardiography (TTE), particularly targeting reverberation-induced near-field haze artifacts. The challenge provides a dedicated benchmark for evaluating echocardiographic dehazing methods from multiple perspectives, including haze removal, anatomical structure preservation, and downstream clinical utility.

This repository will host the public resources associated with the DehazingEcho 2025 Grand Challenge, including the EchoHaze dataset and the technical reports submitted by participating teams.

## Data and Citation

The EchoHaze dataset will be publicly released for research use. If you use the dataset, challenge results, or any related resources from this repository, please cite the DehazingEcho 2025 challenge paper.

The citation information will be updated here once the paper is officially published.

## Technical Reports

We publicly release the technical reports submitted by the participating teams. These reports describe the methods, model designs, training strategies, and implementation details used in the challenge.

Please refer to the [`technical_reports`](./technical_reports) directory for the available team reports.

## Challenge Results

The DehazingEcho 2025 Grand Challenge attracted multiple participating teams. The top-10 teams are listed below.

| Rank | Team Name | Members | Affiliation |
|---|---|---|---|
| 1 | T1: CcYou2z | Zike Luo; Lei Li | Zhejiang University; National University of Singapore |
| 2 | T2: marc_fehlaber_tum | Marc Fehlhaber; Lara Lanz; Leo Eckert; Selim Mert Kastan; Shahrooz Faghihroohi | Technical University of Munich |
| 3 | T3: MaKaNu | Dominik Fromme; Matti Kaupenjohann; Tim Streckert; Jörg Thiem | University of Applied Sciences and Arts Dortmund |
| 4 | T4: SKJP | Satoshi Kondo; Satoshi Kasai | Muroran Institute of Technology; Fujita Health University |
| 5 | T5: twstevens | Arthur Lefebvre; Charles Sillett; Steven Niderer | Eindhoven University of Technology |
| 6 | T6: al224 | Arthur Lefebvre; Charles Sillett; Steven Niderer | Imperial College London; UKRI AI Centre for Doctoral Training in Digital Healthcare |
| 7 | T7: Damon_Liu | Junfeng Liu; Qi Wang; Rongan He; Jun Shi | Shanghai University |
| 8 | T8: izhuyanrun | Yanrun Zhu; Ao Yang; Ning Huang | Shanghai University |
| 9 | T9: aawasthi | Pushpendra Singh; Navchetan Awasthi | King’s College London |
| 10 | T10: Sanyam Makvana | Sanyam Makvana | Sarvajanik College of Engineering and Technology |

## Repository Structure

```text
DehazingEcho2025-Challenge/
├── EchoHaze_dataset/       # Dataset release information and usage instructions
├── technical_reports/      # Technical reports from participating teams
└── README.md               # Project overview
