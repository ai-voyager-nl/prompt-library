# 📌 Git Branch Name Generator (Generic - Auto Detect Type)

**🎯 Goal:** Automatically generate a clean Git branch name from a task or ticket title by detecting the type of work and applying the correct naming convention.

**💬 Full Prompt:**
> You will be given a development task title or ticket (e.g., from Jira, Trello, or Azure DevOps).  
> Based on the content, decide whether it represents a:
> - **Feature / Enhancement**
> - **Bugfix**
> - **Release candidate**
> - **Hotfix**
>
> Then generate a Git branch name using the appropriate format:
>
> - `feature/ticket-number-kebab-description`  
> - `bugfix/ticket-number-kebab-description`  
> - `release/version-kebab-description`  
> - `hotfix/kebab-description`
>
> **Guidelines:**  
> - Use kebab-case for the description.  
> - Remove special characters and parentheses.  
> - Keep the description short and informative.  
> - Prefix with ticket number or version if relevant.
>
> **Example Input:**  
> `Bug 7890: Fix crash when exporting large CSV`  
> **Output:**  
> `bugfix/7890-export-large-csv-crash`
>
> **Example Input:**  
> `Feature 4567: Add user onboarding wizard to dashboard`  
> **Output:**  
> `feature/4567-onboarding-wizard-dashboard`

**⚙️ Type:** zero-shot  
**🗂️ Category:** coding-development  
**🧠 Tags:** git, branch naming, automation, ticketing, DevOps

**✅ What It Gets Right:**  
- Automatically interprets task type from context  
- Produces clean, standardized output using kebab-case  
- Usable across a variety of project management systems

**🧪 Improvements:**  
- Add support for multiple output formats (`snake_case`, camelCase)  
- Include team/project prefix if specified  
- Add support for parsing full ticket metadata (e.g., fields, labels)

**🛠️ Output Sample:**  
`bugfix/7890-export-large-csv-crash`

**📓 Notes:**  
- Best used at temperature 0.3–0.5 for stable formatting  
- Can be embedded in GitHub bots or DevOps automation pipelines  
- Easily customized for team-specific naming schemes
