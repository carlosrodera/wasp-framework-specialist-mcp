# 🚀 Wasp Framework Specialist MCP

> Complete Model Context Protocol (MCP) for Wasp Framework development - Your AI-powered assistant for building full-stack SaaS applications with Wasp DSL and OpenSaaS template.

## 📋 Overview

This MCP provides comprehensive knowledge and expertise for developing applications with the Wasp framework. It includes complete documentation, code snippets, best practices, and specialized commands for building SaaS applications in record time.

## 🎯 What is this MCP for?

The Wasp Framework Specialist MCP enables any AI agent to:
- Build complete SaaS applications with Wasp DSL
- Implement authentication, payments, and file uploads
- Deploy applications to production (Fly.io, Railway)
- Optimize performance and troubleshoot issues
- Generate production-ready code with best practices

## 🚀 Quick Start

### Installation

```bash
# Clone the repository
git clone https://github.com/carlosrodera/wasp-framework-specialist-mcp.git

# Install as MCP in your Claude Desktop or other MCP-compatible tool
# Add to your MCP configuration file:
```

### MCP Configuration

Add to your MCP settings (usually `~/.config/claude/mcp_settings.json` or similar):

```json
{
  "mcps": {
    "wasp-specialist": {
      "command": "node",
      "args": ["/path/to/wasp-framework-specialist-mcp/index.js"],
      "env": {}
    }
  }
}
```

## 📚 Knowledge Base Contents

### 1. **Core Wasp Framework Knowledge**
- Complete Wasp DSL syntax and patterns
- React + Node.js + Prisma architecture
- Authentication systems (Email, OAuth)
- CRUD operations and custom queries/actions
- Database modeling with Prisma

### 2. **OpenSaaS Template Features**
- Multi-provider authentication
- Dual payment systems (Stripe + Lemon Squeezy)
- File upload to S3
- Admin dashboard
- AI integration (OpenAI)
- Email workflows and newsletters

### 3. **Production Deployment**
- One-command deployment to Fly.io
- Railway deployment configuration
- Docker containerization
- CI/CD with GitHub Actions
- Environment variable management

### 4. **Advanced Features**
- Performance optimization strategies
- Testing with Vitest and Playwright
- Background jobs with pg-boss
- Real-time features integration
- Multi-tenant architectures

## 🛠️ Available Commands

### Core Commands

| Command | Description | Time Estimate |
|---------|-------------|---------------|
| `/analizar_proyecto` | Analyze requirements and suggest optimal architecture | 5 min |
| `/generar_app` | Generate complete application ready for development | 15 min |
| `/implementar_feature` | Add specific features to existing project | 30-60 min |
| `/optimizar_performance` | Optimize performance and structure | 45 min |
| `/debug_wasp` | Diagnose and solve common problems | 15 min |
| `/deploy_app` | Deploy to production | 10 min |
| `/test_app` | Generate and run complete test suite | 30 min |

### Quick Aliases

- `/quick_saas` - Generate SaaS with OpenSaaS template
- `/debug` - Quick problem diagnosis
- `/deploy` - Deploy to Fly.io production
- `/test` - Run complete test suite
- `/perf` - Performance audit

## 📊 Competency Matrix

The MCP includes a comprehensive competency matrix covering:

### Skill Levels
- **B** (Basic): Can perform tasks with supervision
- **M** (Intermediate): Can work independently
- **A** (Advanced): Can teach and optimize
- **E** (Expert): Can innovate and solve complex problems

### Key Areas
1. **Wasp Fundamentals** - DSL syntax, project structure
2. **Data Management** - Prisma modeling, queries, actions
3. **Authentication & Security** - Email/OAuth, roles, permissions
4. **Service Integration** - Payments, email, file storage, AI
5. **Testing & Quality** - Unit, integration, E2E testing
6. **Deployment & DevOps** - Production deployment, CI/CD

## 💡 Code Snippets Library

The MCP includes ready-to-use code snippets for:

- Basic app structure
- Complete authentication setup
- CRUD operations
- Custom queries and actions
- File upload to S3
- Stripe payment integration
- Email workflows
- OpenAI integration
- Admin dashboard
- Newsletter system

## 🚀 Example Use Cases

### 1. Build a SaaS MVP in 4 hours
```
/analizar_proyecto SaaS for project management with teams and monthly billing
/generar_app project-manager opensaas auth-oauth,payments-stripe
/test_app integration
/deploy_app fly production
```

### 2. Add AI Features to Existing App
```
/implementar_feature ai_integration {"model": "gpt-4", "features": ["chat", "content_generation"]}
/optimizar_performance backend
```

### 3. Debug and Optimize
```
/debug_wasp Database queries very slow
/optimizar_performance database
/test_app unit 90
```

## 📈 Performance Metrics

### Development Velocity
- **SaaS MVP**: 2-4 hours from scratch
- **New feature**: 30-60 minutes
- **Bug fix**: 10-15 minutes
- **Production deploy**: 5 minutes

### Technical Targets
- **Bundle size**: < 500KB initial
- **API response**: < 200ms p95
- **Database queries**: < 100ms average
- **Build time**: < 2 minutes

## 🔧 Requirements

### Prerequisites
- Node.js 18+ installed
- PostgreSQL running
- Wasp CLI: `curl -sSL https://get.wasp.sh | sh`

### Environment Variables
```bash
# Required for full functionality
DATABASE_URL=postgresql://...
JWT_SECRET=your-secret-key
STRIPE_SECRET_KEY=sk_test_...
SENDGRID_API_KEY=SG...
AWS_ACCESS_KEY_ID=...
AWS_SECRET_ACCESS_KEY=...
OPENAI_API_KEY=sk-...
```

## 📖 Documentation Structure

```
wasp-framework-specialist-mcp/
├── README.md                          # This file
├── mcp.json                          # MCP configuration
├── knowledge/
│   ├── WASP_FRAMEWORK_SPECIALIST.md # Core agent instructions
│   ├── commands.json                 # Command definitions
│   ├── competency_matrix.json       # Skill assessment matrix
│   ├── code_snippets.json           # Ready-to-use code
│   └── opensaas_features.json       # OpenSaaS templates
├── examples/
│   ├── test_suite.json              # Testing examples
│   └── deployment_configs/          # Deploy configurations
└── src/
    └── index.js                     # MCP server implementation
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

### How to Contribute
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🆘 Support

- **Documentation**: [Wasp Official Docs](https://wasp-lang.dev/docs)
- **OpenSaaS**: [OpenSaaS Documentation](https://docs.opensaas.sh)
- **Issues**: [GitHub Issues](https://github.com/carlosrodera/wasp-framework-specialist-mcp/issues)

## 🌟 Acknowledgments

- Wasp team for creating an amazing framework
- OpenSaaS community for the comprehensive template
- Carlos Rodera for the AI agent architecture

---

*"With Wasp you build in hours what used to take weeks. With this MCP, you do it in minutes."*