# Janky Markdown Todo List

**Built with [WonderChat AI](https://wonderchat.dev).**

<a href="https://apps.apple.com/us/app/wonderchat-ai/id6752497385" target="_blank">
  <img src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg" alt="Download on the App Store" height="50">
</a>

## Technical Summary

This project demonstrates how a simple markdown todo list can be managed entirely through natural language prompts using WonderChat AI. The process involves:

1.  **Initial Creation:** A prompt was given to create a markdown todo list with specific tasks. WonderChat AI used `create_file` to generate `todo.md`.
2.  **Adding Tasks:** New tasks were added to the list by instructing WonderChat AI. This involved `read_file` to get the current list and `update_file` to add the new items.
3.  **Marking Tasks Complete:** Tasks were marked as complete by specifying their numbers. WonderChat AI again used `read_file` and `update_file` to modify the checkboxes in `todo.md`.
4.  **Version Control & Deployment:** Throughout the process, changes were staged, committed, and pushed to a GitHub repository using `stage_changes`, `commit_changes`, and `push_changes`. The website itself (this very page) was published using `publish_website`.

This workflow highlights the ability to perform file operations and manage content directly through conversational AI, making common development tasks accessible and efficient directly from a mobile device.