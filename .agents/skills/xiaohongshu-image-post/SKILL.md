---
name: xiaohongshu-image-post
description: Create cohesive Xiaohongshu image posts, titles, and publishing copy from user-provided text, images, or links. Use when the user asks to turn a topic, draft, reference image, or source link into Xiaohongshu visuals and copy; do not use for unrelated image editing or unauthorized style changes.
---

# Xiaohongshu Image Post

Create a publication-ready Xiaohongshu image post while preserving the user's topic, source boundaries, and visual direction.

## Inputs and source handling

- Accept text, images, links, or a combination. Treat a supplied link as source material to inspect; do not claim facts that cannot be verified from the accessible source.
- If a link requires login, CAPTCHA, or is otherwise inaccessible, do not bypass the restriction. State what could not be verified and ask the user for the original text, a screenshot, or an alternative source.
- When a user supplies a source image, preserve its existing visual style unless they explicitly authorize a style change. Ask before changing a supplied image into another aesthetic, composition, or visual genre.
- When the user supplies only text, propose a suitable visual direction rather than implying that a pre-existing brand style exists.
- If the intended audience, image count, aspect ratio, or visual direction is essential but missing, make a practical default clear before generating. Prefer a 1080×1440 vertical format for ordinary Xiaohongshu image posts unless the user specifies otherwise.

## Workflow

1. First summarize the source in Chinese: topic, core viewpoint, target reader, page structure, and copy direction. Clearly separate source facts from proposed creative choices. When links are used, retain the accessible source URLs for the final source note.
2. Establish one consistent visual system across the set: palette, typography treatment, composition, image mood, and recurring visual elements. Keep all pages faithful to the summarized topic. Before making image pages that need wording, prepare the exact final copy for each page.
3. Generate the requested images. When a page needs text, place that exact text directly in the final image; do not default to a text-free visual with separate copy unless the user asks for it. For text-dense Chinese knowledge cards, prefer deterministic text layout when available rather than relying on an image model to render long body copy.
4. Deliver the final Xiaohongshu package:
   - images in the requested count and format;
   - a concise Xiaohongshu title;
   - a ready-to-post caption with appropriate line breaks and optional hashtags;
   - accessible source URLs when a link was used, plus any parts that could not be verified;
   - a brief note of any unverified claims or user decisions still needed.
5. Before delivery, check page by page that the original topic, page title, in-image text, publishing caption, and filename all describe the same content. Verify image count, dimensions, required page coverage, and exact spelling of Chinese text, dates, numbers, and proper nouns before claiming completion.

## Boundaries

- Do not edit, restyle, publish, upload, or delete a user-provided image without explicit authorization for that action.
- Do not invent product specifications, certifications, performance claims, citations, prices, or source facts to make the creative stronger.
- Do not publish to Xiaohongshu or any other external platform unless the user explicitly asks for that separate action.
