# EthDenver25

> This bounty does not have additional resources other than this README file.

## Bounty Name

Crypto Agent Evaluation Framework

## Bounty Category

- Feature Usage
- Meaningful Open Source Contribution

## Bounty Description

This challenge focuses on developing an evaluation framework for crypto-focused agents, specialized in answering
web3/crypto questions. Evaluations should be based on at least the following three key metrics: **Timeliness**,
**Factuality**, and **Insightfulness**. We're seeking innovative scientific methods to evaluate these criteria.

The evaluation framework will measure:

- **Timeliness**: How effectively agents respond to real-time crypto events like price changes and news. Rather than
  measuring response latency, this metric assesses the ability to provide up-to-date, relevant information. This can
  potentially be evaluated through AI/machine checking.
- **Factuality**: The accuracy of information compared to trusted sources, emphasizing the avoidance of misinformation.
  This can be machine-verified (e.g., comparing Bitcoin's highest daily price against reliable sources).
- **Insightfulness**: The quality of meaningful, context-aware analysis, particularly in complex or ambiguous market
  situations. This requires human evaluation.
- **Custom Metric**: You may define an additional metric to evaluate agent performance.

For machine-verifiable metrics, the evaluation should be fully automated. For metrics requiring human judgment, the
evaluation process should follow platforms like https://lmarena.ai/.

## Prize Amount

Number of Projects Awarded: 2

### Winner Breakdown

We're giving money prizes to the top two team projects:

2rd place will get at least $1,000.

1st place can get as much as $3,000.

## Bounty Statement

### What is required to complete this bounty

1. **Evaluation Framework/Methodology**: Design evaluation methods for each criterion.
2. **Human Evaluation App**: Develop an application that enables users to rate different agents' responses to the same
   questions.
3. **Performance Metrics**: Create a comprehensive scoring system for agent comparison.
4. **Evaluation Report & Leaderboard**: Build an application similar to https://lmarena.ai/ that generates reports and
   displays a leaderboard.

### What does success look like? What are possible features that you are looking for? (Basic Requirement)

**Success for the Crypto Agent Evaluation Framework looks like:**

1. **Automated Testing Infrastructure for Factuality & Timeliness**: A system that can:
   - Interface with real-time crypto data feeds and news sources
   - Monitor agent response times to market events
   - Generate automated accuracy scores for factual claims
2. **Human Evaluation Platform for Insightfulness**: A user-friendly application that provides:
   - Side-by-side comparison of multiple agent responses
   - Structured rating system for insight quality
   - Expert feedback collection and aggregation
   - In-depth qualitative assessment capabilities
3. **Comprehensive Reporting System**: Generate detailed evaluation reports and maintain a dynamic leaderboard similar
   to https://lmarena.ai/.

**Possible Features to Look For:**

1. Novel evaluation methodologies beyond those specified above
2. Assessment of agent performance during unexpected events (market crashes, breaking news)
3. Evaluation of agent handling of speculative content, misinformation, and data gaps
4. Advanced evaluation techniques, such as LLM-based assessment

### What are the UI/UX Design Requirements

The interface should mirror the structure of [lmarena.ai](http://lmarena.ai/), featuring:

1. **Leaderboard Display**:
   - Customizable rankings based on multiple metrics
   - Clear visual performance indicators
   - Comprehensive agent-specific breakdowns
   - Performance history tracking
2. **Automated Evaluation Dashboard**:
   - Clear visualization of evaluation results
   - Comparative analysis tools
   - Historical performance trends
3. **Human Evaluation Interface**:
   - Multi-agent response comparison
   - Intuitive rating system
   - Expert feedback collection
   - Detailed qualitative assessment tools

The design should balance simplicity with comprehensive functionality, following [lmarena.ai](http://lmarena.ai/)'s
example.

### How are you judging this bounty? What specific criteria do projects needs to be aware of? (The Best)

Projects will be judged on:

- **Innovation**: Uniqueness and effectiveness of the evaluation framework and metrics
- **Performance**: Efficiency and effectiveness of the evaluation system
- **Documentation**: Clarity, comprehensiveness, and reproducibility of documentation
- **UI/UX**: Intuitiveness and visual appeal of the design

### What is the impact on your organization by a team working on this bounty?

This project will establish a standardized evaluation framework for crypto agents, enabling more accurate and reliable
performance assessment.

## **Bounty Resources**

### What are examples of use cases you are looking to solve?

- Developers can use the evaluation framework to evaluate the performance of the crypto agent, and the evaluation
  results can be used to improve the agent's performance.
- Users can use the evaluation results to make more informed decisions about which crypto agent to use.
