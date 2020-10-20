## Table of Contents

- [Discription](#Discription)
- [Installation](#Installation)
- [Plugins](#Plugins)
- [Demo](#Demo)
- [License](#License)

---

### Discription
[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

SSPackage is a software which is used to capture screenshot of active/current window and is pretty useful when we have to capture multiple screenshot for different reason.

---

### Installation

SSPackage is supported only on windows platform and has been tested on Windows 10  
SSPackage doesn't require installation, you can download it directly from [GitHub](https://github.com/Rahulsingh190792/SSPackage) and start using it.

---

### Plugins

SSPackage is currently not extended with plugins but we might come up with few extended plugins in future.
Though we do not have any plugins still few changes can be made by the user. The changes needs to be made on properties.configuration file

| Keys | Meaning | Default Key |
| ------ | ------ | ------ |
| KeyScreenshot | It is the control key which is used to capure screenshot | ctrl+q |
| KeyAbort | Once your activity is completed and you want to close the application | ctrl+m |
| Width & Height | You can define the size of the Screenshot |  |
| text | This parameter defines what message should be displayed below the screenshot | fig- |

---

### Demo
1. Downlaod the [file](https://github.com/Rahulsingh190792/SSPackage) property.config and SSPackage from git and place them in any directory.

<!-- ![](SShot/SShot1.JPG) -->
<img src="SShot/SShot1.JPG" width=600 >

2. launch the app by double clicking SSPackage.exe, a blank  window will be displayed 

<!-- ![](SShot/SShot2.png)  -->
<img src="SShot/SShot2.png" width=600 >

3. After few second file explorer window will open, please mention the file name with extension (screenshot will be saved in this file) and click save.
Note: If it take too much time to launch the explorer window, you may also launch the SSPackage.exe directly from the Package directory.(It is the faster approach)  

<!-- ![](SShot/SShot3.JPG)  -->
<img src="SShot/SShot3.JPG" width=600 >
4. Now you can select the window which is to be captured and press cntl+q (this is set by default and can be changed, refer the Plugins section of README.md). You are done!!!!

5. Once you have captured the screenshot you can press cntl+m to save and exit the application.
Below is the image from the SShot.docx.

<!-- ![](SShot/SShot4.png)  -->
<img src="SShot/SShot4.png" width=600 >

---

## License

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](http://opensource.org/licenses/mit-license.php)**