PROJECT: Facial Expression Based Emotion Recognition
STUDENT: Charles Dan (2203030073)
DEPT: Computer Science, JABU

HOW TO RUN:
1. Open facial_expression_emotion_recognition.ipynb in Kaggle/Jupyter
2. Add FER2013 and RAF-DB datasets via Kaggle's "Add Data" panel
3. Run all cells sequentially
4. Final model saves to /kaggle/working/jabu_final_model.keras

MODEL FILES:
- jabu_final_model.keras (Full Keras model, 73.34% accuracy)
- jabu_model_float16.tflite (Mobile-optimized, 7.4ms, 135 FPS)

KEY RESULTS:
- Test Accuracy: 73.34% (73.68% with TTA)
- Best Validation: 73.66%
- Latency: 7.4 ms/frame (meets <30ms real-time target)
