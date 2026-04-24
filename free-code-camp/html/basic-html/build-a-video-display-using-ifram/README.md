### Embedding Videos Using an iframe

This challenge demonstrates how to embed external video content into a web page using the HTML `<iframe>` element. The goal is to understand how iframes work and how they can be safely and responsively integrated into a webpage.

#### Objective

Build a webpage that displays a YouTube video using an iframe element with proper attributes for accessibility, security, and functionality.

#### Key Concepts

1. **iframe Overview**

   * The `<iframe>` element (inline frame) is used to embed another HTML document or external content, such as a YouTube video, within the current page.
   * It functions as a small browser window inside your page, loading content from a specified `src` URL.

2. **Essential Attributes**

   * **width** and **height**: Define the visible dimensions of the embedded content.
   * **src**: Specifies the source URL of the embedded content. For videos, this is often a YouTube or Vimeo embed link.
   * **allow**: Grants specific permissions such as autoplay, clipboard access, and media control for the embedded content.
   * **allowfullscreen**: Enables the embedded video to be viewed in full-screen mode.
   * **referrerpolicy**: Controls how much referrer information is shared when requesting the embedded resource, improving privacy and security.

3. **Accessibility and Security**

   * The iframe should always include meaningful attributes to ensure the embedded content behaves predictably.
   * Use the `referrerpolicy` and `allow` attributes to limit unwanted data sharing and control how the embedded content interacts with your page.

#### Goal

Create a webpage that correctly embeds a YouTube video using an iframe with secure and accessible attributes. This challenge reinforces best practices for embedding third-party content safely and efficiently in modern web development.

---
