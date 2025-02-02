
### **1. Data Preprocessing**
- **Feature Engineering**: Raw data ko features mein convert karna jo model ke liye useful ho.  
   - **Approach**: Machine Learning, Deep Learning
- **Feature Selection**: Relevant aur important features ko select karna.  
   - **Approach**: Machine Learning, Deep Learning
- **Data Augmentation**: Training data ko artificially increase karna (e.g., images ke liye rotation, flip).  
   - **Approach**: Deep Learning (especially in computer vision)

### **2. Model Training**
- **Training, Validation, and Test Split**: Data ko training, validation, aur testing sets mein divide karna.  
   - **Approach**: ML, Deep Learning
- **Epoch**: Neural network training ke iterations. Ek epoch mein pura dataset ek bar model ke through pass hota hai.  
   - **Approach**: Deep Learning
- **Batch Size**: Data ke kis hisse ko model ek time pe process karta hai.  
   - **Approach**: Deep Learning

### **3. Optimization**
- **Gradient Descent**: Optimization technique jo weights ko adjust karne ke liye use hoti hai.  
   - **Approach**: ML, Deep Learning
- **Learning Rate**: Step size jo gradient descent ke dauran use hota hai.  
   - **Approach**: ML, Deep Learning
- **Overfitting**: Model training data pe excessively fit ho jata hai aur generalization ka loss hota hai.  
   - **Approach**: ML, Deep Learning
- **Underfitting**: Model training data ko achhe se capture nahi kar pata.  
   - **Approach**: ML, Deep Learning
- **Hyperparameter Tuning**: Model ke hyperparameters (e.g., learning rate, layers) ko optimize karna.  
   - **Approach**: ML, Deep Learning

### **4. Evaluation Metrics**
- **Loss Function**: Model ki performance ko evaluate karne ke liye function.  
   - **Approach**: ML, Deep Learning
- **Precision**: Correct positive predictions ka proportion.  
   - **Approach**: Classification (ML, Deep Learning)
- **Recall**: True positives ko detect karne ka ability.  
   - **Approach**: Classification (ML, Deep Learning)
- **F1-Score**: Precision aur recall ka harmonic mean.  
   - **Approach**: Classification (ML, Deep Learning)
- **Cross-Validation**: Model ki performance ko robustly evaluate karne ke liye multiple subsets mein train karna.  
   - **Approach**: ML

### **5. Advanced Learning Approaches**
- **Transfer Learning**: Pre-trained models ko use kar ke new task pe fine-tune karna.  
   - **Approach**: Deep Learning (especially computer vision, NLP)
- **Model Ensemble**: Multiple models ka combination, jaise Bagging aur Boosting.  
   - **Approach**: ML, Deep Learning (Ensemble models like Random Forest, XGBoost)
 - **Hyperparameters vs. Parameters:** 
     - Hyperparameters: 
         - User-defined settings (jaise learning rate, epochs).
      - Parameters: 
          - Model ke khud seekhay hue weights.

- **Data Leakage**: Jab test data ka kuch hissa training mein chala jaye (ghalti se), jis se results fake lagte hain.**

### **6. Reinforcement Learning (RL)**
- **Reinforcement Learning**: Agent ko environment ke sath interact karna sikhana, taake wo rewards maximize kar sake.  
   - **Approach**: Reinforcement Learning
- **Q-Learning**: Reinforcement learning mein ek popular algorithm, jo optimal policy seekhta hai.  
   - **Approach**: Reinforcement Learning
- **Markov Decision Process (MDP)**: Decision-making process jo uncertain environments mein decisions ko model karta hai.  
   - **Approach**: Reinforcement Learning
- **Exploration vs Exploitation**: Exploration ka matlab nayi cheezon ko try karna, aur exploitation ka matlab known solutions ka fayda uthana.  
   - **Approach**: Reinforcement Learning

### **7. Bias and Variance**
- **Bias**: Model ka assumption jo error introduce karta hai. High bias means underfitting.  
   - **Approach**: ML, Deep Learning
- **Variance**: Model ki sensitivity to training data. High variance means overfitting.  
   - **Approach**: ML, Deep Learning

---

### **Sequence of Use** (Approach-wise):

1. **Machine Learning**:
   - **Data Preprocessing**: Feature Engineering, Feature Selection.
   - **Model Training**: Training-Test Split, Cross-Validation.
   - **Evaluation**: Precision, Recall, F1-Score.
   - **Optimization**: Gradient Descent, Hyperparameter Tuning, Bias-Variance.
   - **Advanced**: Hyperparameter Tuning, Ensemble Learning, Model Evaluation.

2. **Deep Learning**:
   - **Data Preprocessing**: Feature Engineering, Data Augmentation.
   - **Model Training**: Epoch, Batch Size.
   - **Optimization**: Gradient Descent, Learning Rate, Overfitting, Underfitting.
   - **Evaluation**: Loss Function, Precision, Recall, F1-Score.
   - **Advanced**: Transfer Learning, Ensemble Learning.

3. **Reinforcement Learning**:
   - **Exploration vs Exploitation**: Decision-making in unknown environments.
   - **Q-Learning**: Specific method for value function optimization.
   - **Markov Decision Process (MDP)**: Model of states, actions, and rewards.
   - **Reinforcement Learning**: Overall framework to maximize rewards in dynamic environments.

---