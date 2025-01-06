Here’s a structured, terminal-style set of notes based on your input. Let me know if you'd like any adjustments!  

```
# Detection & Analysis Stage (Part 1)

## -> Overview
- Processes, procedures, and guidelines for handling security incidents are established.
- Focus on detecting incidents using:
  - Sensors
  - Logs
  - Trained personnel
  - Context-based threat intelligence
  - Network segmentation and visibility

## -> Sources of Threat Detection
1. **Employee observations** (abnormal behavior noticed).
2. **Alerts from tools** (e.g., EDR, IDS, Firewall, SIEM).
3. **Threat hunting activities**.
4. **Third-party notifications** about potential compromises.

## -> Levels of Detection
1. **Network Perimeter**
   - Tools: Firewalls, internet-facing IDS/IPS, DMZ.
2. **Internal Network**
   - Tools: Local firewalls, host IDS/IPS.
3. **Endpoint Level**
   - Tools: Antivirus, Endpoint Detection & Response (EDR).
4. **Application Level**
   - Tools: Application logs, service logs.

---

# Initial Investigation

## -> Key Steps
1. **Collect Contextual Information**
   - Date/Time of detection and reporting.
   - Source of detection (person, tool, etc.).
   - Nature of the incident (phishing, unavailability, malware, etc.).
   - List impacted systems (if relevant).

2. **Document Actions**
   - Record access and actions taken on impacted systems.
   - Determine if the incident is ongoing or resolved.

3. **Gather Details**
   - Physical location, OS, IP addresses, hostnames.
   - System owner, purpose, and current state.
   - Malware-related info:
     - IP addresses, detection time, type of malware.
     - List of impacted systems.
     - Malicious file details (hashes, copies, forensic data).

## -> Building an Incident Timeline
- Use **time-sorted events** to organize and contextualize:
  - When incidents occurred.
  - Network connections and file downloads.
  - Evidence uncovered during investigations.

### Example Timeline:
| Date       | Time      | Hostname       | Event Description             | Data Source         |
|------------|-----------|----------------|--------------------------------|---------------------|
| 09/09/2021 | 13:31 CET | SQLServer01    | Hacker tool 'Mimikatz' detected | Antivirus Software |

- Focus on attacker behavior to track:
  - Attack occurrences.
  - System/network activity.
  - Detection sources and associated systems.

---

# Incident Severity & Extent Questions

## -> Severity Assessment
- **What is the exploitation impact?**
- **What are the exploitation requirements?**
- **Can business-critical systems be affected?**
- **Suggested remediation steps?**
- **Number of impacted systems?**

## -> Adversary Sophistication Indicators
- **Is the exploit being used in the wild?**
- **Does the exploit have worm-like capabilities?**

- **Action Priority:** High-impact incidents and those affecting multiple systems require immediate escalation.

---

# Incident Confidentiality & Communication

## -> Confidentiality Guidelines
- Keep incident details on a **need-to-know basis** unless laws or management dictate otherwise.
- Possible reasons:
  - Insider threat (e.g., an adversary within the company).
  - Controlled communication for breaches (handled by designated personnel with legal oversight).

## -> Investigation Goals & Expectations
- Define:
  - Type of incident.
  - Available evidence sources.
  - Time estimate for investigation.
  - Likelihood of uncovering the adversary.

- **Dynamic Process:** Expectations and goals evolve with new leads.
- **Communication:** Keep management and involved parties updated with progress and findings.

---

Let me know if you'd like to refine or expand on any sections! 😊
```
