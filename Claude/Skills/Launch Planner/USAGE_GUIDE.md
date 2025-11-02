# Launch Planner Skill - Usage Guide

## What This Skill Does

Launch Planner enforces your ship-fast, no-feature-creep philosophy by helping you:
- Transform vague ideas into concrete, shippable MVPs
- Generate lean PRDs and Claude Code starter prompts
- Make product decisions with your validation-first mindset
- Stay focused on shipping (no perfectionism allowed!)

## When It Triggers

The skill automatically activates when you:
- Share an app idea or mention building/launching something
- Ask for help scoping an MVP or creating a PRD
- Request a Claude Code prompt
- Mention validation, feature decisions, or avoiding feature creep
- Need help staying focused on shipping

## What You'll Get

Every time you work with Launch Planner, you'll receive:

1. **PRD.md** - A lean product requirements doc with:
   - One-line pitch
   - Success metric
   - Core user loop
   - Week 1 features only
   - Explicit list of what NOT to build

2. **claude-code-prompt.txt** - A ready-to-use prompt for Claude Code with:
   - Your tech stack (Node.js, Nest.js, Prisma, HTMX/Next.js)
   - Specific implementation details
   - Database schema
   - Clear list of what to exclude

3. **scope-decisions.md** (when needed) - Decision log tracking what's in/out and why

## Example Interaction

**You**: "I want to build a tool that helps developers track their learning progress"

**Launch Planner will**:
1. Ask the 3 validation questions (Who? What problem? How to measure?)
2. Define the core user loop
3. Generate a lean PRD focused on week 1 deliverables
4. Create a Claude Code starter prompt with your tech stack
5. Call out any feature creep if you suggest additions

## Your Product Philosophy (Built In)

The skill enforces these principles automatically:
- ✅ Ship in 1 week max
- ✅ Build only core user loop features
- ✅ Validate with real users first
- ❌ No auth before validation
- ❌ No features "users might want later"
- ❌ No over-engineering for scale

## Advanced Features

**MVP Patterns**: The skill includes a reference guide with:
- Common MVP scenarios (marketplace, SaaS, content platform, etc.)
- Technical implementation patterns
- Validation metrics by app type
- Feature creep detection red flags
- Week 1 build timeline

When you need deeper guidance, just ask and the skill will reference these patterns.

## Installation

Your **launch-planner.skill** file is ready to install. Upload it in your Claude settings under Skills to start using it immediately.

## Tips for Best Results

1. **Be specific about the problem**: The clearer your problem statement, the better the PRD
2. **Trust the process**: If the skill says "feature creep," it probably is
3. **Start with the PRD**: Always generate the PRD before jumping into code
4. **Use the Claude Code prompt**: It's pre-configured with your tech stack and philosophy
5. **Ship, then iterate**: Get something live, then improve based on real feedback
