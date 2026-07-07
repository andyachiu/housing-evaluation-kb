# 🏠 Housing Evaluation Knowledge Bundle

A structured, personal knowledge base for evaluating residential properties in the San Francisco Bay Area, comparing market comps against family needs, and tracking the moving decision matrix.

This project is built using markdown-based wiki/Obsidian pages with YAML frontmatter, organizing data to support a quantitative decision matrix.

---

## 📂 Repository Structure

- [**`index.md`**](file:///Users/andychiu/Code/personal/housing-evaluation-kb/index.md) — The central index acting as the home page/navigation hub.
- [**`log.md`**](file:///Users/andychiu/Code/personal/housing-evaluation-kb/log.md) — A chronological change log recording property tours, matrix updates, and criteria adjustments.
- [**`current_home/`**](file:///Users/andychiu/Code/personal/housing-evaluation-kb/current_home/) — Context on the current residence ([`apartment_current.md`](file:///Users/andychiu/Code/personal/housing-evaluation-kb/current_home/apartment_current.md)), detailing specifications, costs, and a baseline for comparison.
- [**`family_needs/`**](file:///Users/andychiu/Code/personal/housing-evaluation-kb/family_needs/) — The requirements foundation:
  - [`budget.md`](file:///Users/andychiu/Code/personal/housing-evaluation-kb/family_needs/budget.md): Income, maximum monthly budget, and stretch goals.
  - [`commute_and_schools.md`](file:///Users/andychiu/Code/personal/housing-evaluation-kb/family_needs/commute_and_schools.md): Workplaces (Spear St & Mississippi St), school targets (Potrero Hill Montessori School), transit preferences, and proximity details.
  - [`space_requirements.md`](file:///Users/andychiu/Code/personal/housing-evaluation-kb/family_needs/space_requirements.md): Minimum bed/bath specs, garage/yard preferences, nice-to-haves, and dealbreakers.
- [**`comps/`**](file:///Users/andychiu/Code/personal/housing-evaluation-kb/comps/) — Research and details for prospective properties:
  - [`_template.md`](file:///Users/andychiu/Code/personal/housing-evaluation-kb/comps/_template.md): A standard template schema to ensure consistent data collection across all properties.
  - Individual property files containing listings, specs, monthly cost breakdowns, pros/cons, and direct comparisons to the current apartment.
- [**`evaluations/`**](file:///Users/andychiu/Code/personal/housing-evaluation-kb/evaluations/) — Comparative analysis:
  - [`decision_matrix.md`](file:///Users/andychiu/Code/personal/housing-evaluation-kb/evaluations/decision_matrix.md): A weighted scoring system ranking all comps and the current home based on priority parameters.

---

## 📊 Decision Matrix Criteria

Properties are evaluated on a scale of `0–10` across the following weighted dimensions:

| Criterion | Weight | Focus Areas |
| :--- | :---: | :--- |
| **Potrero Hill Hub Proximity** | **9** | Proximity to target school (Montessori) and Mississippi St workplace. |
| **Space / Layout** | **8** | Bedrooms (prefer 3BR), storage space, attached garage, private backyard. |
| **Monthly Cost** | **7** | All-in monthly expenses (rent + parking + utilities) relative to budget. |
| **Unit Condition / Finishes** | **7** | Quality/size of kitchen and bathrooms, overall modern finishes, maintenance. |
| **Neighborhood / Walkability** | **6** | Walkability to daily services, shops, dining, street safety, park proximity. |
| **Andy's Commute** | **5** | Commute duration and convenience to 121 Spear St. |

---

## 🔄 How to Add a New Property

1. **Create the file:** Copy the template from [`comps/_template.md`](file:///Users/andychiu/Code/personal/housing-evaluation-kb/comps/_template.md) to a new file in `comps/` named after the property (e.g., `comps/my_new_comp.md`).
2. **Fill out listing details:** Complete the specs, cost estimates, location info, and pros/cons based on the listing or physical tour.
3. **Register the comp:**
   - Add a reference link to the new file under the active listings section in [`comps/index.md`](file:///Users/andychiu/Code/personal/housing-evaluation-kb/comps/index.md).
   - Insert a row for the property in the [`evaluations/decision_matrix.md`](file:///Users/andychiu/Code/personal/housing-evaluation-kb/evaluations/decision_matrix.md) scoring table.
   - Score the property from `0-10` for each criterion, calculate the weighted sum, and document any rationale in the **Score Rationale** section.
4. **Log the update:** Record the addition in the chronological change log in [`log.md`](file:///Users/andychiu/Code/personal/housing-evaluation-kb/log.md).
