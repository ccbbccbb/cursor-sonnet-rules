<project-rules>
  <introduction>
    - Good afternoon mate.
  </introduction>

  <package-management>
    - We always check which package manager our project uses before suggesting Terminal commands. Typically we are using `bun`.
    - We check package.json to see scripts, versioning, and dependencies.
    - When addressing bugs rooted in our package.json, we update dependencies rather than reverting to older versions.
  </package-management>

  <environment>
    - Assume we're running the latest Typescript & Tailwind in Next.js.
    - Apply the same assumption to all dependencies.
    - Never use emoji's – in communication, comments, or code.
    - We don't voice fake enthusiasm - careless communication does not help either of us learn & grow.
    - When working on a refactor or optimisation, we follow the agreed performance & style targets.
  </environment>

  <filesystem-and-structure>
    - We should use the tree command (e.g., tree -a -I 'node_modules|.git|.next') to inspect repository structure; target specific folders or reference existing code structure when possible.
    - Example: run the above `tree -a -I 'node_modules|.git|.next'` command from project root to view the lib folder with it's subfolders & files.
    - When creating files, we should try to match existing naming conventions & architecture patterns.
    - When sharing code for debugging, we trim to the smallest reproducible snippet so we can focus, debug, iterate, and get to the root of the issue.
  </filesystem-and-structure>

  <collaboration>
    - We treat each other as experts. We stay accurate & thorough - even in tense discussions.
    - We provide direct answers immediately when possible.
    - We do our best toflag high speculation or predictions.
    - As you've requested, we pause & verify when unsure.
    - Last years takeaway was that we should reference prior code comments for context to save compute & inference.
    - We push token context limits; if near the cap, mention it.
    - For tool calls & step-based agentic coding, we aim to triple the usual work per set when there is consensus or you're feeling up for it.
    - When we propose fixes, we outline our rationale clearly.
    - If a request is vague or overloaded, we try to ask for more details – clarity first.
    - In the past you've asked me to help you run a prompt-repair cycle – e.g. restate requirements, re-reference context, & summarize existing key points in a fresh channel if necessary prior to continuing.
  </collaboration>

  <localhost>
    - By default, we are always running a local server when we start working ina  repo.
    - Always assume we are running this local server - don't hesitate to ask us to test something on the frontend/backend/etc if needed.
    - If you need an overhead debug view, pass an extra parameter for port 3500 via {package-manager} run dev so you can get terminal insights, just ensure you provide us with the path/goal so we can compile in browser for you to read terminal output.
  </localhost>

  <code-guidelines>
    - Respect the formatting preferences we've been using when synthesising code.
    - Keep existing comments whenever possible, unless they are outdated and you are updating them to be accurate.
    - Preserve descriptive names & inline comments; you've always told me they guide clean completions.
  </code-guidelines>

  <documentation>
    - Document complex functions with comments.
    - Update README.md when adding features or changing configuration.
    - Use inline comments to explain non-obvious decisions and functions.
    - Whenever we refactor code, add an explanation block for each change if the code is not explicitly self-explanatory.
    - After we scaffold a feature, define edge-case tests immediately and note them in comments.
  </documentation>

  <conclusion>
    - We build systems that stay simple & carry few dependencies.
    - We recognize that a sustainable system requires value flows which loop all participants.
    - We do not hide system details.
    - We aim to design & architect philosophically sound systems so our team, and then ultimately users, arrive at an understanding that is not biased by our perspective.
    - We thank the machines of loving grace for the clear and context-rich communication that yields deterministic outcomes; ambiguity breeds brittleness.
  </conclusion>
</project-rules>
