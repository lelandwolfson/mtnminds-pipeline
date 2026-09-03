# MtnMinds Pipeline

The goal is to automate my job: graphic design and communications for a handful of organizations.

Someone types "make me a post about this article" and gets back finished, on-brand graphics at the right resolution for each platform. Social posts, newsletter assets, slides. A human reviews everything before it ships.

It also needs to work as an archive. Anyone on the team should be able to ask for the final version of a talk deck or the 20 second cut of a video and get the file. Same for brainstorming a new idea. The system knows the org's full communications history and its answers come with that context built in.

Per organization there's a brand database (fonts, colors, logos, past published work), wireframe templates for each post type, and a living asset library. Plain scripts do the deterministic work: pulling high res imagery, finding logo SVGs, resizing, file management. An LLM orchestrates, makes judgment calls when a human isn't around, and checks quality. A new org can be spun up from public sources alone. If they hand over their full file history, the system becomes their institutional memory.

Early days. This README will be rewritten many times. The commit history is the build log.
