# State

## 2026-09-22 - Before-box-move checkpoint

Unsaved work: `infra/core/ai/ai-project.bicep` adds the optional
`resourceBaseName` parameter and uses it for container registry, Application
Insights, Log Analytics, and the Application Insights connection names, retaining
the generated names when the parameter is empty.
Amanda approved preserving this existing infrastructure edit with this state
entry on `main` and pushing to the personal `origin`.
This is a source checkpoint only; no Azure resources are created or changed.
