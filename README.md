# GeoGuessr.ai - A Prompt-Engineering Approach to Building a GeoGuessr AI Coach

<p align="center">
  <a href="https://geoguessr.ai" target="_blank">
    <img src="https://geoguessr.ai/og-image.webp" alt="GeoGuessr.ai Banner - An AI Coach for GeoGuessr">
  </a>
</p>

<p align="center">
  This repository is the official companion to <a href="https://geoguessr.ai" target="_blank">GeoGuessr.ai</a>, a web tool demonstrating how modern LLMs can be transformed into a powerful **GeoGuessr AI** assistant. This is not just another open-source solver, but rather a deep dive into the philosophy, technical challenges, and prompt engineering required to build a truly useful learning tool.
</p>

---

## The Core Challenge: Building a GeoGuessr AI That Teaches

As many in the community have explored, creating an **AI GeoGuessr** bot that simply predicts coordinates is a solved problem to some extent. However, this approach misses the point of the game. The real challenge, and the one we aimed to solve, is creating a **GeoGuessr AI** that acts as a **coach**, not a cheater.

The goal is to build a system that can explain the **"why"**, not just the **"where"**. It needs to think like a pro player, weighing evidence and identifying the decisive clues that separate a guess from an expert deduction.

## Our Approach: Advanced Prompt Engineering for the Ultimate AI GeoGuessr Coach

Instead of training a specialized model from scratch, our approach focuses on advanced **prompt engineering**. We steer large, generalist vision models like **Google's Gemini 2.5 Pro** and **OpenAI's o3** to perform a highly specific, expert-level analysis.

The core of our "secret sauce" lies in a structured, multi-step reasoning prompt that forces the **GeoGuessr AI** to:
1.  **Systematically Identify Clues:** It must first break down the image into distinct, pro-level categories (Meta Clues, Infrastructure, Language, etc.).
2.  **Weigh Evidence:** It learns to assign higher importance to "smoking gun" clues (like a specific bollard) over generic clues (like a pine tree).
3.  **Synthesize and Explain:** It must present its reasoning in a clear, human-readable format, turning every **AI-powered analysis** into a valuable learning opportunity.

## Standing on the Shoulders of Giants: A Nod to the Pioneers in the GeoGuessr AI Space

The **GeoGuessr AI** space has a rich history of open-source exploration, and our project would not exist without the foundational work and inspiration from this community. We want to give a massive shout-out to some of the key projects that paved the way:

*   **[shokiami/GeoKnowr](https://github.com/shokiami/GeoKnowr):** This project is a fantastic example of a full-stack approach to building a **GeoGuessr AI**. The way `GeoKnowr` structures its FastAPI backend and handles image processing provided a great blueprint for how a production-ready service could be architected. We were particularly inspired by its clean separation of concerns.

*   **[Stelath/geoguessr-ai](https://github.com/Stelath/geoguessr-ai):** A classic and highly influential project in the community. `geoguessr-ai`'s deep dive into using Selenium for browser automation and its early experiments with CNNs really highlighted the core challenges of building an **AI for GeoGuessr**. It's a testament to how much thought has gone into this problem over the years.

By referencing these and other incredible projects, we hope to contribute to the ongoing conversation and build upon the collective knowledge of the community, shifting the focus from pure "solving" to AI-assisted "coaching."

## See it in Action: The Live GeoGuessr AI Tool

We wrapped all of this logic into a user-friendly web interface. It's the live implementation of the principles discussed above.

**➡️ [Try the Live Demo at GeoGuessr.ai](https://geoguessr.ai)**

We offer 3 free analyses per day to allow everyone to experience this new "AI Coach" approach to learning. See for yourself how a purpose-built **GeoGuessr AI** can transform your gameplay.

## The Roadmap

While the core tool is live, we are constantly experimenting with new ways to improve our **AI GeoGuessr coach**:
*   Improving the prompt to recognize even more nuanced meta clues.
*   Adding a gallery of community-submitted "tough rounds" with AI breakdowns.
*   Exploring ways to provide even more targeted training exercises.

## Contribution

This is not an open-source code project, but we welcome contributions in the form of **ideas, feedback, and challenging screenshots!** If you have a round that stumped our **GeoGuessr AI**, please share it. Your feedback is invaluable.
