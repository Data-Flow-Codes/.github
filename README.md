![logo image](https://github.com/Data-Flow-Codes/.github/blob/f223c2fe08e7bbc643e544c35a2d4c6bbcabe6db/profile/assets/DataFlowCodes.png)
# Hybrid Graph Bytecode

## Rationale
Discrete GPU architectures don't benefit from differences in data compared to the main memory bus when using machine learning so the added second memory bus of the graphics card ends up being more of a liability than an asset. The addition of canonical WebAssembly and nonstandard, implementation-specific extensions to the bytecode reflects this. As such, SoC architectures can implement both instruction sets using a uniform compiler pipeline, combining WebAssembly and SPIR-V into one.

## Documentation License and Hosting
The documentation is under the [Creative Commons Attribution-ShareAlike 4.0 International](LICENSE.txt) License. If there is any chance of a license conflict with other contents, please bring it up on the [forum](https://github.com/Data-Flow-Codes/.github/discussions) or the [CodeBerg issue tracker](https://codeberg.org/DataFlow_Codes/bytecode/issues). Current hosting is on GitHub Pages but will move to [CodeBerg Pages](https://codeberg.page/) for its static hosting once the Forgejo runner action is set up on the server and the host configuration is finalized. The forum will continue to be hosted on GitHub afterward because there is no corresponding function on Codeberg.org and comments will need to be heard from both hosts regardless.
