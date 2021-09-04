add_executable(Tutorial06 WIN32 Tutorial06.cpp resource.h)
target_link_libraries(
        Tutorial06
        d3d11 d3dcompiler
        d3dx11d d3dx9d dxerr
        dxguid winmm comctl32
)

