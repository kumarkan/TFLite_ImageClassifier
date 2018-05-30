# TF Lite Android App

This app is a modification of Google's tensor flow for Poets2 (tflite version) : https://codelabs.developers.google.com/codelabs/tensorflow-for-poets-2-tflite/index.html#0

I have added a button to enable/disable NNAPI for tflite at run time. I tested this app on my Android things hardware with movidius stick 

Profiling data :

With NNAPI disabled : Inference time around 150 ms
With NNAPI enabled and inference runnning on Movidius stick : Inference time 75 ms

# To test this app 

1) Clone the directory
2) Import the project in android studio
3) build apk and push it on your device 
