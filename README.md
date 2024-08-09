# Deforestation-monitoring-using-satellite-imagery
<p>
  <img src="https://www.google.com/imgres?q=deforestation%20monitoring%20image&imgurl=https%3A%2F%2Fwww.cyberswift.com%2Fpublic%2Fcyberswift%2Fimages%2Fafforestation-deforestation%2Fafforestation-deforestation-bg.jpg&imgrefurl=https%3A%2F%2Fwww.cyberswift.com%2Fin%2Findustries%2Fafforestation-deforestation&docid=DW7nYX_WZtfyDM&tbnid=OWtUAgcUgLPrzM&vet=12ahUKEwjz5Y-BnuiHAxXYyTgGHT3GOVkQM3oECHEQAA..i&w=1920&h=600&hcb=2&ved=2ahUKEwjz5Y-BnuiHAxXYyTgGHT3GOVkQM3oECHEQAA">
</p>
## Data set link: https://drive.google.com/drive/folders/1XXaInl5FSO7uyB8nQqZDT-OE9u5Y8yRR?usp=sharing
### Note : The gdrive consists of 50 sample images and masks,one can use more samples for better accuracy of the model.
# Description:
A deforestation monitoring project using a Convolutional Neural Network (CNN) model involves leveraging deep learning techniques to detect and analyze deforestation activities from satellite imagery. The project typically includes the following steps:

1. **Data Collection**: Gather satellite images from sources like Landsat, Sentinel, or other high-resolution satellites (or you can use the dataset link provided). These images cover different geographical areas and time periods, allowing the model to track changes over time.

2. **Preprocessing**: The images are preprocessed to enhance features relevant to deforestation. This might include resizing, normalization, and augmentation to make the model more robust to variations.

3. **CNN Model Development**: A CNN architecture is designed or selected, typically involving multiple layers like convolutional, pooling, and fully connected layers. The model is trained on labeled data, where regions of deforestation are marked, to learn patterns that distinguish deforested areas from non-deforested ones.

4. **Training and Validation**: The CNN is trained using a large dataset, with a portion reserved for validation to fine-tune hyperparameters and prevent overfitting. The model learns to extract relevant features from the images and make predictions about deforestation.

5. **Deployment and Monitoring**: Once trained, the model can be deployed to continuously monitor satellite imagery, detecting new instances of deforestation in near real-time. Alerts can be generated when deforestation is detected, allowing for timely intervention.

6. **Evaluation and Improvement**: The model’s performance is continuously evaluated using metrics like accuracy, precision, recall, and F1-score. Based on the results, the model can be further refined and retrained with new data to improve its detection capabilities.

# Sample of images:
The dimensions of the images is 512 x 512.
![Screenshot (483)](https://github.com/user-attachments/assets/9dda6167-48e1-478e-891d-cf2b4ae1ee2d)


