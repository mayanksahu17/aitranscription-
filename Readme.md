# AI Transcription & Translation Model

## Overview
The **AI Transcription & Translation Model** is designed to transcribe English scripts and translate them into 10 Indian regional languages. It also evaluates the translation accuracy using standard metrics such as BLEU or ROUGE.

## Objective
Develop an AI system that can:
1. Transcribe English scripts (input text or file).
2. Translate the transcription into the following Indian languages:
   - Hindi
   - Marathi
   - Gujarati
   - Tamil
   - Kannada
   - Telugu
   - Bengali
   - Malayalam
   - Punjabi
   - Odia
3. Display the translation accuracy for each language.

## Key Features
- **Input**: Accepts English scripts either as text input or uploaded files.
- **Translation**: Provides translations in 10 regional languages.
- **Accuracy Display**: Computes and displays translation accuracy as a percentage for each language using BLEU or ROUGE metrics.
- **Optional UI**: A user-friendly interface for uploading scripts and viewing translation results.

## Success Metrics
- **Accuracy**: Achieve a minimum of 85% translation accuracy for all supported languages.
- **Processing Time**: Ensure that translation time per language does not exceed 10 seconds.
- **Language Coverage**: Support translations in all 10 targeted Indian languages.
- **Documentation**: Provide comprehensive instructions for setup and usage.

## Prerequisites
- Python 3.8 or above
- Libraries: TensorFlow, PyTorch, NLTK, BLEU/ROUGE packages, Flask/Django (for UI)
- GPU support for faster processing (optional but recommended)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/username/ai-transcription-translation.git
   ```
2. Navigate to the project directory:
   ```bash
   cd ai-transcription-translation
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
### Command Line Interface (CLI)
1. Run the script:
   ```bash
   python main.py --input <path_to_file_or_text>
   ```
2. Specify additional parameters if needed (e.g., output directory, metrics).

### Optional UI
1. Start the server:
   ```bash
   python app.py
   ```
2. Access the web application at `http://localhost:5000`.
3. Upload the English script and view translations along with accuracy metrics.

## Results
The results for each language include:
- Translated text.
- Accuracy percentage (BLEU/ROUGE score).

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature description"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Submit a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact
For any questions or feedback, please contact:
- Name: [Your Name]
- Email: [Your Email]

---

Thank you for using the AI Transcription & Translation Model!

