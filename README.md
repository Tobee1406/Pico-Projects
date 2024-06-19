<Img src="/Assets/Img/Raspberry Pi Pico.avif">

# Pico-Projects
Raspberry Pi Pico Projects

![](https://img.shields.io/github/license/Tobee1406/Pico-Projects) ![](https://badges.pufler.dev/visits/Tobee1406/Pico-Projects) ![](https://img.shields.io/github/stars/Tobee1406/Pico-Projects)

## Contents
- [Setup Pico](#setup-pico)
- [Setup Pico W](#setup-pico-w)

# Raspberry Pi Pico/Pico W

[Documentation](https://www.raspberrypi.com/documentation/microcontrollers/raspberry-pi-pico.html)

## Setup Pico
[Pico Setup](https://projects.raspberrypi.org/en/projects/getting-started-with-the-pico/0)

### 1. Connect Pico
Plug your micro USB cable into the port on the left-hand side of the board.

<img src="/Assets/Img/Pico-Top-Plug-v2.png" width="500">

If you need to know the pin numbers for a Raspberry Pi Pico, you can refer to the following diagram.

<img src="/Assets/Img/Pico-R3-Pinout.png" width="500">

### 2. Install Thonny
Go to https://thonny.org/ and download the software.

### 3. Open Thonny
Open Thonny from your application launcher. It should look something like this:

<img src="/Assets/Img/thonny-editor.png" width="500">

### 4. Hello World!
You can use Thonny to write standard Python code. Type the following in the main window, and then click the Run button (you will be asked to save the file).

`print('Hello World!')`

### 5. BOOTSEL
Find the BOOTSEL button on your Raspberry Pi Pico.

<img src="/Assets/Img/Pico-bootsel-1.png" width="500">

Press the BOOTSEL button and hold it while you connect the other end of the micro USB cable to your computer.

<img src="/Assets/Img/plug-in-pico.png" width="500">

### 6. MicroPython (Raspberry Pi Pico)
In the bottom right-hand corner of the Thonny window, you will see the version of Python that you are currently using.

<img src="/Assets/Img/thonny-status-bar-version.png" width="500">

Click on the Python version and choose ‘MicroPython (Raspberry Pi Pico)’:

<img src="/Assets/Img/thonny-micropython-pico-menu.png" width="500">

If you don’t see this option, then check that you have plugged in your Raspberry Pi Pico.

### 7. Firmware
A dialog box will pop up to install the latest version of the MicroPython firmware on your Raspberry Pi Pico.

Click the **Install** button to copy the firmware to your Raspberry Pi Pico.

<img src="/Assets/Img/thonny-install-micropython-pico.png" width="500">

Wait for the installation to complete and click **Close**.

> [!NOTE]
> You don’t need to update the firmware every time you use your Raspberry Pi Pico. Next time, you can just plug it into your computer without pressing the BOOTSEL button.

## Setup Pico W
[Pico W Setup](https://projects.raspberrypi.org/en/projects/get-started-pico-w/1)

### 1. Download
**Download** the latest version of Raspberry Pi Pico W firmware at https://rpf.io/pico-w-firmware.

### 2. Connect Pico W
**Connect** the small end of your micro USB cable to the Raspberry Pi Pico W.
<img src="/Assets/Img/pico-top-plug.png" width="500">

### 3. BOOTSEL
Hold down the **BOOTSEL** button on your Raspberry Pi Pico W.
<img src="/Assets/Img/pico-bootsel.png" width="400">

### 4.  Connect pc
**Connect** the other end to your desktop computer, laptop, or Raspberry Pi.
<img src="/Assets/Img/plug-in-pico.png" width="500">

### 5. File manager
Your file manager should open up, with Raspberry Pi Pico being show as an externally connected drive. Drag and drop the firmware file you downloaded into the file manager. Your Raspberry Pi Pico should disconnect and the file manager will close. 

<img src="/Assets/Img/pico-file_manager.png" width="500">

### 6. Thonny
Open the Thonny editor. If not downloaded, go to https://thonny.org/.

### 7. MicroPython
Look at the text in the bottom right-hand corner of the Thonny editor. It will show you the version of Python that is being used.

If it does not say ‘MicroPython (Raspberry Pi Pico)’ there, then click on the text and select ‘MicroPython (Raspberry Pi Pico)’ from the options.
<img src="/Assets/Img/thonny-select-interpreter.png" width="500">
