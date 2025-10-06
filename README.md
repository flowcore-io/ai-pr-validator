# ⚠️ Repository Moved

This repository has been renamed and moved to:

## 🆕 [flowcore-io/usable-pr-validator](https://github.com/flowcore-io/usable-pr-validator)

**Usable PR Validator** - Validate Pull Requests against your Usable knowledge base standards using Google Gemini AI.

### Why the rename?

This action is specifically designed for integration with [Usable](https://usable.dev), a team knowledge base and memory system. The new name better reflects its purpose and primary use case.

### What changed?

- **Repository Name**: `ai-pr-validator` → `usable-pr-validator`
- **Action Name**: "AI-Powered PR Validator" → "Usable PR Validator"  
- **Default MCP Server**: Now defaults to `https://usable.dev/api/mcp`
- **Default Token Secret**: `MCP_API_TOKEN` → `USABLE_API_TOKEN`
- **Documentation**: Updated to be Usable-specific with better setup instructions

### Migration

Update your workflows from:
```yaml
- uses: flowcore-io/ai-pr-validator@v1
```

To:
```yaml
- uses: flowcore-io/usable-pr-validator@v1
```

Also update your secret names if using defaults:
- `MCP_API_TOKEN` → `USABLE_API_TOKEN`

---

**Please visit the new repository**: https://github.com/flowcore-io/usable-pr-validator
