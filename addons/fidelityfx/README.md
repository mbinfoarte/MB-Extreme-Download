# AMD FidelityFX SDK 2.3.0 (DirectX 12) — para o benchmark do MB Extreme

`fidelityfx-dx12-2.3.0.zip` traz as DLLs assinadas da AMD usadas no teste **Upscaling e geração de quadros (FSR)**:

- `amd_fidelityfx_loader_dx12.dll`
- `amd_fidelityfx_upscaler_dx12.dll` (FSR upscaling)
- `amd_fidelityfx_framegeneration_dx12.dll` (FSR geração de quadros)

O programa baixa este arquivo só na primeira vez que o teste roda e confere o SHA-256
(`032077d5c7e9d2ea67c33a8c92e314a369a270891d058bda6618b5143a12bbaf`) antes de usar.

Origem: [GPUOpen-LibrariesAndSDKs/FidelityFX-SDK](https://github.com/GPUOpen-LibrariesAndSDKs/FidelityFX-SDK), pasta `Kits/FidelityFX/signedbin`.
Redistribuído em forma binária conforme a licença da AMD (`LICENSE-AMD-FidelityFX.md`). Copyright (C) Advanced Micro Devices, Inc.
