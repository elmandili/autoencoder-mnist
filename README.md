# autoencoder-mnist

Minimal workspace for experimenting with autoencoders and variational autoencoders on MNIST.

Files
- [train_.ipynb](train_.ipynb)
- [train.ipynb](train.ipynb)
- [vae.ipynb](vae.ipynb)
- [weights/last.weights.h5](weights/last.weights.h5)

Description
- Jupyter notebooks for building, training, and evaluating autoencoders/VAEs on MNIST.
- Pretrained weights stored in the `weights/` folder.

Requirements
- Python 3.8+
- Typical packages: numpy, matplotlib, tensorflow or pytorch, jupyter

Quick start
1. Create a virtual environment:
   ```sh
   python -m venv .venv
   source .venv/bin/activate 
   ```
2. Install dependencies (create a requirements.txt if needed):
   ```sh
   pip install -r requirements.txt
   ```
3. Open a notebook in VS Code or Jupyter:
   - e.g. open [train.ipynb](train.ipynb) or [05h_LAB_Autoencoders.ipynb](05h_LAB_Autoencoders.ipynb)

Notes
- Use a GPU-enabled environment for larger training runs.
- Inspect notebooks for dataset loading, model definitions, and checkpoints.

License
- MIT