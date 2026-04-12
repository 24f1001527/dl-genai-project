## 📁 Repository Workflow

This project follows a structured Git workflow to ensure reproducibility, clear milestone tracking, and adherence to good software engineering practices.

###  Branching Strategy
The repository is organized using:
- `main` branch → contains the final and most stable version of the project  
- `milestone-*` branches → used for milestone-specific development  

All work for each milestone was completed in its respective branch (e.g., `milestone-1`, `milestone-2`, `milestone-3`) and later merged into the `main` branch. Milestone branches are retained for evaluation and progress tracking.

---

###  Workflow Followed
- Each milestone was developed using Jupyter notebooks  
- Experiments (EDA, preprocessing, modeling) were conducted within notebooks  
- Changes were committed regularly with meaningful messages  
- After completion, milestone branches were merged into `main`  

---

###  Repository Structure
The repository is notebook-driven, where each notebook represents a stage of the project:
- EDA and preprocessing  
- Feature engineering  
- Model training and evaluation  
- Final pipeline  

Additional files include:
- Trained model files (`.pth`)  
- Final report  
- `requirements.txt` for reproducibility  

---

###  Best Practices Followed
- Milestone-wise development using separate branches  
- Reproducible notebooks with end-to-end pipelines  
- Clear and meaningful commit history  
- Version-controlled experiments  

---

###  Reproducibility
All dependencies required to run the project are listed in `requirements.txt`. The project can be reproduced by installing the dependencies and executing the notebooks sequentially.

---

This workflow ensures transparency, reproducibility, and alignment with industry-standard development practices.
