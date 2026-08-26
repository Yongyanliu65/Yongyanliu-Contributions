# ROOT / TMVA-SOFIE Engineering Contributions

Selected engineering contributions to
[ROOT/TMVA-SOFIE](https://github.com/root-project/root/tree/master/tmva/sofie)
during Google Summer of Code 2026.

My work focuses on **ML inference infrastructure, C++ code generation,
dynamic tensor execution, profiling, memory optimization, and compiler
optimization**.

---

## Selected Contributions

### [Dynamic Tensor Shapes & Runtime Shape Infrastructure →](https://github.com/root-project/root/pull/18633)

Contributed to SOFIE's dynamic tensor shape infrastructure, including
dynamic dimensions, shape tensors, runtime shape management, memory
allocation, and operator propagation.

**Upstream:** ROOT PR #18633

---

### [Runtime Profiler Code Generation →](https://github.com/root-project/root/pull/19829)

Added generated profiling infrastructure for analyzing inference execution
and runtime performance in SOFIE-generated code.

**Upstream:** ROOT PR #19829

---

### [Self-Contained Inference Code Generation →](https://github.com/root-project/root/pull/22920)

Made SOFIE-generated C++ inference code self-contained by emitting the
runtime helper implementations required by each model.

This reduces the generated model's dependency on ROOT/TMVA headers and
improves portability of generated inference code.

**Upstream:** ROOT PR #22920

---

### [ConvTranspose Memory Optimization →](https://github.com/root-project/root/pull/18168)

Improved memory usage in ConvTranspose inference paths, including
ConvTranspose convolution and Im2col-related execution.

**Upstream:** ROOT PR #18168

---

### [Conv + Add Operator Fusion →](https://github.com/root-project/root/pull/21979)

Improved SOFIE's Conv + Add fusion path and generated execution behavior.

**Upstream:** ROOT PR #21979

---

## Other Engineering Work

Additional work across ROOT/TMVA-SOFIE includes:

- ONNX parser improvements
- Runtime broadcasting
- Shape tensor management
- Session initialization and memory allocation
- Optimization modes
- BatchNormalization fusion
- Einsum BLAS optimization
- External ONNX data support
- Modern C++ API safety improvements
- Operator implementations and testing
- CI and regression testing
- Keras / ONNX reproducibility improvements

---

## Technical Areas

`C++` · `ROOT` · `TMVA/SOFIE` · `ONNX` · `CMake` · `Linux`

**Focus:** ML Runtime · ML Compiler Infrastructure · Code Generation ·
Performance Engineering · Memory Optimization

---

## Upstream Project

These contributions were developed for the
[ROOT project](https://github.com/root-project/root), an open-source
data analysis framework widely used in high-energy physics.

[Explore ROOT/TMVA-SOFIE →](https://github.com/root-project/root/tree/master/tmva/sofie)
