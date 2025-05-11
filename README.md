Set up your CSV files: make sure all required data files (e.g., BTC-USD.csv, LTC-USD.csv) are prepared and placed in the correct directory.

Verify all file paths: double-check every path in the code to avoid errors due to incorrect locations.

Install all required dependencies: run pip install pandas numpy scikit-learn tensorflow to get everything needed.

Optional – set up TensorBoard: if you want to visualize training (loss, accuracy, etc.), install it with pip install tensorboard then start it using tensorboard --logdir=logs/.

TensorBoard compatibility: if you're using an older TensorFlow version, you might need to downgrade Python (e.g., to 3.10) for it to work correctly.

Consider increasing the number of epochs: more training epochs can improve prediction results but will use more computing resources and may cause overfitting if unchecked.

Trained models are saved in the models/ folder, and logs for TensorBoard are saved in the logs/ folder.
