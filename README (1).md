
# **Stock Market Prediction Using Temporal Convolutional Networks (TCN)**

This project applies **Temporal Convolutional Networks (TCNs)** to predict stock market prices and trends. TCNs are highly efficient for time-series forecasting due to their ability to capture both short- and long-term dependencies, outperforming traditional models like ARIMA and RNNs.

---

## **Features**
- **Data Preprocessing**: Collect, clean, and normalize stock market data.
- **Feature Engineering**: Includes technical indicators (e.g., RSI, MACD, moving averages) and lagged features.
- **TCN Implementation**: Causal convolutions, dilations, and residual connections using TensorFlow/Keras.
- **Evaluation Metrics**: Measures performance with MAE, RMSE, and visualizes predictions vs. actual data.
- **Customizable Framework**: Easily adjustable hyperparameters for different datasets and use cases.

---

## **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Stock-Market-TCN.git
   cd Stock-Market-TCN
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## **Usage**
1. **Prepare Data**: Place stock data in the `data/` folder and preprocess it.
2. **Train Model**:
   ```bash
   python main.py
   ```
3. **Evaluate Model**:
   ```bash
   python main.py --evaluate
   ```
4. **Visualize Predictions**: The script will generate plots for actual vs. predicted prices.

---

## **Project Structure**
```
📂 Stock-Market-TCN
├── 📁 data/                # Raw and preprocessed data
├── 📁 notebooks/           # Jupyter notebooks for exploration
├── 📁 models/              # Saved TCN models
├── 📄 main.py              # Training and evaluation script
├── 📄 utils.py             # Helper functions
├── 📄 requirements.txt     # Required Python packages
├── 📄 README.md            # Project description
```

---

## **Results**
The TCN effectively predicts stock market trends, capturing both short-term patterns and long-term dependencies. Visualization of predictions shows strong alignment with actual values.

---

## **Future Work**
- Integrate external data sources (e.g., news sentiment, macroeconomic indicators).
- Experiment with hybrid models (e.g., TCN + Attention mechanisms).
- Adapt the framework for high-frequency trading data.

---

## **License**
This project is licensed under the MIT License. See the `LICENSE` file for details.

---
