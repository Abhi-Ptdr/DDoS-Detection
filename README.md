# DDoS Detection System

## Project Overview
This project focuses on detecting Distributed Denial of Service (DDoS) attacks using advanced machine learning techniques. By leveraging the **CIC-DDoS2019** and **SDN-Dataset** datasets, it aims to create a robust and scalable intrusion detection system that ensures high accuracy and generalization capabilities.

### Features:
- Utilizes **two datasets** to cover modern and diverse attack scenarios:
  - **CIC-DDoS2019**: Specializes in DDoS attacks with over **12 million labeled records**.
  - **SDN-Dataset**: Ensures diversity by including other types of network intrusions.
- Achieves a detection accuracy of **98.7%** on DDoS attacks.
- Incorporates dimensionality reduction and feature engineering to optimize performance.
- Implements multiple machine learning models to evaluate and select the best-performing one.

## Technologies Used
- **Programming Languages**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Machine Learning Techniques**: Classification, Dimensionality Reduction (PCA), Hyperparameter Tuning
- **Datasets**: CIC-DDoS2019, NSL-KDD

## How to Clone and Run the Project

### Prerequisites
- Python (>=3.8)
- Required libraries:
  ```bash
  pip install pandas numpy scikit-learn matplotlib seaborn
  ```

### Steps to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Abhi-Ptdr/DDoS-Detection.git
   cd DDoS-Detection
   ```
2. Download the datasets:
   - [CIC-DDoS2019](https://www.unb.ca/cic/datasets/ddos-2019.html)
   - [NSL-KDD](https://www.unb.ca/cic/datasets/nsl.html)
   
   Place the datasets in the `data/` folder.

3. Run the data preprocessing script:
   ```bash
   python preprocess_data.py
   ```

4. Train the model:
   ```bash
   python train_model.py
   ```

5. Evaluate the model:
   ```bash
   python evaluate_model.py
   ```

6. Visualize results:
   - View the generated performance metrics and confusion matrix.

## Contribution
Feel free to fork this repository and contribute to its development by submitting pull requests. 

## Contact
- **Developer**: Abhishek Patidar  
- **Email**: abhipatidar253@gmail.com  
- **LinkedIn**: [Abhi Ptdr](https://www.linkedin.com/in/abhiptdr/)

## Acknowledgment
This work has been submitted as a **conference paper** to Springer Journal under the title:
"Empowering DDoS Resilience: Machine Learning Strategies for Enhanced Cybersecurity."
