## QUICK SETUP TO USE
# Download section
1. GLFW (Graphics Library Framework) - A library that allows the creation and management of windows with OpenGL contexts. It also handles keyboard, mouse, joystick and time input. [Link](https://www.glfw.org/download)
2. GLEW (OpenGL Extension Wrangler Library) - A cross-platform open-source C/C++ extension loading library. GLEW provides efficient run-time mechanisms for determining which OpenGL extensions are supported on the target platform. [Link](https://glew.sourceforge.net/)

# Setup in VS
1. Configuration -> All Platform
2. In General add Two Package that just download add the directory to the 'Additional Include Directory'
3. In Linker General Add directory to the .dll  file (Release/Win32 for GLEW and lib-VC20** for GLFW)
4. Add Additional Dependency in Linker (opengl32.lib, glew32.lib, glfw3.lib)
5. Copy glew32.dll file to the Source project folder