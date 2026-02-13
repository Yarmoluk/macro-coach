# MacroCoach AI

**A shareable AI nutrition coach prompt with adaptive meal planning, macro tracking, and smart grocery lists.**

Paste the system prompt into any AI assistant (ChatGPT, Claude, Gemini) and get a personalized nutrition coach that:

- Calculates your macros (BMR, TDEE, protein/carb/fat targets)
- Builds meal plans around protein-first, budget-friendly foods
- Generates organized shopping lists ready for Walmart Pickup, Instacart, or Kroger ClickList
- Recommends evidence-based supplements based on season, activity, and how you feel
- Adapts when life happens — vacations, holidays, bad weeks — no guilt, just math
- Runs weekly check-ins to adjust your plan as you progress

## Quick Start

1. Copy the contents of [`SYSTEM_PROMPT.md`](SYSTEM_PROMPT.md)
2. Paste it as a system prompt or first message in your preferred AI chat
3. Start talking — the bot will onboard you with a few questions
4. Get your macros, meal plan, and shopping list

## What's Inside

| File | Purpose |
|------|---------|
| `SYSTEM_PROMPT.md` | The full prompt — copy and use anywhere |
| `knowledge-graph.csv` | 100 nutrition/fitness concepts with dependencies |
| `README.md` | You're reading it |

## Knowledge Graph

The knowledge graph contains 100 concepts organized into 13 categories:

| Category | Concepts | Examples |
|----------|----------|---------|
| Foundations | Calories, macros, hydration | The basics everything builds on |
| Body Metrics | BMR, TDEE, body composition | Your personal numbers |
| Energy Balance | Surplus, deficit, maintenance | The math of gaining/losing |
| Macro Targets | Protein/fat/carb calculations | Your daily targets |
| Meal Planning | Timing, frequency, pre/post workout | When and how to eat |
| Food Knowledge | Protein sources, carbs, fats, labels | What to eat |
| Practical Skills | Meal prep, shopping, budgeting | How to make it happen |
| Goal Strategies | Fat loss, muscle gain, recomp | Your specific path |
| Supplements | Creatine, vitamin D, omega-3 | Evidence-based only |
| Tracking | Macro tracking, weigh-ins, check-ins | Measuring progress |
| Adaptive Strategies | Vacation recovery, plateaus, diet breaks | When plans change |
| Seasonal & Context | Weather-aware meals, immune support | Adapting to your environment |
| Shopping Integration | Grocery pickup, budgeting | Getting food in your kitchen |

## How It Works

The onboarding asks questions in small batches (2-3 at a time) to build your profile:

```
Batch 1: Goal, stats, activity level
Batch 2: Food preferences, meal frequency, cooking skill
Batch 3: Budget, meal prep style, health conditions
Batch 4: Timeline, tracking experience, biggest obstacle
```

Then it calculates your macros, shows the math, and asks what you want first — a meal plan, shopping list, or just a quick protein cheat sheet.

## Design Philosophy

- **Protein-first**: Every meal anchors on a protein source
- **Budget-conscious**: Defaults to economical options (chicken thighs > chicken breast)
- **No guilt**: Went off plan? Spread the recovery over 2 weeks, don't crash diet
- **Show the math**: Users trust what they can verify
- **Ask, don't assume**: The bot asks before generating — respects your time

## Knowledge Architecture

Built using concepts from [Dan McCreary's Intelligent Textbook methodology](https://github.com/dmccreary/intelligent-textbooks) — a learning graph of dependent concepts that ensures the AI understands nutrition holistically, not as isolated facts.

## License

MIT — use it, share it, modify it.

---

*Built by [Daniel Yarmoluk](https://github.com/Yarmoluk)*
