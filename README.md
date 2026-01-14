# reaction-yield-optimizer
Machine Learning for reaction yield prediction and Bayesian optimization in data-scarce environments.
# Reaction Yield Prediction with Bayesian Optimization

This repository demonstrates an **Active Learning** approach to chemical 
synthesis, specifically addressing the challenges of **Low-Data regimes** in organic chemistry.

### Why this matters for the Glorius Group:
In synthetic methodology, experimental data is expensive. Instead of 
Random Forest alone, this project uses a **Bayesian Acquisition strategy** to suggest the "next best experiment," minimizing the number of 
failed reactions needed to find optimal conditions.

### Technical Approach:
- **Model:** Random Forest Regressor (Surrogate Model).
- **Strategy:** Exploitation-focused selection of unobserved chemical space.
- **Dataset:** Modeled after the Doyle Buchwald-Hartwig amination data.

### Future Integration:
Ready for integration with automated liquid handlers (e.g., Opentrons) 
to create a closed-loop "Self-Driving Lab" system.
