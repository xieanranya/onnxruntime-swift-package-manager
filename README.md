# onnxruntime-swift-package-manager

Mirror of microsoft/onnxruntime-swift-package-manager @ 1.24.2.

The upstream repository AND its binary host (download.onnxruntime.ai) were deleted by Microsoft.
This mirror hosts the source at tag `1.24.2`; the `onnxruntime.xcframework.zip` binary target
points to this repo's release asset — taken unmodified from the official NuGet package
`Microsoft.ML.OnnxRuntime` 1.24.2 (`runtimes/ios/native/onnxruntime.xcframework.zip`).

The `onnxruntime_extensions` target/product was dropped (not needed by consumers of the
`onnxruntime` library).
