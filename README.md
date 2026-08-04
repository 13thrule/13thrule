<div align="center">

# hey, I'm 13thrule 👋

### I build things that sense, and react before they think.

WiFi RF, LED light, an agent's own reasoning loop — different domains, same instinct: put a fast,
reliable reaction path underneath the slow, smart one.

**[→ see the full interactive portfolio](https://13thrule.github.io)** — a live signal trace, a running
LED-ring console you can switch effects on, and the honest story behind everything below.

</div>

<br>

```
   ╱╲    reflex_arc.signal
  ╱  ╲  ╱╲        ╱╲
 ╱    ╲╱  ╲  ╱╲  ╱  ╲
        ▔▔  ╲╱  ╲╱     sense → react → (then, only then) think
```

## what I've actually built

| project | what it does |
|---|---|
| **[led-data-transmission](https://github.com/13thrule/led-data-transmission)** | A 12-LED ring transmits data as light; a webcam decodes it. 33-bit, self-syncing, crosstalk-resistant protocol. |
| **[Switchboard](https://github.com/13thrule/Switchboard-rust)** | A real pub/sub message broker in Rust — zero-copy delivery, cross-process shared-memory transport. |
| **[ANSE](https://github.com/13thrule/ANSE-Agent-Nervous-System-Engine)** | An agent runtime with a reflex arc that reacts before the LLM finishes thinking. |
| **[Nexus WiFi Radar V2](https://github.com/13thrule/Nexus-Wifi-Radar-V2)** | Passive WiFi analysis — device fingerprinting, hidden-network classification, threat scoring, real time. |
| **[Persona Stage](https://github.com/13thrule/persona-stage)** | Fully local, fully offline — gives any script a face and a voice, one HTTP call at a time. |

The full story on each one — including the one place my own README oversold its own internals — lives on
**[the portfolio](https://13thrule.github.io)**, not here.

## the arc

`Dec 2025` — "zero lines written by hand." `Aug 2026` — measuring actual pixel brightness values myself
to debug a light-based data link. Same person, a genuinely different relationship with the code.

<br>

<div align="center">

![Repos](https://img.shields.io/badge/project_repos-11-5FE39A?style=flat-square&labelColor=131410)
![Stars](https://img.shields.io/github/stars/13thrule?style=flat-square&color=5FE39A&labelColor=131410&label=stars)
![Top language](https://img.shields.io/badge/primary_language-Python-5FE39A?style=flat-square&labelColor=131410)

</div>

**languages, by actual bytes written** — computed straight from the repos, not a third-party widget
that can quietly go down:

```text
Python      [###############################.........]   78.4%
HTML        [####....................................]    8.9%
Rust        [##......................................]    6.1%
JavaScript  [#.......................................]    2.6%
CSS         [#.......................................]    1.2%
```

+ Shell, C++/Arduino, Svelte, PowerShell, Batchfile — under 1% each, still real work, just small
footprints (the Arduino continuity tester is maybe 200 lines total and does its whole job).
