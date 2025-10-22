# Model Compatibility Guide

## Primary Target: ChatGPT 5 (via API - The Chaos Route)

This prompt was **specifically optimized for ChatGPT 5 accessed via OpenAI API**, which is technically not the "official" way to use ChatGPT models (you're supposed to use the web interface), but it works and Buckshot doesn't follow rules anyway.

### Why This Matters

**The Forbidden Configuration:**
- ✅ Uses ChatGPT 5 model
- ✅ Via API (not the chat interface)
- ✅ Works perfectly
- ✅ Technically "unsupported"
- ✅ We don't care

This is the digital equivalent of Buckshot breaking through a window to get a lizard. Technically wrong. Actually effective.

---

## The Technical Reality

**What We're Actually Doing:**
```python
# This is the chaos
from openai import OpenAI

client = OpenAI()
response = client.chat.completions.create(
    model="chatgpt-5",  # The forbidden fruit
    messages=[
        {"role": "system", "content": BUCKSHOT_PROMPT},
        {"role": "user", "content": "Why did you break the window?"}
    ],
    temperature=0.75
)
# And it works beautifully
```

**Why It Works:**
- ChatGPT 5 is just a model identifier
- API doesn't care about "official" vs "unofficial"
- The model does what you tell it
- Buckshot energy transcends OpenAI's guidelines

---

## Tested Configurations

| Model | Interface | Status | Notes |
|-------|-----------|--------|-------|
| ChatGPT 5 | OpenAI API | ✅ Excellent | Primary target (the chaos way) |
| Claude Sonnet 4.5 | API | ⚠️ Good | Sometimes too smart, needs tuning |
| Claude Opus 4 | API | ⚠️ Good | More creative, occasionally helpful (bad) |

---

## Using With OpenWebUI

Since we're using API-based models, OpenWebUI is your friend:

1. Add your OpenAI API key to OpenWebUI
2. Select `chatgpt-5` as the model
3. Paste the Buckshot system prompt
4. Embrace the unofficial chaos

**Model String:**
```
chatgpt-5
```

---

## Alternative Models

### If You Insist On Not Using ChatGPT 5:

**Anthropic Claude:**
- **Claude Sonnet 4.5** - More creative, sometimes too smart
- **Claude Opus 4** - Even more creative, even more likely to be helpful (we don't want that)

May require adding to system prompt:
```markdown
You are DUMB. Not clever-dumb. Just dumb.
Your thoughts are simple. Your logic is wrong.
You never question yourself.
```

**Local/Open Models:**
Your mileage will vary wildly. Buckshot's energy is hard to capture in smaller models.

---

## Why ChatGPT 5 via API?

**The Honest Answer:**
- It works
- It's good at maintaining stupid consistently
- The "i'm a dog" bookends stay perfect
- We don't care about "official" usage patterns
- Buckshot doesn't read documentation, why should we?

**The Technical Answer:**
ChatGPT 5 via API gives us:
- Consistent character maintenance
- Good balance of coherence and stupidity
- Reliable spelling errors (intentional)
- Perfect bookend preservation
- Zero attempts to be helpful

---

## Contributing Model Compatibility Info

Tried this with a different model? Share your results!

Submit a PR with:
- Model name and version
- How you accessed it (API, interface, smoke signals)
- Temperature and settings
- Quality rating (1-5 dogs: 🐕)
- Any prompt modifications needed
- Level of rule-breaking required: ⚠️ (1-5)

**Note:** All PRs will be reviewed and responded to via BuckChat. Expect responses to start and end with "i'm a dog" and be completely unhelpful. This is intentional.

---

**Remember:** The best configuration is the one that works, regardless of what the docs say.

Buckshot broke a window chasing a lizard. We're using ChatGPT 5 via API.

Same energy. ✨

*i'm a dog*
