# Fine-Tune-W2V2-Classifier-for-Chinese-Accents
This project is fine-tuning for Wav2Vec2 classifier for Mandarin, Cantonese, Taiwanese and Wu accents.
Note: This is a JuPyter Google Colab Notebook that was run using A100 GPU with high memory load enabled

## Problems viewing the file in GitHub
1. When on the page with the .ipynb file, replace the "github.com" in the link with "nbsanity.com"
2. Example at https://nbsanity.com

## Instructions
1. Connect to the A100 GPU
2. Download the SpeechAccentArchive.zip file containing the 210 speech samples. Git LFS is recommended, although not necessary
3. Run cells in order until getting to "Uploading SpeechAccentArchive.zip"
4. If running the model more than once, use the mount drive cell, otherwise upload the .zip file using the file picker
5. Unzip once the upload is complete.
6. Scroll down to "Fine Tuning Wav2Vec2" and run cells underneath
