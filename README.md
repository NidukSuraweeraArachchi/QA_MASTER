# Web Development Backend

## Environment Variables

Before running the application, you need to set up the following environment variables:

### Jira Configuration
```
JIRA_BASE_URL=your-jira-instance-url
JIRA_EMAIL=your-jira-email
JIRA_API_TOKEN=your-jira-api-token
JIRA_PROJECT_KEY=your-project-key
```

### Application Configuration
Create a `.env` file in the root directory and add your configuration:

```env
# Jira Settings
JIRA_BASE_URL=https://your-instance.atlassian.net
JIRA_EMAIL=your-email@example.com
JIRA_API_TOKEN=your-api-token
JIRA_PROJECT_KEY=PROJECT
```

**Note: Never commit your `.env` file or actual API tokens to version control.**