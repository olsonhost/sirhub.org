Create a polished, production-ready landing page for SirHub.

Project context:
- The public landing page is for sirhub.org
- The actual Forgejo instance is at https://git.sirhub.org
- The companion platform is at https://syndorela.com
- This page should act as the public front door for SirHub and explain how it relates to Syndorela
- Keep the implementation lightweight and deployment-friendly for a normal Apache web server
- Prefer plain HTML/CSS/JS, or a very small PHP page if needed
- No heavy framework unless there is a compelling reason
- No tests needed unless something unusually complex is introduced

Goal:
Build a really cool, modern, credible front page for SirHub with a serious developer aesthetic and a subtle mythic / legendary-engineering vibe that fits the Syndorela universe.

Visual direction:
- Dark modern developer theme
- Clean, high-contrast typography
- Tasteful gradients, glow, glass panels, or subtle depth effects
- Professional and fast-loading, not gimmicky
- Slight “repository forge / code vault / command center” feel
- Fully responsive for desktop, tablet, and mobile
- Strong CTA buttons
- Smooth hover states and polished spacing
- Semantic HTML and accessible contrast

Primary actions:
- Main button: “Open SirHub” -> https://git.sirhub.org
- Main button: “Start with Syndorela” -> https://syndorela.com
- Optional small anchor link near the hero: “How accounts work”

Important messaging requirements:
- Most users should begin in Syndorela
- Syndorela can automatically coordinate account setup and repository provisioning for projects
- Direct access to SirHub is still available and useful
- Users may create an account directly in SirHub, but if they do, they may need to link it to Syndorela manually later
- Phrase that gently and professionally
- The page should encourage starting in Syndorela first without sounding hostile or restrictive

Information architecture:
Build a one-page site with these sections in this order:

1. Hero
2. What SirHub Is
3. Built for automation, open for direct access
4. Developer benefits card grid
5. How accounts work
6. Why use SirHub directly?
7. Typical workflow
8. Optional simple visual diagram
9. Final CTA
10. Footer

Use the following exact copy as the baseline content. You may make tiny edits for flow, punctuation, or layout, but do not change the meaning.

PAGE TITLE:
SirHub — The Repository Forge Behind Syndorela

META DESCRIPTION:
SirHub is the Git and repository hub for the Syndorela ecosystem, combining automated project setup with full direct Git access whenever you need it.

HERO SECTION:
Eyebrow:
The repository hub behind Syndorela

Headline:
SirHub is where Syndorela projects take shape

Subheadline:
The repository hub behind the Syndorela ecosystem — built for automated project provisioning, direct Git workflows, and full visibility into the code that powers your work.

Primary button:
Open SirHub

Secondary button:
Start with Syndorela

Small helper text under buttons:
For most users, the best place to begin is Syndorela. SirHub remains available for direct repository access and advanced Git workflows.

SECTION: WHAT SIRHUB IS
Heading:
What is SirHub?

Body:
SirHub is the code and repository hub that supports the Syndorela workflow.

When a project is created through Syndorela, the required repository structure can be coordinated automatically, making it easy to move from source analysis to generated artifacts and final build targets without manual setup.

SirHub gives those projects a proper Git home: a place to store source repositories, intermediate project artifacts, generated outputs, history, branches, tags, releases, and the complete record of how a project evolves over time.

SECTION: BUILT FOR AUTOMATION, OPEN FOR DIRECT ACCESS
Heading:
Built for automation. Open for direct access.

Body:
Syndorela can provision and manage the repository side of a project for you, but serious development still benefits from direct Git-level access. SirHub is designed to support both.

That means you can enjoy a smooth automated setup through Syndorela while still retaining the ability to inspect, clone, push, review, and manage repositories directly whenever needed.

SECTION: BENEFIT CARDS
Use a 3-up grid on desktop if it fits well.

Card 1 title:
Automated project setup

Card 1 body:
Syndorela can coordinate the repository structure a project needs, reducing manual setup and keeping the workflow consistent.

Card 2 title:
Direct Git workflows

Card 2 body:
Clone, push, pull, branch, tag, and inspect repositories with normal Git tools and habits.

Card 3 title:
Developer-level visibility

Card 3 body:
Browse commits, branches, releases, generated artifacts, and repository history directly in SirHub.

Card 4 title:
Keys, tokens, and access

Card 4 body:
Manage SSH keys, personal access tokens, and direct repository authentication for advanced workflows.

Card 5 title:
Troubleshooting and control

Card 5 body:
When you need to step outside the main application flow, SirHub gives you direct access to the underlying repositories.

Card 6 title:
A stable home for project artifacts

Card 6 body:
SirHub can serve as the long-term repository layer for source code, intermediate data, generated code, and output targets.

SECTION: HOW ACCOUNTS WORK
Heading:
How accounts work

Body paragraph 1:
For most users, the smoothest experience begins in Syndorela. When you start there, Syndorela can coordinate account setup and provision the repositories your project needs as part of the project workflow.

Body paragraph 2:
Direct registration in SirHub is still available for developers who want standalone access to the forge itself, including direct repository browsing, Git operations, SSH key management, and other advanced workflows.

Body paragraph 3:
However, if you create an account directly in SirHub first, you may need to link that account to your Syndorela account manually later. For that reason, most users should begin with Syndorela unless they specifically need direct SirHub access right away.

Highlighted note / callout:
Recommended: Start in Syndorela first for the simplest setup.

SECTION: WHY USE SIRHUB DIRECTLY?
Heading:
Why use SirHub directly?

Intro:
Even in an automated ecosystem, direct access to the repository hub remains valuable.

Use these items as small feature rows, icon bullets, or mini-cards:

Item 1 title:
Browse repositories directly
Item 1 body:
Quickly inspect project repositories without leaving the forge.

Item 2 title:
Use normal Git tools
Item 2 body:
Clone, push, pull, and manage branches with the same workflows developers already know.

Item 3 title:
Manage SSH keys and tokens
Item 3 body:
Set up secure access for terminals, scripts, and automation.

Item 4 title:
Inspect history and generated artifacts
Item 4 body:
Review commits, tags, branches, releases, and machine-generated outputs in one place.

Item 5 title:
Support manual and advanced workflows
Item 5 body:
Step outside the higher-level UI when you need deeper control or troubleshooting access.

Item 6 title:
Work comfortably at the Git layer
Item 6 body:
SirHub stays available for developers who prefer to see the underlying repositories directly.

SECTION: TYPICAL WORKFLOW
Heading:
Typical workflow

Step 1 title:
1. Sign in to Syndorela
   Step 1 body:
   Begin where account coordination and project setup are easiest.

Step 2 title:
2. Start a new project
   Step 2 body:
   Define the source, intermediate storage, generated outputs, and target repositories your project requires.

Step 3 title:
3. Let Syndorela coordinate the repository layer
   Step 3 body:
   Syndorela can provision or connect the necessary SirHub resources as part of the project setup process.

Step 4 title:
4. Use SirHub whenever you want full repository control
   Step 4 body:
   Drop into direct Git access at any time for inspection, history, keys, branches, pushes, pulls, and repository administration.

OPTIONAL DIAGRAM:
If you add a simple visual diagram, label it like this:

Left node:
Syndorela
Subtext:
Project setup, orchestration, analysis, generation

Connector text:
provisions / coordinates

Right node:
SirHub
Subtext:
Repositories, history, branches, artifacts, direct Git access

Small note under diagram:
Start in Syndorela for the smoothest setup. Use SirHub directly whenever you need full repository visibility and control.

FINAL CTA SECTION
Heading:
Begin with automation. Keep direct control.

Body:
Syndorela and SirHub are designed to work together: one coordinates the project workflow, the other gives your code and artifacts a durable Git-backed home. Start with the path that fits your needs — but for most users, Syndorela is the best place to begin.

Primary button:
Open SirHub

Secondary button:
Start with Syndorela

Optional small footer note above the footer:
Standalone SirHub access is available, but most users will have a smoother experience starting in Syndorela first.

FOOTER
Include a clean minimal footer with:
- SirHub
- Link to SirHub
- Link to Syndorela
- Short line like:
  The repository forge behind the Syndorela ecosystem.

Design/content extras:
- Add tasteful iconography where helpful
- Add subtle decorative visuals or background treatment if it improves the page
- Keep the page editable and easy to maintain
- No lorem ipsum
- Use real polished copy only
- Make the CTA buttons very obvious
- The page should feel launch-ready, not like a rough mockup

Deliverables:
- Implement the actual landing page in the target website folder
- Keep file structure simple
- Include any tiny local assets if needed
- Make sure all links point to the correct live URLs
- Please implement the page, not just a mockup or design note