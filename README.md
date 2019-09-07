
# Verify the Correctness of Exported Model and Compare the Performance

Correctness Verification Performance Comparison of of different Deep Learning Frameworks such as Pytorch, Caffe2 and Tensorflow using ONNX format models.

We choose PyTorch to export the ONNX model, and use Caffe2 and Tensorflow as backend.
After that, the outputs and performance of the three models are compared.

The ONNX Tutorial "Verify the Correctness of Exported Model and Compare the Performance" uses only Caffe2 as backend. But it fails when running the Caffe2 Model. In this notebook, we used a workaround to correct this issue. There are also some drawbacks of 

Reference : https://github.com/onnx/tutorials/blob/master/tutorials/CorrectnessVerificationAndPerformanceComparison.ipynb
