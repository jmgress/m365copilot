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