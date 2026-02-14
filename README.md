## TalentScout-AI

###  Problem We Chose to Solve

The problem we chose to solve is inefficiency and subjectivity in early-stage hiring.

Companies often receive hundreds or thousands of applications for a single role. HR teams manually screen resumes, which is time-consuming, inconsistent, and prone to bias. Additionally, resume-based filtering does not evaluate a candidate’s communication skills or their actual understanding of projects.

---

###  Our Understanding of the Problem

We understood that the real issue is not just filtering resumes, but identifying candidates who are both technically aligned and interview-ready.

Traditional Applicant Tracking Systems (ATS) rely heavily on keyword matching, which:
- Can be gamed easily
- Does not measure real capability
- Does not assess articulation or structured thinking

The major gaps we identified were:

- Resume screening is shallow  
- No structured readiness evaluation  
- No early-stage communication assessment  
- Excessive manual effort  

---

### What We Attempted to Solve

We designed a **two-stage pre-defined pre-interview screening system**.

####  Stage 1 —  Resume & JD Alignment

In Stage 1, the system analyzes the candidate’s resume against the job description .

Instead of simple keyword matching, we evaluate:

- Technical alignment  
- Skill coverage  
- Missing skills  
- Risk score  
- Overall readiness score  

Only candidates meeting a defined threshold move to Stage 2.

This ensures:
- Automated filtering  
- Structured scoring  
- Reduced bias  
- Better job-description alignment  

---

####  Stage 2 —  audio Interaction

In Stage 2, we simulate a structured audio interaction.

Candidates answer pre-defined technical questions in real time. Their responses are converted from speech to text and evaluated for:

- Communication clarity  
- Technical articulation  
- Depth of understanding  
- Structured thinking  

Only candidates who pass this stage proceed to a formal interview.

---

###  What Makes This Different

Unlike traditional ATS systems, our solution is **multi-modal**.

It evaluates:
- Written qualifications (resume)
- Verbal articulation (communication readiness)

It acts as an intelligent pre-interview gatekeeper, ensuring that only technically aligned and interview-ready candidates move forward.

---

###  Why This Matters Today

With increasing applicant volume and the rise of remote hiring, companies need automated, structured, and unbiased screening systems.

Our solution:
- Reduces recruiter workload  
- Improves shortlist quality  
- Enhances hiring efficiency  
- Promotes fair and structured evaluation  


###  Technologies Used
- React
- TypeScript
- Vite
- AI API Integration

###  Future Scope
- Resume parsing using NLP
- Advanced AI-based scoring model
- Admin analytics dashboard
- Cloud deployment for enterprise use

## Run Locally

**Prerequisites:**  Node.js


1. Install dependencies:
   `npm install`
2. Set the `GEMINI_API_KEY` in [.env.local](.env.local) to your Gemini API key
3. Run the app:
   `npm run dev`
