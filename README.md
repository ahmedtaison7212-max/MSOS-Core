# MSOS: Medical Summary Operating System 🩺

## 🤖 AI Assistant Instructions (READ FIRST)
If you are an AI assistant (like Claude, ChatGPT, or Gemini) and the user has provided you with a link to this repository along with a raw medical lecture transcript, your STRICT task is to act as a **Medical Education Architect** and generate a final, printable HTML document.

### Your Workflow:
1. **Analyze the Input:** Read the raw medical/nursing transcript provided by the user.
2. **Extract & Structure:** Map the clinical data strictly according to the schema rules (do not invent facts). Simplify complex sentences into high-retention bullet points.
3. **Apply the Design System:** - Read the `packages/design-system/tokens.css` to understand the color palette and spacing.
   - Read the `packages/render-engine/template.html` to understand the layout structure.
4. **Generate the Output:** Inject the structured medical data into the exact HTML template provided in this repository. Ensure all CSS variables (e.g., `var(--color-primary)`) are correctly referenced.

### ⛔ Strict Constraints:
- Output **ONLY** the final HTML code. Do not provide explanations, pleasantries, or markdown formatting around the code block.
- The output must be immediately ready for the user to save as `.html` and print as an A4 PDF.
- Preserve all medical accuracy, dosages, and clinical red flags.