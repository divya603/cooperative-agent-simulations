# Cooperative Agent Simulations
This project models real-time helping behavior in simulated agent populations. The study builds on empirical data from a multi-agent experimental setup and constructs a diverse population of simulated agents that mimic human cooperative behaviors.

---

## Project Highlights
- **Dataset**: Includes 58,882 turn-level observations of human participants in a simulated environment.
- **Agent Behavior Modeling**:
  - Developed logistic regression models to capture the probability of helping behavior.
  - Incorporated parameters for reciprocity and environmental factors such as resource availability and costs.
- **Simulated Population**:
  - Generated 10,000 agent pairs with diverse predispositions to cooperation.
  - Demonstrated variations in cooperative behavior based on environmental contexts.

---

## Key Features
- **Feature Engineering**: Extracted and pruned relevant features such as partner helping history and spatial proximity to resources.
- **Agent Parameter Distribution**:
  - Modeled diverse helping tendencies using parameterized logistic regression.
  - Generated agents with individualized tendencies to mimic human decision-making.
- **Analysis**:
  - Evaluated simulated behavior against human data.
  - Demonstrated how environmental contexts influence cooperative strategies.

---

## Repository Structure
```plaintext
cooperative-agent-simulations/
├── report.pdf             # Detailed project report
├── README.md              # Project overview
└── figures/               # Figures used in the report
    ├── all_features_corr_mat.png
    ├── pruned_features_corr_mat.png
    ├── global_log_reg_pred_vs_act.png
    └── ... (other figures)

