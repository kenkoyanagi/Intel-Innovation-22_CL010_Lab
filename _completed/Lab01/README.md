This lab aims to demonstrate conversion and deploment of an official pytorch model for inferencing use cases to onnx format.

We convert the official pytorch resnet FP32 model to .onnx FP32 format using pytorch_to_onnx.py .

We use onnx_fp32tofp16.py under the onnx_fp32tofp16_conversion directory to convert the FP32 onnx model to FP16 type.

