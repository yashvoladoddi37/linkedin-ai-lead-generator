# HeyCoach LinkedIn AI Lead Generator

## Project Overview

### The Problem
Early-career engineers in service-based companies (WITCH) struggle to transition to top-tier product companies like MAANG. Traditional career coaching and job searching methods are inefficient and lack personalization.

### Our Solution
HeyCoach's LinkedIn AI Lead Generator is a cutting-edge tool designed to:
- Automate professional networking
- Generate high-quality, personalized connection requests
- Leverage AI to identify and engage potential coaching candidates

## Key Features

### Intelligent Profile Targeting
- Scrape LinkedIn profiles of engineers in service-based companies
- Analyze career transition potential using advanced AI algorithms
- Focus on professionals seeking to move from WITCH to MAANG

### AI-Powered Messaging
- Generate contextually relevant, personalized connection messages
- Understand individual career aspirations
- Create compelling outreach that resonates with early-career professionals

### Automated Lead Generation
- Scale your coaching outreach efficiently
- Reduce manual networking efforts
- Increase conversion rates through intelligent targeting

## Technical Architecture

### Components
- LinkedIn Profile Scraper
- AI-Powered Message Generation
- Intelligent Targeting Algorithm
- OpenAI Integration

### Technologies
- Python
- Selenium
- OpenAI GPT
- LinkedIn API Interaction

## Use Cases

1. **Career Coaching Outreach**
   - Identify potential coaching clients
   - Personalize initial contact
   - Streamline lead generation process

2. **Career Transition Support**
   - Connect with engineers seeking growth
   - Provide targeted career development insights
   - Build a community of ambitious professionals

## Getting Started

### Prerequisites
- LinkedIn Account
- OpenAI API Key
- Python 3.8+

### Installation
```bash
git clone https://github.com/yashvoladoddi37/linkedin-ai-lead-generator.git
cd linkedin-ai-lead-generator
pip install -r requirements.txt
```

### Configuration
Set up environment variables:
```
LINKEDIN_USERNAME=your_username
LINKEDIN_PASSWORD=your_password
OPENAI_API_KEY=your_openai_key
```

### Usage Example
```python
from staffspy import LinkedInAccount

account = LinkedInAccount(
    username='your_linkedin_email',
    password='your_password', 
    openai_api_key='your_openai_key'
)

# Scrape and connect with personalized messages
leads = account.scrape_staff(
    company_name='TCS',  # Target service-based company
    search_term='Software Engineer',
    location='India',
    connect=True,
    send_messages=True
)
```

## Ethical Considerations
- Respect LinkedIn's Terms of Service
- Obtain proper consent
- Maintain professional networking etiquette

## Future Roadmap
- Enhanced AI message personalization
- Multi-platform support
- Advanced analytics dashboard

## Contributing
Contributions are welcome! Please read our contributing guidelines.

## License
MIT License

## Attribution
This project builds upon [StaffSpy](https://github.com/cullenwatson/StaffSpy), an open-source LinkedIn scraping tool.

## Contact
Yash Voladoddi - yashvoladoddi37@gmail.com
Project Link: https://github.com/yashvoladoddi37/linkedin-ai-lead-generator

