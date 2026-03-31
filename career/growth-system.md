# Career Growth System

> Your career is not a ladder. It's a portfolio of bets, skills, and relationships that compound over time.

## The Growth Framework

```mermaid
flowchart LR
    Skills -->|produce| Output
    Output -->|builds| Reputation
    Reputation -->|unlocks| Opportunities
    Opportunities -->|provide| Feedback
    Feedback -->|sharpen| Skills
    style Skills fill:#e94560,stroke:#e94560,color:#fff
    style Output fill:#0f3460,stroke:#0f3460,color:#fff
    style Reputation fill:#0a8754,stroke:#0a8754,color:#fff
    style Opportunities fill:#e67e22,stroke:#e67e22,color:#fff
    style Feedback fill:#8e44ad,stroke:#8e44ad,color:#fff
```

> The flywheel: better skills → better output → more visibility → more opportunities → harder problems → better skills

## Skill Acquisition Protocol

### The T-Shape Model

Go deep in 1-2 areas, then broad across adjacent skills.

```mermaid
flowchart TD
    subgraph breadth["BREADTH"]
        direction LR
        Design --- Product --- Data --- DevOps --- Business
    end
    Data --> Depth
    subgraph Depth["DEPTH (Primary Skill)"]
        direction TB
        D1["Backend Engineering"]
        D2["System Design"]
        D3["Distributed Systems"]
        D4["Performance Optimization"]
    end
    D1 --> D2 --> D3 --> D4
    style breadth fill:#16213e,stroke:#0f3460,color:#eee
    style Depth fill:#1a1a2e,stroke:#e94560,color:#eee
```

### Deliberate Practice (Not Just Reps)

```mermaid
flowchart LR
    A["Identify<br/>weakness"] --> B["Design<br/>exercise"] --> C["Execute with<br/>full attention"] --> D["Get immediate<br/>feedback"] --> E["Adjust"] --> A
    style A fill:#e94560,stroke:#e94560,color:#fff
    style B fill:#c0392b,stroke:#c0392b,color:#fff
    style C fill:#e67e22,stroke:#e67e22,color:#fff
    style D fill:#2980b9,stroke:#2980b9,color:#fff
    style E fill:#8e44ad,stroke:#8e44ad,color:#fff
```

> 10,000 hours of autopilot = mediocrity. 1,000 hours of deliberate practice = elite.

## Leverage: Work on the Right Things

Not all work compounds equally. Prioritize high-leverage activities.

```mermaid
quadrantChart
    title Effort vs Impact Matrix
    x-axis Low Effort --> High Effort
    y-axis Low Impact --> High Impact
    quadrant-1 DO THIS FIRST
    quadrant-2 Quick Wins — do immediately
    quadrant-3 IGNORE — eliminate ruthlessly
    quadrant-4 Time Traps — schedule or batch
    Deep work projects: [0.8, 0.9]
    Career-defining features: [0.9, 0.85]
    Quick documentation: [0.3, 0.7]
    Mentoring juniors: [0.4, 0.75]
    Unnecessary meetings: [0.6, 0.2]
    Bike-shedding PRs: [0.7, 0.15]
    Slack messages: [0.2, 0.3]
    Email formatting: [0.15, 0.1]
```

## Building in Public

Visibility compounds. Your best work means nothing if nobody knows about it.

- Write about what you learn (blog, Twitter/X, LinkedIn)
- Share your process, not just results
- Open-source your side projects
- Speak at meetups (start small, local)
- Help others publicly — it builds trust and reach

```mermaid
flowchart TD
    A["Learn something"] --> B["Share it publicly"]
    B --> C["People find you"]
    C --> D["Conversations + trust"]
    D --> E["Harder opportunities"]
    E --> A
    style A fill:#0a8754,stroke:#0a8754,color:#fff
    style B fill:#2980b9,stroke:#2980b9,color:#fff
    style C fill:#8e44ad,stroke:#8e44ad,color:#fff
    style D fill:#e67e22,stroke:#e67e22,color:#fff
    style E fill:#e94560,stroke:#e94560,color:#fff
```

## Networking That Actually Works

Forget "networking events." Build real relationships.

1. **Give first**: Help people with no expectation of return
2. **Be specific**: "I'm working on X" beats "I'm a developer"
3. **Follow up**: One coffee meeting means nothing without follow-up
4. **Curate your circle**: You are the average of the 5 people you spend the most time with
5. **Weak ties matter**: Your next opportunity comes from acquaintances, not close friends (Granovetter's research)

## Career Decision Framework

When evaluating opportunities, rate each 1-10:

```mermaid
mindmap
  root((Opportunity<br/>Scorecard))
    Learning velocity
      Will I grow fast?
    People quality
      Am I around people better than me?
    Autonomy
      Can I own outcomes?
    Market value
      Does this make me more valuable externally?
    Alignment
      Does this match my 5-year direction?
    Compensation
      Fair for the market?
```

| Career Stage | Maximize |
|---|---|
| Early career | Learning velocity |
| Mid career | Leverage + autonomy |
| Late career | Impact + alignment |

## Weekly Career Review (30 min, Sunday)

- What did I learn this week?
- What high-leverage work did I do?
- What low-value work should I eliminate?
- Who did I help? Who helped me?
- What's my #1 priority next week?

## References

- Cal Newport — *So Good They Can't Ignore You*
- Naval Ravikant — *The Almanack of Naval Ravikant*
- Paul Graham — Essays (paulgraham.com)
- Patrick McKenzie (patio11) — Career advice essays
- Sahil Bloom — Career growth frameworks (Twitter/X, newsletter)
