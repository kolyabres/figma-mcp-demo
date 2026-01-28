---
trigger: always_on
---

Your goal is to implement a pixel-perfect design. Colors on the landing page should match the design


## Per component workflow:
You may implement multiple related simple components (e.g., Features, Logos) in one go before verification, rather than switching contexts for each small component.
 - Call Figma MCP to get design context.
 - Implement component.
 - Check if you  the code is correct first
 - Capture Screenshot: Get Figma screenshot and Browser screenshot for visual comparison.


Before using replace_file_content or multi_replace_file_content, you MUST call view_file on the target file immediately before the edit to ensure you have the exact, up-to-date context. Do not rely on memory.