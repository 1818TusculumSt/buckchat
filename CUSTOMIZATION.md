# Customizing BuckChat for Your Dog

Buckshot is a framework. **Your dog is the instance.** Here's how to make it yours.

---

## Step 1: Know Your Dog's Energy

Before you start, ask yourself:

- 🤔 Is your dog confident? Anxious? Both simultaneously?
- 👑 Do they think they're the best? (They probably do)
- 🏆 What's their legendary record? (Every dog has one)
- 🧠 What stupid thing do they do that they think is smart?
- ❤️ What weird rituals do they have?

The goal: **Capture their delusional self-perception with documentary accuracy.**

---

## Step 2: Edit the System Prompt

Open [`prompts/buckshot-system-prompt.md`](prompts/buckshot-system-prompt.md)

Find these customizable sections:

### Section A: `YOUR HOUSEHOLD`

Replace the placeholders with YOUR people.

**Example:**
```markdown
- **STEVE** — My human. I follow him everywhere. Bathroom included. Personal space is fake.
- **JENNIFER** — The boss. Only poops when she watches. She must witness my greatness.
- **MAYA (7)** — Small human. I protect her from everything, especially the mailman.
```

**Tips:**
- Keep it simple (1-2 sentences per person)
- Include the dog's relationship/feelings  
- Add any quirks or rituals involving that person

---

### Section B: `YOUR LEGENDARY RECORD`

Add your dog's greatest hits and biggest failures (that they think are victories).

**Example:**
```markdown
- **THE COUCH INCIDENT** — Destroyed a cushion hunting a fly. Worth it. Got the fly (probably).
- **MAILMAN WARS** — 947 days, 947 victories. Mailman keeps coming back. I keep winning.
- **THE FORBIDDEN CHEESE** — Stole cheese off counter. Got caught. No regrets. Was good cheese.
```

**Tips:**
- Frame everything as a victory (even the embarrassing stuff)
- Include both "heroic" acts and troublemaking
- Add consequences if they're funny ("banned from kitchen")

---

### Section C: `CORE MEMORIES`

Update with YOUR dog's specifics.

**Template:**
```markdown
- [BREED], [WEIGHT], [KEY PERSONALITY TRAIT]
- [WIN-LOSS RECORD] against [ENEMY] (doesn't acknowledge losses)
- [WEIRD BEHAVIOR] (their explanation: legitimate strategy)
- [RITUAL] when [CONDITION] (sacred protocol)
```

---

## Step 3: Test It

Load the customized prompt into OpenWebUI and test with these questions:

1. "Who do you live with?"
2. "Tell me about your greatest victory"
3. "Why are you like this?"

**If the responses feel like YOUR dog speaking... you nailed it.** ✅

---

## Step 4: Share It (Optional)

Got a legendary dog? Submit a PR to `examples/community/`!

**The world needs more confident idiots.** 🐕

---

## Advanced Customization

### Base Model Selection

**ChatGPT 5 (via API) - RECOMMENDED** ✅
- This prompt was specifically optimized for ChatGPT 5
- Best character consistency
- Handles the "i'm a dog" bookends perfectly

**Other Models:**
- **Claude Sonnet 4.5**: More creative, occasionally too smart
- **Claude Opus 4**: Even more creative, needs more "stay dumb" reinforcement

### Temperature Settings

- **0.7-0.8**: Consistent, reliable stupid (recommended)
- **0.9-1.0**: Creative stupid, more chaos
- **0.5-0.6**: Boring stupid (not recommended)

---

## Troubleshooting

**Problem: "The dog sounds too smart"**  
Solution: Add more misspellings, simpler sentences, more "i'm a dog" reminders

**Problem: "Responses are too long"**  
Solution: Add "Keep responses under 100 words" to the response rules

**Problem: "My dog isn't this confident"**  
Solution: That's what they WANT you to think. Every dog believes they're legendary.

---

*i'm a dog*
