# IPL Score Prediction using Deep Learning

This project uses deep learning techniques to predict IPL match scores based on historical data and real-time match conditions. By analyzing factors like venue, teams, players, and match performance, the model provides accurate score predictions, enhancing cricket analytics.

## Tools & Technologies
- **Tools:** Jupyter Notebook / Google Colab
- **Technologies:** Deep Learning, TensorFlow, Keras
- **Libraries:** NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn

## Steps
1. **Import Libraries:** Load necessary libraries (TensorFlow, Keras, Pandas, etc.).
2. **Load Dataset:** IPL data from 2008-2017 including venue, teams, batsmen, bowlers, etc.
3. **Data Pre-processing:** Drop irrelevant columns, label encode categorical data, and split data into training/testing sets.
4. **Define Neural Network:** Use a simple neural network with ReLU activation.
5. **Train the Model:** Train for 50 epochs with training and validation data.
6. **Evaluate Model:** Predict and assess using metrics like Mean Absolute Error (MAE).
7. **Interactive Widget:** Create an interactive interface to predict scores using `ipywidgets`.

## Conclusion
Deep learning enhances cricket score predictions by analyzing complex data patterns, offering valuable insights for teams, analysts, and enthusiasts.
