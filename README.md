<h1>Deep Learning based approach to detect violence</h1>
<h4>We develop a violence detection system using deep learning and Flask. The system processes video footage, identifies violent behavior, and sends an alert email. We created a unique dataset comprising 1000 videos, evenly split between violence and non-violence categories, providing a balanced basis for model training. Frames were extracted from each video, resized to standard dimensions, and normalized, forming the feature set for our models. We employed various models including VGG19, VGG16, MobileNet-v2+LSTM, ResNet-50, and CNN+LSTM. Our best performing model was CNN+LSTM with an accuracy of 98%, closely followed by MobileNet-V2+LSTM at 95%. We developed a Flask application as an interface for our system, enabling real-time violence detection and enhancing user interaction. Our system identifies violent incidents, sends alert emails with detected frames and also violence location, and significantly improves response times.<br><br>
Dataset: https://www.kaggle.com/datasets/mohamedmustafa/real-life-violence-situations-dataset
</h4>
<!-- <h3>Accuracy Analysis of Different models</h3>
<h5>The results are visualized in a bar chart, making it easy to compare the performance of the different models. Each bar represents a model, and the height of the bar corresponds to the accuracy of that model.</h5>

 
