# Xray_Report_Generator.ipynb
Auto-generate chest X-ray reports using vision-language models ViT + GPT-2) — Educational Use Only
# 🩻 X-Ray Report Generator using Vision-Language Models

## ⚠️ Disclaimer

This project is intended for **educational and research purposes only**.  
It is **not** designed or approved for clinical or diagnostic use.

Please do **not** rely on this system for actual medical decision-making.  
All outputs should be reviewed and interpreted by certified medical professionals.

## 📄 Licensing Notes

The pretrained model used in this project, [`nlpconnect/vit-gpt2-image-captioning`](https://huggingface.co/nlpconnect/vit-gpt2-image-captioning), is made available via Hugging Face under the MIT License.

This repository maintains license compatibility and credits the original model authors. For more information, refer to their official model card.


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
