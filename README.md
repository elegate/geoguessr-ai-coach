# GeoGuessr.ai - The Reasoning Behind an AI GeoGuessr Coach

<p align="center">
  <a href="https://geoguessr.ai" target="_blank">
    <img src="https://geoguessr.ai/og-image.webp" alt="GeoGuessr.ai Banner">
  </a>
</p>

<p align="center">
  This repository is the official companion to <a href="https://geoguessr.ai" target="_blank">GeoGuessr.ai</a>, a web tool designed to act as an AI coach for the popular geography game GeoGuessr. This is not an open-source solver, but rather a deep dive into the philosophy, technical challenges, and prompt engineering required to make a truly useful learning tool.
</p>

---

## The Core Challenge: Moving Beyond a Simple "Solver"

As many in the community have explored, creating an AI that simply predicts coordinates is a solved problem to some extent. However, this approach misses the point of the game. The real challenge, and the one we aimed to solve, is creating an AI that acts as a **coach**, not a cheater.

The goal is to build a system that can explain the **"why"**, not just the **"where"**. It needs to think like a pro player, weighing evidence and identifying decisive clues.

## Our Approach: Prompt Engineering on State-of-the-Art Models

Instead of training a specialized model from scratch, our approach focuses on advanced **prompt engineering** to steer large, generalist vision models like **Google's Gemini 2.5 Pro** and **OpenAI's o3**.

The core of our "secret sauce" lies in a structured, multi-step reasoning prompt that forces the AI to:
1.  **Systematically Identify Clues:** It must first break down the image into distinct categories (Meta Clues, Infrastructure, Language, etc.).
2.  **Weigh Evidence:** It learns to assign higher importance to "smoking gun" clues (like a specific bollard) over generic clues (like a pine tree).
3.  **Synthesize and Explain:** It must present its reasoning in a clear, human-readable format before concluding with a location, turning every analysis into a valuable learning opportunity.

## Standing on the Shoulders of Giants: A Nod to the Pioneers

The GeoGuessr AI space has a rich history of open-source exploration. Our project would not have been possible without the foundational work and inspiration from the community. We'd like to give a massive shout-out to some of these key projects:

*   **[Name of High-Ranking Repo #1, e.g., StreetCLIP]:** This project was a pioneer in applying CLIP-based models to the GeoGuessr problem. Their work demonstrated the raw potential of vision transformers for zero-shot geolocation. We learned a great deal from their approach to feature extraction.
*   **[Name of High-Ranking Repo #2, e.g., GeoGuessr AI Bot]:** The way this project handled image preprocessing and tiling provided valuable insights for how to prepare images for analysis, especially in low-resolution scenarios.
*   *(Add 1-2 more relevant projects you found in your Google search)*

By referencing these projects, we hope to contribute to the ongoing conversation and build upon the collective knowledge of the community.

## See it in Action: The Live Tool

We wrapped all of this logic into a user-friendly web interface. It's the live implementation of the principles discussed above.

**➡️ [Try the Live Demo at GeoGuessr.ai](https://geoguessr.ai)**

We offer 3 free analyses per day to allow everyone to experience this new "AI Coach" approach to learning.

## The Roadmap

While the core tool is live, we are constantly experimenting with:
*   Improving the prompt to recognize even more nuanced meta clues.
*   Adding a gallery of community-submitted "tough rounds" with AI breakdowns.
*   Exploring ways to provide even more targeted training exercises.

## Contribution

This is not an open-source code project, but we welcome contributions in the form of **ideas, feedback, and challenging screenshots!** If you have a round that stumped our AI, please share it. Your feedback is invaluable.

---
