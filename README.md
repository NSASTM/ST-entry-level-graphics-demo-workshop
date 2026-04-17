# 1. ST entry-level GUIs Demo Workshop <!-- omit from toc -->

- [1.1. Introduction](#11-introduction)
- [1.2. Prerequisites](#12-prerequisites)
  - [1.2.1. Hardware](#121-hardware)
  - [1.2.2. Software](#122-software)
    - [1.2.2.1. TouchGFX Designer](#1221-touchgfx-designer)
    - [1.2.2.2. Microsoft VSCode](#1222-microsoft-vscode)
- [1.3. Sanity Check](#13-sanity-check)
- [1.4. Hands-on](#14-hands-on)

## 1.1. Introduction
You will find in this repository all the material used during the session and the associated collateral to replicate the activities on your own, during the workshop or afterwards.

## 1.2. Prerequisites

### 1.2.1. Hardware

The hardware setup consists in 2 boards:

|[NUCLEO-C5A3ZG](https://www.st.com/en/evaluation-tools/nucleo-c5a3zg.html#sample-buy)|[RVA15MD](https://riverdi.com/product/015-nucleo-64)|
|:---------------:|:--------:|
|<img src="./img/NUCLEO-C5A3ZG.png" width ="250" />|<img src="./img/RVA15MD.png" width ="250" />|

### 1.2.2. Software

#### 1.2.2.1. TouchGFX Designer

The current version is the 4.26.1.

The TouchGFX Designer installer cannot be downloaded in a standalone way, it is included in the TouchGFX expansion pack for STM32CubeMX.

- Download [X-CUBE-TOUCHGFX](https://www.st.com/en/embedded-software/x-cube-touchgfx.html)
- Extract the X-CUBE-TOUCHGFX\4.26.1\Utilities\PC_Software\TouchGFXDesigner\TouchGFX-4.26.1.msi
  ![TouchGFXDesignerInstaller](./img/TouchGFX-Designer_Installation.gif)
- Run the installer and prefer the default installation folder on C:\ drive.
  
#### 1.2.2.2. Microsoft VSCode

- Download and install VSCode from [Visual Studio Code Download](https://code.visualstudio.com/download)
- Install the extension "STM32CubeIDE for VSCode"
  - Open VSCode 
  - Create a new "stm32Cube" profile (recommended)

  ![Create a profile](./img/VSCode-Create_Profile.gif)
  - Open Extensions panel
  - Search for "STM32CubeIDE extension for VSCode"

  ![Install Extension](./img/VSCode-STM32CubeIDE_Extension.gif)
  - Install, dependencies will get installed automatically

## 1.3. Sanity Check
Before starting the lab, let's check that your setup is functional.

- Plug the Riverdi display on the NUCLEO-C5A3ZG morpho connector

  <img src="./img/NUCLEO-C5A3ZG_RVA15MD.png" width ="250" />

- Launch TouchGFX Designer and create an empty project using the NUCLEO-C5A3ZG template
  ![TouchGFX-Create-NUCLEO-C5A-Project](./img/TouchGFX-Create-NUCLEO-C5A-Project.gif)

- Open VSCode, be sure to be set the right Profile and open the project folder
[🔼 Back to top](#Table of contents)

## 1.4. Hands-on



