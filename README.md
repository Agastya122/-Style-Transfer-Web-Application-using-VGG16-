# -Style-Transfer-Web-Application-using-VGG16-
Developed a web-based deep learning application that performs artistic style transfer using the VGG16 architecture.The system combines content and style images to generate a stylized output, allowing real-time visualization via a browser interface. 
![Stylized Result](https://github.com/Agastya122/-Style-Transfer-Web-Application-using-VGG16-/raw/main/stylized_result.jpg)


# -Features
1. Upload a content image and a style image
2. Perform neural style transfer using a pre-trained VGG16 model
3. View the stylized output in real-time
4. Displays 100+ intermediate images during training
5. Responsive UI with Bootstrap 5

# -Tech Stack
| Component         | Technologies Used                              |
| ----------------- | ---------------------------------------------- |
| Backend           | Python, Flask                                  |
| Deep Learning     | TensorFlow, Keras (VGG16), NumPy,              |
| Frontend          | HTML5, Bootstrap 5                             |
| Visualization     | Matplotlib (for intermediate image generation) |

# -Project Structure
Image_Style_Transfer/
├── static/
│   ├── uploads/               # Uploaded content & style images
│   └── stylized_result.jpg    # Final output image
├── templates/
│   └── index.html             # Frontend HTML template
├── app.py                     # Flask application
├── style_transfer.py          # Core VGG16-based style transfer logic
└── README.md                  # Project documentation

# -Sample Output
content Image:-
![Stylized Result](https://github.com/Agastya122/-Style-Transfer-Web-Application-using-VGG16-/blob/main/content.jpg)



