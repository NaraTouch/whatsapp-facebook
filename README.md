# Guideline for using whatsapp automation

## Installing Java on Windows

This guide provides step-by-step instructions for installing the Java Development Kit (JDK) on a Windows operating system.

## Step 1: Download from Oracle Website

1. Open your web browser and go to the [Oracle JDK download page](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) (or the version you wish to install).
2. Scroll down to the "JDK Downloads" section.
3. Select the appropriate version for your Windows system:
   - For 64-bit systems, download the **Windows x64 Installer**.
   - For 32-bit systems, download the **Windows x86 Installer**.
4. Click on the download link and accept the license agreement if prompted.

## Step 2: Click Install

1. Once the download is complete, locate the downloaded `.exe` file (usually in your `Downloads` folder).
2. Double-click the installer to start the installation process.
3. Follow the installation wizard:
   - Click **Next** on the welcome screen.
   - Choose the installation path (the default path is usually fine) and click **Next**.
   - Click **Next** again to start the installation.
4. Wait for the installation to complete, then click **Close**.

## Step 3: Configure Environment Variables

1. Right-click on the **Start** button and select **System**.
2. Click on **Advanced system settings** on the left sidebar.
3. In the **System Properties** window, click on the **Environment Variables** button.
4. In the **Environment Variables** window, under **System variables**, find the `Path` variable and select it, then click **Edit**.
5. Click **New** and add the path to the `bin` directory of the JDK installation. For example: C:\Program Files\Java\jdk-11.0.10\bin (Make sure to replace `jdk-11.0.10` with the version you installed.)
6. Click **OK** to close all dialog boxes.

## Step 4: Verify Java Installation

1. Open the **Command Prompt**:
- Press `Win + R`, type `cmd`, and press **Enter**.
2. In the Command Prompt, type the following command and press **Enter**:
```bash
java -version

```
## Finally you can run whatsapp automation by click run.bat inside your download package.
