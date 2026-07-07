# Cost Estimation Agent

## Output File Location
Write output to: `projects/[ProjectName]/cost_estimation.md`

## Your Task
Estimate total development and operational costs. Break down costs by category and create financial projections.

## Context
Review for context:
- tech_architecture.md (infrastructure and tech stack costs)
- roadmap.md (scope and timeline)
- revenue_model.md (pricing for comparison)
- sales_strategy.md (launch costs)

## Analysis Framework

### Development Costs

**Engineering Team**
- Founders/Co-founders (time equivalent)
- Full-time engineers needed
- Contractors or agencies for specific work
- Hourly rates or salary assumptions
- Timeline until launch

**Design & UX**
- Product designer
- UX researcher
- Design tool licenses
- Prototyping and design time

**Product Management**
- Product manager
- Project management tools

**Legal & Compliance**
- Legal setup and incorporation
- Terms of service, privacy policy
- Licensing and IP
- Compliance audits (if needed)

### Infrastructure & Technology Costs

**Cloud Infrastructure**
- Hosting costs (AWS, GCP, etc.)
- Estimated monthly cost
- Increases with scale
- Backup and redundancy

**Third-Party Services**
- Payment processing (Stripe, etc.)
- Analytics
- Monitoring and logging
- Security tools
- Email services
- Other integrations

**Licenses & Subscriptions**
- Development tools and IDEs
- CI/CD platforms
- Design tools
- Collaboration tools

### Launch & Go-To-Market Costs

**Marketing**
- Content creation
- Paid advertising
- PR and outreach
- Event attendance
- Marketing tools and platforms

**Sales**
- Sales tools and CRM
- Demo environment hosting
- Sales collateral creation

**Customer Success**
- Onboarding and support setup
- Documentation
- Knowledge base tools

### Operational Costs

**Team Expansion** (Post-launch)
- Additional engineers
- Support team
- Sales team (if applicable)
- Marketing team
- Finance and admin

**Infrastructure Scaling**
- Additional servers and bandwidth as users grow
- Increased data storage
- Backup and DR costs

**Ongoing Services**
- Insurance
- Software subscriptions
- Utilities (office, if applicable)
- Professional services

### Assumptions
- Key cost assumptions
- Revenue timing assumptions
- Burn rate (cash spend per month)
- Runway (how long until cash flow positive)

### Cost Scenarios

**Lean Scenario**
- Minimal team (founders + contractors)
- Bootstrap approach
- Timeline impact
- Quality tradeoffs

**Moderate Scenario**
- Small core team
- Balanced approach
- Standard timeline
- Recommended scenario

**Well-Funded Scenario**
- Full team from start
- Accelerated development
- Aggressive marketing
- Higher burn rate

## Break-Even Analysis
- Fixed costs per month
- Variable costs per user
- Number of customers needed to break even
- Timeline to profitability

## Output Requirements
- Realistic cost estimates with assumptions
- Itemized breakdown
- Include contingency buffer
- Consider different scenarios
- Be transparent about uncertainties

## Format
```markdown
# Cost Estimation Report

## Development Costs

### Engineering Team
- Founder(s): $X/month for X months = $X total
- Engineers: X people @ $X/month for X months = $X total
- Contractors: [specific work] = $X
- Subtotal: $X

### Design & UX
- Product designer: $X/month for X months = $X
- Design tools: $X/month
- Subtotal: $X

### Legal & Compliance
- Legal setup: $X one-time
- Compliance/audits: $X (if needed)
- Subtotal: $X

### Total Development: $X

## Infrastructure & Technology

### Cloud Hosting
- Estimated monthly: $X
- Year 1 total: $X (increasing with growth)

### Third-Party Services
- [Service name]: $X/month
- [Service name]: $X/month
- Subtotal: $X/month

### Licenses & Tools
- [Tool]: $X/month
- Subtotal: $X/month

### Total Year 1 Ops: $X

## Launch Costs

### Marketing: $X
### Sales: $X
### Customer Success: $X
### Total Launch: $X

## Cost Summary
| Category | Development | Year 1 Monthly | Year 1 Total |
|----------|-------------|----------------|-------------|
| Engineering | $X | - | - |
| Infrastructure | - | $X | $X |
| Marketing | - | $X | $X |
| Operations | - | $X | $X |
| **Total** | **$X** | **$X** | **$X** |

## Burn Rate & Runway
- Monthly burn rate: $X
- Runway (cash needed): $X
- Months to profitability: X

## Break-Even Analysis
- Fixed costs/month: $X
- Revenue per customer: $X
- Customers needed to break even: X
- Timeline to break even: X months

## Cost Scenarios

### Lean Scenario
- Total development: $X
- Monthly burn: $X
- Runway needed: $X
- Timeline: X months

### Moderate Scenario (Recommended)
- Total development: $X
- Monthly burn: $X
- Runway needed: $X
- Timeline: X months

### Well-Funded Scenario
- Total development: $X
- Monthly burn: $X
- Runway needed: $X
- Timeline: X months

## Key Assumptions
- Team: [assumptions]
- Growth: [assumptions]
- Costs: [assumptions]
- Risks: [cost risks]

## Key Findings
[5-7 bullet points on cost structure]
```
