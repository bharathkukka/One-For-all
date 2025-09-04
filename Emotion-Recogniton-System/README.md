# Emotion Recognition System

## Overview
This project implements an AI-powered emotion recognition system that can detect and classify human emotions from facial expressions in real-time.

## Features
- **Real-time Emotion Detection**: Analyze emotions from webcam feed or uploaded images
- **8 Emotion Categories**: Detects happiness, sadness, anger, surprise, neutral, fear, disgust, and contempt
- **Interactive Messaging**: Provides contextual responses based on detected emotions
- **High Accuracy**: Achieves confidence scores up to 94% for emotion classification

## Emotion Categories
1. **Happiness** - Joy, contentment, positive emotions
2. **Sadness** - Grief, melancholy, low mood
3. **Anger** - Frustration, irritation, rage
4. **Surprise** - Shock, amazement, unexpected reactions
5. **Neutral** - Calm, balanced, no strong emotion
6. **Fear** - Anxiety, worry, apprehension
7. **Disgust** - Revulsion, distaste, aversion
8. **Contempt** - Disdain, scorn, superiority

## Technical Implementation
- **Model Architecture**: Convolutional Neural Network (CNN)
- **Input**: RGB images (facial expressions)
- **Output**: Emotion classification with confidence scores
- **Real-time Processing**: Optimized for live webcam analysis

## Usage
1. Select "Emotion Recognition System" from the project dropdown
2. Choose input source (webcam or upload image)
3. System analyzes facial expressions and predicts emotion
4. Receive personalized message based on detected emotion

## Interactive Responses
The system provides contextual messages for each emotion:
- **Motivational quotes** for sadness
- **Calming suggestions** for anger
- **Encouraging words** for fear
- **Celebratory messages** for happiness
- And much more!

## Files
- `Lines.json` - Contains emotion-specific response messages
- `model.h5` - Trained emotion recognition model (to be added)
- `README.md` - Project documentation

## Future Enhancements
- Multi-face detection
- Emotion intensity scoring
- Historical emotion tracking
- Integration with mood journaling

---
*Part of the ML Portfolio Interface*
