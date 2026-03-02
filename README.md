# Hybrid Graph Bytecode
Hosted by [CodeBerg](https://codeberg.org/) as an open documentation project. Licene is [CC-BY-SA](https://creativecommons.org/licenses/by-sa/4.0/) and any contents that is incompatible with that license should be cited off-site or alenative licensing negotiated in the [issue tracker](https://codeberg.org/DataFlow_Codes/bytecode/issues).

## Rationale
Discrete GPU architectures don't benefit from differences in data compared to the main memory bus when using machine learning so the added second memory bus of the graphics card ends up being more of a liability than an asset. The addition of canonical WebAssembly and nonstandard, implementation-specific extensions to the bytecode reflects this. As such, SoC architectures can implement both instruction sets using a uniform compiler pipeline, combining WebAssembly and SPIR-V into one.
