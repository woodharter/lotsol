# lotsol

This is just a project of LLM experiments I've been working on. Simple things.

## resume_cover_builder.ipynb

### Overview

This is a notebook that generates and AI readable resume and a cover letter. I finally published it when I mentioned the resume building I had been using to job hunt to a friend. This current job market (Fall/Winter 2024) has been absolutely terrible. Hundreds of applications all denied with souless emails, so I theorized that AI was reading the emails and doing the filtering so why not use AI to create a resume to be read by AI.That is the precised question posed to the AI 

> "_You are highly skilled at resume writing. Your job is to create the best resume for AI to understand and read._"

### Setup

This is a python notebook, you'll have to create a _.env_ file in the same folder with the Anthropic token for your account. You only need to set this once and the notebook will read it each time. The _.env_ file will look something like this.

.env

> ANTHROPIC_API_KEY="sk-ant-api03-pcod6mAxe3v7NPbGkM9Ir5ADeijaDe6DAE"

The third cell is where you fill in (copy/paste) the information on the job you are looking for. I had multiple jobs I was generating for at the same time and only the last one in that cell will be the one used. The variables are overwritten by the later versions if there are still any.

Fill in company_name, job_title and description. These can all be cut/paste from the job site.

The fourth cell is your information. You really only need to do this once. My resume only has the last few jobs I've had so I added older jobs to this list so the AI had even more background and details on me. This should be the **ENTIRE** picture of your career and **EVERY** skill you have.

Fill in overview, skills, experience and education.

### Run

Run the notebook until the 8th cell at which point it creates a docx file with the name of the company you are applying to.

You can stop there. The next section generates a cover letter, but I think those need a lot more work. Your mileage will vary.

I hope this helps you someone. Let me know.