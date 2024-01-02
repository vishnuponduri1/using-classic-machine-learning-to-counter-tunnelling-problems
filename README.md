# using-classic-machine-learning-to-counter-tunnelling-problems
# ## Tunnel Overbreak Analysis

**Objective:** Identify and minimize overbreak in tunneling caused by drilling and blasting.

**Approach:**
- Analyze a live site (RVNL Package 2, Rishikesh) for overbreak causes.
- Develop a predictive model using Rock Engineering Solution (RES) with blast parameters, geology, and area inputs.
- Validate the model with site data not used during model creation.
- Implement control blasting techniques (smooth blasting, pre-splitting) on problematic blasts to observe overbreak reduction.
## Results

1. Overbreak index developed using RES.
2. Average overbreak index: 42.70 for all blasts across 4 tunnels.
3. Overbreak model validated with a high confidence level (R2 = 0.85).
4. Identified and optimized parameters for 4 cases with the highest overbreak index.
5. Application of smooth blasting and pre-splitting reduced overbreak by 4% and 13%, respectively.
6. Altered delay time for 3 blasts, resulting in reduced overbreak.
7. Overbreak variation observed with advancement and confinement factors.

**Equations:**
- Overbreak Index Model: Overbreak = 3.8507 + 0.1187(OI)
- Overbreak Variation Models: 
  - OB = 0.54(Cf/Q) + 5.80; R2 = 0.81
  - OB = 5.22ln(qp/Af) + 7.57; R2 = 0.73

## Inferences
1. Average overbreak index indicates a medium to high risk.
2. Rock Quality Index significantly influences overbreak, even with best practices.
3. Proper treatment crucial for preventing overbreak, even in better rock conditions.
4. Blasting practices align well with geology in the sensitive region.
5. Pre-splitting more effective than smooth blasting in overbreak reduction.

**Conclusions:**
- Overbreak damage charts prepared for each rock class.
- Proposed overbreak model considers geological factors.
- Developed model (using Levenberg–Marquardt algorithm) distinguishes technical and geological overbreak.
- Technical overbreak depends on blast hole length; geological overbreak depends on RMR.
- Cycle time reduction achieved for all rock classes, with the greatest impact in rock class B2.
- Activities like mucking, chipping, and rock support installation contribute to cycle time reduction.


