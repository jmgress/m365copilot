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

## **Transforming Productivity**
- **Satya Nadella (Microsoft CEO)**  
  *"Copilot is reinventing how people work. It's not just about doing more—it's about doing better work."*  
  **Date:** 2024 Microsoft Ignite

- **Jared Spataro (Microsoft AI @ Work)**  
  *"70% of Copilot users say they are more productive, and 68% say it improved the quality of their work."*  
  **Date:** 2024 Work Trend Index

<!--
Sources:
Microsoft Work Trend Index: https://www.microsoft.com/en-us/worklab/work-trend-index/copilots-earliest-users-teach-us-about-generative-ai-at-work
Focus on productivity gains and work quality improvements with M365 Copilot
-->

---

# **Getting Started: Simple Chat**

## **Try M365 Copilot Right Now**

1. **Open Microsoft Teams, Outlook, or Copilot.microsoft.com**
2. **Click the Copilot icon**
3. **Start with simple questions:**
   - "Summarize my emails from this week"
   - "What meetings do I have today?"
   - "Help me draft a response to [person's name]"

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

# **Prompt Library: Reusable Excellence** 💾

## **Save Your Best Prompts**

- **Personal prompt library** for frequently used queries
- **Team sharing** of proven prompts
- **Organizational templates** for consistency
- **One-click reuse** with customization options

## **Build Your Library**

- Save prompts that generate great results
- Organize by task type or project
- Share best practices across teams
- Evolve prompts based on learnings

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

## **Set It and Forget It**

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

# **Best Practice: Refresh Your Chat**

## **Why Start a New Chat When Context Changes**

### **Context Pollution**
- Previous conversations fill the context window
- Old context can confuse or bias new responses
- Model may blend unrelated topics together

### **Better Results**
- Fresh chat = focused, relevant responses
- Faster processing with less context to analyze
- Clearer outputs aligned to your current task

## **When to Start Fresh**
✅ Switching from one project to another  
✅ Moving from creative to analytical work  
✅ Starting a new topic or subject area  
✅ When responses seem off-track or confused

<!-- 
Context pollution is a real issue - keeping old conversations active degrades quality
Starting fresh helps Copilot focus on what matters now
Think of it like clearing your workspace before starting a new task
This is especially important in M365 Copilot where you're pulling from so many sources
-->

---

# **Managing Copilot Memory** 🧠

## **Teach Copilot About You**

- **Add memories** for personalized responses
- **Store preferences** like writing style or tone
- **Save context** about projects and priorities
- **Remove outdated info** to keep it current

## **What to Remember**

- Your role, responsibilities, and goals
- Preferred formats and communication style
- Key projects, clients, or initiatives
- Common abbreviations or internal terms

## **Keep It Fresh**

Review and update memories regularly to maintain accuracy

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

- **Semantic search** across all your M365 data
- **Natural language queries** instead of keywords
- **Intelligent summaries** from multiple sources
- **People, files, emails, chats** - all in one place

## **What Makes It Different**

- Understands intent, not just matches words
- Surfaces relevant context automatically
- Combines web and work data seamlessly
- Generates answers, not just links

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

## **Never Lose a Conversation**

- **Searchable history** of all your Copilot interactions
- **Quick filters** by date, topic, or project
- **Resume any conversation** right where you left off
- **Reference past insights** for future work

## **Pro Tips**

- Use descriptive first messages for easy finding
- Search by keywords from your past prompts
- Review patterns in your most successful queries
- Build on previous work instead of starting over

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

- **Work with complex datasets** directly in Copilot
- **Natural language queries** for data insights
- **Automated visualization** and trend analysis
- **Integrates with Excel, Power BI, and enterprise data**

## **Key Capabilities**
- Upload files (CSV, Excel) for instant analysis
- Ask questions about patterns and anomalies
- Generate charts and summaries automatically
- Export insights back to your workflows

<!-- 
M365 Copilot Analyst is designed for data-driven decision making
Democratizes data analysis - no advanced Excel or analytics skills needed
Can handle large datasets and complex calculations
Great bridge between business users and data teams
Works seamlessly with Microsoft's data ecosystem
-->

---

# **M365 Copilot Researcher**

## **Deep Research at Your Fingertips** 🔍

- **Comprehensive web research** with source citations
- **Multi-source synthesis** across documents and web
- **Automated research reports** with key findings
- **Cross-reference verification** for accuracy

## **Perfect For**

- Market research and competitive analysis
- Literature reviews and background research
- Fact-checking and source validation
- Building evidence-based recommendations

<!-- 
M365 Copilot Researcher transforms how you gather and synthesize information
Saves hours of manual research by aggregating and summarizing from multiple sources
Provides proper citations so you can verify and trace back to original sources
Combines web search with your organizational knowledge base
Ideal for consultants, analysts, and anyone doing knowledge work
-->

---

# **M365 Copilot Notebooks**

## **Organize Your AI Conversations** 📓

- **Persistent workspaces** for ongoing projects
- **Structured collaboration** across multiple sessions
- **Context preservation** between chat interactions
- **Share and collaborate** with team members

## **Benefits**

- Keep related queries and insights together
- Build knowledge repositories over time
- Track project evolution and decisions
- Export and reuse AI-generated content

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

- **Purpose-built agents** for specific tasks and roles
- **Connect to your data sources** and business systems
- **Automated workflows** triggered by events or schedules
- **Shareable across teams** for consistent outcomes

## **Agent Examples**

- Sales assistant with CRM integration
- HR onboarding guide with policy knowledge
- IT support bot with troubleshooting expertise
- Project tracker with status updates

<!-- 
Agents are the next evolution of M365 Copilot - specialized AI assistants
Built using Copilot Studio with no-code/low-code tools
Can be configured with specific knowledge bases, tone, and workflows
Reduce repetitive questions and standardize processes across teams
Enable subject matter experts to scale their knowledge organization-wide
-->

https://catalog.data.gov/dataset?q=&sort=views_recent+desc