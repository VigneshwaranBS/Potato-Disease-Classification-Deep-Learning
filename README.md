# Potato Disease Classification Deep Learning

This repository contains a deep learning-based potato disease classification system, with a web interface built using Flask for the backend and React.js for the frontend.

## Project Overview

The goal of this project is to accurately classify and identify diseases in potato plants using deep learning techniques. By leveraging a trained neural network model, the system can analyze input images of potato plants and provide predictions regarding the presence of various diseases. The web interface allows users to upload potato plant images, view the predictions, and obtain valuable insights.

## Technologies Used

- Python
- Flask (backend framework)
- React.js (frontend framework)
- TensorFlow (deep learning framework)
- HTML/CSS

## Getting Started

To get started with the project, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/VigneshwaranBS/Potato-Disease-Classification-Deep-Learning.git
   ```

2. Set up the backend:

   - Navigate to the backend directory:

     ```bash
     cd Potato-Disease-Classification-Deep-Learning/api
     ```

   - Install the required Python packages:

     ```bash
     pip install -r requirements.txt
     ```

   - Run the Flask development server:

     ```bash
     python main.py
     ```

3. Set up the frontend:

   - Navigate to the frontend directory:

     ```bash
     cd Potato-Disease-Classification-Deep-Learning/frontend
     ```

   - Install the required Node.js packages:

     ```bash
     npm install
     ```

   - Start the React development server:

     ```bash
     npm start
     ```

4. Access the web interface:

   Open your web browser and visit [http://localhost:3000](http://localhost:3000) to access the potato disease classification system.

## Model Training and Deployment

The deep learning model used for potato disease classification was trained on a labeled dataset of potato plant images using TensorFlow. The trained model was then saved and integrated into the Flask backend to provide real-time predictions.

To train the model or make improvements, follow these steps:

1. Prepare a labeled dataset of potato plant images, with separate folders for each class of disease.

2. Train the model using your preferred deep learning techniques, ensuring you achieve satisfactory accuracy and performance.

3. Save the trained model in a suitable format, such as TensorFlow's SavedModel or a serialized file.

4. Replace the existing model in the backend with your trained model.

## Contribution

Contributions to this project are welcome! If you have any ideas for improvements, new features, or bug fixes, please feel free to open an issue or submit a pull request.

When contributing, please adhere to the following guidelines:

- Provide a clear and detailed explanation of your changes.
- Ensure your code follows the project's coding style and conventions.
- Test your changes thoroughly before submitting a pull request.
- Be respectful and considerate in all interactions.


## Acknowledgments

We would like to express our gratitude to the open-source community and the authors of relevant libraries and frameworks that made this project possible.

