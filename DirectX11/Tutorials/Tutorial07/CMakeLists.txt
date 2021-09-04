add_executable(Tutorial07 WIN32 Tutorial07.cpp resource.h)
target_link_libraries(
        Tutorial07
        d3d11 d3dcompiler
        d3dx11d d3dx9d dxerr
        dxguid winmm comctl32
)

