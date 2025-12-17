# Fine-Tune-W2V2-Classifier-for-Chinese-Accents
## Description
This project is fine-tuning for Wav2Vec2 classifier for Mandarin, Cantonese, Taiwanese and Wu accents speaking English.
The model uses the existing open-source classifier Wav2Vec2 from Huggingface, which originally was trained for 11 accents of English from broad areas
and fine-tunes it for 4 Chinese accents.

## Installation/Accessing Notebook
> Note: This is a JuPyter Google Colab Notebook that was run using A100 GPU with high memory load enabled
1. When on the page with the .ipynb file, replace the "github.com" in the link with "nbsanity.com"
2. Example at https://nbsanity.com

## Running Instructions
1. Connect runtime to the A100 GPU (I can't guarantee the program will work with another GPU)
2. Download the SpeechAccentArchive.zip file containing the 210 speech samples. Git LFS is recommended.
3. Run cells in order until getting to "Uploading SpeechAccentArchive.zip"
4. If running the model more than once, use the mount drive cell, otherwise upload the .zip file using the file picker
5. Unzip once the upload is complete.
6. Scroll down to "Fine Tuning Wav2Vec2" and run cells underneath it.

## Citation:
BibTeX
```
@misc{hong2025finetunew2v2chineseaccents,
	title ={Fine-Tune-W2V2-Classifier-for-Chinese-Accents},
	author={Hong, Kalista},
	year  ={2025}
}
```
