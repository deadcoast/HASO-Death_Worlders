# README.md

<div align="center">

<img src="./assets/hfy-logo.svg" width="140" height="140" alt="HFY Framework Logo" />

**Humans Are Space Orc Giants**

A comprehensive story framework for generating "Humans Fuck Yeah" science fiction narratives. Provides complete worldbuilding, mathematical formulas, species taxonomy, and plot structure in machine-readable format optimized for LLM consumption.

[![Claude Opus 4.1](https://img.shields.io/badge/Claude-Opus_4.1-8B5CF6?style=for-the-badge&logo=anthropic&logoColor=white)](https://www.anthropic.com/)
[![GPT-5 Ready](https://img.shields.io/badge/GPT--5-Ready-00A67E?style=for-the-badge&logo=openai&logoColor=white)](https://openai.com/)
[![Hard Sci-Fi](https://img.shields.io/badge/Genre-Hard_SciFi-FF6B6B?style=for-the-badge)]()
[![HFY](https://img.shields.io/badge/Type-HFY-FFD93D?style=for-the-badge)]()
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)]()
[![Version](https://img.shields.io/badge/Version-1.0.0-brightgreen?style=for-the-badge)]()

[Quick Start](#quick-start) • [Document Structure](#document-structure) • [Usage Guide](#usage-guide) • [Examples](#examples)

</div>

---

## Table of Contents

- [Overview](#overview)
- [Document Structure](#document-structure)
- [Quick Start](#quick-start)
- [Usage Guide](#usage-guide)
  - [For AI Models](#for-ai-models)
  - [For Human Writers](#for-human-writers)
- [Document Descriptions](#document-descriptions)
- [Usage Examples](#examples)
- [Best Practices](#best-practices)
- [Consistency Rules](#consistency-rules)
- [Troubleshooting](#troubleshooting)
- [Version History](#version-history)

---

## 🌌 Overview

**Humans Are Space Orc Giants** is a complete story universe framework designed for AI-assisted narrative generation. It establishes a scientifically-grounded HFY (Humanity Fuck Yeah) universe where humans are uniquely powerful giants in a galaxy of smaller, older civilizations.

### Core Premise

- **99.9% of intelligent life** evolved on planets 1/10th Earth's size
- **Humans are the 0.1% exception** from a Death World (Earth)
- **Size ratio**: Humans are 10x taller than average galactic species
- **Theme**: Dismissed outsiders prove their worth through action, not words

### Framework Features

✅ **Mathematically Consistent**: All species characteristics derive from planetary physics formulas  
✅ **Internally Coherent**: No contradictions, all details interconnect  
✅ **Machine-Readable**: Optimized for LLM consumption and story generation  
✅ **Expandable**: Supports multiple stories in the same universe  
✅ **Production-Ready**: Complete 4-chapter story included as reference

---

## 📚 Document Structure

This framework consists of **three primary documents**:

```

hfy-framework/
├── README.md                          # This file - Usage instructions
├── FRAMEWORK_MACHINE_READABLE.md      # Full technical specification
├── FRAMEWORK_HUMAN_READABLE.md        # Narrative-focused version
└── QUICK_REFERENCE.md                 # Condensed essentials

```

### Document Purposes

| Document | Purpose | Token Count | Use Case |
|----------|---------|-------------|----------|
| **Machine-Readable** | Complete technical spec with Python pseudocode, formulas, and structured data | ~20,000 | Full story generation, technical accuracy |
| **Human-Readable** | Narrative explanation with worldbuilding details and complete plot | ~25,000 | Understanding universe, writing reference |
| **Quick Reference** | Condensed essentials for rapid context loading | ~3,500 | Quick lookups, iteration, short context windows |

---

## 🚀 Quick Start

### For AI Models (Claude, GPT-5, etc.)

#### Option 1: Full Context (Recommended for New Stories)

```markdown
# In your IDE or chat interface:

1. Load FRAMEWORK_MACHINE_READABLE.md into context
2. Issue generation command:

"Using the framework, generate Chapter 1: First Contact between 
humans and the Galactic Coalition. Include specific details about 
the ForreFold Drive breakthrough through [g]{mid}, Aurulean reactions 
to human size, and the dismissive treatment at Coalition docks."
```

#### Option 2: Quick Reference (For Iterations)

```markdown
# For faster iteration or limited context:

1. Load QUICK_REFERENCE.md into context
2. Reference full framework only when needed:

"Using the quick reference, write a battle scene where human marines 
board a Baegk bioship. Show the size/strength calculations in action."
```

#### Option 3: Claude Projects (Persistent Context)

```markdown
1. Create new Claude Project: "Space Orc Universe"
2. Add FRAMEWORK_MACHINE_READABLE.md to Project Knowledge
3. All chats in project have automatic access:

"Generate a Portavian Elder's speech after the Battle of Sol"
```

### For Human Writers

1. **Start with FRAMEWORK_HUMAN_READABLE.md** to understand the universe
2. **Reference QUICK_REFERENCE.md** for quick facts during writing
3. **Use FRAMEWORK_MACHINE_READABLE.md** when you need exact formulas or technical specs

---

## 📖 Usage Guide

### For AI Models

#### Required Reading Before Generation

**CRITICAL**: Always read these sections before generating content:

```python
MANDATORY_SECTIONS = [
    "Core Narrative Structure",           # The 3-act HFY formula
    "Species Taxonomy",                    # Physical stats, psychology
    "Death World Theory",                  # Mathematical basis
    "Human Unique Advantages [x]",         # Why humans win
    "Consistency Rules",                   # Immutable facts
    "Story: Complete Plot Structure"       # Reference narrative
]
```

#### Generation Command Template

```markdown
TASK: [Specific scene or chapter request]

REQUIREMENTS:
- Use species data from taxonomy (exact heights, masses, gravity)
- Apply Death World Theory formulas where relevant
- Reference ForreFold Drive technical specs for space combat
- Maintain tone balance (epic + intimate moments)
- Include emotional beats, not just action
- Show human cost (they can be hurt/killed)

STYLE:
- "Practicality over design" in human dialogue/actions
- Size differences mentioned naturally (kneeling, shoulder-riding)
- Technical details integrated organically, not info-dumped
- Coalition species are advanced, not stupid

OUTPUT FORMAT: [Prose narrative / Scene / Dialogue / Technical brief]
```

#### Example Prompts

**Scene Generation:**

```markdown
"Generate first contact scene between Captain Marcus Webb (human) and 
Aurulean diplomat. Webb is 1.75m, diplomat is 0.17m. Include Webb 
kneeling to eye level, Aurulean fear of Death Worlders, and mutual 
curiosity despite size difference. 800 words."
```

**Technical Writing:**

```markdown
"Explain how the ForreFold Drive's four micro-stars generate gravity 
wells for propulsion. Include petawatt output, 15M Kelvin fusion temp, 
and why Coalition scientists initially called it impossible. Technical 
brief format, 400 words."
```

**Battle Sequence:**

```markdown
"Write Battle of Sol Phase 4: Baegk boarding actions. Show combat math 
in practice (human 70kg vs Baegk 150kg, but humans win via tactics). 
Include marine dialogue, CQC violence, and hive-mind confusion. 1200 words."
```

### For Human Writers

#### Understanding the Universe

**Step 1: Read the Complete Story** (in FRAMEWORK_HUMAN_READABLE.md)

- Chapters 1-4 demonstrate how all elements work together
- Pay attention to how formulas appear naturally in narrative
- Note emotional beats and character moments

**Step 2: Internalize Core Rules** (in QUICK_REFERENCE.md)

- Size ratio: 10:1 (humans to Auruleans) - ALWAYS
- Human philosophy: "Practicality over design" - ALWAYS
- Redemption through action, not words - ALWAYS

**Step 3: Use Formulas as Guardrails** (in FRAMEWORK_MACHINE_READABLE.md)

- Planet mass determines species height: `h = 1.75 × (m_planet)^0.6`
- Death World survival probability: Use to justify why humans are rare
- Combat effectiveness: Show, don't tell the calculations

#### Writing Process

1. **Plan your scene**: Which species? Where? What's at stake?
2. **Check consistency**: Reference species taxonomy for accurate stats
3. **Draft**: Write naturally, let technical details support story
4. **Validate**: Cross-check against Consistency Rules in framework
5. **Refine**: Add emotional beats, size-difference moments, cultural callbacks

---

## 📄 Document Descriptions

### FRAMEWORK_MACHINE_READABLE.md

**Purpose**: Complete technical specification for AI consumption

**Contains**:

- Python-style pseudocode for all systems
- Mathematical formulas with variables defined
- Species taxonomy (exact measurements, psychology, capabilities)
- ForreFold Drive engineering specifications
- Death World Theory calculations
- Galactic geography (JADES-GS-z14-0, Obscuration Zone, Sol)
- Plot structure with technical integration points
- Consistency validation rules

**When to use**:

- Generating new stories from scratch
- Need exact technical specifications
- Building expansions to universe
- Ensuring mathematical/scientific accuracy

**Token efficiency**: High information density, minimal narrative fluff

---

### FRAMEWORK_HUMAN_READABLE.md

**Purpose**: Narrative explanation for human understanding

**Contains**:

- Complete 4-chapter story as reference implementation
- Worldbuilding explanations in prose
- Character development and emotional arcs
- Thematic analysis
- All technical details from machine version, but in readable format
- Scene-by-scene breakdown with dialogue examples

**When to use**:

- First time learning the universe
- Understanding tone and style
- Seeing how technical elements integrate into narrative
- Reference for character voice and cultural details

**Token efficiency**: Lower density, optimized for comprehension

---

### QUICK_REFERENCE.md

**Purpose**: Rapid context loading for AI and human quick lookups

**Contains**:

- Essential stats only (species, planets, timeline)
- Condensed formulas
- 3-act plot summary
- Key cultural elements (ship designs, Greater Good Initiative)
- Combat specs for ForreFold Drive
- One-sentence pitch

**When to use**:

- Iterating on existing work (framework already understood)
- Limited context window
- Quick fact-checking during writing
- Need reminder of specific stat or formula

**Token efficiency**: Maximum (3,500 tokens vs 20,000+)

---

## 💡 Examples

### Example 1: Generate New First Contact Scene

**Input to AI:**

```markdown
Load: FRAMEWORK_MACHINE_READABLE.md

Task: Write an alternate first contact where Velrik merchants (22cm tall, 
from 0.15 Earth-mass planet) encounter a human trading vessel. Show their 
reaction to ship size, human physical presence, and the moment they realize 
humans navigated through [g]{mid} - something no Coalition species achieved.

Requirements: 1000 words, merchant POV, include Velrik calculating human 
bone density and being terrified.
```

**AI will generate** using:

- Velrik height from species taxonomy (22cm)
- Size calculation: human 1.75m / Velrik 0.22m = ~8x difference
- Planet mass formula to explain size
- [g]{mid} obscuration details
- ForreFold Drive as explanation for breakthrough

---

### Example 2: Expand Universe with New Species

**Input to AI:**

```markdown
Load: QUICK_REFERENCE.md

Task: Create a new Coalition species called "Lumians" from a 0.25 
Earth-mass planet. Calculate their height, describe physiology, and 
write a scene where they first see humans fight Baegk and realize 
Death Worlders aren't all the same.

Use formulas from framework. 800 words.
```

**AI will calculate**:

```python
Lumian_height = 1.75m × (0.25)^0.6 = 0.87m
# Lumians are ~2x taller than Auruleans, but still half human size
```

Then generate scene showing Lumian perspective on human-Baegk combat.

---

### Example 3: Technical Brief on Fictional Technology

**Input to AI:**

```markdown
Load: FRAMEWORK_MACHINE_READABLE.md section "ForreFold Drive"

Task: Write an in-universe technical manual entry explaining ForreFold 
Drive maintenance procedures. Include all four micro-stars, containment 
field cycling, and safety warnings. Format as DAGR Navy technical document.

500 words, formal military technical writing style.
```

**AI generates** using exact specs:

- Four micro-stars at 15M Kelvin each
- Petawatt output ranges
- Deuterium/tritium fuel specs
- 50+ year operational lifespan
- Gravity manipulation safety protocols

---

## ✅ Best Practices

### For AI Story Generation

**DO:**
✅ Always reference exact heights, masses, gravities from taxonomy  
✅ Show size differences naturally (kneeling, lifting, carrying)  
✅ Integrate formulas through character observations, not exposition  
✅ Include emotional beats alongside action  
✅ Show human vulnerability (they can be injured/killed)  
✅ Use "practicality over design" in human dialogue/decisions  
✅ Apply Greater Good Initiative when humans face moral choices  
✅ Make Coalition species intelligent but risk-averse, not stupid  

**DON'T:**
❌ Change size ratios (10:1 is immutable)  
❌ Make humans invincible (2.6% casualties in Battle of Sol)  
❌ Info-dump technical specs in dialogue  
❌ Ignore gravity/physics constraints  
❌ Make ForreFold Drive available to non-humans (until late in timeline)  
❌ Have Coalition species act illogically stupid  
❌ Forget emotional cost of violence  
❌ Skip cultural callbacks (scythe imagery, warthog ships)  

### For Human Writers

**Maintain Immersion:**

- Technical details should emerge naturally through character experience
- Use size differences for both drama and humor
- Balance epic scale with intimate character moments

**Preserve Tone:**

- Hopeful, not grimdark
- Earned respect, not demanded
- Show human pride without arrogance
- Coalition species deserve sympathy despite failures

**Check Consistency:**

- Before publishing, validate against Consistency Rules section
- Ensure all species stats match planet-of-origin formulas
- Verify timeline makes sense (3k years human, 100k years Coalition)

---

## 🔒 Consistency Rules

### Immutable Facts (NEVER CHANGE)

```yaml
CANNOT_BE_MODIFIED:
  - human_homeworld: Earth (1.0 Earth mass, Death World Class-10)
  - size_ratio: 10:1 (human to Aurulean)
  - human_spaceflight_age: 3,000 years
  - coalition_average_age: 100,000+ years
  - forrefold_drive: unique to humans (until late timeline tech sharing)
  - portavians: victims (not Auruleans)
  - baegk: death world class-12, antagonists
  - greater_good_initiative: SOL-E.001-2_A (core human law)
  - battle_location: Sol System (Earth's home)
  - redemption_method: through action, not persuasion
```

### Variable Elements (CAN MODIFY)

```yaml
CAN_BE_CUSTOMIZED:
  - specific_catalyst_events: (battles, rescues, discoveries)
  - secondary_coalition_species: (introduce new races using formulas)
  - human_character_personalities: (diverse, but death-world-forged)
  - baegk_tactical_variations: (always swarm-based)
  - timeline_extensions: (prequels, sequels, side stories)
  - minor_technologies: (as long as ForreFold remains superior)
```

### Validation Checklist

Before generating/publishing content, verify:

- [ ] All heights/masses match planet-mass formulas
- [ ] Size ratio maintained (humans ~10x larger than Auruleans)
- [ ] ForreFold Drive specs consistent (4 micro-stars, petawatt output)
- [ ] Timeline coherent (3k vs 100k year development)
- [ ] Human vulnerability shown (they take casualties)
- [ ] Coalition intelligence preserved (advanced, just different)
- [ ] Greater Good Initiative referenced if humans face moral choice
- [ ] Cultural elements present (scythes, warthogs, "practicality>design")

---

## 🔧 Troubleshooting

### Common Issues

**Issue**: AI makes humans invincible

```markdown
Solution: Remind AI of Battle of Sol casualties (2.6%, 47k deaths).
Include in prompt: "Humans can be hurt and killed. Show the cost."
```

**Issue**: Size ratios inconsistent

```markdown
Solution: Always specify exact heights in generation prompts.
"Captain Webb (1.75m) speaks to Aurulean diplomat (0.17m)"
```

**Issue**: ForreFold Drive specs vary

```markdown
Solution: Reference exact specs from framework:
"Four micro-stars, 15M Kelvin each, petawatt output, 1000x lightspeed"
```

**Issue**: Coalition species act stupidly

```markdown
Solution: Remind AI they are advanced but risk-averse.
"Coalition is 100k years old, scientifically brilliant, but cautious"
```

**Issue**: Tone too grimdark or too power-fantasy

```markdown
Solution: Specify tone in prompt.
"Balance: epic action + intimate moments, earned respect, show cost"
```

### Getting Help

- **Inconsistency found?** Cross-reference all three documents to identify source
- **Formula unclear?** Check FRAMEWORK_MACHINE_READABLE.md for Python pseudocode
- **Narrative flow issues?** Read complete story in FRAMEWORK_HUMAN_READABLE.md
- **Quick answer needed?** Check QUICK_REFERENCE.md first

---

## 📋 Usage Checklist for AI Agents

```markdown
BEFORE GENERATING CONTENT:

[ ] Framework loaded into context (machine-readable or quick reference)
[ ] Generation task clearly defined (scene, chapter, technical brief)
[ ] Required species identified with exact stats
[ ] Relevant formulas noted (if technical accuracy needed)
[ ] Tone specified (epic/intimate balance)
[ ] Output format determined (prose, dialogue, technical)
[ ] Consistency rules reviewed (immutable facts)

DURING GENERATION:

[ ] Reference exact measurements from taxonomy
[ ] Integrate technical details organically
[ ] Show size differences naturally
[ ] Include emotional beats
[ ] Apply cultural elements (scythes, Greater Good, etc.)
[ ] Maintain human vulnerability
[ ] Keep Coalition intelligent

AFTER GENERATION:

[ ] Validate against consistency rules
[ ] Check formulas applied correctly (if relevant)
[ ] Verify tone matches framework guidelines
[ ] Ensure no contradictions with established lore
[ ] Confirm character voices match species psychology
```

---

## 📅 Version History

### v1.0.0 (Current) - October 2025

- Initial complete framework release
- Three-document structure established
- Complete 4-chapter reference story included
- Mathematical formulas validated
- Consistency rules codified
- AI generation guidelines comprehensive

### Future Roadmap

- [ ] Additional example stories (Battle of Haven-7 expansion)
- [ ] More Coalition species templates
- [ ] Baegk culture deep-dive
- [ ] Pre-contact human history
- [ ] Post-war galaxy state (50+ years later)
- [ ] Visual reference materials (ship designs, species illustrations)

---

## 📜 License

MIT License - Feel free to use this framework for:

- AI-generated stories
- Human-written fiction
- Collaborative projects
- Commercial works (attribution appreciated)
- Derivative universes (with modifications)

---

## 🤝 Contributing

This is a living framework. Expansions welcome:

1. **New Species**: Use planet-mass formulas to create consistent aliens
2. **Side Stories**: Set in same universe, different characters/locations
3. **Technical Expansions**: Deep-dives on ForreFold Drive, Baegk biotech, etc.
4. **Timeline Events**: Fill gaps between Year 0-26 or explore post-war era

**Contribution Guidelines**:

- Maintain consistency with core formulas
- Preserve immutable facts
- Add to, don't contradict
- Document additions in framework format

---

## 🎯 Quick Reference Card

```yaml
ONE-SENTENCE PITCH:
  "When the galaxy's ancient Coalition abandons peaceful refugees to genocide,
   humanity—dismissed as primitive Death World giants—proves that the youngest
   species can teach the oldest what courage means."

CORE SPECIES:
  Humans: 1.75m | Death World | 3k years | ForreFold Drive | Protectors
  Auruleans: 0.17m | Optimal World | 100k years | Refuse to help | Learn lesson
  Portavians: 0.12m | Optimal World | 500k years | Victims | Refugees
  Baegk: 2.5m | Death World | 50k years | Hive-mind | Antagonists

STORY BEATS:
  Act 1: Humans dismissed by Coalition (upper/lower class dynamic)
  Act 2: Portavian genocide, Coalition abandons them, humans invoke Greater Good
  Act 3: Battle of Sol, humans annihilate Baegk fleet, save 3.8M refugees

KEY TECH:
  ForreFold Drive: 4 micro-stars, gravity manipulation, 1000x lightspeed

HUMAN ADVANTAGES:
  10x strength | 33x innovation speed | Gravity warfare | Tactical thinking

RESULT:
  Humans earn respect, Coalition learns, galaxy united against Baegk
```

---

<div align="center">

**Ready to generate?** Load your framework document and start creating.

**Questions?** Reference the specific section in FRAMEWORK_MACHINE_READABLE.md or FRAMEWORK_HUMAN_READABLE.md

**Need quick facts?** Check QUICK_REFERENCE.md

---

*"We are giants. We are different. We earned our place."*  
— Prime Marshal James Flint, DAGR Military Command

</div>
```

---

This README provides comprehensive instructions for both AI models and human writers on how to use your framework effectively. The structure mirrors professional technical documentation while being specifically optimized for AI consumption patterns. Would you like me to adjust any sections or add additional usage examples?
