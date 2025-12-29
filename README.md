# Fashion Deep Learning Recommendation System

This project implements a **content-based fashion recommendation system** using **Deep Learning**.  
Product images are converted into feature vectors using a **pre-trained ResNet50 model**, and visually similar products are recommended using **Nearest Neighbors**.

---

## Project Workflow

- Downloaded and used a fashion image dataset (~44,000 images)
- Extracted image features using **ResNet50 (ImageNet weights)**
- Applied **Global Max Pooling** to obtain fixed-length feature vectors
- Normalized feature vectors for similarity comparison
- Built a **KNN-based recommendation system** using cosine similarity
- Saved extracted features and filenames using Pickle
- Developed an interactive **Streamlit app** for product recommendations

---

## Model Architecture

- **Backbone:** ResNet50 (pre-trained, frozen)
- **Input Size:** 224 × 224 × 3
- **Output:** 2048-dimensional feature vector
- **Pooling:** GlobalMaxPooling2D

---

## Technologies Used

- Python  
- TensorFlow / Keras  
- ResNet50  
- Scikit-learn  
- NumPy  
- Streamlit  

---

## Output

- Recommends visually similar fashion products based on uploaded images
- Deployed as an interactive app on Hugging Face Spaces

🔗 **Live Demo:**  
https://huggingface.co/spaces/sevvaliclal/FashionRecommerderModel

---

## Use Case

This system can be used for:
- E-commerce product recommendation
- Visual similarity search
- Fashion discovery platforms

⭐ If you like this project, consider starring the repository!
