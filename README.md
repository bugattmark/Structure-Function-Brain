# Structure-Function-Brain

tl;dr: I’m teaching a machine learning model to match a person’s brain structure (T1 MRI) with their brain activity over time (fMRI). T1 and fMRI scans from the same person get paired together in a very high dimensional mathematical space, while scans from different people stay apart, so we can one day predict cognitive or clinical traits using only a basic MRI.

Written paper in 

Next iteration:
- Scale up with a lot more data
- Adopt k‑fold cross‑validation
- Fix random seeds for full reproducibility
- Plot train/validation curves with error bars across runs
 
I’m excited to see how these changes will help us better characterize the true capabilities of my model, and hopefully unlock new shortcuts to brain‑based trait prediction.

What I’ve learned so far:
1. Rigorous ML debugging is non‑negotiable.
2. Simple models often outperform over‑engineered ones on small datasets.
3. Persistence pays off when training stubborn networks.
