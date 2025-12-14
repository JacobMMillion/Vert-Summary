# Vert - Job Description

## Full-Stack Developer / Software Engineer | Vert

**Built and maintained a comprehensive influencer marketing management platform** that automated data collection, analysis, and operations for multiple mobile applications. The system integrated social media scraping, database management, support automations, and business intelligence dashboards.

### Key Accomplishments:

**Full-Stack Web Application Development**
- Architected and developed a Flask-based web application with 50+ routes and features, serving as the central hub for influencer marketing operations
- Implemented role-based authentication system with tiered access controls (admin, limited, sourcing hub users)
- Built interactive dashboards with real-time data visualization for engagement metrics, cost analysis, and performance tracking
- Designed responsive UI templates using HTML/CSS/JavaScript for 30+ distinct pages including analytics, quality control, and reporting interfaces

**Data Automation & Integration**
- Developed automated daily scraping system using Apify API to collect social media metrics (views, likes, comments, shares) from TikTok, Instagram, and YouTube across 100+ influencer accounts
- Implemented concurrent processing with thread pools to handle multiple Google Sheets tabs simultaneously, reducing processing time by 70%
- Built robust error handling with exponential backoff retry logic to manage API rate limits and transient failures
- Created scheduled jobs (Heroku cron) to maintain real-time data synchronization across platforms

**Database Architecture & Management**
- Designed and maintained PostgreSQL database schema with 15+ tables including video metrics, payment records, trial data, and user analytics
- Implemented connection pooling for efficient database resource management
- Built data logging system for historical tracking of engagement metrics, comments, captions, and video metadata
- Created automated data migration and table initialization scripts

**Third-Party API Integrations**
- Integrated Google Sheets API for bidirectional data synchronization with influencer management spreadsheets
- Implemented Google Calendar API integration with OAuth2 for automated contract scheduling and event management
- Built App Store Connect API integration to collect and store customer reviews programmatically
- Integrated Stripe API for payment processing and customer lookup in support workflows

**AI-Powered Automation**
- Developed AI customer support bot using OpenAI GPT API to automatically respond to customer emails via Gmail API
- Implemented intelligent email parsing to extract user IDs, emails, and context from support requests
- Built automated contract processing system using GPT to extract dates and signer information from PDF contracts
- Created AI-powered comment filtering system to identify engagement-related comments from social media posts
- Developed automated summary generation system using OpenAI to create weekly performance reports

**Business Intelligence & Analytics**
- Built comprehensive analytics dashboards tracking daily engagement metrics, trial sign-ups, cost per acquisition, and ROI
- Implemented trial trigger system that detects significant spikes in sign-ups and automatically updates video metrics
- Created payment audit system with monthly aggregation and filtering capabilities for financial tracking
- Developed impact scoring and deal pricing algorithms to evaluate influencer performance
- Built sourcing hub with multi-user collaboration features, role-based permissions, and app-specific access controls

**Quality Control & Operations**
- Developed VA (Virtual Assistant) quality control system for reviewing and auditing influencer content
- Built influencer scraper tool to collect profile statistics (follower counts, median views) with caching to reduce API calls
- Created comment hub for managing and analyzing video comments with video addition/deletion capabilities
- Implemented page visit tracking and analytics for user behavior monitoring

**DevOps & Infrastructure**
- Deployed application to Heroku with Procfile configuration for web and worker processes
- Managed environment variables and secrets using .env files and Heroku config vars
- Implemented caching strategies for trending videos and frequently accessed data
- Built progress tracking system for long-running background jobs with real-time status updates

### Technical Stack:
- **Backend:** Python, Flask, PostgreSQL, psycopg2
- **APIs:** Apify, Google Sheets API, Google Calendar API, Gmail API, App Store Connect API, Stripe API, OpenAI API
- **Frontend:** HTML, CSS, JavaScript, Jinja2 templates
- **Data Processing:** Concurrent.futures, ThreadPoolExecutor, pandas
- **DevOps:** Heroku, Git, environment variable management
- **Libraries:** gspread, PyPDF2, simplegmail, openai, apify-client, pytz

### Impact:
- Automated manual data collection processes, saving 20+ hours per week of manual work
- Enabled real-time tracking of influencer performance across 3 mobile applications
- Improved customer support response time through automated email handling
- Provided data-driven insights for influencer selection and budget allocation decisions
