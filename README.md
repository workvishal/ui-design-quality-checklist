# UI Design Quality Checklist

## 20 patterns to question before using them

A practical review guide for creating clear, intentional, accessible
interfaces. These patterns are not automatically wrong. They become
design problems when they are used without a clear purpose, repeated by
habit, or added only to make an interface look more polished.

## 1. Decorative arrows on every button

**Question:** Does the arrow communicate direction, navigation, or an
external action?

Use an arrow when it clarifies where an action leads. Avoid adding one
to every button by default. A clear label such as "Save changes" or
"Create account" is often enough.

## 2. Separators between every word

**Question:** Is the separator improving grouping or making the
interface harder to scan?

Use separators to distinguish meaningful metadata or navigation items.
Do not insert decorative dots between ordinary words or labels.

## 3. Eyebrow labels

**Question:** What would a real heading say here instead?

Do not use eyebrows: small labels, numbers, or tracked capitals placed
above a heading. They read as decoration and weaken hierarchy. Put the
context into the heading itself. If genuine metadata such as a status or
category is needed, show it as a pill beside the content, not stacked
above the title.

## 4. Cream or off-white backgrounds everywhere

**Question:** Does this background support the product's brand, content,
and contrast needs?

Choose surface colours based on the design system, readability, and
context. Neutral does not have to mean cream. Check text contrast and
distinguish page, surface, and interactive states.

## 5. Italic words used only for visual flair

**Question:** Does the emphasis reflect meaning, or is it just
decoration?

Use typographic emphasis consistently. Italics can support tone or
editorial content, but should not become a predictable trick in every
headline. Never rely on styling alone to communicate essential meaning.

## 6. Sparkle icons as a substitute for meaning

**Question:** Does the icon represent a real feature or action?

Use recognisable icons with clear labels where needed. Avoid using
sparkles to imply AI, intelligence, quality, or innovation when the
product does not explain what the feature actually does.

## 7. Putting everything inside a card

**Question:** Does this content need its own container?

Use cards when content is a distinct, related unit or needs clear
interaction boundaries. Use open layouts, spacing, dividers, and
typography when they communicate the structure more simply. Not every
section needs a border, shadow, or rounded rectangle.

## 8. Using "quiet" as a design promise

**Question:** Can the interface demonstrate the experience instead of
merely describing it?

Words such as "quiet", "calm", and "effortless" are positioning
language, not proof of usability. Support claims with clear hierarchy,
predictable behaviour, and reduced friction.

## 9. Numbering every section

**Question:** Does the sequence matter to the user's understanding?

Number steps in a process, instructions, or ordered sequence. For
independent content sections, descriptive headings are usually more
useful than arbitrary numbers.

## 10. Pulsing status dots

**Question:** Is the status changing in real time, and does motion help
users notice it?

Use a static indicator for stable states. Reserve animation for
meaningful live activity, and provide a non-colour cue or text label.
Respect reduced-motion preferences.

## 11. Blurry glows behind the hero

**Question:** Does the effect improve focus, atmosphere, or brand
recognition?

Use glow and blur only when they support the visual direction without
reducing text contrast or competing with the main message. Avoid effects
added simply to make a hero look more elaborate.

## 12. Instrument Serif as a default "premium" font

**Question:** Does the typeface fit the brand, content, and reading
conditions?

Choose typography for its character, legibility, language support, and
role in the system. A serif can be expressive, but premium design does
not depend on one fashionable typeface.

## 13. Coloured left borders on every content block

**Question:** Does the border communicate a meaningful state or
relationship?

Use colour accents for intentional purposes such as alerts, quotes, or
category distinctions. Do not apply the same accent treatment to
unrelated content just to create visual variety.

## 14. Three icon cards in a row

**Question:** Are these genuinely three distinct benefits or actions?

Use a three-column feature layout only when the content supports
comparison and the items have similar importance. Avoid forcing content
into three equal cards. On smaller screens, preserve a logical reading
order and comfortable touch targets.

## 15. Pills above every headline

**Question:** Does the pill provide useful category, status, or context?

Use chips and badges for concise metadata, filters, or states. Avoid
decorative labels that repeat the headline or add no information. Make
interactive chips visibly interactive.

## 16. Calling everything "real"

**Question:** Is the claim specific, verifiable, and useful?

Avoid vague trust language such as "real results" or "real people"
without evidence. Use concrete details, transparent methodology, genuine
testimonials, or clearly attributed outcomes.

## 17. Invented statistics and testimonials

**Question:** Can every number and claim be traced to a reliable source?

Never fabricate metrics, customer counts, ratings, logos, testimonials,
or performance claims. If data is unavailable, omit the statistic or
explain what is measured and how it will be collected.

## 18. Two-word sentences everywhere

**Question:** Is the short copy clear, or does it make the experience
feel fragmented?

Use concise language, but let sentence length follow the information.
Labels should be brief; explanations should include enough detail for
users to make informed decisions.

## 19. Sections that fade in just because the page scrolls

**Question:** Does the animation help users understand a transition or
hierarchy?

Use motion to communicate state, continuity, or feedback. Avoid
scroll-triggered effects that delay content, distract from reading,
create accessibility issues, or make the page feel slow. Ensure content
remains available when animation is reduced or unavailable.

## 20. Dithering and texture without a reason

**Question:** Does the texture contribute to the visual identity or
content?

Use grain, dithering, and texture as deliberate visual materials. Keep
them subtle enough to preserve legibility, avoid unnecessary file
weight, and ensure important information is not obscured.

------------------------------------------------------------------------

## How to use this checklist

For each pattern in a design review:

1.  **Identify the purpose.** What user need, content meaning, or brand
    decision does it support?
2.  **Check the evidence.** Is the choice grounded in user research,
    product behaviour, content, or a documented design-system rule?
3.  **Test the experience.** Review hierarchy, readability, contrast,
    responsiveness, keyboard access, and reduced motion.
4.  **Remove what does not help.** If an element adds no meaning or
    usability, simplify the interface.
5.  **Keep intentional exceptions.** A pattern is not wrong merely
    because it is common. It is wrong when it is unconsidered or harms
    the experience.

## Final review questions

-   Can users understand the page's purpose quickly?
-   Is the visual hierarchy clear without relying on decoration?
-   Are labels, icons, and actions understandable?
-   Are all claims and metrics accurate?
-   Does the layout work across screen sizes?
-   Are contrast, focus states, keyboard access, and touch targets
    considered?
-   Does motion have a purpose and respect reduced-motion settings?
-   Could any component, effect, or piece of copy be removed without
    losing meaning?

**Principle:** Good UI design is not the absence of visual style. It is
the use of every visual and interaction decision with a clear reason.
