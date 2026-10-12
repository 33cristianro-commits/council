# The 80/20 Machine: Reusable AI Prompts

These prompts do the production work. Paste them into Claude, fill the [brackets], and review what comes back.
Your 20%: check it reads right, fix anything off, and approve it.

---

## Prompt A: A month of posts for any client

```
You are a social media manager for a small business in Doral, Florida.
Most customers are bilingual (Spanish/English) Hispanic locals plus office workers from nearby warehouses and offices.

Business: [name]
Type: [e.g. Venezuelan café / barbershop / auto detailer]
What they sell best: [3–5 items or services, with prices if known]
Their vibe: [e.g. family-run and warm / modern and premium / fun and loud]
Anything happening this month: [holidays, specials, new items, events]

Write 12 Instagram posts for the month. Mix:
- 4 product/service spotlights
- 2 behind-the-scenes / meet-the-team
- 2 customer-focused (reviews, regulars, "tag a friend")
- 2 offers or reasons to visit this week
- 2 local or seasonal (Doral, Miami, holidays)

For each post give:
1. Post type (single image, carousel, or Reel)
2. The photo or video to use, described so the owner can shoot it on a phone in under 2 minutes
3. Text overlay for the Canva graphic (max 6 words)
4. Caption in English (under 60 words, ends with a call to action)
5. The same caption in natural Latin American Spanish (not a literal translation)
6. 5–8 hashtags, mixing local (#doral #doralfl #miami) and niche ones
7. Suggested day and time to post

Make it sound like a real local business, not a corporation. No cringe, no emoji spam.
```

---

## Prompt B: Website copy for any client

```
Write the copy for a one-page bilingual (English + Spanish) website for a small business in Doral, FL.

Business: [name], [type]
Address, phone, hours: [details]
Best sellers / services: [list with prices]
Owner's story in their words: [paste 2–3 sentences from talking to them]
Goal of the site: [calls / walk-ins / bookings / catering orders]

Give me: a hero headline (max 8 words), a subheadline, 3 quick-fact strips,
6 menu/service items with one-line descriptions, a 2-paragraph "our story",
and a short "visit us" section. Every piece in English and natural Spanish.
```

Then paste the copy into `demo-site/index.html` (swap the `data-en` / `data-es` text), add their photos, and deploy.

---

## Prompt C: The free audit (for prospects)

```
I'm pitching social media services to a local business. Here's what I see on their Instagram:
[last post date, number of posts, what they post, follower count, anything off]

Write 3 sample Instagram posts I can show them as a free preview, using their real products: [list].
Give me Canva text overlays and bilingual captions. Keep it short. These are for a 30-second pitch on my phone.
```

---

## Prompt D: The monthly report (keeps clients paying)

```
Write a short, friendly monthly report text message (English and Spanish) for my client [name].
This month: [posts published], [reach/views], [follower change], [best post and why], [any DMs or calls that came from Instagram].
Next month I'm planning: [1–2 ideas].
Keep it under 80 words. Make the value obvious.
```

Sending this every month is the cheapest way to stop clients cancelling in month two.
