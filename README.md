## Advanced Data Engineering with Snowflake

#### Scripts from course 

🚀 My Journey into Advanced Data Engineering

This repository documents my progress through the "Advanced Data Engineering with Snowflake" course. It contains all the scripts, notes, and working files I created and used during my learning journey.
What I Learned

Throughout this course, I mastered:

✅ DevOps Practices for Data Pipelines:

    Setting up Snowflake-GitHub integration for version control

    Declarative database object management with CREATE OR ALTER

    Working with feature branches and Pull Requests

    Configuring CI/CD via GitHub Actions for automated deployments

✅ Working with Snowflake CLI:

    Executing snow git execute commands for environment deployment

    Managing multiple environments (staging/production)

✅ Real-World Problem Solving:

    Debugging authentication and access permission issues

    Fixing database name mismatches

    Configuring SSH keys and Personal Access Tokens

    Force-updating repository cache in Snowflake

📁 Repository Structure

The repository follows the course module structure:

    module-1/ — DevOps with Snowflake

        Building and managing data pipelines

        Git integration

        Declarative object management

    module-2/ — Observability in Snowflake

        Pipeline monitoring

        Working with metrics and alerts

Within each module, code is organized by workflow:

    hamburg_weather/pipeline/ — core pipeline scripts

    hamburg_weather/notebooks/ — Snowflake notebooks for development

    hamburg_weather/streamlit/ — Streamlit app for visualization

🔧 How to Use This Repository

If you're taking the same course and want to follow along with the instructor:

    Fork this repository (don't clone directly – you'll want to make your own changes)

    Clone your fork locally:
    ```
        git clone https://github.com/your-username/advanced-data-engineering-snowflake.git
    ```

    Set up Snowflake integration (detailed in Module 1)

    Follow the instructor – all required files are in the corresponding folders

    Important: For exercises using Snowflake CLI, you'll need the repo cloned locally.

🐛 Common Issues & Solutions

During my journey, I ran into several typical problems and found solutions:
Issue	Solution
Database 'WEATHER_SOURCE_LLC_FROSTBYTE' does not exist error	Replace with FROSTBYTE_WEATHERSOURCE in scripts or run ALTER GIT REPOSITORY ... FETCH
Git push failing	Check remote: git remote -v, configure Personal Access Token
GitHub Actions missing secrets	Add SNOWFLAKE_USER, SNOWFLAKE_PASSWORD, SNOWFLAKE_ACCOUNT in Settings → Secrets
📝 Learning Notes

    Module 1 is the most intense – be prepared for integration setup and debugging

    Follow the Marketplace data installation instructions carefully – database naming matters

    Don't hesitate to create feature branches and PRs even in a learning project – it reinforces the skills

🤝 Feedback & Questions

If you spot any errors in the code or have questions about the course, the best place to ask is on Coursera – the instructor and other students can help there.

Happy data engineering! 🎉
