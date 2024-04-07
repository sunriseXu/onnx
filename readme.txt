from onnx import ModelProto, hub
hub.download_model_with_test_data("mnist",repo="sunriseXu/onnx",force_reload=True,silent=True)