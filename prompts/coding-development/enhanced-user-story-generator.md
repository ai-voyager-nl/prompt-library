# 📌 Enhanced User Story Generator

**🎯 Goal:** Generate complete, context-driven user stories with optional customizations for Agile planning, including stakeholder roles, effort estimation, output format, and tone.

**💬 Full Prompt:**  
> Given the following context:  
>   
> [Insert context here]  
>   
> Create a complete user story that includes the following elements:  
> 1. **Title**: A concise, descriptive title for the story.  
> 2. **Description**: Use the format — "As a [type of user], I want to [goal or task] so that [reason or benefit]."  
> 3. **Acceptance Criteria**: A list of specific, testable criteria required for the story to be considered complete.  
> 4. **Additional Notes**: Include any supporting context, constraints, or technical considerations.  
>   
> **Optional Enhancements (if specified):**  
> - **Role Perspective**: Customize the story from a particular stakeholder’s view (e.g., product owner, backend developer).  
> - **Effort Estimation**: Include effort in story points (e.g., 3 points).  
> - **Business Value**: Assign a value label such as Low / Medium / High.  
> - **Priority Level**: Indicate urgency (e.g., Must-have, Should-have).  
> - **Output Format**: Choose between Markdown (default), plain text, or JIRA-friendly format.  
> - **Tone Setting**: Choose the level of technicality (e.g., beginner-friendly, technical).  
> - **Iteration Mode**: Allow feedback and refinement if the story is too broad or unclear.

**⚙️ Type:** Zero-shot  
**🗂️ Category:** coding-development  
**🧠 Tags:** agile, product management, story-points, markdown, user-centered, refinement-loop

**✅ What It Gets Right:**  
- Highly customizable and adaptable for Agile workflows  
- Produces standardized, useful output across different teams and roles  
- Built-in ability to adjust complexity, tone, and output format  
- Encourages iteration and refinement  

**🧪 Improvements:**  
- Could include a “template mode” to generate blank user story formats  
- Add multi-user story generation from a single context  
- Include a checklist at the end for self-validation  

**🛠️ Output Sample:**  
> **Context**: A new feature is being developed for an e-commerce website that allows users to save items to a Wishlist.  
>  
> **User Story**  
> **Title**: Wishlist Feature  
> **Description**: As a registered user, I want to save items to a wish list so that I can easily find and purchase them later.  
> **Acceptance Criteria**:  
> 1. The wish list should be accessible from the user's account page.  
> 2. Users should be able to add and remove items from the wish list.  
> 3. The system should notify users if an item in their wish list goes on sale.  
> **Additional Notes**:  
> - Wishlist must persist across user sessions.  
> - The feature should be responsive on mobile devices.  
> **Effort Estimation**: 3 points  
> **Business Value**: High  
> **Priority**: Must-have  
> **Tone**: Beginner-friendly  
> **Format**: Markdown

**📓 Notes:**  
- Works best with temperature 0.3–0.6 for structured logical output.  
- Can be used in sprint planning, backlog grooming, or as a JIRA integration trigger.
