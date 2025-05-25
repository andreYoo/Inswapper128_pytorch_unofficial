# Inswapper128_pytorch_unofficial
Unofficial Inswapper (Pytorch Inswapper with Trainable Parameters)

This is the Inswapper PyTorch version, which is 99.999999% the same as the Inswapper128. onnx
* It provides a detailed model architecture (with trainable pre-trained model)
* It can be used as a strong backbone for the face identity swap model.


Visualisation results of the network architecture

 (Inswapper_128.onnx)


  (Inswapper_128_torch.onnx) (Simplified version)
  * This ONNX is made by transferring the PyTorch model file (.pt) to the ONNX file using the onnx2torch library.

Reproduction process for this results


Quantitative and quantitative results (l1-distance)

Inswapper_128.onnx vs pytorch model

Inswapper_128.onnx vs Inswapper_128_from_pytorch.onnx

Reproduction process for these results - see the notebook


Copyright—Every study that uses these projects has the responsibility to open their source code and pre-trained model.

