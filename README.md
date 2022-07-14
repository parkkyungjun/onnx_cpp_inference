# onnx
Inference from cpp for a model trained in pytorch

Model type should be .onnx

reference -> nuget

you should add pakages

- Microsoft.ML.OnnxRuntime
- OpenCV.Win.Core
- OpenCV.Win.ImgCodecs
- OpenCV.Win.ImgProc


if you want to gan or segmentation and so on...
- change "const array<int64_t, 2> outputShape = { 1, numClasses };" -> what you want
- results.data() has output data(float) 
