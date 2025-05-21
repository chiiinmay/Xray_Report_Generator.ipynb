# Xray_Report_Generator.ipynb
Auto-generate chest X-ray reports using vision-language models ViT + GPT-2) — Educational Use Only
# 🩻 X-Ray Report Generator using Vision-Language Models

This project demonstrates how to automatically generate descriptive radiology reports from chest X-ray images using a Vision Transformer (ViT) and GPT-2 based language model.

## 🚀 Features
- Pretrained model from Hugging Face: `nlpconnect/vit-gpt2-image-captioning`
- Automatically processes grayscale X-ray images
- Outputs structured radiology-style reports
- Can process multiple images in batch
- Colab-friendly, with minimal dependencies

## 📁 Folder Structure
```
.
├── Xray_Report_Generator.ipynb
├── LICENSE
├── README.md
```

## 🛠 Requirements
- Python 3.8+
- `transformers`, `torch`, `PIL`, `matplotlib`

## 📜 License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## 🙏 Acknowledgements
- Model: `nlpconnect/vit-gpt2-image-captioning`
- Development assisted by ChatGPT (OpenAI)
