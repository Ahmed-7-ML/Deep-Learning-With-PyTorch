# Deep Learning With PyTorch

## Contents

- PyTorch & tensor basics
- Neural networks (MLP), training loops, and evaluation
- Convolutional Neural Networks (CNNs) for vision
- Recurrent models / sequence modeling (optional)
- Transfer learning and fine-tuning
- Regularization, optimization, and training tips
- Model saving/loading and inference

## Getting Started

### Prerequisites
- Python 3.9+ (recommended)
- pip or conda
- (Optional) NVIDIA GPU + CUDA for faster training

### Installation (pip)

```bash
git clone https://github.com/Ahmed-7-ML/Deep-Learning-With-PyTorch.git
cd Deep-Learning-With-PyTorch

python -m venv .venv
# Windows: .venv\Scripts\activate
source .venv/bin/activate

pip install --upgrade pip
pip install -r requirements.txt
```

### Installation (conda) (optional)

```bash
conda create -n dl-pytorch python=3.10 -y
conda activate dl-pytorch
pip install -r requirements.txt
```

### Install PyTorch
If `requirements.txt` doesn’t include the correct PyTorch build, install from the official selector:
- https://pytorch.org/get-started/locally/

Example (CPU-only):
```bash
pip install torch torchvision torchaudio
```

## Datasets

This repo may use public datasets such as:
- MNIST / Fashion-MNIST
- CIFAR-10

## Roadmap (Optional)

- [ ] Add more architectures (ResNet, EfficientNet, etc.)
- [ ] Add experiment tracking (TensorBoard / Weights & Biases)
- [ ] Add tests and CI
- [ ] Add export (TorchScript / ONNX)

## Contributing

Contributions are welcome:
1. Fork the repo
2. Create a feature branch: `git checkout -b feature/my-change`
3. Commit: `git commit -m "Add: ..."`
4. Push: `git push origin feature/my-change`
5. Open a Pull Request

## Acknowledgements
- PyTorch: https://pytorch.org/
- Eng/Amr abdlatif: https://www.youtube.com/watch?v=q1Hk7YiR5SA&list=PLhBhgortqAcjERnXJE1SqmKvL7UFw7xCp
