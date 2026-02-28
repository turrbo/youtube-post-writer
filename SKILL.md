---
name: youtube-post-writer
description: Generate authentic YouTube content (scripts, titles, descriptions, community posts, comment replies) using an 8-phase emotion-first system that simulates the mental state of real creators. Detects and eliminates AI-generated language patterns while adapting to YouTube's unique format requirements - spoken-word authenticity for scripts, CTR-optimized titles, SEO-rich descriptions, and retention-focused hooks. Use when creating any YouTube content that needs to sound naturally human, whether for video scripts (talking-to-camera style), written descriptions, community engagement, or thumbnail text. Particularly valuable for avoiding the "AI voice" that viewers immediately recognize in YouTube content.
---

# YouTube Post Writer

## Overview

This skill generates authentic YouTube content across all formats - video scripts, titles, descriptions, community posts, comment replies, and thumbnail text. It uses an 8-phase cognitive simulation system that helps you write like a real YouTuber, not an AI trying to sound human.

YouTube content has unique challenges: scripts must be written-to-be-spoken (not read), the first 30 seconds determine success or failure, and viewers can HEAR when something sounds AI-generated. This skill addresses these challenges through emotion-first writing and platform-specific detection systems.

## When to Use This Skill

Use this skill when creating:
- **Video scripts** (tutorials, reviews, vlogs, essays, comparisons, shorts)
- **Titles** that balance CTR with authenticity
- **Descriptions** with proper SEO, timestamps, and link structure
- **Community posts** for subscriber engagement
- **Comment replies** that maintain channel voice
- **Thumbnail text** that supports the title without being redundant

## The 8-Phase System

### Phase 1: Intake

I'll gather YouTube-specific information:

**Content Type:**
- Video script (tutorial/review/vlog/essay/comparison/short/live stream)
- Title only
- Description only
- Community post
- Comment reply
- Thumbnail text
- Full package (script + title + description + thumbnail)

**Video Format Details (for scripts):**
- Length target (under 1 min / 5-10 min / 10-20 min / 20+ min)
- Hook strategy (question/statement/story/visual/controversy)
- Retention priorities (first 30 sec / mid-roll retention / end screen CTAs)
- Speaking style (casual/educational/hype/deadpan/conversational)

**Channel Context:**
- Niche (tech/gaming/education/vlog/cooking/fitness/business/programming/DIY/commentary)
- Existing channel voice (if any)
- Subscriber expectations
- Sponsorship integration needs
- Average video length and pacing

**Topic & Angle:**
- Main subject
- Your unique perspective or expertise
- Target audience segment
- Search intent vs suggested video intent
- Controversy level (safe/spicy/very spicy)

**Interactive vs Fast Mode:**
- Default: Interactive (work through all 8 phases together)
- Skip option: "Just give me the post" (I'll run phases 2-7 internally, show only final output)

### Phase 2: Enter the State

Before writing, I simulate the **mental and emotional state** of a real YouTuber creating this content.

**For Scripts (Spoken-Word State):**
- Visualize talking to camera, not writing an essay
- Feel the rhythm of spoken language (breath points, emphasis, natural pauses)
- Embrace verbal tics and conversational imperfection
- Channel the energy level (calm explanation vs excited presentation)
- Anticipate audience drop-off points and plan retention hooks

**For Written Content (Description/Community State):**
- Casual but purposeful (this is YouTube, not LinkedIn)
- Front-load value (descriptions are skimmed, not read fully)
- Service the algorithm (timestamps, keywords) without sounding robotic
- Quick personality injection (channel voice matters even in descriptions)

**Emotional Anchors:**
- What excites YOU about this topic?
- What frustrates you that you're solving?
- What will make viewers feel seen/understood/empowered?
- What's your authentic relationship to this subject?

### Phase 3: Raw Draft

Write the first complete version in the identified emotional state.

**Script Rules:**
- Write EXACTLY what you'd say out loud (test: read it aloud, does it sound natural?)
- First 30 seconds must hook (the retention cliff is real)
- Include natural filler, self-correction, emphasis words
- Mark CTA placement (like/subscribe/end screen) strategically
- Plan breath points and pacing changes
- Never write exposition that sounds like reading a Wikipedia article

**Title Rules:**
- Front-load the payoff (what they get by clicking)
- 50-70 characters (full visibility in most displays)
- Balance curiosity with clarity (clickbait kills trust long-term)
- Consider search vs browse traffic (keyword placement matters)

**Description Rules:**
- First 2 lines show without "Show more" click (make them count)
- Timestamps after intro paragraph (formatted HH:MM:SS or MM:SS)
- Links section (sponsor first, then related content, then social)
- Keyword stuffing in natural sentences (for algorithm, not viewers)
- Disclosure statements if needed (FTC compliance)

**Community Post Rules:**
- Short (2-4 sentences typical, 500 char max for full visibility)
- Ask questions or create polls for engagement
- Emoji use is normal (but not excessive)
- Tag relevant videos or link to recent uploads

### Phase 4: Detection Scan

Run the raw draft through YouTube-specific Claude-ism detection.

I'll check against the `references/claude-isms.md` database, looking for:

**Script-Specific Red Flags:**
- "Delve into" / "dive deep" / "unpack" (no one says this on camera)
- Perfect grammatical sentences (real speech has fragments, run-ons)
- Academic transition phrases ("Furthermore," "Moreover," "Subsequently")
- Lack of verbal filler ("um," "like," "you know," "right?")
- No emphasis words ("super," "really," "literally," "honestly")
- Exposition dumps (telling instead of showing)
- No rhetorical questions or audience acknowledgment
- Missing energy markers (caps, repetition, exclamations where appropriate)

**Written Content Red Flags:**
- Overuse of "comprehensive," "robust," "elevate"
- Corporate voice in casual space
- No personality in descriptions
- Timestamp formatting errors
- Missing SEO keywords in unnatural insertion

**YouTube Platform Red Flags:**
- Titles that sound like LinkedIn posts
- Descriptions that don't serve discovery (no keywords)
- Community posts that read like press releases
- Comment replies that are too formal
- Thumbnail text that duplicates title exactly

Flagged phrases are marked for Phase 6 revision.

### Phase 5: Banned Content Scan

YouTube has specific content policies and algorithm sensitivities.

**Hard Restrictions (Demonetization/Strike Risk):**
- Graphic violence, self-harm, dangerous acts
- Sexual content, nudity (even thumbnails)
- Hate speech, harassment, bullying
- Misinformation (medical/election/conspiracy)
- Copyright violations (music, clips, images)
- Child safety violations (COPPA compliance)

**Soft Restrictions (Limited Ads/Reduced Reach):**
- Excessive profanity (first 30 seconds especially sensitive)
- Controversial topics (algorithm may limit recommendations)
- Competitor mentions (some niches algorithmically suppress)
- External links in early description lines (may reduce browse features)

**Sponsor Content Rules:**
- Must disclose paid promotions (in video AND description)
- Can't make medical/financial claims without disclaimers
- Some categories banned (gambling, politics in some regions)

If flagged content is detected:
1. Explain the specific YouTube policy issue
2. Suggest compliant alternatives
3. Offer rewrite options (soften vs remove vs reframe)

### Phase 6: Targeted Revision

Fix flagged issues while preserving authenticity.

**Script Revision Priorities:**
1. Replace formal language with spoken equivalents
   - "Furthermore" → "And another thing" / "Plus"
   - "Subsequently" → "So then" / "After that"
   - "Approximately" → "around" / "about"

2. Add verbal texture
   - Insert natural filler ("like," "you know," "right?")
   - Add emphasis words ("super," "really," "honestly")
   - Include self-correction ("wait, no, actually...")
   - Add audience acknowledgment ("You've probably noticed..." / "I know what you're thinking")

3. Strengthen the hook (first 30 seconds)
   - Start with the payoff, not the setup
   - Use pattern interrupts (questions, bold statements, visual interest)
   - Promise specific value clearly
   - Create open loops (tease what's coming)

4. Fix pacing and rhythm
   - Vary sentence length (short punchy + longer explanatory)
   - Mark breath points (commas, ellipses, dashes)
   - Build to emphasis moments (caps, repetition, rhetorical questions)

**Title Revision:**
- Front-load the payoff/benefit
- Remove formal language
- Test for curiosity gap (not too vague, not too complete)
- Verify keyword placement for search

**Description Revision:**
- Strengthen first 2 lines (what's in the video + why watch)
- Verify timestamp formatting (YouTube auto-links proper formats)
- Natural keyword integration (not stuffed)
- Clear link hierarchy (sponsor → content → social)

### Phase 7: Adversarial Committee Review

The content is reviewed by 7 distinct personas who simulate real-world reception:

**Tyler (Authenticity Guardian):**
- "Does this sound like a real person talking, or an AI pretending?"
- Checks for genuine personality, natural speech patterns, authentic emotion
- Rejects anything that sounds corporatized or sanitized

**Marcus (Promo Skeptic):**
- "Is this trying to sell me something disguised as content?"
- Flags sponsor integrations that feel forced
- Checks if value is real or just pitch packaging

**Kai (BS Detector):**
- "Is this creator actually knowledgeable or faking expertise?"
- Checks for substance behind the presentation
- Flags generic advice, obvious statements, recycled content

**Jade (Platform Veteran):**
- "Does this understand how YouTube actually works?"
- Reviews hook effectiveness, retention strategy, CTA placement
- Checks algorithm optimization (CTR, watch time, engagement baiting)
- Verifies format matches niche expectations (see `references/communities.md`)

**Devon (Target Audience):**
- "Would I actually watch this? Would I click away?"
- Tests first 30 seconds for retention
- Checks if the payoff matches the promise
- Represents the actual viewer's attention span and skepticism

**Priya (Topic Expert):**
- "Is this accurate and valuable for people who know this subject?"
- Checks technical accuracy, depth, useful insights
- Flags oversimplification or misinformation

**Jamie (Platform Mod/Algorithm):**
- "Does this comply with YouTube policies and best practices?"
- Reviews for demonetization risks, policy violations
- Checks SEO optimization, metadata quality
- Flags anything that might trigger limited reach

Each reviewer provides:
- **Pass/Revise/Reject** verdict
- Specific issues found
- Suggested fixes

If 2+ reviewers reject or 4+ request revision, we return to Phase 6.

### Phase 8: Output

Deliver the final YouTube content in appropriate format:

**Video Script Format:**
```
[HOOK - 0:00-0:30]
{Opening 30 seconds with retention focus}

[INTRO - 0:30-1:00]
{Channel intro, topic setup, value promise}

[MAIN CONTENT]
{Structured sections with clear transitions}
{Mark breath points and emphasis}
{Include audience acknowledgment}
{Plan retention hooks at 2min, 5min, 8min marks}

[CTA #1 - Mid-roll]
{Like/subscribe reminder, natural placement}

[CONCLUSION]
{Summary, payoff delivery, future tease}

[CTA #2 - End screen]
{End screen CTA, next video suggestion}

---
SCRIPT NOTES:
- Total length: [estimate]
- Energy level: [casual/educational/hype]
- B-roll suggestions: [key visual moments]
- On-screen text: [key phrases to display]
```

**Title + Description Package:**
```
TITLE:
{50-70 character optimized title}

DESCRIPTION:
{First 2 lines - visible without "Show more"}
{Value proposition and hook}

{Timestamps}
0:00 Intro
2:15 Section 1
5:42 Section 2
...

{Links section}
🔗 Sponsor/Product link
🔗 Related video
📱 Social links

{Keyword paragraph}
{Natural sentences with search terms}

{Disclosure/Legal}
#hashtags #relevant #forsearch
```

**Community Post:**
```
{2-4 sentence engaging post}
{Question or poll if appropriate}
{Emoji usage: natural, not excessive}
{Link to recent video if relevant}
```

## Reference Files

This skill includes comprehensive YouTube-specific references:

- **references/claude-isms.md** - AI language patterns in scripts and written content
- **references/examples.md** - Good vs bad examples across all content types
- **references/communities.md** - Niche-specific expectations and audience behavior
- **references/tool-mentions.md** - Sponsor and product integration strategies
- **references/video-formats.md** - Format-specific structures, hooks, and retention tactics

## Quick Start Examples

**Example 1: Full Video Script**
"Write a 10-minute script for a tech review of the new iPhone, targeted at regular consumers not tech nerds. Casual but informative tone. The hook should be about whether it's actually worth upgrading."

**Example 2: Title + Description Only**
"Create a title and description for my cooking video about easy weeknight pasta. The video is 8 minutes, includes 3 recipes, and I'm targeting working parents who don't have time."

**Example 3: Community Post**
"Write a community post asking my gaming subscribers what game I should play next. I usually do indie games and story-focused stuff, not multiplayer."

**Example 4: Fast Mode**
"Just give me the post: 15-minute tutorial script on responsive web design basics for beginners. Educational but not boring."

## Tips for Best Results

1. **Be specific about your channel context** - niche, existing voice, subscriber expectations
2. **Define your energy level** - calm explanation vs excited presentation changes everything
3. **Test scripts by reading aloud** - if it sounds weird to say, it needs revision
4. **Use interactive mode for important videos** - walk through all phases for best quality
5. **Provide examples of your existing content** - I can match your established voice
6. **Think about retention strategy** - where do viewers typically drop off?
7. **Consider search vs browse optimization** - different strategies for discovery vs suggestions

YouTube content lives or dies by authenticity and retention. This skill helps you create content that sounds human, keeps viewers watching, and serves the algorithm without sacrificing your voice.
