# Parcel bundler with Transformers.js v3

- This demo uses Transformers.js v^3.0.2.
- The build fails: "Failed to resolve '#onnxruntime-webgpu'"

(As a result, I couldn't reproduce the [getModelJSON bug observed in Transformers.js v2](https://github.com/xenova/transformers.js/issues/366)).

To run:

- `npm i` (once)
- `npm run dev`

Behavior:

Build fails with `"@parcel/core: Failed to resolve '#onnxruntime-webgpu' from './node_modules/@huggingface/transformers/src/backends/onnx.js'"`

<p align="center">
<img width="759" alt="image" src="https://github.com/user-attachments/assets/be7468e1-aa78-4b92-ad80-9df0188cc55a">
</p>
