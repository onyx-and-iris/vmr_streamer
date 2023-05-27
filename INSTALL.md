# Step by step

These instructions should work for both Debug/Release builds. In this case we target Release x64.

![Release][release]

Open up project properties.<br>
![Properties][properties]

In advanced properties ensure `Character Set` is set to `Not Set`
![Character Set][char_set]

Check that `_CRT_SECURE_NO_DEPRECATE` and if targeting an x64 build `VB_X64` are in the preprocessor definitions.
![Preprocessor Definitions][pp_def]

Ensure `Ws2_32.lib` is included as an additional dependency.
![Linker dependencies][linker]

[release]: vmr_streamer/img/vm1-inst.png
[properties]: vmr_streamer/img/vm2-inst.png
[char_set]: vmr_streamer/img/vm3-inst.png
[pp_def]: vmr_streamer/img/vm4-inst.png
[linker]: vmr_streamer/img/vm5-inst.png
