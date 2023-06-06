# Link

This is the link to setup the M2 to work with pytorch and MPS: https://developer.apple.com/metal/pytorch/


the conda environment is `pytorch_test` and running python test.py returns:

```python
    tensor([1.], device='mps:0')
```

so the GPU in the M2Pro is available for pytorch
