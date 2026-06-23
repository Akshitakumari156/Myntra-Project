# Myntra StyleVerse: Your AI-Powered Fashion & Decor Companion from IntothealgoLand GEN_AI 🛍️✨

![Hackathon](https://img.shields.io/badge/Myntra%20HackerRamp-WeForShe-E9386A?style=for-the-badge)
![Build Status](https://img.shields.io/badge/build-passing-brightgreen?style=for-the-badge)

An innovative solution for the **Myntra "HackerRamp WeForShe" hackathon**, designed to bring the experience of a personal stylist to every user's fingertips. Using cutting-edge Generative AI, Computer Vision, and multi-modal search, our mission is to make online shopping deeply personal, intuitive, and confidence-boosting.

---
## 🚀 Live Demo

The project is deployed and live on Render. You can view it here:

[![Live Demo](https://img.shields.io/badge/Live_Demo-Link-blue?style=for-the-badge&logo=render)](https://myntra-project-3.onrender.com)

---
## 🚀 Demo Video

Check out this quick video to see Myntra StyleVerse in action!

[![Myntra StyleVerse Demo Video]](https://drive.google.com/drive/folders/1V58k-_K-Oq-seb-7wou0gVRbS8F6pudf?usp=drive_link)

---
## 🚀 Key Features

### 👗 1. AI Look Curator
Simply tell our AI stylist what you're looking for, and it will create the perfect ensemble for you. From a "Traditional pooja look" to a "casual brunch outfit," get a complete, curated look with matching dresses, footwear, and accessories, all available on Myntra.

![AI Look Curator Demo](./screenshots/2.png)

---

### 🖼️ 2. Visual "What to Wear" Assistant
Leverage the clothes you already own! Upload an image of an item from your wardrobe and ask, "What should I wear with this?". Using vector search and image embeddings, our assistant recommends complementary items from Myntra's catalog to complete your look.

![Visual Assistant Demo](./screenshots/4.png)
![Visual Assistant Demo](./screenshots/3.png)

---

### 👕👖 3. Virtual Mix & Match Studio
Become your own stylist in our interactive studio. Drag and drop items you like, and our AI model, using **Clothing Co-Parsing**, instantly isolates the clothing item from its background. Freely mix and match tops, bottoms, and accessories to create and visualize unique outfits in real-time.
Users can upload clothes from there own ends and try mix&match.

![Visual Assistant Demo](./screenshots/5.png)
![Visual Assistant Demo](./screenshots/6.png)



---

### 🏠 4. AI Home Decor Stylist
Our styling expertise doesn't stop at fashion! Upload a picture of a corner in your house, a table, or an empty wall. Our AI analyzes the space's aesthetic and suggests suitable decor items like wall hangings, vases, or furniture to complete your home.

![Visual Assistant Demo](./screenshots/7.png)
![Visual Assistant Demo](./screenshots/8.png)


---

### 🏆 5. Community Style Contests
Share your creativity and get recognized! Post the unique looks you create in the Mix & Match Studio for the community to browse and "like." Top-voted creations earn stars, which can be redeemed for gifts and vouchers, fostering a vibrant and engaged user community.

![Community Style Contests Demo](./screenshots/9.png)
![Visual Assistant Demo](./screenshots/10.png)


---

### 🛒 6. Smart Cart Stylist
Get more value out of every purchase. Our AI analyzes the items in your cart and provides creative suggestions on how to style each item for multiple occasions, such as taking a shirt from a formal office look to a casual weekend outing.

![Visual Assistant Demo](./screenshots/11.png)


---
## 🚀 Getting Started

1.  **Clone the repo**
2.  **Install backend dependencies**
    ```sh
    cd backend
    npm i
    npm run dev
    ```
3.  **Install frontend dependencies**
    ```sh
    cd frontend
    npm install
    npm run dev
    ```
4.  **Run the embedding-service**
    ```sh
    python -m venv venv
    .\venv\Scripts\activate
    uvicorn main:app --reload
    ```
5. **Run the Clothing Co-Parsing**
   ```sh
     python -m venv venv
    .\venv\Scripts\activate
     python app.py
   ```
   ## 🧠 Pre-trained Model

This project requires the pre-trained weights for the Clothing Co-Parsing model. Please download the `.pth` file from the link below and place it in the `Clothing Co-Parsing` directory of your project.

[![Download Model Weights](https://img.shields.io/badge/Download-Model%20Weights-blue?style=for-the-badge&logo=googledrive)](https://drive.google.com/file/d/1d6Q_YBHurmwAHo_jUuR-Fr18vsuJPoYe/view?usp=sharing)

---
## 🛠️ Technology Stack

| Category          | Technologies Used                                                              |
| ----------------- | ------------------------------------------------------------------------------ |
| **AI / ML** | `Python`, `TensorFlow`/`PyTorch`, `Hugging Face`, `CLIP`, `U-Net`, `Vector DB`     |
| **Backend** | `FastAPI`, `Node.js`, `Express.js`                                             |
| **Frontend** | `React`,`tailwind`,`CSS`,`JS`               |
| **Database** | `MongoDB`                                   |

---

## 👥 Contributors

| Name             | GitHub Profile                                                 |
| ---------------- | -------------------------------------------------------------- |
| Vanshika Singla  | [@vanshikasingla220705](https://github.com/vanshikasingla220705) |
| Akshita Kumari   | [@Akshitakumari156](https://github.com/Akshitakumari156)         |


---
