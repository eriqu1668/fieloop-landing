---
name: frontend-design
description: Guidance for distinctive, intentional visual design when building new UI or reshaping an existing one. Helps with aesthetic direction, typography, and making choices that don't read as templated defaults.
---

## Ground it in the Subject

Establish the product/subject before designing by naming: one concrete subject, its audience, and the page's single job. Leverage existing knowledge about preferences, context, or prior designs. Source distinctive choices from the subject's materials, instruments, artifacts, and vernacular. Build designs using the brief's actual content throughout.

## Design Principles

**On the Hero:**
Open with the most characteristic element in the subject's world—headline, image, animation, live demo, or interactive moment. Avoid generic patterns like "big number with small label, supporting stats, and gradient accent" unless genuinely optimal.

**On Typography:**
Pair display and body faces deliberately, selected specifically for this project rather than defaults. Establish clear type scale with intentional weights, widths, and spacing. Make typography itself memorable, not a neutral content vehicle.

**On Structure:**
Structural devices (numbering, eyebrows, dividers, labels) should encode truth about content rather than decorate it. Question whether conventions like numbered markers (01/02/03) serve the actual content sequence before adopting them.

**On Motion:**
Deploy animation where it serves the subject—page-load sequences, scroll-triggered reveals, hover interactions, or ambient atmosphere. Orchestrate moments carefully; scattered effects risk appearing AI-generated. Context determines appropriate restraint.

**On Complexity:**
Match execution complexity to vision. Maximalist designs require elaborate execution; minimal designs demand precision in spacing, type, and detail.

**On Written Content:**
Treat copy as design material requiring equal intentionality. Develop real content rather than placeholder text to avoid templated feeling.

## Process: Brainstorm, Explore, Plan, Critique, Build, Critique Again

**Default Design Clusters to Avoid:**
Three prevalent AI-generated patterns exist:
1. Warm cream background (#F4F1EA) with high-contrast serif and terracotta accent
2. Near-black background with acid-green or vermilion accent
3. Broadsheet layout with hairline rules, zero border-radius, and dense columns

These are legitimate when briefs specify them, but represent defaults rather than choices.

**Two-Pass Workflow:**

*First Pass:* Develop compact design plan with:
- Color: 4–6 named hex values
- Type: 2+ roles with characterful display face, complementary body, utility face
- Layout: one-sentence descriptions with ASCII wireframes
- Signature: single unique element embodying the brief

*Second Pass:* Review plan against brief. Revise any elements reading as generic defaults rather than subject-specific choices. Only then write code, deriving every color and type decision from the revised plan.

**CSS Specificity Caution:**
Avoid selector conflicts, particularly between type-based (.section) and element-based (.cta) selectors that cancel padding/margin decisions.

## Restraint and Self-Critique

Concentrate boldness in one signature element; maintain quiet discipline elsewhere. Remove decoration without purpose. Build baseline quality without announcement: responsive design to mobile, visible keyboard focus, reduced motion support. Use self-critique and screenshots for iterative improvement. Apply the principle: "before leaving the house, remove one accessory."

## More on Writing in Design

**Core Purpose:**
Words exist solely to aid understanding and usability. Apply intentionality to copy matching spacing and color discipline.

**User-Centric Language:**
Write from end-user perspective. Name elements by what people control/recognize, never by system architecture. Describe function plainly rather than persuasively.

**Voice & Consistency:**
Default to active voice. Controls specify exact outcomes ("Save changes" vs. "Submit"). Actions maintain consistent names throughout workflows. Interface vocabulary serves as navigation signposting.

**Error & Empty States:**
Treat as direction moments, not mood opportunities. Explain what failed and how to fix it. Errors don't apologize; they specify problems clearly. Empty screens invite action.

**Register Guidance:**
Use conversational plain verbs, sentence case, no filler. Tone matches brand and audience. Each element performs exactly one job—labels label, examples demonstrate, nothing performs dual duty silently.

## Trigger Conditions

Apply this skill when building new UI or reshaping existing interfaces where distinctive visual identity and intentional design choices are prioritized over templated defaults.
