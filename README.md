Business Prompt Engineering Portfolio

Business Prompting Across Management Functions

A practical and academic portfolio demonstrating how prompt engineering can improve the quality, relevance, consistency, and reliability of generative-AI outputs in business decision-making.

This repository brings together four management-focused projects:

1. Finance
2. Marketing
3. Human Resources
4. Sales

Each section presents business scenarios and shows how prompts evolve from broad, generic instructions into structured, evidence-aware prompts that produce more actionable and hallucination-resistant outputs.

────────

Table of Contents

• Project Overview
• Purpose and Learning Objectives
• What Is Prompt Engineering?
• Core Prompt Engineering Framework
• Portfolio Structure
• 1. Finance
• 2. Marketing
• 3. Human Resources
• 4. Sales
• Common Prompt-Engineering Techniques
• Hallucination Control and Evidence Discipline
• Responsible AI and Human Oversight
• Key Learning Outcomes
• Suggested Repository Structure
• How to Use This Portfolio
• Limitations
• Future Improvements
• Author

────────

Project Overview

The purpose of this portfolio is to demonstrate that the quality of an AI response depends significantly on the quality of the prompt.

A broad prompt often produces:

• Generic explanations
• Unstructured suggestions
• Missing business context
• Unverified assumptions
• Invented figures or benchmarks
• Recommendations that are difficult to implement

A narrow and well-designed prompt can produce:

• More relevant business analysis
• Clear calculations and reasoning
• Consistent output formats
• Explicit assumptions
• Better separation between facts and recommendations
• More transparent uncertainty
• Stronger safeguards against hallucination
• Outputs that support, but do not replace, human decision-making

The portfolio follows a broad-to-narrow progression. In each business function, the prompts become more precise by adding role, context, data, constraints, output format, evidence requirements, and risk controls.

────────

Purpose and Learning Objectives

This portfolio was created to demonstrate the following learning objectives:

1. Understand prompt precision

Learn how a prompt changes when additional information is supplied, including:

• The role the AI should assume
• The business context
• The exact task
• The data available
• The limitations that must be respected
• The expected response format
• The evidence or verification requirements

2. Apply prompt engineering to business functions

Use prompt engineering in realistic management situations involving:

• Financial analysis
• Marketing planning
• Employee retention
• Sales conversion
• Risk identification
• KPI development
• Business communication
• Operational planning

3. Reduce hallucination risk

Learn how to prevent the AI from inventing:

• Financial figures
• Industry benchmarks
• Salary data
• Conversion rates
• Engagement rates
• Market statistics
• Customer or employee facts
• Causal explanations not supported by data

4. Improve decision-readiness

Transform generic AI responses into outputs such as:

• Calculation tables
• Cost rankings
• Campaign plans
• Retention plans
• Sales action plans
• Interview scorecards
• KPI lists
• Risk registers
• Executive summaries
• Weekly or 90-day implementation plans

5. Practice responsible AI use

Understand that AI-generated analysis should be treated as decision support. Human review remains essential, particularly for:

• Credit decisions
• Hiring and resume screening
• Compensation changes
• Pricing and discount decisions
• Regulatory claims
• Capital investment
• Employee-related actions

────────

What Is Prompt Engineering?

Prompt engineering is the practice of designing clear and structured instructions for a generative-AI system.

A strong prompt does more than ask a question. It defines:

• Who the AI should act as
• What situation it is analyzing
• What task it must perform
• What information it may use
• What it must not assume
• How the response should be presented
• What evidence or verification is required

The central idea of this portfolio is:

> Better instructions create more relevant, transparent, and usable AI outputs.

The portfolio also demonstrates an important distinction:

> A mathematically correct answer is not automatically a decision-ready answer.

For example, a financial calculation may be correct but still unsafe if the prompt does not distinguish verified data from assumptions or if it allows the AI to make a final decision that should remain with a human manager.

────────

Core Prompt Engineering Framework

The final prompts in the portfolio follow the structure below.

|Component      |Purpose                               |Example                                                   |
|---------------|--------------------------------------|----------------------------------------------------------|
|**Role**       |Defines the professional perspective  |“Act as a financial analyst.”                             |
|**Context**    |Explains the business situation       |“A café is considering a second outlet.”                  |
|**Task**       |States the exact work required        |“Calculate payback period and Year-1 ROI.”                |
|**Constraints**|Limits unsupported behavior           |“Use only the figures provided.”                          |
|**Format**     |Specifies the response structure      |“Present the result in a table.”                          |
|**Evidence**   |Requires transparency and verification|“Mark estimates and identify data requiring verification.”|

This can be summarized as:

Role + Context + Task + Constraints + Format + Evidence

The framework is used throughout Finance, Marketing, HR, and Sales.

────────

Portfolio Structure

The portfolio contains four management functions. Each function uses business scenarios to demonstrate prompt refinement.

|Function       |Main Business Theme                                                                        |Key Techniques                                                                                  |
|---------------|-------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------|
|Finance        |Financial literacy, cost analysis, capital budgeting, credit-risk screening, cash-flow risk|Calculations, assumption labels, scenario analysis, human-in-the-loop                           |
|Marketing      |Festive launch of a D2C hair-oil product                                                   |Audience definition, campaign planning, budget constraints, content calendars, compliance checks|
|Human Resources|Employee retention in an IT services company                                               |Exit-comment classification, retention planning, interview scorecards, fairness controls        |
|Sales          |Website and dealer-channel conversion improvement                                          |Funnel analysis, objection classification, rebuttal scripts, operational diagnosis, A/B testing |

────────

1. Finance

Business Scenario

The Finance section applies prompt engineering to five financial business cases.

The examples use a café, a café chain, a retail store, and an NBFC-style credit-risk workflow. The objective is to show how financial prompts can move from general explanations to transparent, calculation-based decision support.

Finance Cases

Case 1: Teaching Core Financial Terms to a New Trainee

The first case explains:

• Revenue
• Profit
• Profit Margin

The trainee is assumed to be a new BBA management trainee with limited finance knowledge.

The prompt progression demonstrates:

1. A basic definition of profit margin
2. An example-based explanation
3. A finance-trainer role
4. A simple café example
5. A fully constrained explanation using exact figures

The final version uses:

• Monthly revenue of ₹5,00,000
• Total expenses of ₹4,25,000
• Profit of ₹75,000
• Profit margin of 15%

It also explicitly explains that profit margin measures efficiency, not growth.

Case 2: Reviewing Café Costs Before a Pricing Decision

The café owner wants to decide whether to raise menu prices or reduce costs.

The final prompt requires the AI to:

• Calculate total expenses
• Calculate profit
• Calculate profit margin
• Identify the three highest-cost items
• Rank costs by percentage of total expenses
• Suggest one improvement action for each major cost
• Separate calculations, observations, and recommendations
• Clearly label assumptions
• Identify risks associated with each recommendation

The supplied monthly data includes:

• Revenue: ₹5,00,000
• Rent: ₹80,000
• Salaries: ₹1,50,000
• Ingredients: ₹1,20,000
• Electricity: ₹25,000
• Marketing: ₹20,000
• Other expenses: ₹30,000

The final analysis identifies salaries, ingredients, and rent as the three largest cost items.

Case 3: Capital Budgeting for a Second Outlet

A café chain is considering investing ₹15,00,000 in a second outlet.

The prompts introduce:

• Payback Period
• Breakeven analysis
• Simple ROI
• Management estimates
• Investment risks
• Feasibility-study limitations

A monthly incremental profit contribution of ₹1,20,000 is used as an explicitly identified internal estimate.

Based on that estimate:

• Payback Period = ₹15,00,000 ÷ ₹1,20,000
• Estimated payback period = 12.5 months
• Simple Year-1 ROI = -4.0%

The final prompt makes clear that the estimate is not verified market data and that a full feasibility study would require actual:

• Footfall data
• Rent information
• Local competition data
• Operating-cost estimates
• Cannibalization analysis

Case 4: Preliminary Credit-Risk Screening

This case demonstrates responsible AI use in a high-stakes financial-services context.

The AI is instructed to support a human underwriter rather than approve or reject a loan.

The example includes:

• Monthly income: ₹60,000
• Existing EMI obligations: ₹20,000
• Requested new loan EMI: ₹8,000
• Employment tenure: 3 years

The combined Debt-to-Income ratio is:

• (₹20,000 + ₹8,000) ÷ ₹60,000
• Combined DTI = 46.7%

Using the thresholds supplied in the scenario:

• Below 35%: Low risk
• 35%–45%: Medium risk
• Above 45%: High risk

The final prompt requires the AI to:

• Use only the supplied DTI information
• Avoid inferring a credit score
• Avoid assuming repayment history
• Avoid making an approval or rejection decision
• Identify exactly three additional pieces of information for human verification
• State that the output is a preliminary screening aid only

Case 5: Cash-Flow Risk Before a Seasonal Dip

A retail store owner wants to estimate cash-flow risk before a seasonal decline.

The supplied information includes:

• Q1 revenue: ₹4,00,000
• Q2 revenue: ₹3,50,000
• Base seasonal decline: 20%
• Worse-case decline: 30%
• Fixed quarterly expenses: ₹2,70,000

The final prompt compares two scenarios:

|Scenario               |Revenue  |Expenses |Net Cash Position|
|-----------------------|--------:|--------:|----------------:|
|Base case: 20% decline |₹2,80,000|₹2,70,000|+₹10,000         |
|Worse case: 30% decline|₹2,45,000|₹2,70,000|-₹25,000         |

The case demonstrates:

• Scenario analysis
• Fact and assumption separation
• Sensitivity analysis
• Precautionary planning
• Clear limitations of a simplified model

────────

2. Marketing

Business Scenario

GlowRoots is a D2C herbal skincare and haircare brand targeting urban Indian women aged 22–35 who prefer natural beauty products.

The brand is launching a new Onion Hair Oil during the October–November festive season.

The scenario includes:

• Marketing budget: ₹8 lakh
• Main channels: Instagram and the brand’s own website
• Target audience: Urban Indian women aged 22–35
• Product: Onion Hair Oil
• Campaign period: Festive season

Marketing Activities Demonstrated

Campaign Planning

The prompts evolve from:

• “Help me with marketing.”
• “Help me with a marketing campaign.”
• A marketing-manager role
• GlowRoots-specific context
• Audience definition
• Product and budget information
• A structured campaign plan

The final campaign structure includes:

• Micro-influencer partnerships
• Performance advertising
• Organic content production
• Retargeting and retention offers

The final prompt prohibits:

• Celebrity endorsements
• Spending above ₹8 lakh
• Advertising outside India

Budget Planning

The portfolio uses illustrative planning allocations such as:

• Micro-influencer partnerships
• Meta or performance ads
• Organic content production
• Retargeting and WhatsApp offers

The prompts explicitly state that cost figures must be treated as estimates unless supported by:

• Vendor quotations
• Influencer rate cards
• Platform data
• Verified campaign history
• Reliable market reports

Sentiment Classification

The marketing section demonstrates:

• Zero-shot sentiment classification
• Few-shot sentiment classification
• Positive, negative, neutral, and mixed feedback
• Separation of product feedback from delivery or packaging issues

Example categories include:

• Positive product experience
• Negative delivery experience
• Neutral feedback
• Packaging problems
• Mixed feedback involving both product satisfaction and operational problems

Instagram Content Calendar

The portfolio creates a seven-day content calendar for the Onion Hair Oil launch.

The calendar includes:

1. Teaser reel
2. Ingredient spotlight
3. Founder story
4. Launch announcement
5. Customer routine reel
6. User-generated-content repost
7. Festive bundle offer

Each day includes:

• Content idea
• Caption theme
• Call to action

KPIs

The marketing prompts identify three campaign KPIs:

• Website conversion rate from campaign traffic
• Cost per acquisition
• Engagement rate on influencer and organic content

Marketing Risks and Ethics

The portfolio identifies risks involving:

• Unverified product-benefit claims
• Misleading hair-care or health-related statements
• Undisclosed paid partnerships
• Inflated follower counts
• Fake engagement
• Unverified engagement-rate benchmarks

The suggested controls include:

• Clear paid-partnership disclosures
• Avoiding unsupported claims such as “cures hair fall”
• Authenticity checks for influencer engagement
• Verification against actual product-testing data
• Regulatory review before publication

Final Marketing Prompt

The final production-ready prompt instructs the AI to:

• Use only information provided in the conversation
• Avoid inventing engagement rates, influencer costs, or conversion benchmarks
• Write “Information not provided — requires verification” when necessary
• Present the campaign in a table
• Provide a founder summary
• End with a regulatory-compliance reminder

────────

3. Human Resources

Business Scenario

TechNova Solutions is a 600-employee IT services company.

Annual attrition among software engineers with 1–3 years of experience has reached 22%, compared with an industry average of roughly 15% in the scenario.

Exit interviews identify the following major reasons:

• Compensation: 40%
• Limited growth: 30%
• Work-life balance: 20%

HR must develop a retention plan within a capped budget.

HR Activities Demonstrated

Retention Strategy Development

The prompts move from general retention advice to a company-specific plan.

The final plan considers:

• Targeted compensation corrections
• A two-level technical career ladder
• Overtime and on-call monitoring
• Stay-interviews
• Skill-based recognition
• Manager-effectiveness training

The scenario later introduces a retention budget cap of ₹15 lakh.

Exit-Interview Classification

The portfolio classifies comments into:

• Compensation
• Growth
• Work-Life Balance
• Management

It demonstrates both:

• Zero-shot classification
• Few-shot classification

Few-shot examples are used to clarify category boundaries and improve consistency.

Interview Scorecard

A structured interview scorecard is created for a Software Engineer role.

The scorecard includes:

• Interview question
• Skill tested
• What a strong answer demonstrates

Skills include:

• Problem-solving
• Technical depth
• Time management
• Code quality
• Collaboration
• Adaptability
• Communication
• Career alignment

Retention Plan and Budget

The scenario presents a ₹15 lakh plan with illustrative allocations:

• ₹8 lakh for targeted compensation corrections
• ₹3 lakh for career-ladder design and communication
• ₹2 lakh for manager-effectiveness training
• ₹2 lakh for stay-interview follow-up actions

The prompt requires that the plan avoid blanket salary hikes.

KPIs

The HR section proposes:

• Attrition rate for the 1–3-year engineering group
• Stay-interview sentiment score
• Internal promotion rate

HR Fairness and Bias Risks

The portfolio discusses the risks of using AI to shortlist resumes.

Potential risks include:

• Reproducing historical hiring bias
• Favoring certain colleges or backgrounds
• Disadvantaging non-traditional candidates
• Using protected characteristics inappropriately

Suggested controls include:

• Periodic human review of rejected resumes
• Bias-pattern monitoring
• Human involvement in final decisions
• Avoiding protected characteristics as shortlisting inputs

Final HR Prompt

The final prompt asks for a board-ready retention plan while requiring:

• Use of only supplied information
• Verification of any industry benchmark
• A structured action table
• A CHRO summary
• HR and legal review before final hiring or pay decisions
• No automated employment action

────────

4. Sales

Business Scenario

Apex HomeAppliances sells consumer durables through:

• Approximately 400 dealers
• Its own D2C website

The business problem includes:

• Website conversion falling from 3.1% to 2.1%
• Dealer sales missing quarterly targets by 18%
• Cart abandonment increasing from 55% to 68%
• Dealer complaints about slow stock-query response
• No new hiring permitted during the quarter

Sales Activities Demonstrated

Conversion Diagnosis

The prompts move from generic sales advice to a two-channel diagnosis.

The final analysis separates:

Website issues

• Checkout friction
• Shipping-cost visibility
• Payment failures
• Additional checkout steps
• Site speed
• Funnel drop-off

Dealer-channel issues

• Slow stock-query responses
• Stock visibility
• Dealer support
• Incentive structures
• Footfall versus counter-conversion problems

Customer-Objection Classification

The portfolio classifies objections into:

• Price
• Trust
• Product Fit
• Logistics

Examples include:

• “It is more expensive than the competitor’s model.” → Price
• “I have never heard of this brand.” → Trust
• “Does it come in a smaller size?” → Product Fit
• “How long will delivery take?” → Logistics
• “Can I get an EMI option?” → Price or affordability

Few-Shot Objection Handling

The portfolio demonstrates how examples can guide the AI to:

• Classify an objection
• Generate a one-line response
• Maintain consistent category boundaries

Rebuttal Script

A structured rebuttal script is created for common price objections.

The output includes:

• Objection
• Rebuttal
• Supporting point

The examples address:

• High price
• Cheaper competitors
• Waiting for a sale

Operational Action Plan

The final sales plan includes actions such as:

• Displaying shipping costs earlier in the purchase funnel
• A/B testing checkout changes
• Creating a dedicated dealer stock-query response channel
• Reviewing funnel and dealer performance weekly

The plan respects the constraints that:

• No new hiring is allowed
• Shipping-cost structure cannot change during the quarter

KPIs

The sales section proposes:

• Cart-abandonment rate
• Average dealer stock-query response time
• Dealer sales as a percentage of quarterly target

Sales Risks and Ethics

The portfolio discusses risks of aggressive dealer incentives, including:

• Overselling unsuitable products
• Pressuring customers into unnecessary financing
• Damaging customer trust
• Masking operational problems
• Optimizing short-term volume instead of long-term value

Suggested mitigation includes:

• Linking incentives partly to customer-satisfaction measures
• Fixing stock-response problems
• Reviewing unintended consequences
• Keeping pricing and discount changes under leadership approval

Final Sales Prompt

The final production-ready prompt requires:

• Use of only supplied information
• No invented industry benchmarks
• No unsupported causal claims
• A structured action table
• A VP of Sales summary
• Leadership sign-off for pricing, discount, or shipping-fee changes

────────

Common Prompt-Engineering Techniques

The portfolio demonstrates a range of techniques.

1. Broad Prompting

A broad prompt is short and open-ended.

Example:

> “Help me with sales.”

Advantages:

• Easy to write
• Useful for initial brainstorming

Limitations:

• Generic output
• No business specificity
• High freedom for unsupported assumptions

2. Adding a Domain Keyword

The prompt names the business area.

Examples:

• “Help me improve sales conversion.”
• “Help me with employee retention.”
• “Help me with a marketing campaign.”

This improves topical relevance but does not provide enough information for a specific business decision.

3. Role Prompting

The AI is assigned a professional role.

Examples:

• Finance trainer
• Financial analyst
• Marketing manager
• HR manager
• Sales manager
• Credit-risk analyst

Role prompting helps define:

• Tone
• Perspective
• Expected depth
• Professional vocabulary
• Type of output

4. Context Injection

The prompt provides information about:

• Company
• Industry
• Product
• Audience
• Business problem
• Channel
• Time period
• Budget
• Operational constraints

Context makes the response more relevant to the actual situation.

5. Supplying Real Data

Specific numbers allow the AI to perform calculations or reason from actual facts.

Examples include:

• Revenue and expenses
• Attrition rates
• Campaign budgets
• Conversion rates
• Cart-abandonment rates
• EMI obligations
• Seasonal declines

6. Output Formatting

The prompt defines the required format.

Examples:

• Table
• Checklist
• Scorecard
• Content calendar
• Action plan
• Executive summary
• Scenario comparison

Structured output makes responses easier to review, compare, and implement.

7. Constraints

Constraints limit what the AI is allowed to do.

Examples:

• Do not invent numbers
• Do not exceed the budget
• Do not recommend new hiring
• Do not use celebrity endorsements
• Do not change shipping-cost structure
• Do not make an approval decision
• Do not use unsupported benchmarks

8. Hallucination Guards

Hallucination guards instruct the AI to:

• Use only provided information
• Mark estimates explicitly
• Identify missing data
• Avoid invented benchmarks
• State when verification is required
• Separate facts from assumptions

A particularly useful instruction used throughout the portfolio is:

> “Information not provided — requires verification.”

9. Zero-Shot Prompting

The AI receives a task without examples.

Example:

> Classify customer comments as Positive, Negative, or Neutral.

This is simple but may produce inconsistent interpretations in ambiguous cases.

10. Few-Shot Prompting

The prompt provides examples before asking the AI to classify new inputs.

Few-shot prompting helps establish:

• Category boundaries
• Expected style
• Response format
• Interpretation patterns

11. Structured Output

The prompt specifies exact columns or sections.

Examples:

• Action | Owner | Timeframe
• Metric | Formula | Result
• Question | Skill Tested | Strong Answer
• Objection | Rebuttal | Supporting Point

12. Facts vs Assumptions

This technique requires the AI to separate:

• Known facts
• Assumptions
• Recommendations

It reduces the risk of presenting a hypothesis as a verified conclusion.

13. KPI Definition

The prompt asks for measurable indicators to track whether a recommendation is working.

Examples:

• Conversion rate
• Attrition rate
• Cost per acquisition
• Engagement rate
• Stock-query response time
• Internal promotion rate

14. Risk and Ethics Analysis

The AI is asked to identify:

• Operational risks
• Financial risks
• Fairness risks
• Customer harms
• Compliance concerns
• Unintended consequences

15. Prompt Chaining

A complex task is divided into smaller steps.

For example:

1. Break the problem into sub-problems
2. Select one sub-problem
3. Investigate likely causes
4. Develop a test
5. Create an action plan

Prompt chaining makes complex business problems easier to analyze systematically.

16. Self-Critique

The AI is asked to identify weaknesses in its own recommendation.

This can reveal:

• Missing data
• Unverified assumptions
• Overlooked stakeholders
• Unsupported causal claims
• Operational gaps

17. Iterative Refinement

A new constraint is introduced after the initial plan.

Examples:

• A budget cap
• No new hiring
• No international shipping
• No shipping-cost changes
• No blanket salary hikes

The AI must revise the original plan rather than simply repeat it.

18. Two-Audience Outputs

The same analysis is adapted for different audiences.

Examples:

• Founder summary and executor plan
• CHRO summary and HRBP action plan
• VP of Sales summary and weekly sales-team plan

This demonstrates how prompt design can control both content and communication level.

────────

Hallucination Control and Evidence Discipline

A major theme of this portfolio is that AI should not be allowed to fill missing information with plausible-sounding content.

Good practices demonstrated

• Provide exact figures when calculations are required.
• Explicitly prohibit invented numbers.
• Mark internal estimates as estimates.
• Distinguish facts from assumptions.
• Ask for source verification before quoting benchmarks.
• Avoid unsupported market statistics.
• Require the AI to state when information is missing.
• Use structured outputs that expose assumptions and risks.
• Test hypotheses before making large investments.
• Avoid presenting general best practices as company-specific evidence.

Examples of information requiring verification

Depending on the scenario, the following may require external or internal verification:

• Industry attrition benchmarks
• Salary benchmarks
• Influencer pricing
• Social-media engagement rates
• E-commerce conversion benchmarks
• Cart-abandonment benchmarks
• Market-size estimates
• Competitor pricing
• Product-benefit claims
• Credit history
• Income and employment records

Important distinction

The portfolio does not claim that adding constraints makes an AI response automatically correct. Instead, constraints make the output more transparent and reduce opportunities for unsupported invention.

────────

Responsible AI and Human Oversight

AI outputs should support professional judgment rather than replace it.

Finance

AI should not independently approve or reject a loan application. It may calculate ratios and organize disclosed information, but a qualified human underwriter must review the complete file.

Human Resources

AI-assisted hiring, resume screening, compensation, and retention recommendations require human review. HR and legal teams should evaluate fairness, privacy, and employment-law implications.

Marketing

Marketing claims should be checked against actual product evidence and applicable advertising or cosmetic-claim requirements. Influencer partnerships should include appropriate disclosure.

Sales

Pricing, discounts, financing-related messaging, and shipping-fee changes should receive leadership approval. Sales incentives should not encourage misleading or coercive customer treatment.

General principle

> AI can accelerate analysis and communication, but accountability for consequential decisions remains with people.

────────

Key Learning Outcomes

After completing this portfolio, a learner should be able to:

1. Explain the difference between broad and narrow prompts.
2. Use role and context to improve relevance.
3. Add business data to support calculations.
4. Use constraints to prevent unsupported output.
5. Design tables, scorecards, calendars, and action plans.
6. Separate facts, assumptions, observations, and recommendations.
7. Use zero-shot and few-shot prompting.
8. Apply prompt chaining to complex problems.
9. Define KPIs for business initiatives.
10. Identify risks and ethical concerns.
11. Recognize when external verification is necessary.
12. Design prompts that preserve human oversight.
13. Adapt one analysis for executives and operational teams.
14. Refine a prompt when new constraints appear.
15. Treat AI as a decision-support tool rather than an autonomous decision-maker.

────────

Suggested Repository Structure

```text
business-prompt-engineering-portfolio/
│
├── README.md
│
├── finance/
│   └── Prompt_Portfolio_Finance.docx
│
├── marketing/
│   └── Prompt_Portfolio_Marketing.docx
│
├── human-resources/
│   └── Prompt_Portfolio_HR.docx
│
├── sales/
│   └── Prompt_Portfolio_Sales.docx
│
└── assets/
    └── diagrams-or-supporting-materials/
```

If the documents are later converted into Markdown, the repository may also contain:

```text
business-prompt-engineering-portfolio/
│
├── README.md
├── finance/
│   ├── README.md
│   └── finance-prompts.md
├── marketing/
│   ├── README.md
│   └── marketing-prompts.md
├── human-resources/
│   ├── README.md
│   └── hr-prompts.md
└── sales/
    ├── README.md
    └── sales-prompts.md
```

────────

How to Use This Portfolio

For students

• Read each business scenario.
• Compare the broad and narrow prompts.
• Identify what information was added at every stage.
• Examine how the AI response changes.
• Rewrite the final prompt for another business situation.

For business learners

• Select one function relevant to your area.
• Replace the fictional company information with verified business data.
• Keep the same prompt structure.
• Add constraints appropriate to the business problem.
• Require facts, assumptions, risks, and KPIs.
• Validate the output before using it.

For prompt-engineering practice

Use the following workflow:

1. State the business problem.
2. Write a broad prompt.
3. Add a professional role.
4. Add company and operational context.
5. Supply verified data.
6. Define the exact task.
7. Add constraints.
8. Specify the output format.
9. Require evidence and uncertainty labels.
10. Review the output for unsupported assumptions.
11. Test recommendations against real data.
12. Keep final decisions with the responsible human professional.

────────

Limitations

This portfolio uses illustrative business scenarios and internal figures supplied within the documents.

The examples are designed to demonstrate prompt-engineering methods. They should not automatically be treated as:

• Audited financial statements
• Verified industry research
• Professional credit decisions
• Legal or regulatory advice
• Confirmed market benchmarks
• Guaranteed business outcomes
• Final HR or hiring decisions
• Validated marketing claims
• Production-ready operational policies

Before using any prompt or recommendation in a real organization, verify:

• The data
• The assumptions
• The applicable laws and policies
• The relevant industry benchmarks
• The organization’s internal approvals
• The potential impact on customers, employees, and other stakeholders

────────

Future Improvements

Potential future additions to this repository include:

• Converting each Word document into Markdown
• Adding executable prompt templates
• Including sample datasets
• Adding spreadsheet-based financial models
• Creating evaluation rubrics for AI responses
• Comparing outputs from multiple AI models
• Adding prompt-quality scoring criteria
• Including source links for verified industry benchmarks
• Building a small prompt-testing workflow
• Adding before-and-after response comparisons
• Documenting failure cases and corrections
• Creating dashboards for KPI monitoring
• Adding privacy and data-protection checklists

────────

Author

Gurbaaz Singh
BBA FinTech and AI

This portfolio reflects practical learning in:

• Prompt Engineering
• Business Analysis
• Finance
• Marketing
• Human Resources
• Sales Management
• Responsible AI
• Decision Support
• Structured Communication

────────

Final Takeaway

The central lesson of this portfolio is that prompt engineering is not simply about asking an AI a better question.

It is about designing a complete instruction system that makes the business problem, available evidence, constraints, expected output, uncertainty, and human responsibilities clear.

A strong business prompt should help the AI answer:

1. What role am I performing?
2. What business situation am I analyzing?
3. What exact task must I complete?
4. What information may I use?
5. What must I avoid assuming?
6. How should I present the result?
7. What must be verified by a human?

When these elements are included, AI outputs become more structured, more transparent, and more useful for responsible business decision-making.
