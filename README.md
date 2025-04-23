# Efficient-Scene-Interpretation-Framework-Using-Dynamic-Dual-Processing

Project Title: Efficient Scene Interpretation Framework Using Dynamic Dual-Processing



Dataset Source:
- MS COCO: https://cocodataset.org/
- OccludedPascal3D: https://paperswithcode.com/dataset/occludedpascal3d



Software Requirements:
- Python 3.8+
- PyTorch >= 1.10
- torchvision
- transformers (Hugging Face)
- matplotlib
- OpenCV
- numpy

Hardware Requirements:
- Google Colab or local CUDA-enabled GPU
- Minimum 8GB RAM



Instructions to Execute:

1. Clone or download the SourceCode folder.

2. Open the notebooks in Jupyter or Google Colab:
   - `Hybrid_Model.ipynb`: Runs the dual-detection pipeline using Faster R-CNN and DETR to generate bounding boxes and occlusion summaries.
   - `Cross_Attention_Captioning.ipynb`: Takes detection output and generates refined image captions using BLIP and cross-attention fusion.

3. To test:
   - Place any test image in the folder and update the path in the respective cell.
   - Run the notebook cells in sequence.

4. Execute cells in order. Final output includes:
   - Object detection result with bounding boxes.
   - Context-rich caption describing the scene.


NOTE:
- Run each cell in sequence for both notebooks.
- Keep input image resolution reasonable (~512x512) for faster results.



