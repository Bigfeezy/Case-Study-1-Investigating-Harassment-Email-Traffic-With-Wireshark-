# Case-Study-1-Investigating-Harassment-Email-Traffic-With-Wireshark-
Individual forensic case study (SBT-DF204): reconstructing a simulated harassment-email incident from a packet capture using Wireshark and tshark, with evidence preservation, filters, timeline and attribution limits.


# SBT-DF204 Case Study 1: Investigating Harassment Email Traffic With Wireshark

Individual digital forensics case study based on the public Nitroba University
Harassment Scenario (Digital Corpora). The work covers evidence preservation,
Wireshark/tshark analysis of a packet capture, and a cautious assessment of
what the traffic does and does not support.

## Scope

- Preserve and verify the capture (MD5, SHA-1, SHA-256 compared with the
  published values), and analyse only a read-only working copy.
- Find the web service and client activity with display filters and
  Follow TCP Stream.
- Correlate HTTP form activity with the reported message.
- Trace the device by MAC address and review cookie and User-Agent evidence.
- Build a UTC timeline from packet timestamps.
- Separate observed facts, inferences and limitations (shared open wireless
  network).

## Tools

- Kali Linux, Wireshark, tshark
- md5sum, sha1sum, sha256sum

## Repository contents

- `report/`: the written report and evidence log
- `screenshots/`: labelled Wireshark screenshots (unrelated personal data redacted)
- `commands.md`: the filters and tshark commands used

## Data and ethics

The packet capture is **not included**. It is controlled training material from
a simulated scenario: download it from the Digital Corpora scenario page and
verify it against the published checksums. All people and accounts in the
scenario are fictional. This repository is an academic exercise; it makes no
claims about real individuals.

## Source

Scenario: https://digitalcorpora.org/corpora/scenarios/nitroba-university-harassment-scenario/
