# Contributing to DarkwebCTI

We welcome contributions from the cybersecurity community! This guide outlines how to contribute effectively to our threat intelligence repository.

## 🎯 **Ways to Contribute**

### 📊 **Intelligence Contributions**
- **New threat channels** - Telegram, Discord, forums
- **Marketplace intelligence** - New markets, updates to existing
- **Malware family analysis** - Technical analysis, IOCs, TTPs
- **Case studies** - Real-world threat hunting scenarios
- **Onion site intelligence** - Active dark web resources

### 🛠️ **Technical Contributions**
- **Monitoring tools** - Automation scripts, crawlers
- **Analysis utilities** - Data processing, enrichment tools
- **YARA rules** - Malware detection signatures
- **Documentation** - Methodology improvements, tutorials

### 🔍 **Research Contributions**
- **Threat landscape analysis** - Market trends, actor profiling
- **Methodology development** - Investigation techniques
- **Tool evaluation** - Security tool assessments

## 📋 **Contribution Guidelines**

### 🔒 **Legal & Ethical Requirements**

**Before contributing, ensure:**
- Information is from **publicly available sources**
- Content serves **defensive security purposes**
- No **illegal activities** are facilitated or endorsed
- **Privacy** of legitimate users is protected
- **Attribution** to original sources is maintained

### 📝 **Content Standards**

#### Intelligence Quality
- **Verified Information**: Cross-reference sources
- **Current Data**: Focus on active threats (last 12 months)
- **Actionable Intel**: Include IOCs, TTPs, defensive recommendations
- **Context**: Provide background and significance
- **Risk Assessment**: Include threat level classifications

#### Documentation Format
- **Markdown formatting** for consistency
- **Clear structure** with headers and sections
- **Tables and lists** for data organization
- **Metadata**: Include dates, sources, confidence levels
- **Professional tone** suitable for security professionals

## 🚀 **Getting Started**

### 1. **Fork & Clone**
```bash
# Fork the repository on GitHub
# Then clone your fork locally
git clone https://github.com/YOUR_USERNAME/darkwebCTI.git
cd darkwebCTI

# Add upstream remote
git remote add upstream https://github.com/shubhamnayak1708/darkwebCTI.git
```

### 2. **Create Feature Branch**
```bash
# Create a descriptive branch name
git checkout -b feature/telegram-stealer-analysis
# or
git checkout -b update/marketplace-intelligence-q4-2025
```

### 3. **Make Your Changes**
- Follow the existing file structure
- Use appropriate directory locations
- Include relevant metadata and sourcing

### 4. **Test & Validate**
- Verify markdown formatting
- Check links and references
- Ensure data quality and accuracy

## 📂 **Repository Structure**

### Directory Guidelines

```
darkwebCTI/
├── intelligence/
│   ├── marketplaces/     # Dark web market intelligence
│   ├── telegram/         # Telegram channel monitoring
│   ├── malware/         # Malware family analysis
│   └── onion-sites/     # Dark web resources
├── docs/
│   ├── methodology/     # Investigation techniques
│   ├── threat-landscape/# Market analysis, trends
│   └── case-studies/    # Real-world scenarios
├── tools/              # Automation, monitoring tools
└── resources/          # References, links, papers
```

### File Naming Conventions
- **Lowercase with hyphens**: `stealer-channels.md`
- **Descriptive names**: `redline-stealer-analysis.md`
- **Date suffixes**: `q4-2025-threat-landscape.md`
- **Consistent extensions**: `.md` for markdown, `.csv` for data

## ✅ **Pull Request Process**

### 1. **Pre-Submission Checklist**
- [ ] Content follows legal/ethical guidelines
- [ ] Information is verified and sourced
- [ ] Markdown formatting is correct
- [ ] File naming follows conventions
- [ ] No sensitive/personal information included
- [ ] Changes are documented in commit messages

### 2. **Pull Request Template**
```markdown
## Description
Brief description of the changes and their purpose.

## Type of Contribution
- [ ] Intelligence update
- [ ] New methodology/tool
- [ ] Documentation improvement
- [ ] Bug fix

## Intelligence Sources
- Source 1: [Description/Link]
- Source 2: [Description/Link]

## Verification
- [ ] Information cross-referenced
- [ ] Sources are publicly available
- [ ] Content serves defensive purposes

## Additional Context
Any additional information relevant to the contribution.
```

### 3. **Review Process**
- **Initial Review**: Automated checks (formatting, links)
- **Content Review**: Manual verification of intelligence quality
- **Security Review**: Ensure no sensitive information disclosed
- **Final Approval**: Maintainer approval and merge

## 🏷️ **Issue Templates**

### Intelligence Requests
```markdown
**Intelligence Type**: [Telegram/Marketplace/Malware/Other]
**Priority**: [High/Medium/Low]
**Description**: Detailed description of needed intelligence
**Use Case**: How this intelligence will be used
**Sources**: Any known sources or starting points
```

### Bug Reports
```markdown
**File/Section**: Affected file or documentation section
**Issue**: Description of the problem
**Expected**: What should happen
**Actual**: What currently happens
**Environment**: Browser, OS, etc. if relevant
```

## 👥 **Community Guidelines**

### 🤝 **Code of Conduct**
- **Professional Communication**: Maintain respectful discourse
- **Collaborative Spirit**: Help others learn and contribute
- **Security Focus**: Prioritize defensive cybersecurity goals
- **Ethical Behavior**: Follow responsible disclosure practices
- **Inclusive Environment**: Welcome contributors of all backgrounds

### 📞 **Communication Channels**
- **GitHub Issues**: Bug reports, feature requests
- **GitHub Discussions**: General community discussion
- **Telegram Group**: Real-time communication (invitation-only)
- **Email**: security-sensitive communications

## 🎖️ **Recognition**

Contributors will be recognized through:
- **GitHub Contributors List**: Automatic recognition
- **Special Mentions**: Significant contributions highlighted
- **Community Credits**: Attribution in documentation
- **Professional References**: LinkedIn recommendations available

## 🔧 **Development Setup**

### Prerequisites
- Git version control
- Markdown editor (VS Code recommended)
- Python 3.8+ (for tools development)
- Tor Browser (for dark web research)

### Recommended Tools
- **VS Code Extensions**: Markdown All in One, markdownlint
- **Python Libraries**: requests, beautifulsoup4, pandas
- **Security Tools**: YARA, Wireshark, Burp Suite

## ❓ **Questions & Support**

- **Documentation Questions**: Check existing docs first
- **Technical Issues**: Open GitHub issue with details
- **Security Concerns**: Email maintainers directly
- **General Discussion**: Use GitHub Discussions

## 📜 **License**

By contributing to DarkwebCTI, you agree that your contributions will be licensed under the GPL-3.0 License.

---

**Thank you for contributing to the cybersecurity community!** 🛡️

*Together, we make the digital world safer through shared threat intelligence.*