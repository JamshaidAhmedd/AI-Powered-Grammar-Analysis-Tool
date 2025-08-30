

<h1 align="center">🧠 AI-Powered Grammar Analysis Tool</h1>
<h3 align="center">Leverage AI to Extract Text, Analyze Grammar, and Enhance Content with Visual Annotations</h3>

<p align="center">
  <img alt="Tech Stack" src="https://img.shields.io/badge/Tech%20Stack-Next.js%20|%20Azure%20Vision%20API%20|%20Google%20Gemini%20AI-blue?style=flat&labelColor=000000">
  <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen?labelColor=000000">
  <img alt="Version" src="https://img.shields.io/badge/version-1.0.0-brightgreen?labelColor=000000">
</p>

<p align="center">
  <a href="#-about-the-project">About</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-features">Features</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-getting-started">Getting Started</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tech-stack">Tech Stack</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-screenshots">Screenshots</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-license">License</a>
</p>

---

## 🖼️ Project Screenshots

Check out the visual preview of your AI-Powered Grammar Analysis Tool:

* **Home Page**:
  ![Home](AI-Powered%20Grammar%20Analysis%20Tool/Home.png)

  * The **Home Page** serves as the introduction to the platform, where users can upload images for text extraction and analysis.

* **Result Screen 1**:
  ![Result Screen1](AI-Powered%20Grammar%20Analysis%20Tool/Result%20Screen1.png)

  * This is the first result screen showcasing the extracted text after OCR processing.

* **Result Screen 2**:
  ![Result Screen2](AI-Powered%20Grammar%20Analysis%20Tool/Result%20Screen2.png)

  * **Result Screen 2** highlights grammar and spelling issues identified by the AI.

* **Result Screen 3**:
  ![Result Screen3](AI-Powered%20Grammar%20Analysis%20Tool/Result%20Screen3.png)

  * This screen demonstrates the annotated image with highlighted errors.

* **Testing Dashboard**:
  ![Testing Dashboard](AI-Powered%20Grammar%20Analysis%20Tool/testing%20DashBoard.png)

  * The **Testing Dashboard** allows users to test the Azure Vision API integration and run the full analysis pipeline with ease.

---

## 💡 About the Project

The **AI-Powered Grammar Analysis Tool** uses cutting-edge AI technologies to extract text from images, analyze grammar, and provide detailed corrections. This tool is perfect for anyone needing precise text recognition and grammar feedback on scanned documents, handwritten notes, or screenshots.

### Features:

* 🧠 **Advanced Text Extraction**: Extract text from images with high accuracy using **Azure Vision API**.
* 💬 **AI Grammar Analysis**: Leverage **Google Gemini AI** to identify grammar, spelling, and syntactic errors.
* 🖼️ **Visual Annotations**: Mistakes are highlighted directly on the image with color-coded annotations.
* 🚀 **Fast and Efficient**: Instant text extraction and analysis with a user-friendly interface.
* 💾 **File Management**: Supports both local and Supabase storage for managing images.
* 📊 **Test Your System**: Built-in testing dashboard for verifying the API and analyzing the full pipeline.

---

## ✨ Features

### Core Features:

* 🏷️ **Image Upload**: Upload images in JPG, PNG, or WebP format.
* ⚡ **Real-time OCR**: Extract text from uploaded images using Azure Vision API.
* 📚 **Grammar & Spelling Check**: Get in-depth grammar analysis from Gemini AI.
* ✍️ **Annotated Images**: View errors directly on images with clear visual cues.
* 🔄 **Complete Analysis Pipeline**: From text extraction to grammar analysis and image annotation.

### Admin Features:

* 👩‍💻 **API Testing Dashboard**: Isolate and test Azure API calls and the full analysis pipeline.
* 📊 **Image Management**: Supports both cloud storage (Supabase) and local storage for saving images.

---

## 🚀 Getting Started

### Prerequisites:

Before getting started, ensure you have the following:

1. **Azure Cognitive Services** account for the Vision API
2. **Google Gemini AI** API key
3. **Supabase** account (optional)
4. **Node.js** 18+ and npm/yarn installed

### Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/your-repository-name.git
   cd your-repository-name
   ```

2. **Install Dependencies**:

   ```bash
   npm install
   ```

3. **Configure Environment**:

   * Copy the contents from `env.example` to `.env.local` and add your API keys.

4. **Start the Development Server**:

   ```bash
   npm run dev
   ```

5. **Test the Application**:

   * Open the app at [http://localhost:3000](http://localhost:3000) and start testing the image upload and analysis process.

---

## 🛠️ Tech Stack

* **Frontend**: Next.js, React, TypeScript, Tailwind CSS
* **OCR**: Azure Cognitive Services Vision API
* **AI Analysis**: Google Gemini AI
* **Image Annotation**: Sharp for SVG overlay generation
* **Storage**: Supabase (optional) or local file system for storing images
* **Validation**: Zod for API contract validation

---

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🤝 Contact & Support

For any inquiries, issues, or feedback, feel free to join the community or contact support via the platform's contact page.

**Start analyzing today and enhance your content with AI-powered grammar analysis!** 🚀

---

