# Agent Up, Dewi!

An interactive anime comic and click-through demos for a **new Contoso Modern Work engineer**. It's an L400 deep dive into **Microsoft 365 Copilot**, **Copilot Studio** (including its harnesses), **MCP** and **A2A**.

**Live site:** https://ibranibeny.github.io/contoso-copilot-agents-comic/

- **Read the comic:** `index.html` (click or press → to advance)
- **Click-through demos:** `demo.html`, covering Microsoft 365 Copilot (Agent Builder) and Copilot Studio (Microsoft Copilot harness): 1) adding knowledge, 2) create agent, 3) use agent, 4) publish agent
- **Auto-play:** press **A** or the **Auto-play** button and the comic plays by itself: speech bubbles, pages, checkpoint answers and diagram traffic move on their own. The speed button sets the pace (0.75× to 2×); → skips ahead, A pauses. To open a session already playing, use https://ibranibeny.github.io/contoso-copilot-agents-comic/?autoplay=1 (add `&speed=1.5` to go faster).
- **Animated traffic flows:** every architecture page plays its traffic hop by hop. Glowing packets travel each connection in order (yellow ones travel back), the boxes involved light up, and a caption explains each step. Pause, replay or pick a step.

## Cast

- **Dewi**: new Modern Work engineer at Contoso; always asks "where does it say that?"
- **Nova**: the team's robotic-hologram AI mentor; every lesson points to Microsoft Learn
- **Orbi**: the agent Dewi builds, Contoso's Onboarding Buddy
- **Kubo**: Contoso's IT Provisioning agent, hosted outside Copilot Studio, speaks A2A

The panels are hand-painted, watercolor-style anime art.

## Chapters (one continuous story)

| # | Chapter | Duration |
|---|---------|----------|
| Prologue | Welcome to Contoso | 5 min |
| 1 | The big picture: MCP, A2A, Microsoft 365 Copilot and Copilot Studio | 20 min |
| 2 | Microsoft 365 Copilot deep dive | 25 min |
| 3 | Copilot Studio and its harnesses, including the "GitHub Copilot harness" | 30 min |
| 4 | Create the agent: Agent Builder and Copilot Studio | 30 min |
| 5 | Create a skill | 25 min |
| 6 | Publish the agent | 25 min |
| 7 | Connect MCP and agent to agent (A2A) | 30 min |
| 8 | Cowork and Code | 25 min |
| 9 | Microsoft 365 Copilot or Copilot Studio: when and why | 20 min |
| Epilogue | Graduation | 5 min |

Each chapter mixes animated comic panels, animated architecture diagrams, comparison tables, a villain (anti-pattern) and a checkpoint quiz.

## Sources and accuracy

Technical content comes from the Microsoft Learn articles linked on every page (retrieved 15 November 2026). The full list is on the in-app **Sources** page. Preview features (marked as such) can change, so re-check the linked articles before you deliver.

This is workshop material, not official product documentation. Contoso and all characters are fictional. Artwork is AI-generated. Azure services in the diagrams use the official Azure Architecture Icons.

## Files

Both pages are single, self-contained HTML files (images inlined), so they work offline and on GitHub Pages without a build step.
