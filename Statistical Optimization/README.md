# 🧩 Wordle Strategy & Statistical Optimization

This module breaks down the mathematical, structural, and linguistic tactics required to solve Wordle puzzles efficiently. It outlines the ultimate opening words, positional letter probabilities, and core gameplay configurations.

---

## 🏆 A. The Ultimate Wordle Opener Leaderboard (Top 10)

When lining up the absolute best starting moves in Wordle, computer algorithms, decision trees, and letter-frequency databases have clear favorites. Here is how the top 10 words line up:

*   **🥇 The Undisputed Champion: SALET**  
    Standing at the very front of the line, **SALET** is mathematically verified by word-bot algorithms as the most optimal opener. It tests premium vowels ($A, E$) and anchors the ultra-high-frequency consonants $S$, $L$, and $T$ in prime slots.
    *   *Example:* The girl confidently inputs **SALET** to kick off her morning puzzle.
*   **🥈 1st Runner-Up: SLATE**  
    Just a hair behind the crown, **SLATE** takes the silver medal. It shares a near-identical structural profile with the champion, making it an incredible baseline for tracking early green vowels.
    *   *Example:* She watches her clever puppy nap while she locks in **SLATE** on row one.
*   **🥉 2nd Runner-Up: CRANE**  
    Taking the bronze is **CRANE**, famously used as the foundational baseline word for the official New York Times Wordle Bot due to its incredible consonant-elimination power ($C, R, N$).
    *   *Example:* The girl relies on **CRANE** to set up an easy path to a three-turn win.
*   **🎖️ 4th Place: TRACE**  
    Lining up right behind the podium, **TRACE** is a premier choice that targets common letter patterns, helping to identify or rule out words ending in a silent $E$ right away.
    *   *Example:* She types **TRACE** while her cat contentedly watches the screen.
*   **🎖️ 5th Place: CARTE**  
    A brilliant tactical word that keeps your vowel choices flexible while aggressively checking if $C$ or $R$ are present in the early slots.
    *   *Example:* The girl tests **CARTE** to mix up her daily starting routine.
*   **🎖️ 6th Place: SLANT**  
    An incredible double-consonant starter ($SL$- and -$NT$) that maps out where structural clusters live in the target word.
    *   *Example:* Her puppy tilts its head as she enters **SLANT** into the empty grid.
*   **🎖️ 7th Place: SHUNT**  
    The absolute best niche choice for wiping out the common $H$ and $N$ consonant blends while safely screening the vowel $U$.
    *   *Example:* The girl utilizes **SHUNT** to quickly filter out complex consonant groupings.
*   **🎖️ 8th Place: STARE**  
    A highly aggressive positional powerhouse that places $S$, $T$, and $R$ in the exact slots where they statistically appear most often in five-letter English words.
    *   *Example:* The girl routinely scores a turn-two win whenever **STARE** yields multiple yellow hints.
*   **🎖️ 9th Place: ADIEU**  
    The legendary "vowel vacuum" choice. While it ranks slightly lower on consonant mapping, it lines up as a massive casual favorite because it burns through four out of five major vowels in a single turn.
    *   *Example:* Her playful kitten swats at the interface just as she hits enter on **ADIEU**.
*   **🎖️ 10th Place: ROATE**  
    An exceptional, lesser-known opening word that targets three premium vowels ($O, A, E$) alongside the top-tier structural anchors $R$ and $T$.
    *   *Example:* The girl completes her top 10 strategy arsenal by deploying **ROATE** on challenging puzzle days.

---

## 📊 B. Advanced Letter Frequency & Positional Probability

A hidden secret to winning Wordle consistently is knowing not just *which* letters are common, but *where* they are most likely to live in a 5-letter word structure.

*   **The Power of Initial 'S':** Statistically, more than 15% of all winning Wordle words begin with the letter **S**. Choosing openers like **SALET** exploits this exact positional probability.
    *   *Example:* The girl noticed that starting her grid with an **S** instantly turned green more often than any other letter.
*   **The Trailing 'E' and 'Y':** The letter **E** is the most common ending letter for Wordle answers, followed closely by **Y**.
    *   *Example:* When the girl's puppy bumped her arm, she accidentally typed a word ending in **Y**, which luckily turned green because **Y** is incredibly common at position 5!
*   **Vowel Splitting:** The optimal strategy is to separate your vowels on turns 1 and 2 (e.g., using **SALET** to test $A/E$, then a word like **CRONY** or **GUIDE** to test $I/O/U$).

---

## ⚙️ C. Structural Gameplay: Normal Mode vs. Hard Mode

The game features an internal toggle setting that completely shifts your mechanical strategy.

### 1. Normal Mode (The Flexibility Strategy)
You can guess any valid word at any time. This allows you to use "Elimination Words" to burn through multiple suspicious letters if you fall into a rhyme trap.
*   **The Scenario:** You discover `_ I G H T`. The correct word could be *MIGHT*, *LIGHT*, *SIGHT*, *NIGHT*, or *RIGHT*.
*   **The Strategy:** Instead of guessing those words one by one and losing your turns, sacrifice one row to input a completely different word that packs all those missing consonants together (e.g., guessing **SLUMS** checks *S*, *L*, and *M* all at once).
    *   *Example:* Stuck on a tricky word, the girl strategically used a burner word to protect her win streak.

### 2. Hard Mode (The Strict Constraints Trap)
Any revealed hints *must* be used in all subsequent guesses. If you get a green box or a yellow box, those letters are locked into your configuration requirements for the rest of the puzzle.
*   *Example:* The girl's clever cat walked across her keyboard while she was playing on Hard Mode, forcing her into a strict guessing pattern that required careful calculation to survive.

---

### 🚀 Contributors
*   **Celine0921** (the main creator of this project)
*   **marcoT0425** (the collab of the project)
