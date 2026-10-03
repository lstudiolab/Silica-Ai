# Silica Ai

Coding-first AI assistant. React/Vite frontend for GitHub Pages; Express/TypeScript API for Render; OpenRouter for model access.

Default model: openai/gpt-6-astra. Keep OPENROUTER_API_KEY only on Render. Set VITE_API_URL to the Render API URL for GitHub Pages.

Render: root apps/api; build npm ci && npm run build; start npm start. Required variables: OPENROUTER_API_KEY, FRONTEND_ORIGIN. Optional: OPENROUTER_MODEL, OPENROUTER_FALLBACK_MODELS.
