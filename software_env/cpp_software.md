# Linux

The preferred Linux distribution is Ubuntu 18.04 or higher. The required packages for the course can be installed with the following commands:

    $ sudo apt-get install build-essentials

To make sure the compiler works create the following small C++ program:

    #include <iostream>

    using namespace std;

    int main()
    {
        cout << "Hello, C++" << endl;
        return 0;
    }

Save the file as example.cpp. Compile and run the code with the following commands:

    $ g++ example.cpp -o example
    $ ./example
    Hello, C++

# Windows

On Windows there are several options for a C++ development environment. An easy solution is to download Visual Studio 2017 Community edition from:

[Download Visual Studio 2017 Community](https://visualstudio.microsoft.com/vs/community/)

Make sure to select "Desktop Development with C++" when installing the package

To build a C++ program in Visual Studio. 

 1. Start The Visual Studio development environment
 2. Select **File/New Project...** from the menu.
 3. In the category "Visual C++" select "Windows Console Application"
 4. Give your application a name.
 5. Click **OK**

In the opened file replace the code with:

    #include <iostream>

    using namespace std;

    int main()
    {
        cout << "Hello, C++" << endl;
        return 0;
    }

To build and run the application click **Debug/Start without debugger**


