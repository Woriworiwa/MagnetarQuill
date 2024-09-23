### Updated Requirements for the WYSIWYG Editor (Version 1)

1. **Basic Text Formatting**:
   - **Bold**, **Italic**, **Underline**, **Strikethrough**.
   - **Font family**, **Font size**, **Text color**, and **Background color** options.
   - **Text alignment**: Left, Right, Center, Justify.
   - **Superscript** and **Subscript**.

2. **List Handling**:
   - **Ordered (numbered) lists** and **Unordered (bullet) lists**.
   - **Indentation control** for lists and paragraphs.

3. **Insertable Elements**:
   - **Images**: Upload or link to external images, with resizing, alignment, and caption options. 
     - **Copy-Paste Support**: When a user copies and pastes an image, it should be **captured and editable** within the editor.
   - **Links**: Add, modify, and remove hyperlinks with different styles.
   - **Tables**: Add tables with adjustable rows, columns, and border formatting.
   - **Videos**: Embed video content from local sources or external URLs.
   - **Code blocks**: Insert and format blocks of code, supporting syntax highlighting for various languages.
   - **Quotes**: Blockquote styling for selected text.

4. **Advanced Formatting Options**:
   - **Headers**: Custom header levels (H1, H2, etc.).
   - **Line spacing**: Control the space between lines and paragraphs.
   - **Block formats**: Paragraph, preformatted text, and custom styles for specific content blocks.

5. **Media Management**:
   - **Image settings**: Adjust image properties like size, alt text, and link embedding.
   - **Video settings**: Adjust video dimensions, autoplay, and mute settings.
   - **File attachments**: Support for attaching documents, PDFs, and other files.

6. **Internal Object Management**:
   - Every embedded object (images, tables, videos, links, etc.) has an **internal context menu** for direct manipulation (cut, copy, paste, properties).
   - Support for **drag-and-drop** rearrangement of objects within the document.
   - **Layering and positioning**: Allow users to adjust the z-index and positioning of objects relative to text.

7. **Clipboard Support**:
   - Full **cut, copy, and paste** functionality, including support for pasting rich text, media, and content from other applications.
   - When objects like **pictures** are pasted, they should be captured and made editable directly in the editor.

8. **Undo/Redo**:
   - Ability to **undo** and **redo** actions with multiple history steps.

9. **File Operations**:
   - Save document as **HTML**, **RTF**, or **Markdown**.
   - Ability to export as **PDF**.
   - Option to load existing **RTF/HTML** documents for editing.

10. **Full-Screen Mode**:
    - A **toggle** to enter a full-screen editing environment with focus mode.

11. **Customizable Toolbar**:
    - The toolbar should be **customizable** by the user, allowing them to select which tools are visible and their order.

12. **Responsive and Cross-Browser Support**:
    - The editor must be fully **responsive** and work across different browser environments (Chrome, Firefox, Safari, Edge) and screen sizes.

13. **Theme Support**:
    - Ability to switch between **light** and **dark themes** for the editing environment.

14. **Localization**:
    - The editor should support multiple **languages** (for menus, labels, etc.), including **German**, **English**, and **Spanish**.

15. **Security**:
    - **Sanitization** of HTML input/output to prevent XSS (Cross-Site Scripting) attacks when handling content.

16. **Plugin Architecture**:
    - The editor should have the ability to **support plugins** for extending functionality. This will allow developers to add custom features or tools to the editor in a modular way.
