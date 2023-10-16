# ERROR: segmentation fault core dumped at load_pretrainedmodel stage

Just downgrade sentencepiece to 0.1.91
```pip install sentencepiece==0.1.91```

# RuntimeError: CUDA error: CUBLAS_STATUS_EXECUTION_FAILED when calling `cublasSgemm( handle, opa, opb, m, n, k, &alpha, a, lda, b, ldb, &beta, c, ldc)`

```conda install pytorch==1.13.1 pytorch-cuda=11.6 -c pytorch```

Install Pytorch Version according to your cuda version

