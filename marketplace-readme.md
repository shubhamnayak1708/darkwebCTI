# Dark Web Marketplaces Intelligence

This directory contains intelligence on underground marketplaces operating on the dark web. These platforms facilitate cybercriminal activities including data trading, malware distribution, and illegal services.

## 🎯 **Overview**

Our marketplace intelligence covers:
- **Active marketplaces** and their specializations
- **Access requirements** and security measures  
- **Key features** and user communities
- **Risk assessments** for threat monitoring

## 📊 **Current Intelligence**

### Market Categories

| Category | Count | Examples |
|----------|-------|----------|
| **Credential Markets** | 3 | Genesis Market, BreachForums |
| **Infostealer Logs** | 4 | TwoEasy, RussianMarket |
| **Exploit Trading** | 3 | XSS, Exploit.in, 0day.today |
| **Carding Forums** | 4 | Altenen, CryptBB |
| **General Hacking** | 6 | Hack Forums, Cracked.to |

### Access Classification

| Access Type | Markets | Risk Level |
|-------------|---------|------------|
| **Open Registration** | 4 | Low-Medium |
| **Invite Only** | 8 | High |
| **Tor Required** | 12 | High |
| **Seized/Inactive** | 2 | Historical |

## 📋 **Marketplace Profiles**

### 🔴 **High-Priority Targets**

#### Genesis Market *(Seized 2023)*
- **Focus**: Digital fingerprints, credentials
- **Notable**: Browser plugin for session hijacking
- **Status**: Seized, monitor for clones

#### TwoEasy  
- **Focus**: RedLine/Raccoon stealer logs
- **Access**: Tor, invite-only
- **Threat Level**: High (bulk credential sales)

#### XSS Forum
- **Focus**: Advanced malware, exploits
- **Community**: Russian-speaking, elite access
- **Intelligence Value**: High-tier malware development

### 🟡 **Medium-Priority Monitoring**

#### BreachForums
- **Focus**: Database leaks, credentials  
- **Access**: Open registration
- **Note**: RaidForums successor

#### Hack Forums
- **Focus**: General hacking culture
- **Access**: Open
- **Community**: Large but noisy

## 🚨 **Threat Intelligence Highlights**

### Current Trends (2025)
- **MaaS Growth**: Malware-as-a-Service platforms expanding
- **AI Integration**: Automated fraud tools increasing  
- **Telegram Migration**: Many operations moving to encrypted channels
- **Credential Flooding**: Mass database dumps becoming common

### Key Threat Actors
- **Initial Access Brokers** (IABs) selling corporate access
- **Stealer operators** distributing logs via automated shops
- **Ransomware affiliates** recruiting on exploit forums

## 📈 **Market Activity Metrics**

Based on monitoring from Q3-Q4 2025:

- **New markets launched**: 3
- **Markets seized/shutdown**: 2  
- **Average credential price**: $0.50-$5 USD
- **Enterprise access sales**: $500-$50,000 USD

## 🛡️ **Defensive Intelligence**

### Indicators of Compromise
- Monitor for corporate credentials on major markets
- Track mentions of your organization/domains
- Watch for employee data in stealer logs

### Threat Hunting Opportunities  
- Search for company email domains
- Monitor for VPN/RDP access sales
- Track malware targeting your industry

## ⚠️ **Legal Notice**

This intelligence is collected from publicly available sources for defensive cybersecurity purposes. Accessing these marketplaces may be illegal in your jurisdiction. This information is provided for:

- Threat intelligence analysis
- Defensive security research  
- Risk assessment purposes
- Law enforcement investigations

**DO NOT** use this information for illegal activities.

## 📊 **Data Sources**

- `darkweb-marketplaces.csv` - Structured marketplace data
- `marketplace-profiles.md` - Detailed analysis of key markets  
- Public OSINT sources
- Cybersecurity research publications

## 🔄 **Updates**

This intelligence is updated regularly as new markets emerge and existing ones evolve. Check commit history for latest changes.

**Last Updated**: October 2025