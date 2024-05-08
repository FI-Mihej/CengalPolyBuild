![GitHub tag (with filter)](https://img.shields.io/github/v/tag/FI-Mihej/InterProcessPyObjects) ![Static Badge](https://img.shields.io/badge/OS-Linux_%7C_Windows_%7C_macOS-blue) ![Static Badge](https://img.shields.io/badge/coverage-47%25-blue) ![Static Badge](https://img.shields.io/badge/covered_lines_of_code-2508-blue)

![PyPI - Version](https://img.shields.io/pypi/v/InterProcessPyObjects) ![PyPI - Format](https://img.shields.io/pypi/format/cengal-light?color=darkgreen) ![Static Badge](https://img.shields.io/badge/wheels-Linux_%7C_Windows_%7C_macOS-blue) ![Static Badge](https://img.shields.io/badge/Architecture-x86__64_%7C_ARM__64-blue) ![PyPI - Python Version](https://img.shields.io/pypi/pyversions/cengal-light) ![Static Badge](https://img.shields.io/badge/PyPy-3.8_%7C_3.9_%7C_3.10-blue) ![PyPI - Implementation](https://img.shields.io/pypi/implementation/cengal-light) 

![GitHub License](https://img.shields.io/github/license/FI-Mihej/InterProcessPyObjects?color=darkgreen) ![Static Badge](https://img.shields.io/badge/API_status-Stable-darkgreen)

# !!! A placeholder to preserve the name. The release of the project is expected very soon.

# CengalPolyBuild: A Comprehensive and Hackable Build System for Multilingual Python Packages

Our build system offers an automatic, customizable framework tailored for Python packages that incorporate modules in various programming languages. It is specifically designed to support Cython (including automatic conversion from Python to Cython), C/C++, Objective-C, Go, and Nim, with ongoing expansions to include additional languages.

Key Features:

* Automatic Compilation: Seamlessly compiles your code and gathers binary artifacts to integrate into your Python wheel.
* Module Management: Provides templates for easy management of project modules. You can add, rename, or move modules within the project tree effortlessly.
* License Management: Automates the download of license texts based on specified names and inserts license headers directly into your source files.
* Version Management: Facilitates the tracking and updating of version numbers in your sources, ensuring consistency across your project.

This build system is designed to simplify the development process, enhance productivity, and ensure your project adheres to licensing and versioning standards effectively.

# Based on [Cengal](https://github.com/FI-Mihej/Cengal)

This is a stand-alone package for a specific Cengal module. Package is designed to offer users the ability to install specific Cengal functionality without the burden of the library's full set of dependencies.

The core of this approach lies in our 'cengal-light' package, which houses both Python and compiled Cengal modules. The 'cengal' package itself serves as a lightweight shell, devoid of its own modules, but dependent on 'cengal-light[full]' for a complete Cengal library installation with all required dependencies.

An equivalent import:
```python
```

Cengal library can be installed by:

```bash
pip install cengal
```

https://github.com/FI-Mihej/Cengal

https://pypi.org/project/cengal/


# Projects using Cengal

* [CengalPolyBuild](https://github.com/FI-Mihej/CengalPolyBuild) - A Comprehensive and Hackable Build System for Multilingual Python Packages: Cython (including automatic conversion from Python to Cython), C/C++, Objective-C, Go, and Nim, with ongoing expansions to include additional languages. (Planned to be released soon) 
* [InterProcessPyObjects](https://github.com/FI-Mihej/InterProcessPyObjects) - High-performance package delivers blazing-fast inter-process communication through shared memory, enabling Python objects to be shared across processes with exceptional efficiency. 
* [cengal_app_dir_path_finder](https://github.com/FI-Mihej/cengal_app_dir_path_finder) - A Python module offering a unified API for easy retrieval of OS-specific application directories, enhancing data management across Windows, Linux, and macOS 
* [cengal_cpu_info](https://github.com/FI-Mihej/cengal_cpu_info) - Extended, cached CPU info with consistent output format.
* [cengal_memory_barriers](https://github.com/FI-Mihej/cengal_memory_barriers) - Fast crossplatform memory barriers for Python.
* [flet_async](https://github.com/FI-Mihej/flet_async) - wrapper which makes [Flet](https://github.com/flet-dev/flet) async and brings booth Cengal.coroutines and asyncio to Flet (Flutter based UI)
* [justpy_containers](https://github.com/FI-Mihej/justpy_containers) - wrapper around [JustPy](https://github.com/justpy-org/justpy) in order to bring more security and more production-needed features to JustPy (VueJS based UI)
* [Bensbach](https://github.com/FI-Mihej/Bensbach) - decompiler from Unreal Engine 3 bytecode to a Lisp-like script and compiler back to Unreal Engine 3 bytecode. Made for a game modding purposes
* [Realistic-Damage-Model-mod-for-Long-War](https://github.com/FI-Mihej/Realistic-Damage-Model-mod-for-Long-War) - Mod for both the original XCOM:EW and the mod Long War. Was made with a Bensbach, which was made with Cengal
* [SmartCATaloguer.com](http://www.smartcataloguer.com/index.html) - TagDB based catalog of images (tags), music albums (genre tags) and apps (categories)

# License

Copyright © 2012-2024 ButenkoMS. All rights reserved.

Licensed under the Apache License, Version 2.0.
