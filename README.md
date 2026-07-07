# AI Project Analysis Team

An intelligent multi-agent system for comprehensive project analysis and validation. Define your project idea once, and let specialized AI agents conduct deep analysis across market research, technical architecture, business model, and go-to-market strategy.

## What It Does

This system orchestrates 13 specialized AI agents that work sequentially to analyze project ideas from concept to product phase. Each agent brings expertise in a specific domain:

- **Market Research Agent**: Analyzes market size, growth, and demand
- **Competitor Analysis Agent**: Researches 0-3 competitors and competitive landscape
- **Trends & Technology Agent**: Identifies relevant tech trends and emerging tools
- **Tech Architecture Agent**: Designs technical stack and infrastructure
- **Idea Validation Agent**: Validates problem-solution fit and core assumptions
- **Revenue Model Agent**: Designs pricing strategy and unit economics
- **Customer Analysis Agent**: Builds customer personas and buying behavior
- **Sales Strategy Agent**: Creates go-to-market and sales plan
- **Roadmap Agent**: Defines MVP scope and development phases
- **Cost Estimation Agent**: Estimates all development and operational costs
- **Timeline Agent**: Creates detailed schedule and milestones
- **Risk Analysis Agent**: Identifies risks and mitigation strategies
- **Executive Summary Agent**: Synthesizes all findings into actionable recommendations

## How It Works

### 1. Prepare Your Idea
Create a project folder under `projects/` with your detailed project idea in `input.md`:

```
projects/
└── YourProjectName/
    └── input.md   (Your detailed project idea)
```

**input.md should include:**
- Problem statement (what problem are you solving?)
- Target user/market (who has this problem?)
- Proposed solution (how do you solve it?)
- Key differentiators (why you vs alternatives?)
- Relevant background (any context we should know?)

### 2. Run Analysis
From the `project-analysis-agent-team` directory, open a terminal and call Claude CLI with your project:

```bash
cd project-analysis-agent-team
claude "Analyze the project in projects/[ProjectName]/ using the system orchestrator"
```

The system will:
- Read your project input
- Orchestrate all agents in sequence
- Generate detailed reports for each analysis
- Handle errors and report issues

### 3. Review Reports
After successful analysis, your project folder contains:

```
projects/YourProjectName/
├── input.md
├── market_research.md
├── competitor_analysis.md
├── trends_technology.md
├── tech_architecture.md
├── idea_validation.md
├── revenue_model.md
├── customer_analysis.md
├── sales_strategy.md
├── roadmap.md
├── cost_estimation.md
├── timeline.md
├── risk_analysis.md
├── executive_summary.md
└── dashboard.html
```

Each report is self-contained but cross-references related reports.

## Execution Workflow

The system runs agents **sequentially** for quality and dependency management:

### Phase 1: Market Research (Parallel checks)
1. Market Research Analysis
2. Competitor Analysis
3. Trends & Technology

### Phase 2: Technical Architecture
4. Tech Architecture (reads Phase 1 outputs for context)

### Phase 3: Business Model
5. Idea Validation
6. Revenue Model
7. Customer Analysis
8. Sales Strategy

### Phase 4: Operations & Risk
9. Roadmap
10. Cost Estimation
11. Timeline
12. Risk Analysis

### Phase 5: Executive Summary
13. Executive Summary (synthesizes all reports)

## Error Handling

If any agent fails:
- **All output files are deleted** (except input.md)
- **Error message is displayed** with the issue
- **You must fix the issue** (e.g., add missing details to input.md)
- **Re-run the analysis** to retry

This ensures output consistency and prevents partial analyses.

## Report Formats

All reports follow a standardized markdown format with:

- **Executive Summary**: Quick overview and key findings
- **Detailed Analysis**: Structured sections by topic
- **Data Tables**: Key metrics and comparisons
- **Recommendations**: Actionable next steps
- **Key Findings**: 5-7 critical bullet points

## Agent Capabilities & Limitations

### What Agents Can Do
- Analyze based on provided project details
- Research using general knowledge (as of Feb 2025)
- Synthesize insights across domains
- Identify risks and opportunities
- Provide structured, actionable analysis

### What Agents Cannot Do
- Conduct real-time market research (no internet access)
- Gather proprietary competitor data
- Make definitive go/no-go decisions (that's your call)
- Guarantee accuracy for specific markets/verticals
- Include personal data or sensitive information

## Output Quality Notes

- Reports are detailed but realistic
- Estimates are ranges with assumptions stated
- Confidence levels are noted where appropriate
- Comparisons use logic over data when data unavailable
- Each report is self-contained and reviewable

## Project Organization

```
project-analysis-agent-team/
├── README.md                    (This file)
├── SYSTEM_PROMPT.md            (Orchestration logic)
├── .gitignore                  (Git configuration)
│
├── agents/                     (Reusable agent definitions)
│   ├── market_research.md
│   ├── competitor_analysis.md
│   ├── trends_technology.md
│   ├── tech_architecture.md
│   ├── idea_validation.md
│   ├── revenue_model.md
│   ├── customer_analysis.md
│   ├── sales_strategy.md
│   ├── roadmap.md
│   ├── cost_estimation.md
│   ├── timeline.md
│   ├── risk_analysis.md
│   └── executive_summary.md
│
└── projects/                   (All project analyses)
    ├── ProjectA/               (Ignored by git)
    │   ├── input.md
    │   ├── market_research.md
    │   ├── competitor_analysis.md
    │   ├── ... (all 13 reports)
    │   └── dashboard.html
    │
    ├── ProjectB/
    │   ├── input.md
    │   └── [will be generated]
    │
    └── [more projects...]
```

## Getting Started

1. **Create a project folder:**
   ```
   mkdir projects/ProjectMyIdea
   ```

2. **Write your idea in input.md:**
   ```markdown
   # Project Idea: [Your Idea]
   
   ## Problem
   [What problem are you solving?]
   
   ## Target User
   [Who has this problem?]
   
   ## Solution
   [How do you solve it?]
   
   ## Differentiators
   [Why is your solution better?]
   
   ## Background
   [Any relevant context?]
   ```

3. **Run analysis:**
   ```bash
   claude "Analyze the project in projects/ProjectMyIdea/ using the system orchestrator"
   ```

4. **Review all reports** in your project folder

5. **Make decisions** based on the analysis

## Tips for Best Results

### Input Preparation
- Be specific about target users and problems
- Describe your solution clearly
- Provide market context if known
- Share any competitive awareness
- Note any constraints (budget, timeline, skills)

### Report Review
- Start with executive_summary.md
- Dive into key areas (e.g., revenue if business model is question)
- Cross-reference related reports for complete picture
- Note assumptions and confidence levels
- Validate findings against your own research

### Iteration
- Refine idea based on findings
- Create new project folder for updated analysis
- Track changes and insights across iterations
- Use reports to inform pivots or go/no-go decisions

## Use Cases

This system works well for:
- **Validating startup ideas** before building
- **Analyzing side project opportunities** quickly
- **Assessing new features** or product pivots
- **Understanding market viability** of concepts
- **Creating business plans** for pitches or funding
- **Competitive analysis** and positioning
- **Technical architecture decisions** with business context
- **Go/no-go decision frameworks** for leadership

## Limitations & Caveats

- **Knowledge cutoff**: Analysis based on information available through Feb 2025
- **Market specificity**: Best for tech products; less reliable for niche industries
- **Assumptions matter**: Analysis is only as good as input assumptions
- **Not a substitute for**: Real customer interviews, actual market data, expert domain knowledge
- **No personal data**: System sanitizes all outputs (no emails, phone numbers, personal details)

## Contributing & Customizing

The agents are defined in `agents/` folder. To modify:

1. Edit the relevant agent markdown file
2. Adjust analysis framework or output format
3. Re-run analysis on existing project
4. Iterate until happy with output style

All agents follow similar structure for consistency.

## Privacy & Data

- **No data is stored externally** - all analysis happens locally
- **No personal information** - system avoids storing PII
- **Git ignored** - project folders are in .gitignore
- **Audit trail** - save input.md with each project for reference
- **Shareable** - agents themselves can be shared publicly (no sensitive data)

## FAQ

**Q: How long does analysis take?**
A: Typically 10-15 minutes depending on project complexity and input detail.

**Q: Can I stop analysis mid-way?**
A: Yes, but you'll need to re-run. Failed analysis deletes output files.

**Q: What if reports seem generic?**
A: Update input.md with more specific details. Better input = better analysis.

**Q: Can I use this for non-tech projects?**
A: Partially. System works best for tech/software products. May struggle with physical products or services.

**Q: How do I customize reports?**
A: Edit agent definitions in `agents/` folder, then re-run analysis.

---

**Ready to validate your idea?** Start with a detailed input.md and run your first analysis today.
