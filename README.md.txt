# Medical-AI-CT-Segmentation

基于 PyTorch 和 MONAI 的 COVID-19 CT 肺部病灶分割项目。

## 📊 实验结果
- **内部测试集最佳 Dice**: 0.7686 (v11 - 2.5D UNet)
- **外部验证微调 Dice**: 0.4572 (v15 - Fine-tuning)

## 📂 文件说明
- `chestct-kaggledatasets.ipynb`: 包含从 v1 到 v15 完整的实验代码（数据预处理、模型训练、评估、可视化）。

## 🚀 环境要求
- PyTorch, MONAI, nibabel, matplotlib

## 📖 引用
如果你觉得本项目有帮助，欢迎引用。