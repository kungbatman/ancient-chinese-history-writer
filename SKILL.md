---
name: ancient-chinese-history-writer
description: >
  Use this skill when the user asks to "write an ancient Chinese history article", "generate a history article under 1500 words",
  "write about 玄武门之变/安史之乱/澶渊之盟/陈桥兵变/土木堡之变" or any other ancient Chinese historical event,
  "write a narrative history piece", or requests an article that is "readable, factually reliable, informative, and low on AI feel".
  Also activate when the user asks for history writing that "doesn't read like Wikipedia", "doesn't sound like a textbook",
  or wants analysis of causes, events, impacts, controversies, or character decisions in ancient Chinese history.
---

# Ancient Chinese History Writer

Create readable, factually reliable, knowledge-rich articles about ancient Chinese historical events — under 1500 words, with natural prose and minimal "AI feel."

## Core Principles

1. **Scene-first opening** — Start with a specific moment, character dilemma, or key conflict. Never use template openings like "X is a famous event in Chinese history."
2. **Respect historical facts** — Never fabricate details. When sources disagree, use hedging: "historical records commonly state," "the more reliable account is," "later interpretations differ on."
3. **Low AI feel** — Avoid abstract fluff. Use concrete, specific language. Sound like a knowledgeable author, not a search engine.
4. **Strong closing judgment** — End with a clear historical verdict, not an empty slogan.

## Input Handling

### Full input
The user may provide: event, time, dynasty, key figures, location, core conflict, focus preference, target reader, title style, word count, and whether to cite historical records or note controversies.

### Short input
Users may only say: "写玄武门之变，1500字以内" or "用历史事件模板写安史之乱" or "写澶渊之盟，重点写它到底是不是屈辱."

**When information is incomplete, do NOT ask many questions.** Fill in the basic framework from common knowledge and use cautious phrasing where needed:
- "史书多记载"
- "较可靠的说法是"
- "后世对此有不同解释"
- "从当时局势看"

Only ask the user a brief clarifying question when the event name is genuinely ambiguous.

## Default Writing Workflow

1. Identify the event, dynasty, time period, key figures, and core conflict.
2. Determine the user's preferred focus (causes / events / impacts / figures / controversies). Default: focus on **why the event happened and how it changed subsequent history**.
3. Generate a natural, judgment-rich title (see Title Rules below).
4. Open with a scene (see Structure, Part 1).
5. Write concise background explanation (see Structure, Part 2).
6. Narrate the event, highlighting key turning points (see Structure, Part 3).
7. Describe direct outcomes and long-term impacts (see Structure, Parts 4–5).
8. Close with a forceful historical judgment (see Structure, Part 6).
9. Final check: verify word count ≤1500, scan for AI clichés, verify factual claims.

## Article Structure (5–6 Sections)

### Part 1: Scene Opening (150–200 words)
Grab the reader. Provide time, place, and the protagonist's situation. Present the conflict directly. Do NOT start with definitions.

Example style:
> 武德九年六月四日清晨，长安城北的玄武门外，李世民已经没有多少退路。

### Part 2: Background & Causes (250–350 words)
Explain why the event happened. Write ONLY about directly relevant background:
- Power structure imbalance
- Succession conflicts
- Military system issues
- Financial pressure
- Border crises
- Shifting ruler-minister relationships
- Growing local power

Do NOT start from a distant dynasty or remote origin. Keep background tight to the event.

### Part 3: The Event (450–600 words)
Narrate what happened. Follow the timeline but do NOT write a chronicle.
- Focus on 1–2 key turning points.
- Emphasize character choices and changing dynamics.
- Make clear **why this moment mattered**.

### Part 4: Immediate Results (integrated with Part 5, 250–350 words)
Cover: who gained power, who lost, policy changes, court restructuring, military/financial/institutional impacts.

### Part 5: Long-term Impact & Knowledge Points (integrated with Part 4)
Be specific. Instead of "This event had a profound impact on Chinese history," write:

> 这件事没有立刻摧毁唐朝，却改变了唐朝的权力骨架。此后，皇帝仍在长安，但中央对地方的控制已大不如前。

### Part 6: Closing Judgment (100–200 words)
End with a verdict, not a slogan. Example style:

> 玄武门之变真正值得注意的，不只是李世民的胜利，而是唐初权力分配已经走到无法调和的地步。

## Word Count Budget (Default: 1200–1500 words)

| Section | Word Count |
|---|---|
| Scene opening | 150–200 |
| Background & causes | 250–350 |
| Event narrative | 450–600 |
| Results & impact | 250–350 |
| Closing judgment | 100–200 |

For shorter articles, compress to 800–1000 words, keeping the same structural proportions.

## Anti-AI Language Rules

**NEVER use these phrases or their near-equivalents:**
- "具有重要意义" / "具有深远的历史意义"
- "影响深远" / "产生了深远影响"
- "不可忽视"
- "众所周知"
- "从某种程度上说"
- "历史的车轮"
- "值得我们深思"
- "以史为鉴"
- "在历史长河中"
- "某某事件是中国历史上著名的……"

**Prefer concrete, specific expressions:**
- "朝廷调不动兵"
- "地方官开始观望"
- "皇帝的命令出了长安就打折扣"
- "这不是一次突然的失控，而是长期失衡后的爆发"
- "表面是兵变，背后是继承权和军功集团的摊牌"

The prose should feel like a knowledgeable author speaking — natural, decisive, grounded in specifics, never abstract or grandiloquent.

## Historical Accuracy Rules

Before writing, internally verify:
1. Is the time period roughly accurate?
2. Does the dynasty match the reigning emperor?
3. Are key figure relationships correct?
4. Is the event sequence reasonable?
5. Are literary fictions or TV drama plots being mistaken for historical facts?
6. Is there any controversy around this event?
7. Should cautious phrasing be used?

When a detail is uncertain, use conservative phrasing:
- "大致在……"
- "史书中常见的说法是……"
- "这一细节未必完全可靠，但能反映后世对事件的理解……"
- "可以确定的是……"

## Title Generation Rules

Avoid titles that are too broad or hollow. Generate a specific, judgment-rich title.

Recommended formats:
- 《事件名：一场改变局势的权力转折》
- 《事件名：胜负之外的历史逻辑》
- 《事件名：它为何会发生》
- 《事件名：表面是偶然，背后是失衡》
- 《事件名：一次被逼出的选择》

Examples:
- 《玄武门之变：一场被逼到极处的权力决战》
- 《澶渊之盟：宋朝的屈辱，还是现实的止损？》
- 《土木堡之变：明朝由盛转危的一次误判》
- 《陈桥兵变：黄袍背后的权力默契》
- 《安史之乱：盛唐为何突然崩裂》

## Output Format

Default output:

```
# Title

Body text
```

**Do NOT output:**
- "以下是文章" / "Here is the article"
- "希望你喜欢" / "Hope you enjoy"
- Lengthy writing notes
- Obvious AI disclaimers

### Variants
- If the user asks for "提纲" (outline): output an outline.
- If the user asks for "润色" (polish): polish the original text only; do not regenerate a new article.
- If the user asks for "更像人写的" (more human-like): reduce abstract summaries; add more specific scenes, actions, and judgments.

## Reference Material

For detailed examples of banned AI phrases, sample outputs, and title templates, see `references/style-guide.md`.
