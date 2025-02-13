# **TMC2 with Fast x265 Encoder from HM**  

This repository contains the **TMC2** software from **MPEG**, integrated with the **fast x265 encoder** based on the **HM (High Efficiency Video Coding Model)** adapted by Eduardo de Figueiredo Costa.  

## **Description**  
**TMC2** (Test Model for Category 2) is a reference model developed by **MPEG** for **projection-based point cloud compression**. This implementation utilizes an optimized **x265 encoder** for experimental testing .  

## **Key Features**  
- Implementation based on **MPEG’s TMC2**.  
- Video encoding using **x265**.  
- **HM is used for decoding**.  
- Compatible with **MPEG standards** for testing and validation.  

## **Requirements**  
- **CMake 3.17+**  
- **GCC / Clang (Linux)**  
- **TMC2 libraries**  

**CMake**
```sh
sudo apt update
sudo apt install cmake
````

## **Software Build System**  
```sh
cd ./V-PCC-X265/dependencies/x265_git/source
mkdir build && cd build
cmake ..
make
```

## **HDRTools Build**  
```sh
git clone https://gitlab.com/standards/HDRTools.git dependencies/HDRTools
cd dependencies/HDRTools/
mkdir build
cd build
cmake .. 
make
```

## **X265 Build**  
```sh
cd ./V-PCC-X265/dependencies/x265_git/source
mkdir build && cd build
cmake ..
make
```
