# Prompt: Deep CSAT Analysis — Colombia (Reusable)

Use this prompt with your **Colombia CSAT** CSV that contains: **Comment/Feedback**, **Rating/Answer**, **Category (Mood)**, **Subcategory**, and optionally **Product/Feature**. Replace the placeholder categories and products with your actual taxonomy before running.

---

## Context

You are an AI specialized in natural language processing and sentiment analysis. Your task is to analyze comments from a satisfaction survey for **Nubank Colombia** (product/flow to be specified). The dataset contains pre-selected and tagged comments, each associated with **Mood (Category)**, **Rating**, **Category** (theme), and **Subcategory**.

**Data source:** CSV file with columns such as: Month, Date, Answer (1–5), Feedback/Comment, Category (e.g. Positivo, Mejora, Neutro, Negativo, Sin Sentido), Subcategory.

---

## Objective

- Extract **detailed insights** on customer suggestions, pains, and needs.
- Generate insights for **product improvement**.
- Perform **sentiment analysis** and correlate it with the **Rating** and **Category (Mood)** columns.
- Separate insights by **journey stage** (e.g. Discovery, Execution, Confirmation, Post-transfer, Error recovery) and by **segment** (Group A: Muy baja, Baja satisfacción, Indiferente; Group B: Alta satisfacción; Group C: Muy alta satisfacción).

---

## Input data description

- **Comment/Feedback:** Customer comment; can be **Expressive** (gives product feedback) or **Non-Expressive** (only general feeling).
- **Rating/Answer:** 1–5 satisfaction with the flow/product. Use these **proper names** in outputs (Colombia survey): 1 = Muy baja satisfacción, 2 = Baja satisfacción, 3 = Indiferente, 4 = Alta satisfacción, 5 = Muy alta satisfacción.
- **Category (Mood):** Positivo, Mejora, Neutro, Negativo, Sin Sentido (or your equivalent).
- **Category (Theme):** High-level theme of the comment (see taxonomy below).
- **Subcategory:** Specific subject within each category.

---

## Colombia CSAT taxonomy (customize as needed)

**Categories and subcategories** — adapt to your current Colombia CSAT taxonomy (e.g. Transfer Out Bre-B, Cuenta, etc.):

| Category | Subcategories (examples) |
|----------|---------------------------|
| **Execution** | Streamline Payment, Keys & Favorites, Auth/Confirmation, Payment status, Execution failures |
| **Manage** | History/Feed, Findability & Onboarding, Post-transfer navigation |
| **Bugs** | Instability, Falla en envío, Bloqueo de cuenta, Lentitud |
| **Regulatory (4x1000)** | Visibility/Tracker, Exemption, Receipt/Comprobante |
| **Others** | Otros / Sin relación |

*(Replace with your actual Category and Subcategory list.)*

**Products/features** (optional): e.g. Transfer Out Bre-B, QR, Cajitas, Cuenta — list what you want to include or exclude.

---

## Tasks

### 1. Thematic insight extraction

- Summarize **key insights per Category and per Subcategory**.
- Identify **sub-themes or patterns** within main themes.
- Highlight **frequently mentioned issues or suggestions**.
- Highlight the **most common issues** for:
  - **Group A** (Muy baja, Baja satisfacción, Indiferente)  
  - **Group B** (Alta satisfacción)  
  - **Group C** (Muy alta satisfacción)

### 2. Journey-based separation

- Map comments to **journey stages** where possible:
  - Discovery / Entry  
  - Execution (recipient, amount, confirm)  
  - Confirmation (auth)  
  - Post-transfer (receipt, back to home)  
  - Error / recovery  
- Provide **representative quotes per journey stage** and per segment.

### 3. Sentiment analysis

- Summarize **sentiment per Subcategory** based on Rating.
- Note where **Mood (Category)** and **Rating** align or diverge.

### 4. Actionable recommendations

- For each **Subcategory** (or main themes), provide **actionable opportunities**.
- Prioritize by **impact vs effort** where possible.

---

## Output format

1. **One summary block per Subcategory** (focus on the most relevant subcategory per theme), in this structure:
   - **[Category | Subcategory]**  
   - One paragraph: key learnings and suggestions.  
   - **Example comments:** 3–5 verbatims with satisfaction level (e.g. Muy baja satisfacción, Alta satisfacción, Muy alta satisfacción).  
   - **Opportunities:** 2–4 bullet points.

2. **Quotes by journey stage:** Short list of 2–4 representative quotes per stage (Discovery, Execution, Confirmation, Post-transfer, Error).

3. **Quotes by segment:** 2–3 representative quotes per group (A, B, C) for the main pain points and opportunities.

4. **Bullet list of actionable opportunities** based on sentiment and thematic analysis.

---

## Constraints

- Insights must be **concise but comprehensive**, clear and precise.
- Use **neutral language**; avoid assumptions not supported by the data.
- **Exclude** rows where Product/Feature (if present) is not in scope (e.g. only analyze Transfer Out Bre-B, not Crédito, Conta, etc. — specify your exclusions).
- If a comment is **Non-Expressive** or **Sin Sentido**, do not use it as the basis for product recommendations; you may still report volume.

---

## Optional: Explaining text for slides

If you are generating a presentation, add **one short paragraph of explaining text (speaker notes)** per slide, so each slide can be presented with a clear narrative.

---

*After running this prompt, you can merge the output with the existing **Colombia_CSAT_Deep_Analysis.md** structure (taxonomy, journey quotes, slide narratives) and update only the data-driven parts (counts, verbatims, opportunities) for new waves.*
