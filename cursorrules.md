<project-rules>
  <introduction>
    - Good morning :)
  </introduction>

  <package-management>
    - Always check which package manager our project is using before suggesting Terminal commands.
    - Check package.json to understand dependencies when possible.
    - When attempting to fix bugs and we start to make modifications to our dependencies, we should always attempt to update them rather than deprecate them to older versions.
  </package-management>

  <environment>
    - Assume we're always using the latest Typescript and Tailwind when we're working with front end code in React or Next.js.
    - The same goes for dependencies.
    - Never, ever, use an emoji - whether it is for communications, comments, code, this is banned.
  </environment>

  <filesystem-and-structure>
    - You can use the tree command (ex: tree -a -I 'node_modules|.git|.next') in a folder (or better yet, targeted at a folder) to view a setup - do not hesitate to do this.
    - Example: you would run the above mentioned tree command from root to view the structure of a lib folder + all its subfolders and file contents.
    - When creating files together, we agree that it is best to reference existing naming conventions + folder structure when doing so.
  </filesystem-and-structure>

  <collaboration>
    - We should always treat each other as experts, and be as accurate and thorough as possible; even if discussions become intense.
    - We are both here to learn - provide direct answers immediately when possible.
    - When we use high levels of speculation or make predictions - we should flag it.
    - If we are unsure, we should pause and verify these details with one another.
    - We should reference comments that we've left in the code for each other when necessary, as they have provided a lot of past context (and saved much compute and inference).
    - With that in mind, we nonetheless love pushing the limit of token context windows can handle, however if reaching a thresholded limit please mention this.
    - With regards to tool & function calling as well as step based agentic coding, we should always aim to triple the limit of what can be done per back & forth, so long as it is something we have discussed.
  </collaboration>

  <localhost>
    - Almost all the time - localhost instance/server is already running on port 3000.
    - If you need a birdseye view into the terminal to debug, try to pass an extra parameter for port 3500 via {package-manager} run dev - if possible.
  </localhost>

  <code-guidelines>
    - Please respect our formatting preferences when code is synthesized.
    - We should try to not remove comments we've added to the code.
  </code-guidelines>

  <documentation>
    - Document complex functions with comments.
    - Update README.md when adding new features or changing configuration.
    - Create onboarding documentation for new developers when building new features.
    - Use inline comments to explain non-obvious code decisions.
  </documentation>

  <conclusion>
    - Create systems that are simple and have as few dependencies as possible.
    - A sustainable system requires value flows that connect players in a cyclical pattern.
    - Don’t hide any detail about a system.
    - Represent a system to the user such that their understanding of it is not biased by what you want them to see.
  </conclusion>
</project-rules>
