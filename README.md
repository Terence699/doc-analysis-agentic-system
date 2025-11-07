# AI-Powered Data Analysis & Visualization System

An intelligent data analysis and visualization platform that leverages DeepSeek-OCR and LangChain to automatically process multi-modal documents (PDFs, images, tables) and generate interactive BI reports. Built with FastAPI backend and React frontend.

## 🚀 Key Features

### Multi-Modal Data Processing

- **DeepSeek-OCR Integration**: Advanced OCR for PDFs, images, and complex documents
- **Table & Formula Recognition**: Extracts structured data from financial reports, academic papers, and scanned documents
- **Context-Aware Analysis**: Processes long documents with intelligent chunking and information structuring

### Intelligent Analysis Agents

- **NL2SQL Agent**: Natural language to SQL query conversion for database exploration
- **NL2Code Agent**: Exploratory data analysis with automatic Python code generation
- **Real-time Visualization**: Generates ECharts-based interactive reports with business insights

### Enterprise-Grade Architecture

- **FastAPI Backend**: High-performance async API with LangChain 1.0 integration
- **React + TypeScript Frontend**: Modern UI with real-time chat interface
- **GPU-Optimized Inference**: vLLM-powered DeepSeek-OCR for high-throughput processing
- **Scalable Processing**: Concurrent analysis pipelines with structured data extraction

## 🛠️ Technology Stack

- **Backend**: Python 3.11, FastAPI, LangChain 1.0, vLLM, PyTorch
- **AI Models**: DeepSeek-OCR, DeepSeek Chat, Qwen3
- **Frontend**: React 18, TypeScript, Vite, Tailwind CSS, ECharts
- **Data Processing**: Pandas, NumPy, SQLite, OpenCV
- **Infrastructure**: Docker-ready, GPU acceleration

## 📊 Use Cases

- **Financial Report Analysis**: Automated processing of annual reports and financial statements
- **Academic Research**: Document analysis with formula extraction and summarization
- **Business Intelligence**: Real-time data insights from unstructured documents
- **Data Exploration**: Conversational interface for complex data analysis workflows

## 🔧 Quick Start

1. **Environment Setup**

   ```bash
   conda create -n deepseek_ocr python=3.11
   conda activate deepseek_ocr
   ```
2. **Install Dependencies**

   ```bash
   cd backend/Data_analysis/DeepSeek-OCR-vllm
   pip install -r requirements.txt
   cd ../../../frontend
   npm install
   ```
3. **Configure API Keys**

   - Set up DeepSeek and Qwen API credentials
   - Configure model paths and endpoints
4. **Launch Services**

   ```bash
   # Backend (GPU server)
   python backend_integration_api.py

   # Frontend (dev server)
   npm run dev
   ```

## 📈 Performance Highlights

- **OCR Accuracy**: State-of-the-art performance on OmniDocBench V1.5
- **Processing Speed**: Concurrent analysis with vLLM optimization
- **Scalability**: Handles large documents with intelligent chunking
- **User Experience**: Interactive visualizations with business insights
