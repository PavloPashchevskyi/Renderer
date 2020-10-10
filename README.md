1. clone git repository:

    git clone https://github.com/PavloPashchevskyi/Renderer.git

2. In properties of your linker`s input, append the following relative path

    ../Lib/vulkan/x64/vulkan-1.lib

    to the additional dependencies. If you are going to build the Project for x86 architecture, your relative path should be

    ../Lib/vulkan/x86/vulkan-1.lib

3. In the common properties of C/C++ compiler, append the following relative path
    
    ../Include

 to the additional directories with include files. It should be done for processor architecture(s) you are going to build the Project.

4. Build the Project for your OS

5. Execute the Project in your OS and enjoy!