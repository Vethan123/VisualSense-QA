# VisualSense QA

VisualSense QA is a visual question answering (VQA) application built using Streamlit and ViLT (Vision-and-Language Transformer). It allows users to ask questions about images, and the model provides answers based on the content of the images.

## Features

- **Visual Question Answering (VQA):** Users can upload images and ask questions about them. The model processes the image and generates answers to the questions asked.
- **Interactive Interface:** The Streamlit interface provides an intuitive and user-friendly experience for interacting with the VQA model.
- **ViLT Integration:** ViLT (Vision-and-Language Transformer) powers the VQA model, allowing it to understand both visual and textual inputs.

## Getting Started

To run VisualSense QA locally, follow these steps:

1. Clone the repository:

    ```
    git clone https://github.com/vethan123/visualsense-qa.git
    ```

2. Navigate to the project directory:

    ```
    cd visualsense-qa
    ```

3. Install the required dependencies:

    ```
    pip install -r requirements.txt
    ```

4. Run the Streamlit app:

    ```
    streamlit run app.py
    ```

5. Access the app in your web browser at `http://localhost:8501`.

## Usage

- Upload an image using the file uploader.
- Type a question related to the content of the image in the text box provided.
- Click the "Ask" button to submit the question.
- The model will process the image and generate an answer to the question asked.

## Contributing

Contributions are welcome! If you'd like to contribute to VisualSense QA, please follow these guidelines:

- Fork the repository.
- Create a new branch (`git checkout -b feature/your-feature-name`).
- Make your changes and commit them (`git commit -am 'Add new feature'`).
- Push to the branch (`git push origin feature/your-feature-name`).
- Create a new pull request.



## Credits

- **ViLT:** The Vision-and-Language Transformer model is developed by the Hugging Face team.
- **Streamlit:** VisualSense QA is built using Streamlit, an open-source app framework for Machine Learning and Data Science projects.

## Contact

For questions or feedback, please contact [yadamvethan1@gmail.com].
