<h1>Image Captioning with BLIP and Gradio</h1>

<p>This project is an AI-powered image captioning tool developed using Python and the Gradio framework. It leverages the BLIP model from Hugging Face to generate captions for images. The user-friendly Gradio interface allows users to upload images and receive AI-generated captions.</p>

<h2>Features</h2>
<ul>
    <li><strong>Image Upload</strong>: Upload any image through the Gradio interface.</li>
    <li><strong>AI-Generated Captions</strong>: Automatically generate captions using the BLIP model from Hugging Face.</li>
    <li><strong>Easy-to-Use Interface</strong>: Simple, web-based UI for image captioning.</li>
</ul>

<h2>Project Overview</h2>
<p>This image captioning tool is designed to provide a smooth and intuitive experience for generating captions from images. By leveraging the BLIP model, it ensures high-quality and context-aware captions.</p>

<h3>Technologies Used</h3>
<ul>
    <li><strong>Python</strong>: The primary programming language used for backend logic.</li>
    <li><strong>Gradio</strong>: For building the user interface that allows image uploads and displays generated captions.</li>
    <li><strong>Hugging Face BLIP</strong>: Pre-trained model for generating captions from images.</li>
    <li><strong>Pillow</strong>: Used for handling image operations in Python.</li>
</ul>

<h2>Installation</h2>
<ol>
    <li><strong>Clone the repository</strong>:
        <pre><code>git clone https://github.com/RikGanguli/Image-Captioning-System.git
cd Image-Captioning-System
        </code></pre>
    </li>
    <li><strong>Install required dependencies</strong>:
        <p>Make sure you have Python installed. Then, install the required Python packages using:</p>
        <pre><code>pip install -r requirements.txt</code></pre>
        <p><strong>Required libraries</strong>:</p>
        <ul>
            <li>gradio</li>
            <li>transformers</li>
            <li>Pillow</li>
            <li>Numpy</li>
        </ul>
    </li>
    <li><strong>Run the application</strong>:
        <p>After installing the dependencies, run the Gradio application:</p>
        <pre><code>python image_captioning.py</code></pre>
    </li>
    <li><strong>Access the application</strong>:
        <p>The Gradio interface will be launched, and you can access it via your browser at <code>http://127.0.0.1:7860/</code>.</p>
    </li>
</ol>

<h2>Usage</h2>
<ol>
    <li>Upload an image using the Gradio UI.</li>
    <li>Wait for the BLIP model to generate a caption.</li>
    <li>The AI-generated caption will be displayed below the image.</li>
</ol>

<h2>Credits</h2>
<p>Developed by <strong></strong>Rik Ganguli Biswas</strong> as a part of the IBM AI Developer Professional Certificate</p>

