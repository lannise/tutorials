# [ONNX](https://github.com/onnx/onnx) tutorials

## Importing and Exporting from frameworks

| Framework / tool | Installation | Exporting to ONNX (frontend) | Importing ONNX models (backend) |
| --- | --- | --- | --- |
| [Caffe2](http://caffe2.ai) | [onnx/onnx-caffe2](https://github.com/onnx/onnx-caffe2) | [Exporting](tutorials/OnnxCaffe2Export.ipynb) | [Importing](tutorials/OnnxCaffe2Import.ipynb) |
| [PyTorch](http://pytorch.org/) | [part of pytorch package](http://pytorch.org/docs/master/onnx.html) | [Exporting](tutorials/PytorchOnnxExport.ipynb), [Extending support](tutorials/PytorchAddExportSupport.md) | coming soon |
| [CTNK](https://github.com/Microsoft/CNTK) | coming soon | coming soon | coming soon |
| [Apache MXNet](http://mxnet.incubator.apache.org/) | [onnx/onnx-mxnet](https://github.com/onnx/onnx-mxnet) | coming soon | [Importing](tutorials/OnnxMxnetImport.ipynb) [experimental] |
| [TensorFlow](https://www.tensorflow.org/) | [onnx/onnx-tensorflow](https://github.com/onnx/onnx-tensorflow) | coming soon | [Importing](tutorials/OnnxTensorflowImport.ipynb) [experimental] |
| [Apple CoreML](https://developer.apple.com/documentation/coreml) | [onnx/onnx-coreml](https://github.com/onnx/onnx-coreml) | - | [Importing](tutorials/OnnxCoremlImport.ipynb) |

## End-to-end tutorials

* [Converting SuperResolution model from PyTorch to Caffe2 and deploying on mobile device](tutorials/PytorchCaffe2SuperResolution.ipynb)
* [Transferring SqueezeNet from PyTorch to Caffe2 and to Android app](tutorials/PytorchCaffe2MobileSqueezeNet.ipynb)

## Contributing

We welcome improvements to the convertor tools and contributions of new ONNX bindings. Check out [contributor guide](https://github.com/onnx/onnx/blob/master/docs/CONTRIBUTING.md) to get started.

Use ONNX for something cool? Send the tutorial to this repo by submitting a PR.