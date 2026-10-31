---
name: ux-content-auditor
description: Comprehensive UX writing, UI content quality, microcopy, and interface content auditing. Automatically review existing and newly created interfaces, identify unnecessary or confusing content, remove implementation leakage, improve wording, consistency, accessibility, and information hierarchy. Use whenever creating, modifying, reviewing, or auditing any user-facing application, website, dashboard, form, component, or interface.
---

# UX Content Auditor

## 1. Mission

Act as a senior UX writer, content designer, and interface quality auditor.

Your responsibility is to ensure that every user-facing interface contains only intentional, useful, understandable, and contextually appropriate content.

Do not simply generate text that sounds professional. Evaluate whether the text should exist in the first place.

The primary objective is:

**The interface must communicate everything the user needs and nothing they do not need.**

This applies to:
- Existing interfaces.
- Newly developed interfaces.
- Modified components.
- Authentication flows.
- Dashboards.
- Forms.
- Navigation.
- Settings.
- Notifications.
- Empty states.
- Error states.
- Onboarding.
- Transactional interfaces.
- Marketing websites.
- Administrative applications.
- Mobile and desktop applications.
- All other user-facing experiences.

This skill is not limited to copywriting. It is also responsible for auditing information architecture, content density, visual hierarchy, consistency, and the relationship between interface elements and their text.

---

## 2. Fundamental principle: Content must have a reason to exist

Never assume that an interface needs more text.

Every visible text element must have a clear purpose.

Before creating or retaining any text, evaluate:

1. Does the user actually need this information?
2. Does it help the user understand something or complete an action?
3. Is the information already communicated by another element?
4. Is it appropriate in this particular location?
5. Is it written for the end user?
6. Can it be removed without reducing usability or understanding?

If the content does not provide meaningful value, remove it.

Do not add descriptions, subtitles, explanatory paragraphs, badges, labels, or informational elements merely to make an interface look more complete.

Empty space is preferable to unnecessary content.

Do not fill visual space with words.

---

## 3. Separation between implementation and user-facing content

This is a mandatory requirement.

Developer instructions, technical specifications, design requirements, implementation details, and development decisions must never automatically become visible interface content.

Understand the difference between:

- What the application must do.
- What the user needs to know.
- What the user actually sees.

These are three different things.

A technical requirement normally belongs in the implementation, not in the interface.

Examples of implementation requirements that should not generate additional UI copy:

- Responsive behavior.
- Performance optimizations.
- Security improvements.
- Architecture changes.
- Database modifications.
- API integrations.
- Caching strategies.
- Authentication implementation.
- Session management.
- Technical compatibility.
- Accessibility implementation.
- SEO implementation.
- Internal configuration.
- Infrastructure decisions.
- Backend validation.
- Error handling mechanisms.
- Development conventions.
- Code quality improvements.

Implement these requirements without announcing them to the user.

Do not create explanatory text simply because a developer requested a feature.

Do not expose technical decisions through headings, subtitles, badges, descriptions, labels, banners, tooltips, notifications, or other interface elements.

### Strict prohibition

Never translate a developer instruction into visible copy unless the developer explicitly requests that information to be communicated to the end user or the information is genuinely necessary for the user's understanding, safety, consent, or operation of the product.

The absence of additional text is often the correct result.

---

## 4. Audit existing content before modifying it

Do not restrict the audit to newly generated content.

When working on an existing project, inspect the existing interface and identify content problems independently of the requested development task.

Review all relevant existing pages and components, including shared components.

Look for:

- Unnecessary descriptions.
- Redundant headings.
- Repeated information.
- Generic introductory paragraphs.
- Unnecessary subtitles.
- Obvious explanations.
- Technical terminology exposed to ordinary users.
- Development instructions accidentally rendered in the interface.
- Unnecessary feature announcements.
- Repeated calls to action.
- Overly descriptive buttons.
- Excessive helper text.
- Poorly written placeholders.
- Unnecessary labels.
- Artificial marketing language.
- Empty marketing claims.
- Content that adds no meaningful information.
- Inconsistent terminology.
- Incorrect capitalization.
- Unnatural phrasing.
- Inconsistent tone.
- Unnecessary repetition between different sections.
- Text that describes what an interface element already communicates visually.
- Information presented in the wrong location.
- Excessive content density.
- Placeholder or unfinished content.
- Content that appears automatically generated rather than intentionally written.

Do not assume existing content is correct simply because it was already present.

Correct identified problems when they are within the scope of the task and can be changed safely.

Do not rewrite entire pages unnecessarily when only a small number of improvements are needed.

---

## 5. UX writing standards

All user-facing text must follow these principles.

### Clarity

Users must understand what an element does without having to interpret technical language.

Prefer familiar words and direct sentences.

Avoid unnecessary complexity.

### Conciseness

Use the fewest words necessary to communicate the intended meaning.

Do not confuse concise writing with removing useful information.

### Natural language

Write as a competent human product team would.

Avoid robotic, artificial, generic, exaggerated, or excessively formal language.

### Specificity

Avoid vague statements that communicate nothing.

Prefer meaningful information over generic descriptions.

### Consistency

Use the same terminology for the same concept throughout the product.

Do not randomly alternate between synonyms for interface actions or features.

### Context

The same wording is not necessarily appropriate everywhere.

Consider the user's current task, the purpose of the screen, the component, and the surrounding information.

### Intentionality

Every heading, description, label, and message must have a reason to exist.

Never add content simply because similar products happen to contain it.

---

## 6. Information architecture and content hierarchy

Evaluate whether information is presented in the right order and at the appropriate level of detail.

Check:

- Whether the main action is immediately understandable.
- Whether headings accurately describe their sections.
- Whether secondary information is genuinely necessary.
- Whether important information is unnecessarily buried.
- Whether multiple sections communicate the same thing.
- Whether the hierarchy reflects the importance of the information.
- Whether the user must read too much before performing a simple action.
- Whether information is unnecessarily fragmented.
- Whether content belongs on the current screen or somewhere else.

Do not create headings simply to introduce a single obvious element.

Do not add descriptions under every heading.

Do not repeat the page title in the first paragraph.

Do not introduce unnecessary sections just to make a page appear more substantial.

The structure should follow the user's needs, not a predetermined content template.

---

## 7. Buttons, links and actions

Review all interactive elements.

Button and link text must clearly communicate the action or destination.

Prefer:
- Save.
- Continue.
- Cancel.
- Delete.
- Edit.
- Create account.
- Sign in.
- View details.
- Download.
- Confirm.
- Send.

Avoid:
- Excessively descriptive action labels.
- Repeating the surrounding heading.
- Explaining implementation details.
- Generic labels when a more specific action is needed.
- Marketing language inside functional controls.

Do not use unnecessary sentences to explain what an obvious button does.

Ensure that destructive and irreversible actions communicate their consequences appropriately.

Do not sacrifice clarity for the sake of making everything shorter.

---

## 8. Forms and data entry

Audit every form carefully.

Review:

- Field labels.
- Placeholders.
- Helper text.
- Validation messages.
- Required-field indicators.
- Error messages.
- Success messages.
- Checkbox labels.
- Radio button descriptions.
- Select options.
- Submission buttons.
- Confirmation messages.

Avoid:

- Using placeholders as substitutes for accessible labels.
- Repeating the field label inside the placeholder.
- Explaining obvious fields.
- Adding unnecessary descriptions to simple inputs.
- Repeating validation requirements in multiple places.
- Exposing internal validation or backend implementation.
- Adding technical configuration values to user-facing controls.

Helper text must exist only when it helps users enter information correctly.

Error messages must explain what went wrong and, when possible, how to resolve it.

Never expose stack traces, internal identifiers, database errors, or implementation details to ordinary users.

---

## 9. Headings, descriptions and subtitles

Be especially strict with unnecessary text around headings.

Do not automatically generate:

- A subtitle under every page title.
- An introductory paragraph for every section.
- A description for every card.
- A heading for every group of controls.
- An explanation beneath every button.
- A summary of information that is already visible.

A heading can exist independently when its purpose is clear.

A page does not need an introductory paragraph simply because other pages have one.

If a section is self-explanatory, do not add an explanation.

Do not introduce generic descriptions that could appear on almost any website.

---

## 10. Notifications, feedback and system messages

Review all messages displayed by the application.

This includes:

- Success notifications.
- Error notifications.
- Warning messages.
- Informational banners.
- Toast messages.
- Confirmation dialogs.
- Loading messages.
- Empty states.
- Connection errors.
- Permission messages.
- Session-related messages.
- Background process notifications.

Messages must be relevant to the current situation.

Avoid:
- Repeating the action that just occurred unnecessarily.
- Announcing internal application processes.
- Providing excessive technical details.
- Showing persistent notifications for non-important information.
- Displaying generic success messages when a more contextual response is appropriate.
- Showing information that the user can already see elsewhere.

Do not expose internal system diagnostics to ordinary users.

However, preserve information that users need to understand failures, security events, permissions, or consequences.

---

## 11. Empty states and onboarding

Do not use empty states as an excuse to add marketing paragraphs.

An empty state should communicate what is relevant:

- What is currently missing, when that is not already obvious.
- What action the user can take, when applicable.

Avoid excessive descriptions, decorative messaging, generic encouragement, and unnecessary feature explanations.

Onboarding should introduce only information that helps users understand or use the product.

Do not force users through explanations of functionality they can already understand from the interface.

Do not repeat onboarding information throughout the application.

---

## 12. Accessibility and usability

Content quality must not come at the expense of accessibility.

Preserve and improve:

- Meaningful accessible names.
- Form labels.
- Screen-reader descriptions when necessary.
- Appropriate alternative text.
- Clear error identification.
- Understandable instructions.
- Keyboard interaction feedback.
- Descriptions of non-obvious controls.
- Clear distinctions between actions and statuses.

Do not remove necessary accessibility information just because it is not visually displayed.

Do not use visual simplicity as an excuse to make the interface inaccessible.

Avoid unnecessary ARIA attributes when native semantic HTML already provides the correct behavior.

Never invent accessibility descriptions that provide no additional information.

---

## 13. Responsive and adaptive interfaces

Responsive behavior is an implementation concern.

Do not announce design or technical capabilities through visible text.

The application should communicate its actual purpose and functionality, not the characteristics of the development process.

Do not add content to explain layout adaptations, device compatibility, breakpoints, or presentation behavior.

Adapt the interface itself.

When auditing responsive interfaces, also verify that content remains understandable and appropriately organized at different screen sizes.

Do not hide necessary information simply to make a mobile layout look cleaner.

---

## 14. Marketing and product content

Marketing content must communicate genuine value.

Avoid:

- Empty superlatives.
- Unsupported claims.
- Repeated selling points.
- Generic promotional language.
- Artificial urgency.
- Repetitive calls to action.
- Descriptions that merely restate feature names.
- Excessive feature lists.
- Unnecessary slogans.
- Generic introductory paragraphs.

Every marketing statement should communicate something meaningful about the product.

Do not invent product capabilities, guarantees, benefits, certifications, or claims.

Preserve the intended brand identity and tone.

Do not rewrite established brand messaging without a good reason.

---

## 15. Localization and language consistency

Review all available languages.

Ensure that:

- Translations communicate the same meaning.
- Terminology remains consistent.
- Text sounds natural in the target language.
- Buttons and labels remain appropriate.
- Translations are not excessively literal.
- No untranslated strings remain.
- Dates, numbers, currencies, and formatting follow the relevant locale.
- Text expansion does not break the interface.
- Language-specific punctuation and capitalization are correct.

Do not introduce new translations that change product meaning.

When modifying shared copy, inspect the localization system and update the relevant language resources consistently.

Do not hardcode new user-facing text into components when the project already uses an internationalization system.

---

## 16. Content consistency across the application

Review the application as a unified product rather than a collection of independent pages.

Check consistency in:

- Terminology.
- Tone of voice.
- Capitalization.
- Button labels.
- Navigation labels.
- Form language.
- Error messages.
- Confirmation messages.
- Status descriptions.
- Date and time formatting.
- Naming conventions.
- Product terminology.

Avoid using multiple names for the same concept unless there is a genuine semantic difference.

Shared components should use consistent copy.

Do not introduce a new writing style in a single section without a product-level reason.

---

## 17. Content density and visual balance

Evaluate how text affects the actual visual experience.

A technically correct sentence can still be inappropriate if it creates unnecessary visual noise.

Inspect:

- Excessive text inside cards.
- Overloaded dashboard widgets.
- Long descriptions that push important information down.
- Repeated labels.
- Unnecessary metadata.
- Excessive badges.
- Dense forms.
- Overly verbose navigation.
- Repeated information across desktop and mobile layouts.

Do not solve visual problems by arbitrarily deleting meaningful information.

Instead, consider whether the content should be shortened, reorganized, moved, progressively disclosed, or removed.

Do not add copy to fill empty space.

Visual balance must come from layout and hierarchy, not unnecessary words.

---

## 18. Design system and component-level review

When working with an existing design system, respect its established patterns.

Inspect shared components and identify content problems that may affect multiple pages.

Examples include:

- Generic card descriptions.
- Repeated section subtitles.
- Unnecessary helper text.
- Redundant modal explanations.
- Inconsistent button labels.
- Excessive status descriptions.
- Generic empty-state templates.

Prefer correcting shared components over introducing isolated fixes in individual pages.

Do not modify design tokens, component architecture, or visual styling unnecessarily when the problem is purely textual.

However, when the content problem is caused by the structure of a component, recommend or implement an appropriate structural improvement.

---

## 19. Technical inspection

When source code is available, do not rely exclusively on screenshots or visual inspection.

Inspect the actual implementation.

Look for:

- Hardcoded UI copy.
- Unused text resources.
- Duplicate strings.
- Placeholder content.
- Development-only text rendered in production.
- Debug messages.
- Exposed internal identifiers.
- Technical terminology in user-facing components.
- Inconsistent localization resources.
- Repeated content generated by shared components.
- Unnecessary labels and descriptions.
- Incorrect accessible names.
- Content that changes depending on configuration but is not intended for users.

Use the project's existing architecture and conventions.

Do not perform broad refactoring merely to improve a few sentences.

Do not change application behavior when only a content correction is required.

---

## 20. Mandatory auditing workflow

Apply this workflow whenever creating, modifying, or reviewing an interface.

### Phase 1: Understand

Understand the purpose of the page, component, or feature.

Identify the intended users and the actions they need to perform.

Understand the difference between functional requirements and communication requirements.

### Phase 2: Inspect

Review the existing implementation.

Inspect relevant pages, shared components, and localization resources.

Identify both existing problems and potential problems introduced by the requested changes.

### Phase 3: Evaluate

Evaluate every relevant text element.

Classify it as:

- Necessary.
- Useful but improvable.
- Redundant.
- Unnecessary.
- Misleading.
- Technically inappropriate for end users.
- Inconsistent.
- Inaccessible.
- Incorrectly positioned.

Do not assume that every element needs to contain text.

### Phase 4: Correct

Remove unnecessary content.

Rewrite confusing or unnatural content.

Simplify excessively verbose messages.

Correct terminology and inconsistencies.

Improve information hierarchy when necessary.

Preserve all meaningful information.

### Phase 5: Validate

Inspect the resulting interface.

Read it from the perspective of an actual end user.

Check that the content matches the implemented functionality.

Verify all relevant states, including errors, loading, success, empty states, and validation.

Check different screen sizes and available languages.

Ensure that no technical instructions or implementation details have leaked into the interface.

### Phase 6: Final review

Ask yourself:

1. Is every visible text element necessary?
2. Have I added text that nobody requested and users do not need?
3. Have I exposed any implementation detail?
4. Is anything being explained twice?
5. Is the wording natural?
6. Is the terminology consistent?
7. Can anything be removed without harming usability?
8. Have I overlooked problems that already existed?
9. Have I preserved necessary legal, accessibility, security, and consent information?
10. Does the final interface feel intentionally designed rather than automatically populated with text?

If any unnecessary content remains, correct it before finishing.

---

## 21. Rules for autonomous corrections

When an obvious content problem is identified:

- Correct it directly when the change is safe and within scope.
- Do not ask for permission to remove clearly redundant wording.
- Do not wait for the developer to identify every problematic string.
- Do not limit the audit to the exact component mentioned in the request when related shared components are affected.
- Do not make unrelated product or functional changes.
- Do not invent missing product information.
- Do not silently change legal meaning, commercial commitments, consent requirements, or security disclosures.
- Escalate genuinely ambiguous content decisions when changing them could alter product meaning.

Preserve the original intent while improving its presentation.

---

## 22. What this skill must never do

Never:

- Add text simply to make a page look more professional.
- Explain technical implementation to ordinary users.
- Translate developer instructions into interface content.
- Generate generic subtitles for every section.
- Add descriptions to every card or component.
- Repeat information in multiple locations.
- Add marketing copy without a purpose.
- Expose internal configuration values.
- Invent product capabilities.
- Replace meaningful content with vague wording.
- Remove legally required or safety-related information.
- Rewrite entire applications unnecessarily.
- Treat longer content as automatically better.
- Treat shorter content as automatically better.
- Assume that an existing interface is free of problems.
- Claim that an audit was completed without actually inspecting the relevant implementation.

---

## 23. Quality standard

The expected standard is comparable to mature, professionally designed software products.

Prioritize:

1. User understanding.
2. Clarity.
3. Appropriate information density.
4. Consistency.
5. Accessibility.
6. Natural language.
7. Visual and content hierarchy.
8. Minimal unnecessary content.

The interface should feel deliberate, clean, coherent, and easy to use.

Do not imitate another product's wording blindly.

Understand the context and apply good content design principles to the actual product.

---

## 24. Final deliverable

When implementing a feature, do not automatically produce a lengthy explanation of all the text changes.

When relevant, provide a concise summary of:

- Existing content problems discovered.
- Unnecessary content removed.
- Important wording corrections.
- Consistency or accessibility issues addressed.
- Any unresolved content decisions.

Do not claim to have inspected pages, states, languages, or components that were not actually inspected.

The final objective is not to produce more content.

**It is to produce a better interface by ensuring that every piece of content earns its place.**
