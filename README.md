# YouTube-blogs-generator-using-Gemini
Convert your youtube videos into well structured Blog posts using Gemini PRO. The application also summarises Youtube video in seconds.

## Features
- **Automated Summary Generation**: Quickly generate summaries from YouTube videos by simply providing the video link.
- **Structured Blog Post Creation**: Convert summaries into comprehensive blog posts with sections for Introduction, Key Takeaways, Main Content, and Conclusion.
- **Streamlit Web Interface**: Offers an easy-to-use Streamlit web interface for seamless user interaction.

## Setup
### Prerequisites
- Python 3.6 or later
- Pip package manager

### Installation Instructions
1. Clone the GitHub repository:
   ```
   git clone https://github.com/yourusername/youtube-blog-post-generator.git
   cd youtube-blog-post-generator
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Obtain a Google API Key (for generative AI features):
   - The application's UI provides guidance on obtaining this key.

### How to Run the Application
1. Start the app with Streamlit by running the following command in your terminal:
   ```
   streamlit run app.py
   ```

2. Navigate to the provided local URL (usually http://localhost:8501) in your web browser to access the app.

## How to Use
1. **Input Your Google API Key**: For security, enter your Google API key into the designated field within the app.
2. **Enter a YouTube Video Link**: Paste the URL of the YouTube video you want to convert into a blog post.
3. **Choose Your Action**: Select whether to generate a video summary or convert the video directly into a structured blog post.
