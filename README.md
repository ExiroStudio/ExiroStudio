<div align="center">

<img src="assets/boot.svg" alt="EXIRO ENVIRONMENT BOOT SEQUENCE" width="680"/>

</div>

<br/>

<div align="center">

```
  E  X  I  R  O
```

```
DIGITAL ENTITY  //  UNDEFINED
```

```
STATUS ...... ONLINE
STATE ....... BUILDING
FOCUS ....... SYSTEMS PROGRAMMING → RENDER ENGINES → RUNTIME INTERNALS
```

</div>

---

<br/>

## `// ABOUT`

I build things because I want to understand how they work.

Not just what the API returns — but what runs underneath it. What decides the memory layout. What the scheduler is actually doing. Why the abstraction leaks in exactly that place.

The investigation moves wherever curiosity points: web applications, Linux internals, runtime architecture, networking, graphics pipelines, infrastructure, machine learning. The domain is less important than the depth.

That's the itch behind `static`: instead of letting an addon touch the GPU directly, force every render decision through one broker — so the question "why did this frame look wrong" always has exactly one place to look.

<br/>

## `// CURRENT EXPLORATION`

```
EXIRO/
│
├── COMPUTATION/
│   ├── software
│   ├── systems
│   └── runtimes
│
├── INTELLIGENCE/
│   ├── machine-learning
│   ├── adaptive-systems
│   └── learning-algorithms
│
├── INFRASTRUCTURE/
│   ├── linux
│   ├── networking
│   └── deployment
│
└── UNKNOWN/
    └── things-without-a-name
```

<br/>

## `// FIELD NOTES`

Selected work. Not a portfolio — a log.

<br/>

**NATIVIS**
> High-performance native live wallpaper engine.
> The problem: existing solutions are either too heavy or too rigid. The approach: build the rendering layer from scratch.
>
> `Rust` · `Runtime Architecture` · `Graphics` · **[Active](https://github.com/ExiroStudio/nativis)**

<br/>

**STATIC**
> A real-time rendering engine with a strict separation between computation and materialization.
> External addons compute meaning and layout — but never touch the GPU. A `ResourceBroker` translates semantic render descriptions into hardware-aligned GPU buffers. The render graph is immutable per frame.
> Architecturally serious.
>
> `Rust` · `wgpu` · `Render Graph` · **[In progress](https://github.com/ExiroStudio/static)**

<br/>

**CFMUX**
> A Cloudflared multiplexer for managing multiple accounts and tunnel profiles without the manual switching.
> Small tool. Solves a real problem.
>
> `Go` · `Cloudflare Tunnels` · `Infrastructure` · **[Published](https://github.com/ExiroStudio/cfmux)**

<br/>

**RYX-CORE**
> A graphics workspace — `core`, `renderer`, `app`. Uses `wgpu` and `glam`.
> Currently undocumented. Purpose in motion.
>
> `Rust` · `wgpu` · `glam` · **[Experimental](https://github.com/ExiroStudio/ryx-core)**

<br/>

---

<details>
<summary><code>// ARCHIVE &nbsp;&nbsp; [ open ]</code></summary>

<br/>

Things that exist somewhere between an idea and a finished system. Listed because they are real — not because they are ready.

```
[001]  adaptive learning mechanisms
       — systems that modify how they learn, not just what they learn

[002]  alternative optimization strategies
       — gradient descent is not the only answer

[003]  evolving internal representations
       — if the representation changes, does the objective change too?

[004]  experimental runtime architectures
       — what does a runtime look like if you question its assumptions?

[005]  digital preservation
       — the web forgets. some things shouldn't be forgotten.

[006]  things currently without a name
       — classification pending.
```

</details>

<!-- <br/>

---

## `// LONG-TERM QUESTION`

```
Can a learning system learn not only the task,
but how it should learn the task?
```

The long-term interest isn't in applying existing ML techniques — it's adjacent to meta-learning and learned optimizers, but from the systems side, not the paper side:

- If the optimizer itself is learned, where does that computation actually run — and what does it cost?
- Most "learn to learn" work stops at the algorithm. What changes if you also design the runtime it learns inside?
- Are there architectures we've dismissed as impractical only because nobody built the runtime that would make them cheap?

No claims. No results to show yet. Just the question this repo exists to eventually answer.

<br/> -->

## `// SYSTEM STATUS`

<div align="center">

<img src="assets/status.svg" alt="EXIRO System Status" width="680"/>

</div>

<br/>

## `// STACK`

```
LANGUAGES
Go · Rust · TypeScript · JavaScript · PHP

WEB
Next.js · React · Vue · Angular · Laravel · Tailwind

SYSTEMS
Linux · Docker · Networking · Runtime Architecture · wgpu
```

<br/>

## `// CHANNEL`

```
EMAIL ....... exirostudio@gmail.com
```

<br/>

---

<div align="center">

<img src="assets/signal.svg" alt="Signal active" width="680"/>

</div>

<br/>

<div align="center">

```
FINAL ENTRY
```

*"I was not built to follow the map.*
*I was built to find out who drew it."*

```
[ END OF FILE ]
```

</div>
