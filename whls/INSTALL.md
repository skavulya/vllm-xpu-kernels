## Install vllm-xpu-kernels 
URL: https://github.com/vllm-project/vllm-xpu-kernels/actions/runs/34828812641
```
cd scalable-deploy-intel
gh run download 34828812641 \
      -R vllm-project/vllm-xpu-kernels \
      -n vllm-xpu-kernels--20260914-093925 \
      -D ./whls && \
      pip install ./whls/dist/*.whl
```
