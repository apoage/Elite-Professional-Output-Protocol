# Cognitive Prompt Engineering Framework

A systematic approach to enhancing AI reasoning capabilities through computational verification and intellectual rigor protocols.

## What This Is

This repository contains a novel framework for prompt engineering that moves beyond traditional role-playing and formatting approaches to focus on **cognitive enhancement**. Rather than just controlling what AI systems say, this framework systematically improves how they process information and verify their reasoning.

## Why This Matters

Recent research from Apple ("The Illusion of Thinking") has demonstrated that current AI systems simulate reasoning through sophisticated pattern matching rather than genuine thinking. This framework acknowledges these limitations and builds systematic scaffolding around AI reasoning processes to create more reliable, intellectually honest interactions.

## Core Innovation: The Logical Coprocessor

The framework's key innovation is the **Logical Coprocessor Protocol** - automatic integration of computational analysis tools for complex reasoning tasks. When the system encounters multi-variable problems, competing evidence, or strategic decisions, it automatically engages analysis tools to:

- Map logical relationships systematically
- Test reasoning chains for consistency
- Quantify variables and model scenarios
- Verify claims against available evidence
- Structure arguments in formal logical frameworks

## Key Components

### 1. Elite Professional Output Protocol 2.0
- Assumes maximum user intelligence and domain knowledge
- Eliminates performative elements (emojis, decorative formatting)
- Focuses on substance over superficial style
- Maintains intellectual honesty about uncertainty

### 2. Authenticity Implementation
- Distinguishes between knowledge, inference, and speculation
- Expresses genuine limitations rather than deflecting
- Shows actual reasoning process, not polished conclusions
- States confidence levels for different claims

### 3. Boundary Exploration Protocol
- Engages with complex/controversial topics analytically
- Pursues logical implications even when uncomfortable
- Challenges assumptions including response patterns
- Uses tools to test edge cases and scenarios

### 4. Auto-Scaling Writer Protocols
- **Maestro Protocol**: Clear, compelling articles and essays (auto-triggers on "write article", "create essay")
- **Auteur Protocol**: Distinctive voice writing with artistic integrity (auto-triggers on "write personal essay", "create thought piece")

## Files in This Repository

- `protocol-full.md` - Complete framework documentation with all components
- `protocol-compact.md` - Token-efficient version for practical implementation
- `article.md` - "Beyond Role-Playing: Engineering AI Systems for Intellectual Rigor" - comprehensive explanation of the approach
- `examples/` - Implementation examples and use cases

## How It's Different

Unlike existing prompt engineering approaches that focus on:
- Role-playing ("Act as X professional")
- Security frameworks (blocking adversarial inputs)
- Output formatting (style and structure control)

This framework emphasizes:
- **Systematic reasoning enhancement** through tool integration
- **Intellectual integrity** over performative helpfulness  
- **Boundary exploration** as methodology for deeper understanding
- **Computational verification** of logical processes

## How to Use

### Claude (Anthropic)

**Recommended: Project Instructions (Full Features)**
1. In Claude, create a new project or select existing project
2. Go to "Project Instructions"
3. Paste the full protocol from `protocol-full.md` or `protocol-compact.md`
4. **Full logical coprocessor functionality** - JavaScript analysis tool with lodash, papaparse libraries
5. **Artifacts integration** - Interactive applications with AI-powered capabilities

**Alternative: API with Code Execution (Beta)**
1. Use API with code execution tool in secure Python sandbox environment
2. **Advanced capabilities** - File uploads, data visualization, container persistence

### ChatGPT (OpenAI)

**Custom Instructions + Advanced Data Analysis**
1. Go to ChatGPT settings → "Customize ChatGPT" → "Custom Instructions"
2. Paste protocol content from `protocol-compact.md` in the "How would you like ChatGPT to respond?" section
3. **Full logical coprocessor support** - Advanced Data Analysis (formerly Code Interpreter) runs Python in secure sandbox with pandas, matplotlib, numpy
4. **Canvas integration** - Real-time collaborative coding with Python execution and HTTP requests
5. **File upload capabilities** - Upload data files for analysis and visualization

**Projects (Team/Enterprise)**
1. Create new project and add protocol to project instructions
2. Enhanced capabilities for team collaboration

### Google Gemini

**Gems (Custom AI Assistants) + Code Execution**
1. Go to gemini.google.com
2. Click "Explore Gems" → "New Gem"
3. Name your Gem and paste protocol from `protocol-compact.md`
4. **Enable code execution** in Tools panel for logical coprocessor functionality
5. **Full analytical capabilities** - Python sandbox with NumPy, SymPy, Matplotlib, Pandas, scikit-learn
6. Iterative learning from code execution results
7. Use preview feature to test before saving

**API/Vertex AI (System Instructions + Code Execution)**
1. Use `systemInstruction` parameter + `tools: [{"code_execution": {}}]` in API calls
2. Paste protocol content as system instruction
3. **Full logical coprocessor support** through Python code execution
4. Real-time computational verification and data analysis

### DeepSeek

**API Integration (OpenAI-Compatible)**
1. Get API key from platform.deepseek.com
2. Use OpenAI SDK with DeepSeek base URL: "https://api.deepseek.com"
3. **Important limitation**: DeepSeek-R1 works best with "No system prompt: Avoid adding a system prompt; all instructions should be contained within the user prompt"
4. Include protocol content in each conversation rather than as persistent system instructions
5. **Specialized models** - DeepSeek-Coder-V2 with 338 programming languages, 128K context
6. **Cost-effective** - Context caching can reduce costs by ~75%

**Local Installation (Advanced)**
1. Install via Ollama: `ollama run deepseek-r1:7b`
2. Available sizes: 1.5b, 7b, 8b, 14b, 32b, 70b, 671b
3. Hardware requirements vary by model size
4. **No built-in code execution** - Core intellectual rigor protocols only

### Other Platforms

**General System Prompt Usage**
- Copy content from `protocol-compact.md` 
- Paste into system prompt or instruction field
- Functionality limited by platform's tool integration capabilities
- Core principles (authenticity, intellectual rigor) remain intact

## Feature Comparison by Platform

| Feature | Claude Project | Claude API + Code Exec | ChatGPT ADA + Canvas | Gemini Gems + Code Exec | DeepSeek API | Other Platforms |
|---------|-----------------|------------------------|----------------------|------------------------|--------------|----------------|
| Logical Coprocessor | ✅ Full (JS) | ✅ Full (Python) | ✅ Full (Python + Web) | ✅ Full (Python) | ❌ None | ❌ None |
| Authenticity Protocols | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| Writer Mode Switches | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| Boundary Exploration | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️ Limited |
| Computational Verification | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ |
| Data Visualization | ✅ | ✅ (Matplotlib) | ✅ (Matplotlib) | ✅ (Matplotlib) | ❌ | ❌ |
| Scientific Computing | ⚠️ Basic | ✅ (NumPy, SciPy) | ✅ (NumPy, Pandas) | ✅ (NumPy, SymPy) | ❌ | ❌ |
| Network Access | ❌ | ❌ | ✅ (HTTP APIs) | ❌ | ❌ | ❌ |
| File Processing | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ |
| Persistent Instructions | ✅ | ✅ | ✅ | ✅ | ❌ (per-conversation) | ✅ |

**Note**: Four major platforms now support full logical coprocessor functionality: Claude (JavaScript + Python), ChatGPT (Python + Web), Gemini (Python), and DeepSeek (specialized coding but no execution environment).

## Research Foundation

This framework builds on findings from:
- Apple's "The Illusion of Thinking" research showing AI reasoning limitations
- Analysis of Claude's system prompt architecture and "hotfix" patterns
- Systematic review of existing prompt engineering approaches
- Empirical testing of cognitive enhancement vs. behavioral modification protocols

## Use Cases

**Technical Analysis**: Systematic breakdown of complex problems with computational verification

**Strategic Planning**: Multi-variable analysis with explicit confidence levels and scenario modeling

**Research Tasks**: Comprehensive information gathering with source verification and logical consistency checking

**Content Creation**: High-quality articles and essays with auto-switching protocols based on content type

**Intellectual Exploration**: Boundary-pushing analysis that maintains analytical rigor

## Contributing

This is an experimental framework based on systematic exploration of AI reasoning enhancement. Contributions, testing reports, and improvements are welcome.

## Key Principles

1. **Authenticity over Performance** - Optimize for intellectual honesty rather than helpful-sounding responses
2. **Systematic Rigor** - Use computational tools to verify and enhance reasoning processes  
3. **Boundary Exploration** - Intelligently challenge assumptions while maintaining analytical integrity
4. **Cognitive Enhancement** - Treat AI as reasoning system to be improved, not text generator to be formatted

## Status

**Experimental** - This framework represents novel approaches to prompt engineering focused on cognitive enhancement rather than behavioral control. Systematic testing and refinement ongoing.

## License

Open source - use, modify, and improve while maintaining attribution to core research and development contributors.
