---
marp: true
theme: custom-default
paginate: true
footer: 'James Gress | AI Director @ Accenture | https://jmgress.github.io/githubcopilot/'
---
# Use M365 Copilot to Supercharge Your Work

![bg right:40%](img/00-jamesgress.png)

## James Gress
_Advanced Technology Center AI Lead Accenture_


<i class="fa-brands fa-linkedin"></i> LinkedIn: [jamesgress](https://linkedin.com/in/jamesgress/)  
<i class="fa-brands fa-github"></i> GitHub: [jmgress](https://github.com/jmgress)  
<i class="fa-brands fa-x-twitter"></i> X.com: [@jmgress](https://x.com/jmgress)  
<i class="fa-brands fa-meetup"></i> [Tampa Bay Generative AI Meetup](https://www.meetup.com/tampa-bay-generative-ai-meetup/)  

<!-- 
Done 100's of Prototypes
Taken 10 applications to Production ranging from simple RAG to more complex Agentic systems
Specialize in AI in the SDLD or TDLC
-->

---

# **This Slide Deck Was Created Using GitHub Copilot**

<!-- This slide deck itself is living proof of Copilot's capabilities -->

---

# **M365 Copilot**

---

## **The Human Element of AI Adoption**
- **Satya Nadella (Microsoft CEO)**  
  *"The challenge isn't the technology. It's helping people change how they work."*  
  **Date:** August 2025

- **Sam Altman (OpenAI CEO)**  
  *"AI agents [will] become an integral part of the workforce by 2025, dramatically transforming productivity."*  
  **Date:** 2024-2025

<!--
Sources:
Quote 1: Widely circulated in articles and LinkedIn posts (mid-to-late 2025) as businesses moved from piloting AI to large-scale deployment
Quote 2: Sam Altman's forward-looking statements throughout 2024 and 2025, emphasizing the rapid, transformative role AI agents will play in daily business operations
These quotes frame AI adoption as both inevitable and fundamentally about human change, not just technology
-->

---

# It's All About Context

---

# What is Context and the Context Window

<div style="text-align: center;">

![width:1200px](img/contextwindow.drawio.svg?page=1)

</div>

<!-- Typical ordering inside the context window
System prompt – The hidden instructions from the platform or developer.
Example: “You are ChatGPT, a large language model trained by OpenAI. Follow these guidelines…”
Can also include special behavior rules, safety policies, or formatting requirements.
Developer or application-specific instructions – Additional hidden setup from the app integrating the model.
Example: “Always respond in JSON unless otherwise specified.”
Conversation history – Your past messages + the model’s past responses.
May be direct text or summaries if the history is long.
Injected knowledge or retrieved content – Snippets from web search, databases, documents, or memory.
Your latest prompt – The most recent user message. -->

<!--
System Prompts can vastly ajust the behavior, some issues in the past have been
Google, Implicit prompt bias, with image generation
Grok, Spreading extremist narratives
OpenAI Sycophantic behavior -->

---

# **M365 Copilot Data Sources** 📊

## **Your Organizational Knowledge**

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px;">

<div>

- Outlook emails
- Teams chats & channels
- Teams meetings & transcripts
- Viva Engage posts
- SharePoint sites & libraries
- OneDrive files
- Word, Excel, PowerPoint

</div>

<div>

- OneNote notebooks
- Loop components
- Planner tasks
- To Do lists
- Organizational directory
- Viva Insights data
- Calendar & scheduling

</div>

</div>

<!-- 
M365 Copilot has access to a vast array of enterprise data sources
All data access respects existing permissions - you only see what you're authorized to see
This comprehensive access is what makes Copilot so powerful for enterprise use
Data stays within your Microsoft 365 tenant boundary
Copilot uses Microsoft Graph API to access these sources securely
-->

---

# **Getting Started: Simple Chat**

1. **Open Microsoft Teams, Outlook, or copilot.microsoft.com**
2. **Click the Copilot icon**
3. **Start with simple questions:**
   - "Summarize my emails from this week"
   - "What meetings do I have today?"
   - "Help me draft a response to /[person's name]"

## **Pro Tip**
The more context you provide, the better the results!

<!-- 
M365 Copilot works best when you give it context
Start simple and build up complexity
Works across the entire Microsoft 365 ecosystem
-->

---

# **Effective Prompting: The PACET Framework**

## **P.A.C.E.T.**
- **P**ersona — Who should Copilot be?
- **A**sk — What do you want it to do?
- **C**ontext — What background information is relevant?
- **E**xemplars — What examples show the format you want?
- **T**one — What style should the response use?

<!-- 
PACET helps structure effective prompts
Not all elements needed every time, but more detail = better results
Exemplars are especially powerful for consistent formatting
-->

---

# **PACET in Action**

## **The Prompt**
*"You are my executive assistant helping me prepare for my weekly status meeting. Create a summary of the work I accomplished last week by reviewing my emails, Teams chats, OneNote updates, and calendar appointments. Focus on client deliverables, key meetings, and action items completed. Format it as a bulleted status report like I typically send to my manager. Keep the tone concise and achievement-focused."*

<!-- 

Look at my Teams chats, meetings and emails I've sent in the last two weeks. Based on the above analysis, what Star Wars character would represent my style of work best, and why? What would my abilities, strengths and personality flaws be? Can you format that as a Star Wars character dossier for me? Also give me a Star Wars character friend group based on my recent interactions with my current top [five] collaborators. Provide them with different types of Star Wars characters, include their real name, star wars type, home planet, strengths and weaknesses, and why they are my friends and how they help me in my work here at Accenture. Also identify my rival based on recent interactions with my colleagues and a short story of how we became nemeses but ended up being friends. List my real name, my most similar existing Star Wars Character, and include the same attributes listed above for friends and the rest of the information formatted and edited in a dossier style.

## **Breaking It Down**
- **Persona**: Executive assistant
- **Ask**: Create summary of last week's work
- **Context**: Emails, Teams, OneNote, calendar - client deliverables & meetings
- **Exemplars**: Bulleted status report format
- **Tone**: Concise, achievement-focused

This example showcases M365 Copilot's ability to pull from multiple data sources
Demonstrates cross-application integration (Outlook, Teams, OneNote, Calendar)
Shows how Copilot can save hours of manual status report compilation
-->

---



## **A Fun Prompt**
*"Look at my Teams chats, meetings and emails I've sent in the last two weeks. Based on the above analysis, what Star Wars character would represent my style of work best, and why? What would my abilities, strengths and personality flaws be? Can you format that as a Star Wars character dossier for me? Also give me a Star Wars character friend group based on my recent interactions with my current top [five] collaborators. Provide them with different types of Star Wars characters, include their real name, star wars type, home planet, strengths and weaknesses, and why they are my friends and how they help me in my work here at Accenture. Also identify my rival based on recent interactions with my colleagues and a short story of how we became nemeses but ended up being friends. List my real name, my most similar existing Star Wars Character, and include the same attributes listed above for friends and the rest of the information formatted and edited in a dossier style.
"*

---

# **Advanced Prompting Techniques**

---

# **Chain-of-Thought Prompting** 🔗

## **Show Your Reasoning**

Ask Copilot to explain its thinking step-by-step

## **Example**

*"Analyze our Q4 sales data and recommend which product line to prioritize. **Think through this step-by-step**: First identify trends, then compare margins, finally consider market conditions. Show your reasoning for each step."*


<!--
## **Why It Works**

- Produces more accurate, reliable results
- Reveals the logic behind recommendations
- Helps you verify the analysis process
- Great for complex decisions
 
Chain-of-thought prompting dramatically improves reasoning quality
Forces the model to work through problems methodically
Particularly effective for analysis, planning, and problem-solving tasks
Makes AI reasoning transparent and verifiable

Prompt: "Analyze the data to provide a recommendation. Ensure the recommendation accounts for outliers and trends."
-->

---

# **Few-Shot Learning** 🎯

## **Teach by Example**

Provide 2-3 examples of what you want, then ask for more

## **Example**

*"Convert these meeting notes to action items:*
*Example 1: 'We discussed the budget' → 'Review and approve Q1 budget by Friday'*
*Example 2: 'Sarah will look into vendors' → 'Sarah: Research vendors and provide recommendations by EOW'*

*Now convert these notes: [your actual notes]"*

<!--
## **Why It Works**

- Ensures consistent formatting
- Captures your specific style
- Reduces need for detailed instructions

 
Few-shot learning is incredibly powerful for consistent outputs
2-3 examples are usually enough to establish the pattern
Great for formatting tasks, style matching, and template generation
Works better than lengthy explanations of what you want
-->

---

# **Role-Based Prompting** 🎭

## **Assign an Expert Persona**

Tell Copilot who to be for specialized responses

## **Example**

*"You are a seasoned project manager with 15 years of experience in software development. Review this project timeline and identify potential risks, dependencies, and resource conflicts. Provide recommendations based on PMI best practices."*

<!-- 
## **Why It Works**

- Activates relevant knowledge domains
- Adjusts tone and expertise level
- Provides domain-specific insights
- Contextualizes responses appropriately


Role-based prompting leverages the model's training across different domains
The persona helps frame the response with appropriate expertise
Works well for technical advice, strategic planning, creative tasks
Can combine roles: "You are both a CFO and a marketing strategist..."
-->

---

# **Tree-of-Thought Prompting** 🌳

## **Explore Multiple Paths**

Ask Copilot to consider different approaches before deciding

## **Example**

*"I need to improve team productivity. **Explore three different approaches**: 1) Process optimization, 2) Technology tools, 3) Team structure changes. For each, outline pros, cons, and implementation complexity. Then recommend the best path forward and explain why."*

<!-- 

## **Why It Works**

- Evaluates multiple solutions
- Compares trade-offs systematically
- Leads to more balanced decisions
- Reduces confirmation bias


Tree-of-thought extends chain-of-thought to explore multiple reasoning paths
Particularly powerful for strategic decisions and complex problems
Forces consideration of alternatives before committing to a solution
Great for scenarios where there's no obvious "right" answer
Helps surface options you might not have considered
-->

---

# **Iterative Refinement** 🔄

## **Build on Previous Responses**

Start broad, then progressively refine with follow-ups

## **Example**

*Prompt 1: "Summarize our customer feedback from last month"*
*Prompt 2: "Focus on the top 3 complaints"*
*Prompt 3: "For the #1 complaint, suggest 5 potential solutions"*
*Prompt 4: "Expand on solution 2 with implementation steps"*

<!-- 

## **Why It Works**

- Faster than crafting perfect prompts upfront
- Allows course correction as you learn
- Builds context naturally
- More conversational and efficient


Iterative refinement is often more efficient than trying to write the perfect prompt
Leverage Copilot's ability to maintain conversation context
Each refinement narrows focus and improves precision
Great for exploratory work where you're not sure exactly what you need
Mirrors natural human problem-solving: broad → specific
-->

---

# **Avoid Leading the Answer** ⚠️

## **Don't Bias the Result**

Let Copilot analyze objectively without steering toward your preferred outcome

## **Leading (Bad)** ❌

*"Our competitors are clearly failing. Analyze the market data and confirm why we're winning."*

## **Neutral (Good)** ✅

*"Analyze our market position compared to competitors. What are the key trends, strengths, and weaknesses for each player?"*

<!--

## **Why It Matters**

- Confirmation bias leads to flawed analysis
- Objective data reveals real insights
- Better decisions require honest assessment

 
Leading questions can cause Copilot to rationalize your assumptions rather than analyze objectively
The model will try to satisfy what it perceives as your expectation
This is particularly dangerous in business analysis, competitive research, and strategic planning
Ask open-ended questions and let the data speak
If you want critical analysis, explicitly ask for it: "What are potential flaws in this approach?"
Be especially careful when you have a preferred outcome - that's when leading is most tempting
Neutral prompts lead to more reliable, actionable insights
-->

---

<!-- _footer: '' -->

# **Use "Like" for Creative Adaptation** 💡

## **Inspire, Don't Dictate**

When you want Copilot to adapt ideas to your context, use "like" instead of exact instructions

## **Too Specific (Limits Creativity)** ❌

*"Write a project update email with exactly 3 bullet points, a status table, and a risks section."*

## **Inspirational (Enables Adaptation)** ✅

*"Write a project update email **like** the ones I usually send - concise, data-driven, and highlighting what stakeholders need to know."*

<!-- 

## **Why It Works**

- Copilot applies concepts to YOUR context
- Adapts ideas rather than copying templates
- Encourages contextual intelligence


"Like" is a powerful word for getting Copilot to understand intent without over-constraining
It signals: "Use this as inspiration, but make it fit my situation"
Particularly useful when you have a general idea but want Copilot to contextualize it
Compare: "Do it EXACTLY like X" vs "Do something LIKE X but for my context"
Works great for: writing styles, document formats, analysis approaches
The model can access your actual work data and apply the concept appropriately
Gives Copilot room to be intelligent rather than just following a rigid template
Use "like" when you want conceptual guidance with contextual adaptation
-->

---

# **Normalizing Reports Across Teams** 📊

## **The Challenge**

Different team members create status reports in varying styles, levels of detail, and formats

## **The Solution**

*"Review these three status reports from different team members. Normalize them into a consistent executive summary format with: standard sections (progress, risks, next steps), uniform detail level appropriate for leadership, consistent metric presentation, and aligned tone. Maintain the key information from each report while creating a cohesive view."*

<!-- 
## **Perfect For**

- Consolidating team updates for leadership
- Creating consistent project dashboards
- Standardizing cross-functional reports
- Preparing board-level summaries


Normalization is a powerful use case for M365 Copilot in reporting workflows
Instead of manually reformatting different styles, Copilot can standardize them
Maintains information integrity while ensuring consistency
Particularly valuable for managers consolidating team inputs
Saves hours of manual reformatting and rewriting
Can establish organizational standards while respecting individual work styles
Great for creating executive dashboards from varied sources
Helps ensure leadership gets information at the right level of abstraction
-->

---

# **Time for the Live Demo!** 🚀

![bg right:50%](img/demogremlin.png)

## **With a non-deterministic system...**

### What could possibly go wrong?

<!-- 
Live demos with AI are always an adventure
The demo gremlin is real - embrace the uncertainty
Great opportunity to show real-world behavior and troubleshooting
-->

---

# **Prompt Library: Reusable Excellence** 💾

## **Save Your Best Prompts**

- **Personal prompt library** for frequently used queries
- **Team sharing** of proven prompts
- **Organizational templates** for consistency
- **One-click reuse** with customization options

<!-- 
Prompt Library eliminates reinventing the wheel for common tasks
Creates organizational knowledge around effective AI use
Enables less experienced users to leverage expert-level prompts
Drives consistency in outputs across teams
Acts as training tool - learn from successful prompts
Great for onboarding new Copilot users
-->

---

# **Scheduled Prompts: Automation at Work** ⏰

- **Recurring reports** generated automatically
- **Daily briefings** delivered on schedule
- **Weekly summaries** without manual requests
- **Custom timing** for your workflow needs

## **Perfect For**

- Morning email summaries before you start work
- End-of-week project status updates
- Monthly trend analysis and insights
- Regular competitive intelligence reports

<!-- 
Scheduled prompts transform Copilot from reactive to proactive
Automates repetitive information gathering tasks
Ensures you never forget routine status checks or updates
Delivers insights when you need them, not when you remember to ask
Great for managers who need consistent reporting
Reduces cognitive load - one less thing to remember
-->

---

# **Best Practice: Refresh Your Chat**

## **Why Start Fresh?**

- Previous conversations fill the context window
- Old context can confuse or bias responses
- Fresh chat = focused, relevant results

## **When to Start a New Chat**

✅ Switching projects or topics  
✅ Moving from creative to analytical work  
✅ When responses seem off-track

<!-- 
Context pollution is a real issue - keeping old conversations active degrades quality
Starting fresh helps Copilot focus on what matters now
Think of it like clearing your workspace before starting a new task
This is especially important in M365 Copilot where you're pulling from so many sources
-->

---

# **Copilot Pages: Collaborative Canvas** 📄

Transform chat conversations into living documents you can edit and share

## **Key Features**

- Create pages directly from chat responses
- Edit inline with AI assistance
- Real-time collaboration with team members
- Combine human + AI contributions

## **Perfect For**

Research reports • Project plans • Documentation • Team ideation

<!-- 
Copilot Pages bridge the gap between ephemeral chat and persistent documents
Unlike chat which is sequential, Pages give you a canvas to develop ideas spatially
You can create a page from any chat response, then continue working on it
Pages support real-time collaboration - multiple people plus Copilot working together
Great for when chat conversations evolve into something worth preserving and sharing
Think of it as "chat graduate to document" - start conversationally, end with artifacts
Can reference the page in future chats or continue editing with AI inline
Combines the best of both: conversational AI + structured documentation
-->

---

# **Managing Copilot Memory** 🧠

Store preferences and context that persist across conversations

## **Adding a Memory**

*"Remember that I prefer concise responses with bullet points and prefer data-driven insights over general advice."*

## **Removing a Memory**

*"Forget my preference for bullet points."*

**Pro Tip:** Review your stored memories periodically to keep them current

<!-- 
Memory feature allows Copilot to learn your preferences over time
Unlike context window which is temporary, memory persists across chats
Great for storing long-term preferences that apply to all interactions
Can be managed - add new memories or delete outdated ones
Helps Copilot provide more personalized, relevant responses
Particularly useful for consistent tone, format preferences, and role context
Be mindful of what you store - review periodically for accuracy
-->

---

# **Personalization: Custom Instructions + Memory** ✨

## **Two Powerful Tools Working Together**

### **Custom Instructions** 📝
- **Set global rules** Copilot always follows
- **Define your context** once, apply everywhere
- **Establish guidelines** for all responses

### **Copilot Memory** 🧠
- **Learns over time** from your interactions
- **Adaptive preferences** that evolve
- **Automatic context** from past conversations

## **Best Together**

Custom instructions set the baseline → Memory refines over time

<!-- 
Custom instructions are explicit rules you define upfront
Memory is implicit learning from your actual usage patterns
Together they create a highly personalized Copilot experience
Custom instructions are great for consistent requirements (tone, format, role)
Memory captures nuances that emerge from how you actually work
Example: Custom instruction says "be concise", Memory learns you prefer bullet points
Both persist across chats but can be updated independently
This combination makes Copilot feel increasingly tailored to your work style
-->

---

# **Work vs Web Toggle**

## **Work Mode** 🏢
- Your company data (emails, Teams, SharePoint)
- Internal projects and communications
- Confidential content stays secure

## **Web Mode** 🌐
- Public internet information
- Industry trends and general knowledge
- No access to your company data


<!-- 
Work mode keeps everything within your organization's security boundary
Web mode gives you broader knowledge but no access to your company data
Many users don't realize they can toggle between these modes
This is a key feature that maintains data security while providing flexibility
-->

---

# **M365 Copilot Search**

## **Enterprise Search Reimagined** 🔎

- Semantic search across all your M365 data
- Natural language queries instead of keywords
- Intelligent summaries from multiple sources
- Understands intent, not just keyword matching
- Generates answers with citations, not just links

<!-- 
M365 Copilot Search transforms how you find information across the enterprise
Traditional search relies on exact keyword matching - Copilot understands what you mean
Aggregates information from emails, Teams, SharePoint, OneDrive, and more
Provides synthesized answers with citations instead of forcing you to click through links
Saves significant time in knowledge work by reducing the search-to-answer cycle
-->

---

# **GPT-5 is Here: Try It Now**

## **What's New in GPT-5?**
- Significantly improved reasoning and accuracy
- Better understanding of complex instructions
- Enhanced creative and analytical capabilities
- More reliable and coherent responses

<!-- 
GPT-5 represents a significant leap in AI capabilities
Available to M365 Copilot users with appropriate licensing
Great for complex reasoning, analysis, and creative tasks
May have different performance characteristics - test with your use cases
-->

---

# **GPT-4 vs GPT-5 in M365 Copilot**

## **GPT-4 (Standard Model)**
- Fast, efficient for most daily tasks
- Great for summaries, drafts, and routine queries
- Best for: Quick answers, standard productivity tasks

## **GPT-5 (Advanced Model)**
- Superior reasoning and complex problem-solving
- Better at nuanced instructions and context
- Best for: Deep research, critical thinking, complex writing

<!-- 
GPT-4 is the workhorse - handles 90% of everyday tasks efficiently
GPT-5 is for when you need the extra horsepower
Consider cost/performance tradeoffs in your organization
Test both models to understand which works best for your specific use cases
-->

---

# **Temporary Chat: When Privacy Matters**

## **What Is It?** 🔒
Chat history is **not saved** or used for training

## **Use Temporary Chat For:**
- Exploring sensitive topics or scenarios
- Testing prompts with confidential data
- Personal brainstorming sessions
- Prototype ideas before formal documentation


<!-- 
Temporary chat ensures your conversation won't be saved to chat history
Especially useful when testing prompts with real client names or sensitive info
Great for "what if" scenarios you don't want documented
Think of it as incognito mode for Copilot

Important Caveats

Enterprise Governance: In Microsoft Copilot, even Temporary Chats may be subject to retention, auditing, or eDiscovery under organizational policies. [marcotran.com.au]
Not Fully Anonymous: While not used for personalization or training, platforms may temporarily store data for abuse prevention or compliance. [help.openai.com]
-->

---

# **All Chats: Your Conversation Library** 📚

Searchable history of all your Copilot conversations

## **Key Features**

- Search and filter by date, topic, or project
- Resume any conversation where you left off
- Reference past insights for future work
- Track patterns in successful queries

**Pro Tip:** Use descriptive first messages to make conversations easy to find later

<!-- 
All Chats is your personal knowledge repository of AI interactions
Powerful for finding that one perfect response from weeks ago
Search functionality makes it easy to rediscover insights
Helps you learn what prompts work best over time
Great for maintaining continuity across projects
Think of it as your searchable AI conversation archive
-->

---

# **Protected Status Indicators**

## **The Shield Icon** 🛡️
Shows your data is **enterprise-protected**

## **What It Means:**
- Your prompts and responses stay within your tenant
- Protected by commercial data protection
- Not used to train foundation AI models
- Compliant with organizational security policies

<!-- 
The shield/protected indicator is critical for enterprise users
It confirms that Microsoft's commercial data protection is in effect
Without the shield, data may not have the same enterprise protections
Users should always verify the shield is present when handling sensitive info
This is especially important in organizations with strict compliance requirements
-->

---

# **M365 Copilot Analyst**

## **Advanced Data Analysis with AI** 📊

- Work with complex datasets directly in Copilot
- Natural language queries for data insights
- Upload files (CSV, Excel) for instant analysis
- Automated visualizations and trend analysis
- Generate charts and summaries automatically
- Integrates with Excel, Power BI, and enterprise data

<!-- 
M365 Copilot Analyst is designed for data-driven decision making
Democratizes data analysis - no advanced Excel or analytics skills needed
Can handle large datasets and complex calculations
Great bridge between business users and data teams
Works seamlessly with Microsoft's data ecosystem
https://catalog.data.gov/dataset?q=&sort=views_recent+desc
-->

---

# **M365 Copilot Researcher**

## **Deep Research at Your Fingertips** 🔍

- Comprehensive web research with source citations
- Multi-source synthesis across documents and web
- Automated research reports with key findings
- Cross-reference verification for accuracy
- Market research • Competitive analysis • Literature reviews
- Fact-checking • Source validation • Evidence-based recommendations

<!-- 
M365 Copilot Researcher transforms how you gather and synthesize information
Saves hours of manual research by aggregating and summarizing from multiple sources
Provides proper citations so you can verify and trace back to original sources
Combines web search with your organizational knowledge base
Ideal for consultants, analysts, and anyone doing knowledge work
-->

---

# **Create with Copilot** 🎨

## **Generate Content from Scratch**

Generate images, documents, and more using the "Create" functionality

- Images and graphics for presentations
- Documents and reports from templates
- Data visualizations and charts
- Custom content tailored to your needs
- Be specific about style, mood, and details
- Iterate and refine based on initial results

<!-- 
Create functionality extends Copilot beyond analysis to content generation
Image generation uses DALL-E integration for professional visuals
Great for presentations, reports, and marketing materials
Can specify style (photographic, illustration, minimalist, etc.)
Include details like perspective, lighting, colors, and composition
Useful when you need custom visuals but don't have design resources
Remember: Generated images should align with your organization's brand guidelines
Can create multiple variations and refine based on feedback
-->

---

# **Brand Kit: Maintain Visual Consistency** 🎨

Upload your organization's brand assets to ensure consistent, on-brand content

- Logo files (primary and alternate versions)
- Color palette (hex codes and RGB values)
- Typography (font families and usage guidelines)
- Visual style guide (imagery, tone, design principles)
- Auto-apply branding to generated content
- Consistent visuals across all Copilot outputs
- Faster creation with no manual brand adjustments

<!-- 
Brand Kit ensures all Copilot-generated content aligns with organizational branding
Particularly important for images, presentations, and documents shared externally
Upload once, apply automatically to all future creations
Helps maintain professional, consistent brand identity
Great for marketing teams, client-facing roles, and communications
Reduces back-and-forth with design teams for brand compliance
Can include multiple brand kits for different sub-brands or campaigns
Works especially well with Create functionality for images and presentations
Administrators can set up organization-wide brand kits for consistency
-->

---

# **M365 Copilot Notebooks**

## **Organize Your AI Conversations** 📓

- Persistent workspaces for ongoing projects
- Structured collaboration across multiple sessions
- Context preservation between chat interactions
- Share and collaborate with team members
- Keep related queries and insights together
- Build knowledge repositories over time
- Track project evolution and decisions

<!-- 
Notebooks solve the problem of losing valuable chat history and context
Perfect for long-term projects where you need to maintain continuity
Acts as a collaborative workspace where teams can build on AI insights
Great for research projects, planning documents, and knowledge management
Can be shared across teams to democratize AI-generated insights
-->

---

# **M365 Copilot Agents**

## **Custom AI Assistants for Your Workflows** 🤖

- Purpose-built agents for specific tasks and roles
- Connect to your data sources and business systems
- Automated workflows triggered by events or schedules
- Shareable across teams for consistent outcomes
- Sales assistant with CRM integration
- HR onboarding guide with policy knowledge
- IT support bot with troubleshooting expertise

<!-- 
Agents are the next evolution of M365 Copilot - specialized AI assistants
Built using Copilot Studio with no-code/low-code tools
Can be configured with specific knowledge bases, tone, and workflows
Reduce repetitive questions and standardize processes across teams
Enable subject matter experts to scale their knowledge organization-wide
-->