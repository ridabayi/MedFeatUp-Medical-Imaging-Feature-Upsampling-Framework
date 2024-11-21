# **MedFeatUp: Medical Imaging Feature Upsampling Framework**  
*Advanced AI-Powered Resolution Enhancement for Medical Diagnostics*  

![Demo of MedFeatUp in Action](https://github.com/ridabayi/MedFeatUp-Medical-Imaging-Feature-Upsampling-Framework/blob/main/all_feats-ezgif.com-video-to-gif-converter.gif)
*Figure: MedFeatUp's impact on feature resolution for medical imaging*  

---

## **🚀 Key Features**  

- **📈 High-Resolution Feature Maps**: Upscales deep learning features up to 32x without semantic loss.  
- **🧠 Backbone Flexibility**: Works seamlessly with **ViT**, **ResNet**, **DINO**, and more.  
- **⚕️ Tailored for Medical Imaging**: Specially adapted for X-rays, MRIs, CT scans, and histopathology.  
- **🔧 Customizable Training**: Train upsamplers on your dataset for domain-specific optimization.  

---

## **💻 Installation**  

### Quick Setup:  
```bash
pip install git+https://github.com/ridabayi/MedFeatUp.git


git clone https://github.com/ridabayi/MedFeatUp.git
cd MedFeatUp
pip install -e .


🔥 Get Started in 3 Steps
1️⃣ Load a Pretrained Upsampler:

python
Copier le code
import torch
upsampler = torch.hub.load("ridabayi/MedFeatUp", 'dino16', use_norm=False)
features = upsampler(image_data)
2️⃣ Train Your Custom Upsampler:

bash
Copier le code
python train_implicit_upsampler.py --config configs/implicit_upsampler.yml
3️⃣ Run the Gradio Demo:

bash
Copier le code
python gradio_app.py
Navigate to http://localhost:7860 to explore.


Figure: MedFeatUp's Gradio interface in action

🔬 Applications
📊 Super-Resolution for Medical Data
Enhance imaging datasets with improved clarity for better diagnostic precision.
🎯 Improved Segmentation
Enable finer segmentation of lesions, organs, and other anatomical structures.
🖼️ Clinical Visualizations
Generate high-quality feature maps for AI-assisted decision-making.

Figure: Improved segmentation using MedFeatUp
