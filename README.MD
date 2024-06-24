# Simple File Uploader Utility

## Overview

The **Simple File Uploader Utility** is designed to streamline the process of transferring files from your phone to your Ubuntu machine. This utility provides a quick and efficient way to set up an HTTP server that allows file uploads directly to a specified directory on your Ubuntu system.

## Features

- **Easy setup**: Quickly start an HTTP server on your desired port.
- **Customizable file destination**: Specify the directory where the files should be uploaded.
- **Cross-platform compatibility**: Transfer files from any device that supports HTTP file uploads, such as smartphones.

## Getting Started

To use this utility, simply execute the script with the desired directory and port number as arguments. Here’s how you can start the server:

```bash
./file-uploader -d <location to download files to> -p <port of the HTTP server>
```
### Example Usage

If you want to upload files to '/home/username/uploads' and the server to run on port 8000, you would run:
```bash
./file-uploader -d /home/username/uploads -p 8000
```
## Prerequisites

Ensure that you have Python installed on you machine, as this script is built with Python 3.7

## Installation
#### Clone the Repository
```bash
git clone https://github.com/mohdgazyani235/file-uploader.git
cd file-uploader
```
#### Make the script executable
```bash
chmod +x file-uploader
```
#### Run the script
```bash
./file-uploader.py -d /desired/upload/path -p 8000
```
## Usage
- Open a web browser and navigate to 'http://localhost:<port>'
- Use the upload form to select and upload files to the specific directory


