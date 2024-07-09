---
title: Notes on "Computation Is All Around Us, and You Can See It if You Try"
date: 2024-06-15
tags:
  - personal-notes
  - quanta-magazine
description: Personal Notes on "Computation Is All Around Us, and You Can See It if You Try" Article
---

- Magazine: Quanta Magazine
- Article: [Computation Is All Around Us, and You Can See It if You Try](https://www.quantamagazine.org/computation-is-all-around-us-and-you-can-see-it-if-you-try-20240612/)

> Bohr: Algebra is like sheet music. The important thing isn’t “can you read music?” It’s “can you hear it?” Can you hear the music, Robert?
> — Oppenheimer 2023

> Those who were seen dancing were thought to be insane by those who could not hear the music.
> — Friedrich Nietzsche

با این دیدگاه که با داشتن اطلاعات کافی می‌توان تمام پدیده‌هارا پیش‌بینی کرد؛ آیا هیچ چیز کاملاً تصادفی‌ای در جهان وجود دارد؟

> Something seemingly random, like a coin flip, can be fully described by some complex computational process that yields an unpredictable outcome of heads or tails. The outcome depends on myriad variables: the force and angle and height of the flip; the weight, diameter, thickness and distribution of mass of the coin; air resistance; gravity; the hardness of the landing surface; and so on. It’s similar for shuffling a deck of cards, rolling dice or spinning a roulette wheel — or generating “random” numbers on a computer, which just involves running some purposely complicated function. None of these is a truly random process.

---

به نقل از جادی، در UNIX فایل
`/dev/random`
از ورودی‌ها و درایورهای مختلف کامپیوتر بصورت مداوم اطلاعاتی رو جمع‌آوری می‌کند(entropy) تا در تولید داده رندوم در مواقع نیاز به‌کار برده شود. این موضوع مرا به این فکر واداشت که آیا می‌توان با توابع کاملاً ریاضیاتی و بدون ورودی، عدد تصادفی‌ای تولید کرد یا خیر.

> **Deterministic** refers to a process or system that is _entirely predictable_ in its behavior, given its initial conditions and the rules governing it.
> 
> It is not possible to generate purely unpredictable random numbers _without any external input_ and _using only mathematical functions_. **This is because mathematical functions are deterministic by nature**. Given the same initial conditions (or seed), they will always produce the same output. True randomness, which is unpredictable and non-deterministic, cannot be achieved through purely deterministic processes.
> — Chat GPT

آیا می‌توان نتیجه گرفت از آنجایی که ریاضی Deterministic است، هیچ چیز تصادفی‌ای در جهان وجود ندارد؟ اگر ثابت‌شود که تمامی رخدادهای جهان بوسیله ریاضیات قابل مدل‌سازی است، می‌توان به چنین نتیجه‌ای رسید؟

[Hey Chat GPT,] Could all the rules of the universe be modeled with math?

[Answer:] The idea that all the rules of the universe could be modeled with mathematics is a central assumption in many areas of physics and philosophy. This perspective, often referred to as **mathematical Platonism** or **mathematical realism**, suggests that the universe operates according to precise mathematical laws that can, in principle, be discovered and described by human beings.

**What have been modeled**:

- **Classical Mechanics**: Isaac Newton's laws of motion and universal gravitation
- **Electromagnetism**: James Clerk Maxwell's equations describe how electric and magnetic fields interact and propagate.
- **Quantum Mechanics**: At microscopic scales, quantum mechanics provides a mathematical framework to describe the behavior of particles. The Schrödinger equation, for instance, describes how the quantum state of a physical system changes over time.
- **General Relativity**: Albert Einstein's theory of general relativity uses the mathematics of differential geometry to describe how matter and energy influence the curvature of spacetime, which we perceive as gravity.

**What have'nt yet**:

- **Incomplete Theories**: Some aspects of physics remain not fully understood or unified. For example, combining general relativity (which describes gravity) with quantum mechanics (which describes the other fundamental forces) into a single theory of quantum gravity remains an unresolved challenge.
- **Complex Systems**: In fields like biology, weather, and economics, systems are highly complex and chaotic, making precise mathematical modeling very challenging. These systems often require probabilistic or statistical approaches rather than deterministic ones. \[[The New Math of How Large-Scale Order Emerges](https://www.quantamagazine.org/the-new-math-of-how-large-scale-order-emerges-20240610)\]

— Chat GPT

---

> Earlier this year, Avi Wigderson [received the Turing award](https://www.quantamagazine.org/avi-wigderson-complexity-theory-pioneer-wins-turing-award-20240410/), the “Nobel Prize of computing,” partly for formally connecting randomness with mathematical functions that are hard to compute. He and his colleagues created a process that takes a suitably complex function and outputs “pseudorandom” bits that can’t be efficiently distinguished from truly random bits. Randomness, it seems, is just computation we cannot predict.
