# Qualcomm vendor sepolicy (SM8550)

`device/qcom/sepolicy_vndr/sm8550` for `aston` / `astonc`.

Branch **`17`** = the Android 17 build tree (this is what the ROM builds against).
The plain LineageOS-24 counterpart of each repo is available upstream.

Local commits on top of LineageOS CAF policy:

- `sm8550: Add opluscamera_app to DSP neverallow exceptions`
- `sm8550: Gate the opluscamera_app DSP exceptions behind an m4 def`
