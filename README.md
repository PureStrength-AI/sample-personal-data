# LinkedIn Easy Apply Automation Application

This application streamlines the process of applying for jobs on LinkedIn by automating the submission of applications based on user-defined criteria and personal data.
Key Files to Edit Before Running the Application

## config.yaml

This YAML file is the primary configuration file for the application. It contains important settings that the application uses to run correctly. You should edit this file to set up:

    Credentials: Your LinkedIn login credentials.
    Application Settings: Preferences for job application submissions, like delay times between applications.
    Other Configurations: Additional parameters that control the application's behavior.

## job_filters.md

The job_filters.md file allows you to define the criteria for job searches. In this file, you can specify:

    Keywords: Keywords to use in the LinkedIn job search.
    Locations: Desired locations for job listings.
    Job Types: Types of jobs you are interested in (full-time, part-time, etc.).
    Other Filters: Any additional filters LinkedIn offers, like industry or experience level.

## personal_data.md

This markdown file contains your personal data that will be used in job applications. Ensure you fill out:

    Personal Information: Your name, address, contact information.
    Professional Summary: A brief professional introduction or summary.
    Skills and Qualifications: List of your skills and qualifications relevant to the jobs you are applying for.

Other Files

sample-cover-letter.pdf and plain_text_cover_letter.md: These files contain your cover letter. The PDF is for visual formatting, and the markdown file is a plain text version.

sample-resume.pdf and plain_text_resume.md: Similar to the cover letter files, these contain your resume. Ensure both the PDF and markdown versions are up to date.


## How to Use

Edit Configuration Files: Update config.yaml, job_filters.md, and personal_data.md with your information and preferences.

Update Resume and Cover Letter: Ensure your resume and cover letter are current in both PDF and markdown formats. Make sure the name of the `.pdf` files still have the work `resume` and `cover-letter` in them. 