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

Make sure to select "Desktop Development with C++" when installing the package.

We will use the Qt Creator as the development environment, with the Microsoft Compilers.

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

## Windows Subsystem for Linux

In Windows there is also an option of using a Linux based development environment without any virtual machines. To use this install the "Ubuntu 18.04 LTS" App from the Windows App Store. This will add a command line based Linux environment. Follow the instructions for Linux on how to install software.

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
