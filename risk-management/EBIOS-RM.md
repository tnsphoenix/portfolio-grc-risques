# EBIOS Risk Manager (EBIOS RM)

## What is EBIOS RM?
EBIOS Risk Manager is a **French risk management methodology**, developed by ANSSI (the French National Cybersecurity Agency). It allows organizations to 
**assess and treat cybersecurity risks** while engaging all stakeholders.

---

## EBIOS RM vs ISO 27005

| | ISO 27005 | EBIOS RM |
|---|---|---|
| **Origin** | International | French (ANSSI) |
| **Approach** | Generic | Attack scenario-oriented |
| **Vision** | Assets & vulnerabilities | Attackers & intentions |
| **Usage** | Worldwide | France + Europe |
```
ISO 27005                    EBIOS RM
─────────────────────────    ─────────────────────────
What to protect ?       →    Who will attack ?
Assets & vulnerabilities→    Attackers & scenarios
Defensive vision        →    Offensive vision
Generic approach        →    Contextual approach
```

💡 In practice in France : EBIOS RM is used for the method and ISO 27005 for the theoretical framework.

----------------------------------------------------------------------------------------------------------------------------------
## The 5 Workshops *(Les 5 ateliers)*
```
Workshop 1 → Scoping & Security Baseline
Workshop 2 → Risk Sources
Workshop 3 → Strategic Scenarios
Workshop 4 → Operational Scenarios
Workshop 5 → Risk Treatment
```

----------------------------------------------------------------------------------------------------------------------------------

### Workshop 1 — Scoping & Security Baseline
*(Cadrage et socle de sécurité)*

Define the scope of the study, identify the organization's most critical assets called **business values**, and assess the existing security baseline.

| 🇬🇧 English | 🇫🇷 Français | Definition |
|---|---|---|
| **Business value** | Valeur métier | What is critical for the org (e.g. payment system) |
| **Supporting asset** | Bien support | What supports the business value (e.g. server, app) |
| **Security baseline** | Socle de sécurité | Security measures already in place |

----------------------------------------------------------------------------------------------------------------------------------

### Workshop 2 — Risk Sources
*(Sources de risque)*

Identify **who** could attack the organization and **why**. These are called risk sources and their objectives are called target objectives.

| 🇬🇧 English | 🇫🇷 Français | Example |
|---|---|---|
| **Risk source** | Source de risque | Cybercriminal, hostile state, insider |
| **Target objective** | Objectif visé | Steal data, disrupt a service |
| **Motivation** | Motivation | Financial, ideological, espionage |

----------------------------------------------------------------------------------------------------------------------------------

### Workshop 3 — Strategic Scenarios
*(Scénarios stratégiques)*

Build high-level attack scenarios by combining risk sources with business values. These scenarios describe **what** the attacker targets and **what impact** it would have.

**Formula *(Formule)* :**
```
Risk Source + Business Value + Impact = Strategic Scenario
Source de risque + Valeur métier + Impact = Scénario stratégique
```

**Example *(Exemple)* :**
```
Risk source     : Organized cybercriminal
      +
Business value  : Customer database
      +
Impact          : Theft and resale of personal data
      =
Strategic scenario : Ransomware targeting the customer database
```

----------------------------------------------------------------------------------------------------------------------------------

### Workshop 4 — Operational Scenarios
*(Scénarios opérationnels)*

Detail the **technical attack paths** that could lead to the strategic scenarios. This is where you analyze how an attacker would concretely carry out the attack.

| 🇬🇧 English | 🇫🇷 Français | Definition |
|---|---|---|
| **Attack path** | Chemin d'attaque | Sequence of technical attacker actions |
| **Likelihood** | Vraisemblance | Probability the scenario occurs |
| **Severity** | Gravité | Level of impact on the organization |

**Example attack path *(Exemple de chemin d'attaque)* :**
```
Step 1 → Phishing email → compromise of a user workstation
Step 2 → Privilege escalation → admin access
Step 3 → Lateral movement → database access
Step 4 → Exfiltration → theft of customer data
```

----------------------------------------------------------------------------------------------------------------------------------

### Workshop 5 — Risk Treatment
*(Traitement du risque)*

Define and prioritize the **security measures** to implement based on the identified scenarios, then build the risk treatment plan.

| 🇬🇧 English | 🇫🇷 Français |
|---|---|
| **Security measure** | Mesure de sécurité |
| **Risk treatment plan** | Plan de traitement du risque |
| **Residual risk** | Risque résiduel |
| **Risk owner** | Propriétaire du risque |

----------------------------------------------------------------------------------------------------------------------------------

## Key Vocabulary / Vocabulaire clé

| 🇬🇧 English | 🇫🇷 Français |
|---|---|
| ANSSI | Agence Nationale de la Sécurité des Systèmes d'Information |
| Business value | Valeur métier |
| Supporting asset | Bien support |
| Security baseline | Socle de sécurité |
| Risk source | Source de risque |
| Target objective | Objectif visé |
| Strategic scenario | Scénario stratégique |
| Operational scenario | Scénario opérationnel |
| Attack path | Chemin d'attaque |
| Likelihood | Vraisemblance |
| Severity | Gravité |
| Risk treatment plan | Plan de traitement du risque |
| Risk owner | Propriétaire du risque |

---

## Sources
- [ANSSI — EBIOS Risk Manager](https://www.ssi.gouv.fr/guide/ebios-risk-manager/)
- [EBIOS RM Official Documentation (EN)](https://www.ssi.gouv.fr/en/guide/ebios-risk-manager/)

*Last updated : March 2026*
