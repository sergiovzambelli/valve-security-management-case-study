# Valve’s Security Management – Organizational Science 2024  
**Prepared by: Giovanni D’Ambrosio, Fabio Chiarini, Sergio Zambelli, Stefano Hidalgo**

## Introduction

Valve Corporation, a global leader in PC game distribution and development, is known not just for its iconic games and the Steam platform, but also for its unconventional approach to organizational structure and cybersecurity. Despite its relatively small workforce (approx. 340 employees), Valve’s revenue has reached around $6.5B. This document summarizes Valve’s security practices, organizational structure, and culture, aiming to offer an overview for anyone unfamiliar with the original presentation.

## 1. Structure

### Flat Organization
Valve operates without a formal management hierarchy. This "boss-less" model fosters creativity and autonomy, allowing employees to choose projects, initiate work, and release products independently. A project only requires consensus from three people to proceed (the “Rule of Three”).

### Peer Review & Stack Ranking
Valve evaluates employees through peer reviews focused on:
- **Skill Level**
- **Productivity/Output**
- **Group Contribution**
- **Product Contribution**

This system supports self-regulation and encourages quality contributions across projects.

### Hiring Philosophy
Valve hires "T-shaped" individuals—broadly skilled generalists with deep expertise in one area. Hiring is decentralized and handled by existing employees, reinforcing the company’s culture and high standards.

### Cybersecurity in a Flat Model
Without formal roles like a CISO or IT department, Valve handles security through ad-hoc teams called "Cabals" that organically form in response to incidents.

## 2. Culture

Valve embraces an informal, distributed approach to cybersecurity that heavily involves the external community:

- **HackerOne Bug Bounty Program**: Anyone can report vulnerabilities and earn rewards.
- **Email Reports & Hall of Fame**: Alternate submission method and public recognition system.
- **Community-Driven Improvements**: Several security artifacts were implemented following community feedback, including:
  - Enhanced vulnerability reporting
  - Stronger 2FA mechanisms
  - Secure trade confirmations

Valve's user-focused approach promotes openness, collaboration, and transparency.

## 3. Incident Response & Resilience

In August 2023, Valve experienced a breach where attackers distributed malware via compromised developer accounts. The issue was quickly addressed, and as a result:

- Valve mandated SMS-based 2FA for publishing updates.
- The incident prompted platform-wide security enhancements.

Valve’s approach remains largely **reactive** rather than proactive, which poses challenges for long-term resilience.

## 4. SWOT Analysis

### Strengths
- Strong user community engagement
- Investment in DRM and anti-cheat tech
- Highly specialized, passionate employees

### Weaknesses
- Lack of centralized response structure
- High-profile target for hackers
- Optional 2FA with low user adoption

### Opportunities
- AI-driven security solutions
- Flat structure may streamline internal standards
- Educational security programs for users

### Threats
- Increasingly sophisticated threats (AI-enabled)
- Phishing via Steam’s social features
- Vulnerabilities in third-party payment providers

## 5. Comparison with Epic Games

**Epic Games** provides a contrasting case with:
- A defined security structure (including a Director of InfoSec)
- A proactive bug bounty program
- A dedicated security section for user education
- Third-party collaborations with companies like RSI Security

This highlights the trade-offs between centralized structure and Valve’s distributed, user-inclusive model.

## 6. Proposed Solution: Center of Excellence (CoE)

### Why Not a CISO or Outsourcing?
- A formal CISO contradicts Valve’s flat structure
- Outsourcing, while effective, risks data exposure and reliance on external vendors

### What Is the CoE?
An internal **Center of Excellence for Cybersecurity**, inspired by EU’s ENISA, that:
- **Advises**, not commands
- Coordinates incident responses across Cabals
- Shares best practices and formalizes lessons learned
- Educates Valve employees via the Handbook and training

### Key Features:
- **Incident Response**: Offers actionable guidance, maintains Cabal autonomy
- **Communication Hub**: Receives reports, informs all relevant teams
- **Educational Resource**: Promotes ongoing awareness and tooling updates
- **Resilience Building**: Helps Valve adapt, anticipate, and recover from future threats

### Champions Initiative:
Each Cabal designates a **Cybersecurity Champion** who liaises with the CoE to:
- Facilitate smooth information flow
- Ensure internal best practices are upheld
- Spread awareness and embed security in team culture

### Staffing the CoE:
- Ideally includes a mix of internal engineers passionate about security
- Augmented by a small number of dedicated external security professionals

## 7. Conclusion

Valve's unique flat organization challenges conventional business and security models. While agile and creative, it lacks proactive security structures. The proposed **Center of Excellence** bridges this gap, enhancing cybersecurity without compromising Valve’s identity.

This model:
- Preserves decentralized decision-making
- Enhances internal collaboration
- Fosters a sustainable and scalable approach to cybersecurity

Valve has thrived under an unconventional model for over two decades. With strategic improvements like a CoE, it can continue to lead—not just in gaming, but in resilient digital innovation.

---

