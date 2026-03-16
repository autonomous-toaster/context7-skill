# Context7 Skill Package

Query library documentation via Context7 API for up-to-date code examples, API references, and implementation details.

## Installation

### Global
```bash
pi install npm:@autonomous-toaster/context7-skill
```

### Project
```bash
pi install -l npm:@autonomous-toaster/context7-skill
```

### Trial (Temporary)
```bash
pi -e npm:@autonomous-toaster/context7-skill
```

## Requirements

- **Context7 API Key** - Set the `CONTEXT7_API_KEY` environment variable
- pi coding agent

## Features

- Search for any library or technology in the Context7 database
- Get relevant code snippets and examples
- Retrieve API references and documentation
- Compare multiple libraries
- Access implementation patterns and best practices

## Usage

Once installed, use the skill with prompts like:

- "What's the latest API for react hooks?"
- "Show me examples of using FastAPI decorators"
- "Compare authentication approaches in passport.js"
- "Find documentation for the latest langchain features"

## Environment Setup

```bash
# Set your Context7 API key
export CONTEXT7_API_KEY="your-api-key-here"

# Verify it's set (don't print the actual key!)
echo "API key is set: $([ -n "$CONTEXT7_API_KEY" ] && echo 'YES' || echo 'NO')"
```

## API Endpoints

The skill provides access to:

1. **Library Search** - Find libraries by name or technology
2. **Documentation Context** - Get relevant snippets for specific queries
3. **Code Examples** - Retrieve practical implementation examples
4. **Best Practices** - Access community-recommended patterns

## More Information

See the included `SKILL.md` file for detailed API documentation and advanced usage patterns.
