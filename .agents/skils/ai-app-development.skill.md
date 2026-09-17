# AI App Development Skill

## Purpose
Build AI-powered app features that are useful, safe, observable, cost-aware, and integrated cleanly with the product.

## When To Use It
Use when adding chat, assistants, content generation, summarization, recommendations, semantic search, image generation, agent workflows, prompt templates, evals, or OpenAI-backed features.

## Checklist
- Define the user value, input, output, model behavior, and failure fallback before coding.
- Use current official provider docs for API syntax, model choices, rate limits, and safety guidance.
- Keep prompts, tools, schemas, and model configuration versioned and reviewable.
- Validate and constrain model inputs and outputs with schemas where practical.
- Protect secrets and route API calls through the backend when keys are required.
- Add cost controls, rate limits, logging, and user-visible loading/error states.
- Avoid sending unnecessary personal or sensitive data to model providers.
- Add lightweight evals or golden examples for important AI behavior.
- Document configuration, model choices, and expected limitations.

## Rules
- Never expose API keys in frontend code.
- Do not make AI the authority for security, billing, permissions, or irreversible actions.
- Prefer structured outputs for app logic.
- Treat prompts as product code, not throwaway text.
- Make failures graceful and understandable.

## Output Format
Return:
- AI feature design.
- Model/provider assumptions.
- Prompt/schema/tool changes.
- Files changed.
- Cost, privacy, and safety notes.
- Evals or manual verification steps.

## Common Mistakes To Avoid
- Calling the model directly from the browser with a secret key.
- Shipping free-form AI output into critical workflows without validation.
- Ignoring latency, cost, rate limits, and abuse.
- Skipping fallback behavior.
- Hardcoding prompts in scattered components.

## Example Prompt
Use `_codex/skills/ai-app-development.skill.md` to add an AI assistant feature to this app. Use backend-mediated API calls, structured outputs where needed, safe prompts, useful error states, and basic eval examples.
