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

## Qt Creator

For the part of the course that will use the LUNARC resources we will use the development environment Qt Creator as well as the Qt library. You can download these tools on Linux as well, to get familiar with them. Download Qt and Qt Creator here:

[Download Qt Creator and Qt](https://www1.qt.io/offline-installers/)

To build a C++ program in Qt Creator:

 1. Start Qt Creator
 2. Select **File/New File or Project...**
 3. Under **Projects**, select **Non-Qt Project** and **Plain C++ Application**
 4. Click **Choose..**
 5. Select a name for the project.
 6. Click **Next**
 7. Click **Next**
 8. Click **Next**
 9. Click **Finish**

This will create a template C++ application.

Build and run the application by selecting **Build/Run**. Output from the application will be shown in the lower part of the window.

# Windows

On Windows there are several options for a C++ development environment. An easy solution is to download Visual Studio 2017 Community edition from:

[Download Visual Studio 2017 Community](https://visualstudio.microsoft.com/vs/community/)

Make sure to select "Desktop Development with C++" when installing the package

To build a C++ program in Visual Studio:

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

## Qt Creator

For the part of the course that will use the LUNARC resources we will use the development environment Qt Creator as well as the Qt library. You can download these tools on Windows as well, to get familiar with them. Download Qt and Qt Creator here:

[Download Qt Creator and Qt](https://www1.qt.io/offline-installers/)

To build a C++ program in Qt Creator:

 1. Start Qt Creator
 2. Select **File/New File or Project...**
 3. Under **Projects**, select **Non-Qt Project** and **Plain C++ Application**
 4. Click **Choose..**
 5. Select a name for the project.
 6. Click **Next**
 7. Click **Next**
 8. Click **Next**
 9. Click **Finish**

This will create a template C++ application.

Build and run the application by selecting **Build/Run**. Output from the application will be shown in the lower part of the window.

# Max OS X

To use C++ under Mac OS X you need to install Xcode, which is found in the Mac OS X app store. 

## Qt Creator

For the part of the course that will use the LUNARC resources we will use the development environment Qt Creator as well as the Qt library. You can download these tools on Mac OS X as well, to get familiar with them. Download Qt and Qt Creator here:

[Download Qt Creator and Qt](https://www1.qt.io/offline-installers/)

To build a C++ program in Qt Creator:

 1. Start Qt Creator
 2. Select **File/New File or Project...**
 3. Under **Projects**, select **Non-Qt Project** and **Plain C++ Application**
 4. Click **Choose..**
 5. Select a name for the project.
 6. Click **Next**
 7. Click **Next**
 8. Click **Next**
 9. Click **Finish**

This will create a template C++ application.

Build and run the application by selecting **Build/Run**. Output from the application will be shown in the lower part of the window.
