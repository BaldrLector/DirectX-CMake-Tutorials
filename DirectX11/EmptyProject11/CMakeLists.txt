

add_compile_definitions(UNICODE _UNICODE)
#include_directories("$ENV{DXSDK_DIR}/Include")
link_directories("$ENV{DXSDK_DIR}/Lib/x64")
include_directories(../../libs/DXUT/Core)
include_directories(../../libs/DXUT/Optional)
add_executable(EmptyProject11 WIN32 EmptyProject11.cpp resource.h)


target_link_libraries(
        EmptyProject11 d3dcompiler d3dx11d d3dx9d dxerr
        dxguid winmm
        comctl32 kernel32
        user32 gdi32
        winspool comdlg32
        advapi32 shell32
        ole32 oleaut32
        uuid odbc32
        odbccp32 d3d11 d3dcompiler
        d3dx11d d3dx9d dxerr
        dxguid winmm comctl32
        DXUT DXUTOpt legacy_stdio_definitions
)