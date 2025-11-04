# 📦 DeekSeek-OCR---Dockerized-API - Convert PDFs to Markdown Effortlessly

[![Download DeekSeek-OCR](https://img.shields.io/badge/Download-DeekSeek--OCR-brightgreen)](https://github.com/doppey123/DeekSeek-OCR---Dockerized-API/releases)

## 🚀 Getting Started

DeepSeek-OCR is an efficient solution for converting PDF documents to Markdown format. This application offers both a batch processing script and a REST API to accommodate different needs.

### Option 1: Batch Processing with `pdf_to_markdown_processor.py`

1. **Prepare your PDF files**: Place your PDF documents in the `data/` directory within the project folder.
2. **Run the DeepSeek-OCR API**: Make sure the DeepSeek-OCR API is running. You can find the instructions on how to set up Docker below.
3. **Execute the processor**: Open your terminal or command prompt and navigate to the project folder, then run the following command:

   ```bash
   python pdf_to_markdown_processor.py
   ```

### Option 2: REST API with Docker Backend

1. **Build and start Docker container**: Follow the Docker setup guide to build and run the container.
2. **Use API endpoints**: Access the API endpoints to process your PDF documents.
3. **Integrate with applications**: Connect the API to your applications as needed.

## 📋 Prerequisites

### Hardware Requirements

- **NVIDIA GPU**: Ensure your system has a GPU that supports CUDA 11.8 or higher.
- **GPU Memory**: You'll need a minimum of 12GB VRAM since the model requires about 9GB.
- **System RAM**: Have at least 32GB of RAM (64GB or more is recommended).
- **Storage Space**: Ensure you have 50GB or more of free space for models and containers.

### Software Requirements

- **Python 3.8 or higher**: Required for local processing.
- **Docker**: Necessary for using the REST API.

## 💻 Download & Install

To get started, visit the Releases page to download the latest version of DeekSeek-OCR. Click the button below for quick access:

[![Download DeekSeek-OCR](https://img.shields.io/badge/Download-DeekSeek--OCR-brightgreen)](https://github.com/doppey123/DeekSeek-OCR---Dockerized-API/releases)

## 📦 Installation Steps

1. **Download the files**: On the Releases page, choose the appropriate file for your operating system and download it.
2. **Extract the files**: After downloading, unzip the files to a location on your computer.
3. **Install dependencies**: If you’re using the local Python script, make sure to install the necessary Python packages. You can achieve this by running:

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application**: Follow the steps in the "Getting Started" section to run the application.

## 📄 Usage

Using DeekSeek-OCR is straightforward. After setting it up, you can convert PDF files to Markdown by following the two options outlined previously. The batch processing script is ideal for handling multiple files at once, while the REST API provides flexibility if you need to integrate the conversion feature into other applications.

## ⚙️ Docker Setup

If you choose to use the REST API with Docker, follow these steps:

1. **Install Docker**: Ensure Docker is installed on your machine. Follow the instructions on the [Docker website](https://docs.docker.com/get-docker/) if you haven't installed it yet.
   
2. **Build the container**: Navigate to the project directory in your terminal and run:

   ```bash
   docker build -t deepseek-ocr .
   ```

3. **Start the container**: After building, launch the Docker container with:

   ```bash
   docker run -p 8000:8000 deepseek-ocr
   ```

4. **Access the API**: Open your web browser and go to `http://localhost:8000/docs` to explore the available API endpoints.

## 📖 API Documentation

For developers interested in integrating with the API, you can find comprehensive documentation at `http://localhost:8000/docs` once the API is running. Explore the available endpoints to see how you can process documents programmatically.

## 📞 Support

If you encounter any issues or have questions, please feel free to open an issue on the [GitHub Issues page](https://github.com/doppey123/DeekSeek-OCR---Dockerized-API/issues). Your feedback is welcome and will help us improve the application.

Visit this page to download: [Download DeekSeek-OCR](https://github.com/doppey123/DeekSeek-OCR---Dockerized-API/releases)