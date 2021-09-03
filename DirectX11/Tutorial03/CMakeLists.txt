add_executable(Tutorial03 WIN32 Tutorial03.cpp resource.h)
target_link_libraries(
        Tutorial03
        d3d11 d3dcompiler
        d3dx11d d3dx9d dxerr
        dxguid winmm comctl32
)

