conda create -n dreamerv3 python=3.8 -y
pip install -U "jax[cuda12_pip]" -f https://storage.googleapis.com/jax-releases/jax_cuda_releases.html
pip install setuptools==63.2.0 wheel==0.38.4