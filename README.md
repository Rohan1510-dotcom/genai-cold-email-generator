🚀 Cold Email Generator 

🧠 Powered by Groq | LangChain | Streamlit 

📖 Overview

The Cold Email Generator is an intelligent business development tool designed for services companies that want to reach potential clients through personalized, AI-generated cold emails.

The system automatically extracts job listings from a company’s careers page, analyzes the job descriptions using Groq-powered language models, and crafts tailored outreach emails. Each email highlights your company’s relevant expertise and includes portfolio links dynamically fetched from a vector database, ensuring contextually aligned communication.

💡 Use Case Example

Let’s imagine a scenario:

Nike is currently hiring a Principal Software Engineer, investing significant time and resources in hiring, onboarding, and training.
Meanwhile, Atliq, a software development company, offers dedicated engineering teams for enterprise clients.

To save Nike time and cost, Mohan, a Business Development Executive from Atliq, decides to reach out.

Using this Cold Email Generator, Mohan simply inputs Nike’s careers page URL, and within seconds, the system:

Extracts job listings (like “Principal Software Engineer”)

Analyzes the role description using Groq

Searches Atliq’s portfolio vector database for relevant project case studies

Generates a personalized cold email that pitches Atliq’s development services in the context of Nike’s current needs

The result is a highly targeted, data-driven cold email that speaks directly to the client’s challenges and hiring requirements — drastically improving engagement and conversion rates.

⚙️ Features

✅ Job Scraper:
Extracts live job listings from any company’s careers page using BeautifulSoup and requests.

✅ Job Description Analysis (Groq):
Processes and summarizes job details using Groq’s lightning-fast inference for semantic understanding.

✅ Context-Aware Email Generation (LangChain):
Chains together contextual prompts that combine job requirements with your company’s service offerings.

✅ Vector Database Integration:
Finds and embeds portfolio links similar to the job’s tech stack or requirements (using FAISS / Pinecone).

✅ Streamlit Frontend:
Simple and intuitive web interface where users can:

Enter the careers page URL

Review extracted job postings

Generate and view cold emails instantly

✅ Download & Copy Options:
Easily copy emails or download them as text for quick outreach.
