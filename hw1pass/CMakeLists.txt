add_llvm_library(LLVMHW1 MODULE        # Name of the shared library that you will generate
       hw1pass.cpp                     # Your pass
       PLUGIN_TOOL
       opt
)
