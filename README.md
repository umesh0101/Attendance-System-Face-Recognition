# Attendance-System-Face-Recognition
• Captured 50 face images using Haar Cascade, and saves the images with unique filenames corresponding to user’s name and roll no.
• Images are converted to blob for face detection with confidence above a threshold, used pre-trained model for storing facial embeddings.
• Used scikit-learn’s LabelEncoder for encoding names and saved to the ”le.pickle” file, SVM recogniser for classification of images.
• The recognized names and confidence scores are displayed on the frame, along with bounding boxes around the detected faces.
