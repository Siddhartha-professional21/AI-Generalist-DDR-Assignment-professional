# AI Generalist Assignment - Option A (DDR Report Generation)

AI pipeline that converts **Sample Report.pdf** + **Thermal Images.pdf** into a professional **Detailed Diagnostic Report (DDR)**.

## 🎯 What It Does
- Extracts observations from inspection report
- Pulls thermal findings from images report  
- Merges data logically (handles conflicts/missing info)
- Generates client-ready DDR with severity ratings

## 📋 Requirements Met
✅ Property Issue Summary  
✅ Area-wise Observations  
✅ Root Cause Analysis  
✅ Severity Assessment  
✅ Recommended Actions  
✅ Missing Info Handling ("Not Available")  

## 🛠 Tech Stack
PyMuPDF (PDF extraction)
→ Groq LLM (llama-3.1) (structured extraction/merging)
→ Markdown formatter

## 🚀 Run It
1. Upload PDFs to Colab
2. Run notebook → Auto-generates `DDR_Report.md`
3. **See output:** [DDR_Report.md](DDR_Report.md)

## 📹 Demo Video
3-min walkthrough in submission email.

## 🔧 Improvements
- LangChain RAG chains
- Automated validation
- OCR for tables/images
