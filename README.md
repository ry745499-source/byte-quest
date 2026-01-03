# 1. Problem Statement

Generative AI systems frequently produce factually incorrect information with high confidence. A critical issue within this space is **AI hallucination**, where models generate fake citations, non-existent research papers, incorrect references, or broken links that appear legitimate but cannot be verified.

This creates serious risks including misinformation, academic dishonesty, legal liability, and loss of trust in AI-generated content. There is a strong need for a system that can automatically **detect, verify, and flag unreliable claims and citations** produced by AI models.

---

# 2. Project Name

**VeriFact AI – AI Hallucination & Citation Verification System**

---

# 3. Team Name

**Creativity Minds**

---

# 4. Deployed Link (optional)

https://verifact-ai.vercel.app  
*(Prototype Deployment)*

---

# 5. 2-minute Demonstration Video link

https://drive.google.com/your-demo-video-link  
*(Anyone with the link can view)*

---

# 6. PPT Link

https://drive.google.com/your-ppt-link  
*(PDF format only, view access enabled)*

---

## Project Overview

**VeriFact AI** is a system designed to analyze AI-generated content and evaluate its factual reliability. It detects factual claims and citations, verifies them using trusted academic and web sources, and flags hallucinations, fake references, and broken links.

The platform provides a **clear trust assessment** for AI-generated outputs, enabling users to confidently differentiate between reliable and unreliable information.

---

## Key Features

- Automatic factual claim extraction
- Citation and reference validation
- Fake paper and non-existent source detection
- Broken and inaccessible link checking
- Hallucination risk flagging
- Trust score for AI-generated content
- Transparent verification results

---

## How the System Works

1. User inputs AI-generated text
2. The system extracts factual claims and citations
3. Claims are validated using trusted APIs and sources
4. Citations are checked for existence, correctness, and accessibility
5. Results are classified as:
   - ✅ Verified
   - ⚠️ Partially Verified
   - ❌ Hallucinated / Fake

---

## Technology Stack

### Frontend
- Next.js 14 (App Router)
- TypeScript
- Tailwind CSS
- ShadCN/UI

### Backend
- Node.js (Next.js API Routes)
- Python FastAPI (Verification Engine)

### AI & Verification
- LLM APIs (OpenAI / Gemini)
- spaCy (NLP & entity extraction)
- CrossRef API
- Semantic Scholar API
- Search API (Bing / SerpAPI)

### Database
- PostgreSQL (Supabase)

### Deployment
- Vercel (Frontend & Node APIs)
- Render / Railway (Python Microservice)

---

## Setup and Installation

### Prerequisites
- Node.js 18+
- Python 3.10+
- PostgreSQL database

### Frontend Setup
```bash
npm install
npm run dev
