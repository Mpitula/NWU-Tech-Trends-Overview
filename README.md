# CMPG-323-Overview-37460366
Development of a comprehensive solution for NWU Tech Trends to measure and report the time and cost savings achieved through automation solutions, including the creation of a web API, web application, RPA bot, and detailed reporting tools.
# Repostitory created for each project 
1. CMPG-323-Overview-37460366: Used for project 1
2. CMPG-323-Project-2-37460366: Used for project 2
3. CMPG-323-Project-3-37460366: Used for project 3
4. CMPG-323-Project-4-37460366: Used for project 4
5. CMPG-323-Project-5-37460366: Used for project 5
# Documentation
https://github.com/Mpitula/CMPG-323-Overview-37460366/blob/main/README.md
# Branching Strategy
The branching strategy will follow a basic workflow to guarantee steadiness and clarity:
In each project, the git-flow branching strategy will be used. Gitflow is a branching model that uses different branches to move code from development to production. It's an organized approach that allocates specific roles to various branches and characterizes how and when they should interact. Gitflow is well-suited for collaboration and versatile development and can offer assistance with
1. Reducing time spent merging
2. Maximizing time spent writing code
3. Controlling workflow easily
4. Tracking project evolution
5. Identifying bugs
6. Supporting emergencies
7. Distinguishing between development and production code
# Use of a .gtitgnore File
Each project will have a .gitignore file that specifies files and folders to exclude from version control.
1. File to ensure that unnecessary files are not included in the repositories.
2. File specifies which files and directories should be ignored when committing changes.
4. Ensure that sensitive data such as passwords, API keys, and connection strings are not committed to the repository, protecting them from exposure.
5. Prevent unnecessary files from being tracked by Git, keep the repository clean, and reduce clutter.

Examples:
Build directories (bin/, obj/), Visual Studio files (*.suo, *.user), Eclipse files (.project), and Configure files (appsettings.json) often contain sensitive information.
# Storage of credentials and sensitive information 
1. **Environment Variables**: Store sensitive data such as API keys, database credentials, and secret keys in environment factors. Utilize a `.env` file to oversee these factors locally
2. **Secret Management Tools**: For production environments, utilize secret management tools given by cloud administrations (e.g., AWS Secrets Manager, Azure Key Vault) to store and get to touchy data safely. This lets you dynamically oversee and recover privileged insights without hardcoding them into your codebase.
3. **Encryption**: Encrypt sensitive data before storing it in configuration files or databases. Utilize strong encryption algorithms to protect the information and ensure that only authorized users and systems can decrypt it.
4. **Access Control**:Restrict access to sensitive data to only those who need it. Utilize GitHub's built-in get-to-control features to limit who can see and alter your repositories. Make sure this repository is private and only shared with authorized clients.
5. **Version Control Best Practices**: Never commit sensitive data directly into your version control system. Utilize placeholders or environment variables to handle sensitive information, and guarantee your `.gitignore` file is accurately configured to exclude files that contain sensitive data.

