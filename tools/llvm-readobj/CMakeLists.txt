set(LLVM_LINK_COMPONENTS
  DebugInfoCodeView
  Object
  Support
  DebugInfoCodeView
  DebugInfoMSF
  )

add_llvm_tool(llvm-readobj
  ARMWinEHPrinter.cpp
  COFFDumper.cpp
  COFFImportDumper.cpp
  ELFDumper.cpp
  Error.cpp
  llvm-readobj.cpp
  MachODumper.cpp
  ObjDumper.cpp
  WasmDumper.cpp
  Win64EHDumper.cpp
  )
