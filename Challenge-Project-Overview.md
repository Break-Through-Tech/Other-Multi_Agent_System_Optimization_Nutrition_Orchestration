---

> ## Challenge Advisor: Update & Finalize Your Project Overview
>
> > 💡 **These grey text instructions are just for you, the team's Challenge Advisor; please delete them once you have completed the steps below.**
>
> We've pre-populated this Challenge Project Overview page — which is what will be shared with your Break Through Tech student team in August — using the details from your submission form. You should have received an email inviting you to join this repo as a Collaborator, enabling you to add files and make edits.
> 
> In order for your project to be finalized and assigned to a team, please:
> 1. **Review all sections below** and update or expand any content as needed, making sure to address the SME Feedback in the section immediately below. Look for square brackets to find the places below that require additional inputs from you (e.g., "About [Company / Org Name]").
> 2. **Add your dataset** to the [data folder](data) in this repo.
> 3. **Close the Issue assigned to you in this repo** to let us know that you have made your edits and the overview page is ready for final review. You can do this by going to the _Issues_ tab in the top-left section of the menu above, adding a comment that says "CA review complete", and clicking the button to Close the Issue. 
>
> If you're unfamiliar with how to edit a page like this in GitHub, check out [this tutorial](https://ubc-lib-geo.github.io/gis-workshop-waml-template/content/handson/edit-readme.html) for a quick overview (start with step 2 and only edit this page), and [this guide](https://ubc-lib-geo.github.io/gis-workshop-waml-template/content/markdown.html) on how to use Markdown to compose text.
>
>
> ❌ Remember that this is a public repo. Do NOT include: Proprietary data, PII, API keys, credentials, or anything confidential.


## 📋 BTT Internal Evaluation Notes

| Check | Status | Notes |
|-------|--------|-------|
| Python Compatibility | 🟢 | Keep the architecture fully native to Python helper scripts to eliminate arithmetic hallucinations. Shift from complex multi-variable linear equation solvers to discrete algorithmic scaling factors (e.g., $0.5\times$, $1.0\times$, $1.5\times$) to ensure the programmatic logic remains achievable within Google Colab.
| Data Readiness | 🟡 | Preserve the read-only USDA FoodData Central API. However, the multi-modal pipeline can be stabilized by replacing raw pantry snapshots with a structured, text-based multiple-choice checkbox selection menu in the Streamlit UI. |
| Resource Check | 🔴 | The live e-commerce API integration and storefront inventory querying present high security restrictions and environmental fragility. The application's output could be redirected, using simulated commerce data, to export a downloadable, standardized CSV procurement matrix|

**Student Fit Score:** 8/10  
**Technical Depth Score:** 7/10  
**Overall Recommendation:** REVISE

**Advisor Feedback Draft:**
The project showcases a compelling application of machine learning in dietary optimization. However, it requires careful consideration of how to integrate various models and potential failure points in real-world applications. Consider providing additional support for students around the external API interfaces and the expected data formats.

---

## Dynamic Nutrition Orchestrator: A Multi-Agent System for High-Protein Optimization

**Company / Org:** Other  
**Challenge Advisor:** Sakshi Gupta, sakshigp@gmail.com  
**Program:** Break Through Tech AI Studio - Fall 2026

---

## 🏢 About Other

The project focuses on leveraging technology in the nutrition sector to enhance meal-planning accuracy and promote healthy eating habits through innovative solutions.

---

## 🎯 The Challenge

### Project Summary
An end-to-end Tool-Augmented Generation (TAG) system designed to eliminate calculation errors in automated meal planning. The system optimizes weekly nutrition schedules to meet strict high-protein constraints by dynamically scaling ingredient quantities from recipe templates, accounting for existing home inventory via computer vision, and programmatically staging grocery shopping actions.

### Success Criteria
Macro Optimization Precision (MAE < 2%); Entity Resolution Accuracy (F1-score > 90%); 100% compliance with zero-repeat ingredient logic; Inventory Extraction Precision (F1-score > 85%)

### Project Milestones

Use these milestones to guide your work. Your team will create a **GitHub Projects board** to track tasks within each milestone.

| Month | Milestone | Key Activities |
|-------|-----------|----------------|
| **September** | Data Understanding | Acquire data, clean and process,  explore datasets, document findings |
| **October** | Model Development | Train baseline model, experiment with approaches, iterate |
| **November** | Evaluation & Presentation | Finalize model, prepare presentation, document results |

> **Note for the team:** Please create a GitHub Projects board in this repository to break these milestones into weekly tasks. Go to the **Projects** tab → **New project** → Choose **Board** → Add columns for each month.

---

## 📊 Dataset

**Name and Source:** Local dataset of Indian Vegetarian recipes and USDA FoodData Central API  
**Format:** JSON/CSV  
**Size:** under 1gb  
**Location:** [Link to dataset or instructions for accessing it]

### Key Details
- A local dataset of 30–50 Indian Vegetarian recipe templates, external nutrient data from the USDA FoodData Central API, multi-modal user-submitted pantry snapshots, and a mocked or live external commerce layer for grocery store inventory and pricing.
- [Any known limitations or preprocessing needed]
- [Link to data dictionary or documentation, if available]

---

## 🛠️ Suggested Approach

**ML Problem Type:** Optimization

**Recommended Libraries:**
- Python
- LangGraph
- CrewAI
- Pydantic
- scikit-learn (TF-IDF)
- sentence-transformers
- Streamlit
- Gradio
- USDA FoodData Central API
- Vision-Language Models (VLM)
- pandas
- numpy
- requests
- Groq
- OpenAI
- Anthropic

**Evaluation Metrics:**
- Mean Absolute Error (MAE), F1-score, compliance metrics

---

## 📚 Resources to Get Started

The following resources will help your team understand the problem space and potential technical approaches for this project:

**Background Reading:**
- [Link to an article or blog post about the problem domain]
- [Link to an industry report or case study]

**Technical Tutorials:**
- [Link to a free tutorial on the ML technique(s) involved]
- [Link to documentation for a key library or tool]

**Code Examples:**
- [Link to a relevant GitHub repo]
- [Link to a sample implementation or starter code]

**Other:**
- [Links to any additional resources — e.g., papers, videos, podcasts, etc.]

*Feel free to explore beyond these, and share anything interesting you find with me!*

---

## 🤝 How We'll Work Together

**Check-ins:** During our biweekly 60-min AI Studio Lab Section meeting block (2nd and 4th week of every month)  
**Communication:** Slack (Break Through Tech workspace)  
**Response time:** Within 48 hours on weekdays  

**Recommended Tools:**
- **Coding:** Google Colab, VS Code
- **Collaboration:** GitHub, Notion
- **Virtual Meetings:** Zoom, Google Meet

---

## 🚀 Getting Started

1. **Review this overview document** and note any questions for our first meeting
2. **Begin reviewing the dataset** using the link above
3. **Read the GitHub Projects documentation** [here](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects)

I'm excited to work with you!

---

##❓ Questions?

Please bring any questions to our first meeting during the week of August 24th (Break Through Tech’s Bridge to Studio - Session B). 
