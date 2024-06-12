# How-to-Verify-CUDA-Installation
# How to Verify CUDA Installation via Command Line

## Description

This tutorial provides step-by-step instructions on how to verify the installation of CUDA on your system using command-line tools. It covers methods for checking CUDA on Linux, Windows, and macOS platforms, ensuring you can confirm the presence and version of CUDA and the associated NVIDIA drivers.

## For Linux:

1. **Check the CUDA version:**
   - Open a terminal and type the following command:
     ```bash
     nvcc --version
     ```
   - If CUDA is installed, this will return the version of the CUDA compiler (nvcc).

2. **Check the NVIDIA driver and CUDA toolkit:**
   - Type the following command:
     ```bash
     nvidia-smi
     ```
   - This command will display the NVIDIA System Management Interface, which shows the GPU information along with the CUDA version that is supported by the driver.

## For Windows:

1. **Check the CUDA version:**
   - Open Command Prompt and type the following command:
     ```cmd
     nvcc --version
     ```
   - This should display the CUDA version if it is installed.

2. **Check the NVIDIA driver and CUDA toolkit:**
   - Open Command Prompt and type:
     ```cmd
     nvidia-smi
     ```
   - This will show the GPU information and the CUDA version.

## For Mac:

macOS does not natively support CUDA, but if you have installed CUDA through a custom setup, you can follow similar steps as for Linux. Note that CUDA support for macOS has been deprecated by NVIDIA.

1. **Check the CUDA version:**
   - Open Terminal and type:
     ```bash
     nvcc --version
     ```

2. **Check the NVIDIA driver and CUDA toolkit:**
   - Type:
     ```bash
     nvidia-smi
     ```

If these commands return information about CUDA, then CUDA is installed on your system. If the commands are not found, it indicates that CUDA is not installed.

