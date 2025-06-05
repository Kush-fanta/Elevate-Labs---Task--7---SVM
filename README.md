# Elevate-Labs---Task--7---SVM
## Steps Performed

### 1. Load and Prepare the Dataset
- Loaded CSV file.
- Dropped the `index` column.
- Selected two features (`age` and `chol`) for 2D visualization.
- Scaled the features using `StandardScaler`.
- Split into train and test sets.

### 2. Train SVM Models
- Trained SVM with **linear kernel**.
- Trained SVM with **RBF kernel**.

### 3. Visualize Decision Boundary
- Used a custom `plot_decision_boundary` function.
- Visualized both linear and RBF kernel decision boundaries in 2D.

### 4. Hyperparameter Tuning
- Used `GridSearchCV` to find optimal values for:
  - `C` (Regularization)
  - `gamma` (for RBF kernel)

### 5. Cross-Validation Evaluation
- Used 5-fold cross-validation.
- Reported mean accuracy score.
