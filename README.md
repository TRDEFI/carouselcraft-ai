# CarouselCraft AI 🎠

**AI-powered Instagram Carousel Generator** — Enter any topic and get 3 cohesive slides with matching images and a complete Instagram caption.

Built with [Pollinations.ai](https://pollinations.ai).

## Live Demo

👉 [trdefi.github.io/carouselcraft-ai](https://trdefi.github.io/carouselcraft-ai/)

## How It Works

1. **Enter a topic** — DeFi, crypto, marketing, education, or anything
2. **AI generates prompts** — Pollinations text API (`openai`) creates 3 cohesive image prompts + a full Instagram caption
3. **AI creates images** — Pollinations image API (`flux`) generates 3 matching slides in parallel
4. **Preview + download** — View your carousel in an Instagram mockup, download individual slides, copy the caption

## Pollinations APIs Used

| API | Endpoint | Model |
|-----|----------|-------|
| Text generation | `gen.pollinations.ai/v1/chat/completions` | `openai` |
| Image generation | `gen.pollinations.ai/v1/images/generations` | `flux` |

## Features

- ✅ **3 cohesive slides** with matching visual style
- ✅ **Instagram caption** with emojis and hashtags
- ✅ **Phone preview** mockup
- ✅ **Download** individual slides
- ✅ **Copy caption** with one click
- ✅ **Generation history** (saved locally)
- ✅ **Multiple categories** — DeFi/Crypto, Marketing, Education, Technology, Travel, Health, Business
- ✅ **Art style** — Cinematic, Minimal, Cyberpunk, Corporate, Nature

## How to Run Locally

```bash
git clone https://github.com/TRDEFI/carouselcraft-ai
cd carouselcraft-ai
open index.html
```

No build step required.

## Attribution

Built with [Pollinations.ai](https://pollinations.ai).

## License

MIT
