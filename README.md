# OptiCareer - AI-Powered Job Search Optimization

## Overview

OptiCareer is a multi-agent AI system that maximizes job search effectiveness by providing intelligent profile optimization, job matching, networking strategies, and career progression insights. The system leverages LinkedIn data through MCP server integration to deliver personalized recommendations and actionable insights for job seekers.

## Key Features

### Phase 1: Core Job Intelligence & Profile Analysis
- **Job Search & Analysis**: Deep company/position analysis and job matching
- **Profile Optimization**: AI-powered LinkedIn profile enhancement recommendations
- **Skills Gap Identification**: Analyze missing skills for target roles
- **Intelligent Job Ranking**: Personalized job opportunity scoring

### Phase 2: Enhanced Strategic Features
- **Network Strategy**: Optimal networking paths and connection strategies
- **Career Progression Analysis**: Career path insights and timeline predictions
- **Content Strategy**: LinkedIn engagement and thought leadership suggestions
- **Application Timing**: Optimal timing for applications and outreach

## Technology Stack

- **Agent Framework**: OpenAI Agent SDK with multi-agent architecture
- **Data Integration**: LinkedIn MCP Server (stickerdaniel/linkedin-mcp-server)
- **AI Models**: OpenAI GPT-4 and Claude APIs
- **Web Automation**: ChromeDriver for browser automation
- **Backend**: FastAPI
- **Frontend**: React/Next.js
- **Data Protocol**: MCP (Model Context Protocol)

## Multi-Agent Architecture

### Core Agents (Phase 1)
- **Job Intelligence Agent**: Scrapes job postings, analyzes companies, provides application insights
- **Profile Optimization Agent**: Compares profiles with successful peers, suggests improvements
- **Skills Gap Agent**: Identifies missing skills and recommends learning paths

### Advanced Agents (Phase 2)
- **Network Strategy Agent**: Optimizes networking and connection strategies
- **Content Strategy Agent**: Suggests LinkedIn posts and engagement tactics
- **Career Progression Analyzer**: Tracks career paths and provides salary insights
- **Application Timing Agent**: Predicts optimal application and outreach timing

## Installation

### Prerequisites
- Node.js 18+
- Python 3.8+
- ChromeDriver
- OpenAI API key
- Claude API key

### Setup
```bash
# Clone the repository
git clone [repository-url]
cd opticareer

# Install dependencies
npm install
pip install -r requirements.txt

# Set up environment variables
cp .env.example .env
# Add your API keys and configuration

# Set up LinkedIn MCP server
# Follow LinkedIn MCP server setup instructions

# Run the application
npm run dev
```

## Usage

### User Journey
1. **Connect LinkedIn**: Securely connect your LinkedIn credentials
2. **Profile Analysis**: System analyzes your current profile and preferences
3. **Dashboard Review**: View personalized insights across all recommendations
4. **Take Action**: Follow specific recommendations for profile optimization, job matches, and networking
5. **Track Progress**: Monitor improvements and receive ongoing updates

### Key Capabilities
- Profile strength assessment and optimization
- Job matching with relevance scoring
- Skills gap analysis and learning recommendations
- Company research and culture insights
- Network analysis and connection strategies

## Performance Metrics

- **Profile Optimization Score**: Improvement in profile completeness and keyword relevance
- **Job Match Quality**: Relevance score of recommended positions
- **Skills Gap Accuracy**: Precision of identified skill gaps vs. job requirements
- **Response Time**: Average time for agent analysis (target: <30 seconds)

## Development Timeline

### Week 1
- LinkedIn MCP server setup and integration
- Basic Job Intelligence Agent implementation
- Simple web interface for job search

### Week 2
- Profile Intelligence Agent development
- Skills gap analysis functionality
- Dashboard with recommendations display

### Week 3+ (Post-bootcamp enhancement)
- Network Strategy Agent implementation
- Career progression analysis
- Advanced matching algorithms

## Safety & Ethics

- Respects LinkedIn's terms of service
- Implements ethical scraping practices
- Ensures user data privacy and consent
- Provides transparent AI recommendations

## Risk Mitigation

- **LinkedIn Rate Limiting**: Intelligent request throttling and caching
- **Data Privacy**: Local credential storage and user data encryption
- **Cost Management**: Daily spending limits and efficient model usage
- **Scraping Reliability**: Fallback mechanisms for failed requests

## Contributing

[Contributing guidelines to be added]

## License

[License information to be added]

## Support

[Support information to be added] 