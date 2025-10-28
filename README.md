# Job-Scraping-Agent-with-Gemini-LLM

 job scraping agent that uses Google's Gemini LLM to extract relevant job information, match it with the user's resume, and export results to Excel. This solution will:

Accept user resume (PDF/DOCX)
Extract skills and experience from the resume
Scrape job listings from multiple sources
Use Gemini to analyze job relevance
Export matching jobs to Excel with title, skills, and application link


# Create project directory
mkdir job-scraper
cd job-scraper

# Create virtual environment
python -m venv venv
venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Create directories
mkdir resumes output

# Create .env file (use Notepad or any text editor)
echo GEMINI_API_KEY=your_actual_api_key_here > .env

# Place your resume in the resumes folder
# Then run the script
python job_scraper.py
