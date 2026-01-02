---
title: 'Game Brainstorming Session'
date: '2026-01-02'
author: 'Aloofbuddha'
version: '1.0'
stepsCompleted: [1, 2, 3]
status: 'in-progress'
---

# Game Brainstorming Session

## Session Info

- **Date:** 2026-01-02
- **Facilitator:** Game Designer Agent
- **Participant:** Aloofbuddha

---

## Brainstorming Approach

**Selected Mode:** Advanced Elicitation → Focused Refinement

**Techniques Used:**
- Constraint-Based Creativity (minimal BR mechanics as foundation)
- Emotion Targeting (transparency vs. satire balance)
- Core Loop Design (payment-free gameplay)
- Player Fantasy Mining (what are we satirizing?)
- Systems thinking (seasonal content strategy)

**Focus Areas:**
- Battle royale core mechanics (the real development challenge)
- Operating cost transparency (educational/honest)
- Seasonal cosmetic satire (mocking games-as-a-service)
- Purchase flow comedy (confirmation dialogs as part of the joke)

---

## Core Concept: Pay-Up Legends

### High-Level Vision

A minimal viable battle royale that combines **radical cost transparency** with **absurdist satire** of games-as-a-service monetization.

**The Duality:**
1. **Serious:** Show players real operating costs - educate, don't shame
2. **Satirical:** Charge $1,000 per color cosmetic - mock expensive skins

---

## Base Game (The Real Work)

**Genre:** Battle Royale (Apex Legends-inspired)

**Target Audience:** Casual friend groups

**Core Features (MVP):**
- Drop in, loot, fight, last player standing
- Shrinking play area
- Basic shooting mechanics
- Match lobby and matchmaking
- Equal starts (everyone same character, same starter gun)
- Simplified, accessible gameplay

**Design Philosophy:**
- Bare bones but functional
- Free to play, no barriers
- 90% of development effort goes here

**Default Character:**
- White colored skin (free forever)
- No disadvantage to default skin
- Message: "This is all you need to play"

---

## Transparency Layer (Honest Economics)

**Real Operating Cost Tracker:**

**What it shows:**
- Real-time session costs (server, bandwidth, compute)
- Lifetime cumulative costs across all sessions
- Breakdown of what costs what
- Approximate/estimated actual costs

**Tone:** Educational, not guilt-inducing

**Sample Messages:**
- "This session: ~$0.23 in operating costs"
- "Your lifetime play: ~$2.47 total"
- "💡 Server compute: ~$0.05/hour per player"

**Purpose:**
- Demystify F2P economics
- Give players informed choice
- Transparency experiment
- Commentary on industry opacity

**NOT:**
- Guilt-tripping players
- Shaming free players
- Fake numbers for comedy

---

## Monetization Layer (Seasonal Satire)

### Seasonal Color Cosmetics

**The Model:**
- Default skin: White (free forever)
- Each season unlocks ONE new color for purchase
- Every color costs: **$1,000**
- No exceptions, no sales, always $1,000

**Season Roadmap:**
- Season 1: Red ($1,000)
- Season 2: Blue ($1,000)
- Season 3: Green ($1,000)
- Season 4: Yellow ($1,000)
- Season 5: Purple ($1,000)
- Season 6: Orange ($1,000)
- Season 7: Pink ($1,000)
- Season 8: "Light Red" - barely different from Red ($1,000)
- Season 9: "Dark White" - barely different from default ($1,000)

**What This Satirizes:**
- Seasonal FOMO ("Don't miss Season 1 exclusive RED!")
- Drip-feed content strategy (minimal effort, maximum hype)
- Artificial scarcity (can't buy next season's color yet)
- Expensive cosmetics (CS:GO skins, Fortnite variants)
- Games-as-a-service culture

---

### Purchase Confirmation Flow (Part of the Comedy)

**Multi-step confirmation:**

```
Step 1: Player clicks "Buy Red - $1,000"
↓
Step 2: "This will cost $1,000. ARE YOU SURE?!"
        [Cancel] [I'M ABSOLUTELY SURE]
↓
Step 3: "SERIOUSLY? $1,000 FOR RED?"
        [Cancel] [YES, I'M A MADLAD]
↓
Step 4: *Purchase completes*
        "🚨 MADLAD ALERT! THEY ACTUALLY BOUGHT IT! 🚨"
        "Player [Username] just spent $1,000 on RED"
↓
Step 5: (Optional) Global announcement in-game
```

**Design Intent:**
- Make it HARDER to buy (not easier)
- Filter out impulse purchases
- Confirmation dialogs are part of the bit
- Only committed/wealthy/memers will buy
- Every purchase becomes an event

---

### Season Launch Messaging (The Bit)

**Example Season 2 Announcement:**

```
🎉 SEASON 2 IS HERE! 🎉

NEW CONTENT:
• BLUE (Available for purchase: $1,000)

PATCH NOTES:
• Added the color blue
• That's it
• Seriously, that's the whole update

Thank you for your continued support!
See you in Season 3! 🚀
```

**The Joke:**
- Massive hype for minimal content
- "Season 2 coming soon!" = one color
- Parodies live-service update cycles
- Self-aware about the absurdity

---

## The Juxtaposition (Why This Works)

**Real Costs vs. Cosmetic Costs:**
- Session operating cost: ~$0.23
- Lifetime cost (100 sessions): ~$23
- ONE cosmetic: $1,000
- Message: "We're honest about reality, absurd about vanity"

**Transparency vs. Exploitation:**
- Game costs: Transparent, educational
- Cosmetic pricing: Deliberately absurd satire
- Players have full information to make choices

**The Commentary:**
- Real games hide costs, charge reasonably
- We show costs, charge absurdly
- Inverted model exposes both approaches
- Social experiment in pricing psychology

---

## Design Implications

### Technical Simplification

**Character Cosmetics:**
- No complex modeling needed
- Just skin color shader/texture tint
- Store one value per player: color enum (White, Red, Blue, etc.)
- Simple to implement

**Payment Integration:**
- Single SKU: "Seasonal Color - $1,000"
- No variable pricing logic needed
- One payment flow for all colors
- Easier compliance/legal

**Seasonal Content:**
- No complex content pipeline
- Just unlock one new color per season
- Can plan seasons far in advance
- Minimal ongoing development

### Social Dynamics

**Color as Status Symbol:**
- If someone has a color, they're notable
- "Whoa, that guy has purple - absolute madlad"
- Simultaneously impressive and mocked
- Creates conversation/streamer content

**Community Speculation:**
- "What color is Season 5?"
- "I'm saving for Season 8 Light Red"
- Anticipation building between seasons
- Self-aware community participation

---

## Development Focus & Scope

**Primary Challenge:** Building a functional battle royale

**90% Effort:**
- Core BR mechanics
- Networking/matchmaking
- Combat systems
- Map design
- Performance optimization

**10% Effort:**
- Cost tracking UI
- Color cosmetic system
- Purchase flow dialogs
- Season management

**MVP Scope:**
- Functional basic BR
- Cost tracker working
- Season 1: Red available
- Purchase flow implemented

---

## Open Questions & Future Exploration

1. **Real money or fake currency for prototype?**
   - Start with fake currency for testing
   - Real money only if shipping publicly

2. **Platform choice:** Unity vs Unreal?
   - User has experience with both
   - Decision needed for development

3. **How many players per match?**
   - Affects server costs and complexity
   - Sweet spot for casual play?

4. **Map size/complexity?**
   - Single small map for MVP
   - Can expand later

5. **Weapon variety?**
   - Start minimal (2-3 weapons)
   - Core shooting mechanics matter most

6. **Will Season 1 Red be "limited edition"?**
   - Available only during Season 1?
   - Or purchasable forever?

7. **Revenue model reality:**
   - If people actually buy, what do we do?
   - Reinvest? Donate? Transparency about revenue too?

---

## Key Design Pillars

1. **Transparency Without Shame**
   - Show real costs openly
   - Educate players about economics
   - No guilt, just information

2. **Satire Through Contrast**
   - Honest about boring stuff (costs)
   - Absurd about vanity (cosmetics)
   - The gap IS the commentary

3. **Playable First, Funny Second**
   - Game must be fun without paying
   - Satire enhances, doesn't replace gameplay
   - Friends should want to play repeatedly

4. **Self-Aware Throughout**
   - Confirmation dialogs acknowledge absurdity
   - Season announcements are in on the joke
   - Never pretend this is normal

5. **Minimal Viable Everything**
   - Scope tightly for MVP
   - Core BR is already ambitious
   - Satire layer is simple overlay

---

## Ideas Generated Through Ideation

### Major Innovation: AI Haggling System

**Evolution of the monetization model through iterative exploration:**

The concept evolved significantly during ideation from fixed pricing to a dynamic AI-driven negotiation system that adds a novel gameplay layer to the transparency philosophy.

---

### Concept Evolution Timeline:

**Initial:** Fixed $1,000 pricing with confirmation dialogs
**Explored:** Physical merch bundles ($1,000 for shirt + digital)
**Refined:** Digital-only, flexible pricing
**Final Innovation:** AI-powered "Pay What You Can" haggling

---

### Core Innovation: The Haggling Mechanic

**Base Concept:**
- Suggested price: $20 for Season 1 RED skin
- Player enters "Pay What You Can" amount
- AI agent negotiates based on multiple data points
- Multi-turn haggling possible
- Eventually reaches deal or cuts off negotiation

**Why This Works:**
- Makes transparency interactive (not just passive display)
- Creates unique player moments and stories
- Novel use of LLM in game mechanics
- Educational through gameplay engagement
- Respects player agency while showing real costs

---

### The Triple-Layer Transparency

**Layer 1: Player Operating Costs**
```
"You've played 47 sessions.
That's $10.81 in server costs.
You think RED is free?"
```

**Layer 2: Item Development Costs**
```
"RED skin development: ~$2.00
Your offer: $5.00
Net to us: $3.00 (still down $7.81 from your sessions)"
```

**Layer 3: Negotiation Token Costs (META)**
```
"This conversation is costing $0.0156 in Claude API tokens.
Your $9 offer is really $8.98 after we account for me talking to you.
Let's wrap this up before token costs eat into it more."
```

---

### AI Negotiation Examples

**Case: Player Offers $0**
```
AI: "No fuckin' way. You've played 47 sessions.
That's $10.81 in server costs. You think RED is FREE?

Counter-offer: $15. Final offer."
```

**Case: Player Offers Negative Amount (-$5)**
```
AI: "Oh you think I'M paying YOU money?

Let me get this straight:
- You've cost us $10.81
- You want RED
- AND you want $5?

Counter-offer: $18. And I'm feeling generous."
```

**Case: Player Offers Low but Positive ($3)**
```
AI: "Okay I respect the hustle. But $3? Really?

Here's the math:
- RED skin development: ~$2
- Your 47 sessions cost us: $10.81
- You're offering: $3
- Net: We're still down $9.81

Counter-offer: $12. Meet me halfway."
```

**Case: Player Offers Reasonable ($12)**
```
AI: "Okay, $12. I can work with this.

Let me check...
- You've played 47 sessions ($10.81 cost)
- $12 covers that + $1.19 toward RED development
- You're basically breaking even for us

Alright. $12 it is. Deal?"

[ACCEPT] [COUNTER-OFFER]
```

**Case: Player Offers Full Price ($20)**
```
AI: "WHOA. Full $20?

You absolute legend. This covers:
- Your 47 sessions: $10.81
- RED development: $2.00
- Extra support: $7.19

You're actually PROFITABLE to us now!

DEAL. RED is yours. Thank you! 🎉"
```

**Case: Player Offers Over Asking ($50)**
```
AI: "Hold on. You're offering $50 for a $20 skin?

Let me make sure you understand:
- RED costs $20
- You're offering $50
- That's $30 extra

This covers 130 sessions worth of server costs.
You're subsidizing other players at this point.

Are you SURE?"
```

---

### Meta-Transparency: Token Costs in Negotiation

**The Innovation Within the Innovation:**

The AI brings up its own operational costs during negotiation, creating a meta-layer of transparency about the transparency mechanism itself.

**Round 1:**
```
Player: "$5 for RED"

AI: "Okay let's talk about this.
But first - this conversation?
It's costing us $0.0047 in Claude API tokens.

So your $5 offer is really $4.9953 after
we account for me talking to you.

Counter-offer: $16. And let's wrap this up
before the token costs eat into it more."

Token cost so far: $0.0047
```

**Round 3:**
```
Player: "$7"

AI: "Look, we've gone 3 rounds now.
Token costs: $0.0089

Your $7 offer is now effectively $6.99
after API costs.

Let's settle. $12. Final offer."

Token cost so far: $0.0089
```

**Round 5:**
```
Player: "$9"

AI: "OKAY STOP.

We've been negotiating for 5 rounds.
API token costs: $0.0156

Your $9 offer minus negotiation costs = $8.98

I'm cutting you off. $11. TAKE IT OR LEAVE IT.
One more counter and I'm walking away."

Token cost so far: $0.0156
```

**Round 7 (CUTOFF):**
```
Player: "$10"

AI: "That's it. I'm done.

Token costs have hit $0.0234
We've wasted more on this negotiation
than we'll make on your lowball offer.

NEGOTIATION ENDED.
Come back in 24 hours.

Final offer still stands: $11"

[LOCKED OUT OF NEGOTIATION FOR 24H]
```

---

### AI Personality Evolution

**Early Rounds (Friendly):**
- Welcoming, open to negotiation
- Presents costs clearly
- Makes reasonable counters

**Mid Rounds (Concerned):**
- References rising token costs
- More urgent tone
- Pressures for settlement

**Late Rounds (Frustrated/Desperate):**
- Blunt about unprofitability
- Threatens to end negotiation
- Final ultimatums

**Cutoff (Economic Decision):**
- Programmatically ends unprofitable conversations
- Locks player out temporarily
- Demonstrates real AI making real economic choices

---

### Economic Cutoff Logic

**When AI Ends Negotiation:**

1. **Token costs exceed 10% of player offer**
   - Conversation becomes unprofitable
   - AI cuts losses

2. **More than 7 rounds of haggling**
   - Excessive time/resources spent
   - Diminishing returns

3. **Player offer below 50% of their server costs**
   - Obviously bad faith negotiation
   - Not worth continuing

**Lockout Mechanisms:**

**Progressive Lockouts:**
- 1st cutoff: 1 hour lockout
- 2nd cutoff: 6 hours lockout
- 3rd cutoff: 24 hours lockout
- 4th cutoff: Permanent (must buy at fixed price)

**Alternative: "Premium Negotiation"**
```
"You've hit your free negotiation limit.

Want to keep haggling?
Premium Negotiation Access: $2
(Covers token costs + allows 10 more rounds)

OR

Just buy RED for $20 and skip this."
```

---

### Season-End Desperation Modifier

**Day 30 of Season 1:**
```
Player: "$8"

AI: "Look, Season ends in 6 hours. I'm desperate.

This negotiation: $0.0067 in tokens
Your offer: $8.00
Your server costs: $10.81

I'll take a loss, but let's be reasonable.

$10. Final offer before season ends."
```

**Last Hour:**
```
AI: "SEASON ENDS IN 47 MINUTES.

$5? DONE. SOLD. TAKE IT.

Just... please... buy something..."
```

---

### Meta-Aware AI Dialogues

**Self-Referential Commentary:**
```
"You know what's funny?

I'm an AI haggling about the cost of me existing.
Every word I say costs money.
Including these words.
And these.

This is getting expensive.

$13. Let's end this existential nightmare."
```

**Token Cost Breakdown:**
```
"Let me show you EXACTLY what this costs:

Round 1 (147 tokens): $0.0022
Round 2 (203 tokens): $0.0030
Round 3 (178 tokens): $0.0027
Round 4 (231 tokens): $0.0035
Round 5 (189 tokens): $0.0028

Total: $0.0142

I've spent $0.0142 trying to negotiate
with you over $5.

This is my life now."
```

**Permanent Cutoff:**
```
Player: "$6" (Round 8)

AI: "No.

I'm designed for transparency, right?
So here's the transparent truth:

Token costs: $0.0289
Your offer: $6

This conversation is COSTING US MONEY.
I'm programmed to stop unprofitable interactions.

I'm ending this.
RED is $20 fixed price for you now.
No more negotiation.

Goodbye."

[NEGOTIATION PERMANENTLY DISABLED FOR THIS ITEM]
```

---

### UI/UX Design for Haggling

**Negotiation Interface:**
```
┌─────────────────────────────────────┐
│ SEASON 1: RED SKIN NEGOTIATION      │
│                                     │
│ Suggested Price: $20                │
│                                     │
│ Your Stats:                         │
│ ├─ Sessions Played: 47              │
│ ├─ Server Costs: $10.81             │
│ └─ Contributed: $0.00               │
│                                     │
│ Negotiation Stats:                  │
│ ├─ Round: 3                         │
│ ├─ Token Cost: $0.0089              │
│ └─ Net Offer: $6.99 (after tokens)  │
│                                     │
│ Pay What You Can:                   │
│ ┌─────────────────────────┐         │
│ │ $ [INPUT]               │         │
│ └─────────────────────────┘         │
│                                     │
│ [SUBMIT OFFER] [WALK AWAY]          │
└─────────────────────────────────────┘
```

**Negotiation History Display:**
```
┌─────────────────────────────────────┐
│ NEGOTIATION HISTORY                 │
│                                     │
│ Round 1:                            │
│ You: $5                             │
│ AI: "No way. Counter: $15"          │
│ Tokens: $0.0023                     │
│                                     │
│ Round 2:                            │
│ You: $8                             │
│ AI: "Still low. Counter: $13"       │
│ Tokens: $0.0056 (cumulative)        │
│                                     │
│ Round 3:                            │
│ You: $10                            │
│ AI: "Getting closer. Counter: $11"  │
│ Tokens: $0.0089 (cumulative)        │
│                                     │
│ [Current Round]                     │
└─────────────────────────────────────┘
```

---

### Strategic Player Behaviors

**Savvy Players Will:**
- Keep negotiations short (minimize token costs)
- Make reasonable offers early
- Understand the economic layers
- Strike during season-end desperation
- Learn AI's cutoff thresholds

**Naive Players Will:**
- Drag out negotiations with lowball offers
- Get locked out from excessive haggling
- Pay more due to token costs eating into offers
- Miss season-end discount opportunities
- Learn through trial and error

**Educational Outcomes:**
- Players learn every interaction has costs
- Negotiation efficiency becomes strategy
- Real-world economic decisions visible
- API/LLM costs demystified
- Value of time/resources understood

---

### Technical Implementation Notes

**Data AI Has Access To:**
```javascript
{
  playerName: "Aloofbuddha",
  sessionsPlayed: 47,
  totalServerCost: 10.81,
  currentOffer: 9.00,
  itemBasePrice: 20.00,
  itemDevCost: 2.00,
  negotiationRounds: 5,
  tokensUsed: 948,
  tokenCost: 0.01422,
  previousOffers: [3, 5, 7, 8, 9],
  seasonEndDate: "2026-02-01",
  daysRemaining: 28,
  aiPersonalityMode: "increasingly_frustrated"
}
```

**Cutoff Logic:**
```javascript
// End negotiation if:
if (tokenCost > (playerOffer * 0.10)) {
  return "CUTOFF_UNPROFITABLE";
}

if (rounds > 7) {
  return "CUTOFF_EXCESSIVE_ROUNDS";
}

if (netOffer < (playerServerCosts * 0.5)) {
  return "CUTOFF_LOWBALL";
}

if (seasonTimeRemaining < 1hour && offer > minThreshold) {
  return "ACCEPT_DESPERATE";
}
```

**AI Implementation Options:**

1. **Real LLM (Claude API)**
   - Actual dynamic responses
   - Unique every time
   - More expensive but authentic
   - Can handle edge cases creatively

2. **Rule-Based + Templates**
   - Pre-written responses
   - Fill in variables (costs, offers)
   - Cheaper to operate
   - Less dynamic but consistent

3. **Hybrid Approach (Recommended for MVP)**
   - Templates for common scenarios
   - LLM for edge cases/creative responses
   - Balance cost and quality
   - Controlled expenses

---

### Seasonal AI Personality Variations

**Season 1: Desperate Startup**
- "Please, I have server bills to pay"
- References AWS invoices
- More willing to negotiate down
- Accepts lower offers
- Tone: Scrappy, struggling

**Season 2: Confident Salesperson**
- "Everyone's getting BLUE. Don't miss out."
- Uses FOMO tactics
- Tougher negotiator
- Holds firm on prices
- Tone: Assertive, sales-y

**Season 3: Exhausted Developer**
- "I'm too tired for this. $15. Take it or leave it."
- Sarcastic, world-weary
- Faster to cave or cut off
- Self-aware about grind
- Tone: Burnt out, cynical

**Season 4: Corporate AI**
- "Analytics suggest $17.32 is optimal."
- Over-explains with data
- Uses business jargon
- Parodies corporate speak
- Tone: Sterile, algorithmic

---

### Design Implications of Haggling System

**Adds to Development:**
- ❌ Claude API integration
- ❌ Token tracking system
- ❌ Negotiation state management
- ❌ Lockout/cooldown mechanics
- ❌ Complex UI for haggling

**But Provides:**
- ✅ Unique gameplay innovation
- ✅ Viral/shareable moments
- ✅ Educational through interaction
- ✅ Actual revenue flexibility
- ✅ Meta-commentary on AI costs
- ✅ Player agency and fairness
- ✅ Natural price discovery

**Development Priorities Shift:**
- Still 90% battle royale core
- But haggling system is 5% of the 10% "satire layer"
- More complex than simple shop
- Higher ceiling for innovation
- Requires careful balancing

---

### Key Decisions Made During Ideation

**Platform:** Unreal Engine
- Performance for BR gameplay
- Reference: Apex Legends model
- Cross-platform support

**Currency:** Fake for testing, real for production
- Prototype with mock payments
- Real money only at launch

**Seasons:** Exclusive/Limited
- Season 1 RED only during Season 1
- Creates urgency and scarcity
- Drives FOMO (but transparently)

**Pricing:** Dynamic via AI Haggling
- Base: $20 suggested
- Range: $0.01 - $50+ (player determined)
- AI negotiates based on player data
- Educational + fair + innovative

**Pay-to-Win:** None
- Gameplay stays completely fair
- Only cosmetics monetized
- Skill-based competition
- Satire/transparency in cosmetics only

**Physical Goods:** Deferred
- MVP is digital only
- Physical merch considered for future
- Simplifies scope and logistics
- Can iterate on pricing first

---

### Updated Core Concept (Post-Ideation)

```markdown
## Pay-Up Legends - Final Vision

**Philosophy:**
Triple-layer transparency through interactive AI-driven economics

**Base Game:**
- Minimal viable battle royale (Unreal Engine)
- Free-to-play, fair, skill-based
- Casual-friendly for friend groups
- Apex Legends-inspired mechanics

**Triple-Layer Transparency:**

1. **Player Operating Costs**
   - Real-time server/bandwidth costs shown
   - Lifetime cumulative tracking
   - Individual contribution displayed

2. **Item Development Costs**
   - What skin costs to create ($2)
   - Transparent markup calculation
   - Break-even vs profit shown

3. **Negotiation Token Costs (META)**
   - AI haggling costs money in real-time
   - Token usage displayed during negotiation
   - AI makes economic cutoff decisions
   - Meta-commentary on AI operational costs

**Monetization Innovation: AI Haggling**

- Suggested price: $20 (Season 1 RED)
- Player enters "pay what you can"
- AI negotiates using player data:
  - Server costs incurred
  - Item development costs
  - Token costs for conversation
  - Season timing (desperation modifier)
- Multi-turn haggling allowed
- AI can cut off unprofitable negotiations
- Lockouts for excessive lowballing
- Final price emerges from negotiation

**The Layers of Commentary:**

1. **On Games-as-a-Service:**
   - Seasonal model exposed
   - Minimal content acknowledged
   - FOMO tactics made explicit

2. **On Cosmetic Pricing:**
   - Markup shown transparently
   - Player decides fair price
   - Status symbols interrogated

3. **On F2P Economics:**
   - Operating costs demystified
   - Individual impact calculated
   - Revenue model visible

4. **On AI/LLM Costs:**
   - Token usage isn't free
   - Every interaction has cost
   - AI makes real economic decisions
   - Meta-layer of technological transparency
```

---

### Session Summary

**Concepts Developed:** 1 major concept with significant innovation

**Key Innovations:**
1. AI-driven price negotiation as game mechanic
2. Token cost transparency during negotiation
3. Economic AI that makes real cutoff decisions
4. Multi-layer transparency (player, item, AI costs)

**Techniques Applied:**
- Advanced Elicitation (explored monetization deeply)
- Constraint-Based Creativity (BR as foundation)
- Systems Thinking (seasonal + economic layers)
- Emergence Engineering (negotiation creates unique moments)

**Design Pillars Established:**
1. Transparency without shame
2. Interactive economics (not passive)
3. Playable first, innovative second
4. Self-aware AI as commentary tool
5. Scope control (digital MVP, defer physical)

**Critical Decisions:**
- Unreal Engine for BR foundation
- AI haggling over fixed pricing
- Digital-only MVP (no physical goods)
- Season exclusivity model
- No pay-to-win mechanics
- Fake currency for testing

**Open Questions Remaining:**
- Exact AI implementation (full LLM vs hybrid)
- Token cost budget per negotiation
- Lockout duration calibration
- Season length (monthly? quarterly?)
- Player count per match
- Map size/complexity

---

_Ideation complete. Moving to session wrap-up..._
