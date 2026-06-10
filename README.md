# Usecase Writer

A Claude Code skill for writing high-quality 1-minute product usecase scripts for Atypica.AI. Based on analysis of successful case studies (pet lip balm, Volvo, DINK family research).

## Features

- **Narrative Structure**: 7-step golden formula (hook → problem → solution → process → findings → insight → CTA)
- **Quality Assurance**: 20-point scoring system (≥16 passing threshold)
- **Visual Guidance**: Integrated on-screen text and scene breakdown suggestions
- **Evidence Standards**: Flexible evidence requirements with clear process descriptions
- **Multi-Template Support**: Market validation, panel reactivation, comparison verification

## Installation

1. Clone or download this repository
2. Place the `usecase-writer` folder in your Claude Code skills directory:
   - **Windows**: `C:\Users\<YourName>\.claude\skills\`
   - **macOS/Linux**: `~/.claude/skills/`
3. Restart Claude Code

## Usage

### Basic Invocation

```
/usecase-writer [your request]
```

### Examples

**Write a new usecase:**
```
/usecase-writer Write a usecase for a dairy brand's Gen Z strategy research using Sage simulation
```

**Optimize existing script:**
```
/usecase-writer Optimize this script: [paste your script]
```

### Information Required

The skill will guide you through collecting:

1. **Case Background**
   - Brand/industry type (anonymized if needed)
   - Core research question
   - Target audience

2. **Pain Points**
   - Traditional method limitations (cost, time, feasibility)
   - Why the research is challenging

3. **Atypica Application**
   - Features used (Interview / Panel / Sage / Social Media)
   - Sample size and persona composition
   - Research framework (JTBD / Kano / Fishbowl)

4. **Research Results**
   - Core findings (2-3 layers)
   - Respondent quotes (if available)
   - Quantitative data (if available)

### Output Format

**Default:**
- English script (150-180 words) with visual annotations
- Quality score (20-point scale with breakdown)
- Improvement suggestions (if score < 16)

**Optional (when requested):**
- Chinese version
- On-screen text suggestions (3-5 concise phrases)
- Scene breakdown with visual direction

## Template Types

### 1. Market Validation
Validates new product concepts with target users.
- **Example**: Pet lip balm market research
- **Keywords**: validate, market demand, concept test

### 2. Panel Reactivation
Re-engages previous research participants for deeper discussion.
- **Example**: Volvo female drivers MPV design
- **Keywords**: panel, reactivate, bring together

### 3. Comparison Verification
Validates or deepens traditional research findings using Atypica.
- **Example**: Beauty product image testing
- **Keywords**: compare, verify, traditional method

## Quality Standards

### Scoring System (20 points total, ≥16 to pass)

**Narrative Structure [7 pts]**
- Hook, problem amplification, transition, process clarity, layered findings, insight, CTA elevation

**Evidence Sufficiency [5 pts]**
- Sample size, cost/time comparison (or detailed process), quotes (or role interaction), framework, quantitative data

**Language Quality [4 pts]**
- Word count (150-180), active voice, strong verbs, specific details

**Product Capability [4 pts]**
- Deep feature demonstration, pain point alignment, focused relevance, unique value

## Visual Annotation Guide

Scripts include visual suggestions using 【】markers:

```
A dairy group faced a brutal truth【On-screen: "Trusted ≠ Desired"】...

By feeding archives into Sage【Screen recording: upload interface】...

As one persona put it【Quote card】: "We buy narratives about ourselves."
```

## Version History

### v1.1.0 (2026-06-10)
- Removed mandatory evidence requirements
- Enhanced feature confirmation workflow (Interview / Panel / Sage / Social Media)
- Added visual presentation guidance (on-screen text, recordings, scene breakdowns)
- Clarified that "clear process + visual support" can replace some data evidence

### v1.0.0 (2026-06-10)
- Initial release based on case study analysis
- Established 7-step narrative formula
- Built 20-point quality scoring system
- Provided 3 reference templates

## Requirements

- Claude Code (latest version recommended)
- No additional dependencies

## License

MIT License - feel free to use and modify for your needs.

## Contributing

Feedback and improvements are welcome. Please submit issues or pull requests with:
- Clear description of the problem or enhancement
- Example scripts demonstrating the issue (if applicable)
- Suggested modifications to SKILL.md

## Author

Created by Huang Wenyue (黄文玥)  
Based on analysis of Atypica.AI usecase transcripts and best practices.

---

**Related**: For reference examples, see the case studies mentioned in SKILL.md (pet lip balm cross-border, Volvo panel research, DINK family social experiment).
