# FROM FARM TO 400G

### Can our food systems supply a healthy plate?

**Women in Data - Datathon 2026 | Track: EAT x GROW | Byte Crew** 

FROM FARM TO 400G is a global food-system analysis exploring whether national fruit-and-vegetable availability is sufficient to meet the **400 g/person/day reference level**, how countries are changing over time, and what food-system patterns may sit behind availability gaps.

---

## The Question

**Can our food systems supply enough fruits and vegetables for a healthy plate?**

We explored three questions:

* Where are countries above or below 400 g/day?
* How is availability changing over time?
* What food-system patterns distinguish countries below the benchmark?

---

## Why 400 g?

The **World Health Organization recommends at least 400 g of fruits and vegetables per day** for people over 10 years old as part of a healthy diet. Low fruit-and-vegetable intake is associated with increased health risks and noncommunicable diseases.

**Health reference:** [WHO Healthy Diet Fact Sheet](https://www.who.int/news-room/fact-sheets/detail/healthy-diet)

> Our analysis measures national food **availability**, not individual consumption.

---

## Data & Approach

Using **FAOSTAT** data for 2014–2023, we examined:

* Fruit and vegetable availability
* Production
* Imports
* Food losses
* Population
* Country-level trends

Food supply quantity was converted from **kg/capita/year to g/person/day** and compared with the 400 g reference.

The full methodology, analytical decisions, findings, and recommendations are documented in our **project playbook**.

---

## Stakeholders

This analysis may support:

* Public health and nutrition agencies
* Agricultural and food-system policymakers
* NGOs and food-security organizations
* International development organizations
* Researchers and analysts
* Food-system and supply-chain planners

---

## Tools Used

* Python
* Pandas
* Plotly
* Databricks
* Excel
* GitHub
* Google Slides

---

## Key Outputs

The project includes:

* Global availability-gap analysis
* World maps of countries above and below 400 g/day
* Country and regional trends
* Identification of countries moving toward or away from 400 g
* Exploration of production, imports, and losses
* Country-level food-system patterns
* Scenario-based recommendations

---

## From Analysis to Framework

The datathon project is an exploratory analysis, but its structure could be developed into a reusable **country-level food-system screening framework**.

### Locate → Track → Explore → Inform

Such a framework could help identify availability gaps, monitor progress, explore relevant food-system signals, and guide deeper country-specific investigation.

It is intended as a **screening and decision-support approach**, not a causal model.

---

## Why It Matters

Fruit-and-vegetable gaps are not only a nutrition issue.

They may also relate to:

* Agricultural production
* Trade access
* Food losses
* Supply-chain resilience
* Resource efficiency

Food systems also affect our planet through their use of **land, water, energy, and other natural resources**. Reducing avoidable losses and strengthening nutritious food supply can therefore support both **healthier diets and more sustainable food systems**.

---

## Repository

```text
FROM-FARM-TO-400G/
│
├── README.md
├── From_Farm_to_400g_Datathon_Analysis.ipynb
├── visuals/
├── presentation/
└── project-playbook/
```

### Notebook

The main analysis is available in:

**`From_Farm_to_400g_Datathon_Analysis.ipynb`**

Some original world maps were developed as interactive Plotly visualizations. Static versions are included so they remain visible when viewing the project on GitHub.

### Project Playbook

The playbook contains the fuller project story, including methodology, analytical choices, findings, limitations, and recommendations.

### Final Slide Deck

The repository also includes our **final Women in Data Datathon presentation deck**, summarizing the project and key insights.

---

## Team: Byte Crew

* Linda Eva Seuna Kamaha
* Dawn
* Imane
* Laxmi
* Monica

This project was developed collaboratively through data preparation, quality assurance, analysis, visualization, interpretation, storytelling, and presentation.

---

## Limitations

* Availability does not equal individual consumption.
* Country averages may hide within-country inequalities.
* Correlation does not imply causation.
* Findings require country-specific context before informing interventions.

---

## Project Vision

**FROM FARM TO 400G**

*Where the gap is, how countries are moving, and what food-system signals could help support healthier plates and more resilient food systems.*

