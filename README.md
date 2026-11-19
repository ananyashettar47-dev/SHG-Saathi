# SHG Saathi

### AI-Powered Business Management & Empowerment Platform for Women Self-Help Groups

> **GAVS Hackathon | Tech4Bharat | Theme 8: Youth & Women
> Empowerment**

SHG Saathi is a proposed digital operations platform designed to help
Women's Self-Help Groups (SHGs) manage bulk orders, allocate production
tasks, track progress, understand costs, and maintain transparent member
payment records.

The project aims to reduce the administrative burden of coordinating
group-based production and help SHGs manage orders with greater clarity
and confidence.

## 1. The Problem

Many SHGs produce garments, handicrafts, food products, textiles, and
other handmade goods. When a group receives a bulk order, coordinating
the work can involve notebooks, phone calls, and disconnected
spreadsheets.

This can make it difficult to: - Record order quantities, delivery
dates, and material requirements. - Divide work based on members'
skills, availability, and workload. - Track production progress and
quality checks. - Understand the full cost of an order. - Maintain clear
records of work completed and member earnings.

## 2. Our Proposed Solution

SHG Saathi acts as a digital operations assistant for an SHG. It brings
order information, member details, task allocation, production updates,
and cost records into one place.

An AI assistant helps prepare plans, monitor progress, identify
potential delays, and recommend next steps. Important decisions remain
under the control of the SHG leader.

## 3. Core Features

1.  **Smart Order Management** -- Record product details, order
    quantity, buyer price, deadline, and material requirements.
2.  **AI-Assisted Task Allocation** -- Recommend task assignments based
    on member skills, availability, and workload.
3.  **Production Tracking** -- Track work through stages such as
    Assigned, In Progress, Completed, and Quality Checked.
4.  **Cost & Payment Tracking** -- Calculate material costs, labour
    amounts, order costs, and member-wise earnings using transparent,
    predefined rules.
5.  **Agentic AI Assistant** -- Help create plans, use application
    tools, monitor milestones, flag delays, and recommend corrective
    actions.

## 4. Illustrative Use Case

A group receives an order for 500 cotton bags with a 15-day delivery
window.

SHG Saathi can help the leader: - Record the order and deadline. -
Prepare a draft production plan. - Suggest task distribution based on
member capacity. - Track task completion and quality checks. - Flag
delays and recommend a revised allocation. - Prepare a cost and
work-completion summary.

**Note:** Any sample members, orders, costs, and performance figures
used in the prototype are simulated unless explicitly identified as real
and permissioned data.

## 5. What Makes It Agentic AI?

The goal is to build more than a question-answering chatbot. The
assistant is intended to follow a workflow:

1.  Understand the order and available member capacity.
2.  Prepare a multi-step production plan.
3.  Call application tools or Python functions to work with structured
    records.
4.  Monitor progress against deadlines.
5.  Identify exceptions and recommend next actions.

The AI may prepare recommendations, but the SHG leader must approve
important changes. Cost and payment calculations should be handled by
deterministic application logic, not guessed by an AI model.

## 6. Proposed Technology Stack

  Layer                  Technology
  ---------------------- ----------------------
  Programming language   Python
  User interface         Streamlit
  Data storage           SQLite
  Data handling          Pandas
  AI assistant           Gemini API (planned)
  Version control        Git and GitHub

*Update this table as the implementation evolves. Do not list a
technology as implemented until it is actually integrated.*

## 7. Project Status

**Current stage:** Concept and prototype planning.

Planned development milestones: - 
[ \] Set up the project repository
and Python environment. 
- \[ \] Build the Streamlit application
skeleton.
 - \[ \] Create member and order data models.
 -  - \[ \] Implement
order creation and management.
- \[ \] Implement task allocation
rules.
 - \[ \] Add production status tracking.
 -  - \[ \] Add cost and
member payment calculations.
 - \[ \] Integrate the AI assistant with
application tools.
 - \[ \] Test using clearly labelled simulated
scenarios.
 - \[ \] Seek feedback from an SHG coordinator or relevant
organisation, where possible.


## 8. Responsible Design

-   Use only sample or permissioned data.
-   Do not publish personal details, phone numbers, bank details, or
    identifiable member records.
-   Keep access to member earnings and sensitive records restricted.
-   Show how cost and payment calculations are derived.
-   Require human approval for important operational changes.
-   Clearly distinguish prototype demonstrations from real-world
    validation.

## 9. Repository Structure

The repository is expected to grow into a structure similar to:

``` text
SHG-Saathi/
├── README.md
├── app.py
├── requirements.txt
├── .gitignore
├── data/
│   └── sample_data.csv
├── database/
│   └── schema.sql
├── modules/
│   ├── orders.py
│   ├── allocation.py
│   ├── production.py
│   └── costing.py
├── ai/
│   └── assistant.py
├── docs/
│   ├── architecture.md
│   └── workflow.md
└── screenshots/
```


## 10. Team
                   Responsibility   	Key tasks
Member 1	Frontend & Dashboard	Streamlit UI, dashboard, order forms and member views
Member 2	Database & Backend	    SQLite database, member profiles, order records and task management
Member 3	AI & Agent Development	Gemini API, AI assistant, task allocation recommendations and delay detection
Member 4	Business Logic & Testing 	Cost calculations, payment tracking, testing, documentation and PPT


## 11. References & Learning Resources

-   [DAY-NRLM -- Aajeevika](https://aajeevika.gov.in/)
-   [NABARD](https://www.nabard.org/)
-   [Python Documentation](https://docs.python.org/3/)
-   [Streamlit Documentation](https://docs.streamlit.io/)
-   [Gemini API Documentation](https://ai.google.dev/gemini-api/docs)

These are background and technical learning resources, not endorsements
or evidence of a partnership.

## 12. Disclaimer

SHG Saathi is a hackathon project concept and prototype under
development. Features described as planned are not necessarily
implemented. The project does not claim deployment with an SHG, verified
field impact, or integration with government programmes unless such work
is completed and documented.

------------------------------------------------------------------------

**SHG Saathi -- Helping women's groups turn collective skill into
coordinated opportunity.**
