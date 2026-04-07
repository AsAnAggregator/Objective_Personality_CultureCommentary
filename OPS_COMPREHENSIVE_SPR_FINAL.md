# OBJECTIVE PERSONALITY SYSTEM: COMPREHENSIVE SPARSE PRIMING REPRESENTATION
## Formal Notation ↔ Common Notation Conversion Framework

---

# PART 1: ONTOLOGICAL FOUNDATIONS

## 1.1 Ontoclean Framework Application

**Onto-Clean Category Assignments**:

| Concept | Category | Rigidity | Identity | Unity | Notes |
|---------|----------|----------|----------|-------|-------|
| Psychological Function | Substance | Rigid | Essential | Essential | Intrinsic, multiply realizable |
| Ordonnance Position [1-4] | Role | Non-rigid | Relative | Relative | Relational, context-dependent |
| Modality (M/F) | Intrinsic Mode | Rigid | Essential | Essential | Constitutive of function's nature |
| Grant Stack | Compound | Non-rigid | Relative | Relative | Aggregate of Type instantiating Roles |
| Psyche Instance | Substance | Rigid | Essential | Essential | Concrete individual, embodied token |

**Ontological Principles**:
- **Types** [+R, +U, +I, +D]: Intrinsic, multiply realizable (psychological functions)
- **Roles** [−R, ∼U, −I, +D]: Relational, position-dependent (ordonnance positions [1-4])
- **Compounds**: Tokens instantiating Types within Roles (Grant stacks, animal pairings)

---

## 1.2 Jungian Complementarity Principle (Jung, CW 6)

**Core Insight (Jung [667-670])**:

One function dominates consciousness with absolute sovereignty. A second function must exist as **auxiliary** (secondary) because:

1. Two functions of equal power would create contradictory orientations (impossible for adaptation)
2. The auxiliary must be **not antagonistic** to the primary
3. **Antagonism Rule**: 
   - Judging functions (T/F) are antagonistic to each other → cannot pair as primary + auxiliary
   - Perceiving functions (S/N) are complementary to judging functions → can pair with them
   - Example: Thinking pairs with Sensation OR Intuition, never with Feeling

**Implication for OPS**:
- Valid function pairs are constrained by non-antagonism
- The auxiliary serves the primary without claiming autonomy
- This principle explains why [2]/[3] (the auxiliary pair) must be on the opposite axis from [1]/[4] (the primary pair)

---

## 1.3 Psyche Ontology

**Status**: Psychological functions are genuine phenomena in their own right—not epiphenomena or mechanisms.

**View**: Energic/teleological—functions serve telos (purpose), not mechanical causation.

**Structure**: The psyche has ontological status as a dynamic ordering of purposive operations.

---

# PART 2: OPS STRUCTURAL FOUNDATIONS

## 2.1 Core Architecture

### The 16 Atomic Psychological Functions
M/F modality variant of each of Jung's 8 functions:

**Observer Axis**: Sensory and Intuitive perception
- Si, (f)Si, (m)Si — Introverted sensation
- Se, (f)Se, (m)Se — Extroverted sensation  
- Ni, (f)Ni, (m)Ni — Introverted intuition
- Ne, (f)Ne, (m)Ne — Extroverted intuition

**Decider Axis**: Thinking and Feeling judgment
- Ti, (f)Ti, (m)Ti — Introverted thinking
- Te, (f)Te, (m)Te — Extroverted thinking
- Fi, (f)Fi, (m)Fi — Introverted feeling
- Fe, (f)Fe, (m)Fe — Extroverted feeling

### The Three Levels of Type Structure

**Level 1: Unmodalized Functions** (8 Jungian types)
- Pure function without modality anchor
- Attitude (I/E) and axis (observer/decider) only
- Example: Se, Ti, Fe, Ni

**Level 2: Modalized Functions** (16 OPS atomic types)
- Functions with M/F modality designation
- Example: (m)Se, (f)Ti, (m)Fe, (f)Ni

**Level 3: Grant Stack Ordonnance** (static ranking)
- Four modalized functions in positions [1][2][3][4]
- From most to least differentiated
- Example: [1](f)Ne - [2](m)Fi - [3](f)Te - [4](m)Si

**Level 4: Animal Stack** (higher-order combinatoric)
- Observer/decider pairings that reveal ordonnance structure
- Dynamic priority ordering (savior vs. demon)
- Example: PB/C(S) means Play-Blast (savior), Consume-Sleep (demon)

**Level 5: Type Profile** (full specification)
- Complete type notation with all layers
- Example: FF - Si/Ti - SB/P(C)

---

## 2.2 The Grant Stack: Static Baseline

**Definition**: The Grant stack is the **fixed, unchanging ordonnance** of the four functions from most to least differentiated [1][2][3][4].

**Properties**:
- Determined entirely by the **lead function** (first in savior pair) via STACK_ANCHORS_BY_LEAD
- Once set, ordonnance never changes (static)
- Each function appears in exactly 2 animals
- Each function maintains the same bracket number across both animal appearances
- Bracket positions always in ascending order: [1-2], [1-3], [2-4], [3-4]

**Oscillation Rule**: Attitudes alternate I/E/I/E across [1][2][3][4]

**Relationship Rules**:
- [1]/[4]: Same axis | Opposite polarities (I/E) | Opposite modalities
- [2]/[3]: Same axis | Opposite polarities (I/E) | Opposite modalities
- [1]/[4] axis is always opposite to [2]/[3] axis (observer ↔ decider)

---

## 2.3 Animals: Higher-Order Relational Heuristic

**Definition**: Animals are observer/decider attitude pairings that **reveal** (not determine) ordonnance structure.

### Four Animal Types

| Animal | Observer | Decider | Bracket Span | Jumper? | Definition |
|--------|----------|---------|--------------|---------|------------|
| **Sleep (S)** | Introverted (IO) | Introverted (ID) | [1-3] or [2-4] | YES | Most introverted pairing |
| **Blast (B)** | Introverted (IO) | Extroverted (ED) | [1-2] or [3-4] | NO | Introverted observer base |
| **Consume (C)** | Extroverted (EO) | Introverted (ID) | [1-2] or [3-4] | NO | Extroverted observer base |
| **Play (P)** | Extroverted (EO) | Extroverted (ED) | [1-3] or [2-4] | YES | Most extroverted pairing |

**Jumper Constraint**: Sleep and Play can span non-adjacent ordinals ([1-3] or [2-4]).
**Non-Jumper Constraint**: Blast and Consume can only span adjacent ordinals ([1-2] or [3-4]).

### Animal Stack Organization

**Notation**: [A1][A2]/[A3]([A4])
- **A1, A2** = savior pair (first two animals, most accessible)
- **A3, (A4)** = demon pair (last two animals, least accessible)
- **Priority order** determines how animals are listed in common notation

---

# PART 3: FORMAL NOTATION

## 3.1 Formal Notation Structure

**Format**: [Modality] - [SaverObserver/SaverDecider] - [AnimalStack]

**Example**: `FF - Si/Ti - SB/P(C)`

### Component 1: Modality [SensoryModality][ExtDeciderModality]

**Possible values**: MF, FM, MM, FF

- **char_1** = Modality of sensory function (Se or Si wherever it appears in stack)
- **char_2** = Modality of extroverted decider (Te or Fe wherever it appears in stack)

**Reading**:
- M = Masculine (grounded, fixed, anchored, matter-like)
- F = Feminine (fluid, airy, unanchored, form-like)

**Critical insight**: Two anchor points fully determine all four function modalities via inversion rules.

### Component 2: Savior Pair [Observer/Decider]

**Format**: Unmodalized function names separated by slash

- **First function** = Savior observer (the lead function)
- **Second function** = Savior decider (auxiliary function)

**Example**: Ne/Te, Si/Fi, Se/Ti, Fe/Se

**Purpose**: Identifies which functions appear in the savior pair (first two animals).

### Component 3: Animal Stack [A1A2/A3(A4)]

**Format**: Four animal initials in priority order

- **A1A2** = Savior pair (separated only by letter)
- **/** = Demarcation between savior and demon
- **A3(A4)** = Demon pair (4th animal in parentheses, least differentiated)

**Example**: PB/C(S) = Play-Blast savior, Consume-Sleep demon

**Purpose**: Indicates which animals are present and their priority order.

---

## 3.2 What Formal Notation Tells You (And What It Doesn't)

**Formal notation tells you**:
- Which two functions are in the savior pair
- The modality profile for those functions
- Which animals are present and their priority order

**Formal notation does NOT directly tell you**:
- The ordonnance positions ([1], [2], [3], [4])
- Which axis the [2]/[3] functions occupy
- The specific functions at [2], [3], [4]

**These are derived mechanically via STACK_ANCHORS_BY_LEAD.**

---

# PART 4: MODALITY SYSTEM

## 4.1 Modality Anchoring Principle

**Core Principle**: Once you specify [1] with a modality, [4] is automatically determined.

**Mechanism**:
- The **sensory modality** (char_1) anchors all sensory and intuitive functions
- The **ext-decider modality** (char_2) anchors all extroverted deciders and introverted deciders
- **Inversion rule**: If one pole is masculine, its inverse is feminine

### 4.2 [1]/[4] Modality Pairings

**These are mechanically determined by the lead function type:**

#### Observer Axis (If [1]/[4] are both observer)

| [1] Function | [1] Modality | [4] Function | [4] Modality |
|---|---|---|---|
| Si | (m) | Ne | (f) |
| Si | (f) | Ne | (m) |
| Se | (m) | Ni | (f) |
| Se | (f) | Ni | (m) |
| Ne | (m) | Si | (f) |
| Ne | (f) | Si | (m) |
| Ni | (m) | Se | (f) |
| Ni | (f) | Se | (m) |

#### Decider Axis (If [1]/[4] are both decider)

| [1] Function | [1] Modality | [4] Function | [4] Modality |
|---|---|---|---|
| Ti | (m) | Fe | (f) |
| Ti | (f) | Fe | (m) |
| Fi | (m) | Te | (f) |
| Fi | (f) | Te | (m) |
| Te | (m) | Fi | (f) |
| Te | (f) | Fi | (m) |
| Fe | (m) | Ti | (f) |
| Fe | (f) | Ti | (m) |

**Pattern**: [1] and [4] are **always same axis, opposite polarity, opposite modality.**

### 4.3 [2]/[3] Modality Rules

**Axis Opposition**: 
- If [1]/[4] are observer axis → [2]/[3] are decider axis
- If [1]/[4] are decider axis → [2]/[3] are observer axis

**Modality Inheritance**:
- [2] modality follows the ext-decider anchor (char_2)
- [3] modality is inverse of [2]
- OR [2] modality follows the observer anchor if [2]/[3] are observers

**Function Determination**:
- Use the **opposite axis inverse pairings** (not arbitrary choice)
- The specific function depends on which axis and which attitudes STACK_ANCHORS requires

### 4.4 Fixed Inverse Pairings (Structural, Not Modality-Based)

**OBSERVER AXIS**:
- Si ↔ Ne (introverted sensation ↔ extroverted intuition)
- Se ↔ Ni (extroverted sensation ↔ introverted intuition)

**DECIDER AXIS**:
- Ti ↔ Fe (introverted thinking ↔ extroverted feeling)
- Fi ↔ Te (introverted feeling ↔ extroverted thinking)

**These pairings are FIXED and NON-NEGOTIABLE.** They derive from Jung's complementarity principle and the structure of consciousness itself.

---

# PART 5: STACK ANCHORS BY LEAD

## 5.1 The Four STACK_ANCHORS Rules

These rules are **deterministic** based on the lead function's observer/decider type and attitude.

### Rule 1: Introverted Observer Lead (Si or Se with I attitude)

```
[1] = IO (introverted observer) — the lead function
[2] = ED (extroverted decider)
[3] = ID (introverted decider)
[4] = EO (extroverted observer)
```

**Oscillation**: I/E/I/E ✓
**Axis opposition**: [1]/[4] observer ↔ [2]/[3] decider ✓

### Rule 2: Extroverted Observer Lead (Ne or Ni with E attitude)

```
[1] = EO (extroverted observer) — the lead function
[2] = ID (introverted decider)
[3] = ED (extroverted decider)
[4] = IO (introverted observer)
```

**Oscillation**: E/I/E/I ✓
**Axis opposition**: [1]/[4] observer ↔ [2]/[3] decider ✓

### Rule 3: Introverted Decider Lead (Ti or Fi with I attitude)

```
[1] = ID (introverted decider) — the lead function
[2] = EO (extroverted observer)
[3] = IO (introverted observer)
[4] = ED (extroverted decider)
```

**Oscillation**: I/E/I/E ✓
**Axis opposition**: [1]/[4] decider ↔ [2]/[3] observer ✓

### Rule 4: Extroverted Decider Lead (Te or Fe with E attitude)

```
[1] = ED (extroverted decider) — the lead function
[2] = IO (introverted observer)
[3] = EO (extroverted observer)
[4] = ID (introverted decider)
```

**Oscillation**: E/I/E/I ✓
**Axis opposition**: [1]/[4] decider ↔ [2]/[3] observer ✓

---

## 5.2 Critical Application Principle

**The savior pair functions do NOT map directly to [1] and [2].**

Instead:
1. Identify the **lead function type** (which STACK_ANCHORS rule applies)
2. Apply the rule to get [1] position requirement (attitude + observer/decider type)
3. Place the **lead function** at [1] (it must match the requirement)
4. For the **savior decider** function:
   - Identify its **attitude and axis type** (I/E and observer/decider)
   - Find which STACK_ANCHORS position matches that requirement
   - Place the savior decider there (may be [2], [3], or [4])
5. Derive remaining functions via **axis opposition** and **inverse pairings**
6. Verify **oscillation** and **relationship rules** hold

**Example**: Formal notation `MM - Se/Ti`
- Se is extroverted observer → STACK_ANCHORS extroverted observer lead applies
- Se[1] (matches EO requirement) ✓
- Ti is introverted decider (ID requirement is at [2])
- Ti[2] ✓
- [3] = ED (extroverted decider) → opposite axis from Ti = Fe ✓
- [4] = IO (introverted observer) → opposite axis from Se = Ni ✓
- Ordonnance: Se[1] - Ti[2] - Fe[3] - Ni[4] ✓

---

# PART 6: COMMON NOTATION

## 6.1 Common Notation Structure

**Format**: Four lines, one per animal in priority order

```
(DirectionalityPrefix) [BracketRange] AxisLetters AnimalName = (m/f)Function1 + (m/f)Function2
```

**Example**:
```
(Di) [1-2] SF Consume = (m)Fi + (f)Se
(Oe) [2-4] NT Play = (f)Ne + (m)Te
(Oi) [3-4] ST Blast = (f)Te + (m)Si
(Di) [1-3] NF Sleep = (m)Fi + (m)Si
```

### Component 1: Directionality Prefix (Ordonnance Number + Function Type)

**Format**: (XY) where X = Ordonnance marker, Y = Observer/Decider type

**Valid prefixes**:
- **(Oi)** = Ordonnance[1 or 3 or 2 or 4] Introverted Observer (Si or Ni appears first)
- **(Oe)** = Ordonnance[1 or 3 or 2 or 4] Extroverted Observer (Se or Ne appears first)
- **(Di)** = Ordonnance[1 or 3 or 2 or 4] Introverted Decider (Ti or Fi appears first)
- **(De)** = Ordonnance[1 or 3 or 2 or 4] Extroverted Decider (Te or Fe appears first)

**Selection Rule**: Use the **type of the FIRST function** in the bracket range.

**Example**:
- Blast [3-4] with Si[3] + Te[4] → Si is introverted observer → **(Oi)**
- Play [2-4] with Fe[2] + Ne[4] → Fe is extroverted decider → **(De)**

### Component 2: Bracket Range

**Format**: [X-Y] where X and Y are ordonnance positions

**Valid ranges only**:
- [1-2] (adjacent)
- [1-3] (non-adjacent, jumper only)
- [2-4] (non-adjacent, jumper only)
- [3-4] (adjacent)

### Component 3: Axis Letters

**Format**: Two-letter pair from standardized axis notation

**Standardized pairs** (Keirsey temperaments—order is FIXED):
- **NT** = Intuition + Thinking
- **NF** = Intuition + Feeling
- **ST** = Sensation + Thinking
- **SF** = Sensation + Feeling

**Critical rule**: Axis letters do NOT reorder based on function sequence. If the animal contains intuition and thinking, it's **NT** regardless of which appears first.

### Component 4: Animal Name

**Valid animal names**:
- Sleep, Blast, Consume, Play

### Component 5: Modalized Function Pair

**Format**: (m/f)Function1 + (m/f)Function2

- **First function**: The one that appears first in ordonnance order
- **Second function**: The one that appears second in ordonnance order
- **Modality prefix**: (m) for masculine, (f) for feminine

**Example**: (f)Ne + (m)Te means feminine extroverted intuition + masculine extroverted thinking

---

## 6.2 What Common Notation Shows

Common notation makes explicit:
- ✓ The ordonnance numbering [1][2][3][4]
- ✓ The modality of each function
- ✓ Which animals contain which functions
- ✓ The priority order of animals
- ✓ The direction/type of each function (via directionality)
- ✓ The axis structure of each animal (via axis letters)

---

# PART 7: CONVERSION ALGORITHM: FORMAL → COMMON

## 7.1 Step-by-Step Algorithm

### INPUT: Formal Notation
Format: [Modality] - [Observer/Decider] - [AnimalStack]
Example: `FF - Si/Ti - SB/P(C)`

### PROCESSING STEPS

#### STEP 1: Parse the Lead Function and Identify STACK_ANCHORS Rule

```
Read the savior observer function from the formal notation
↓
Determine: Is it introverted or extroverted? Is it observer or decider?
↓
Match to correct STACK_ANCHORS rule
↓
Lock in the attitude pattern [I/E/I/E] or [E/I/E/I]
```

**Example**: Si (introverted observer) → STACK_ANCHORS introverted observer lead
- Pattern: [1]=IO | [2]=ED | [3]=ID | [4]=EO

#### STEP 2: Place Lead Function at [1]

```
The savior observer function ALWAYS goes to [1]
(It's the first differentiated function)
Verify it matches [1] requirement from STACK_ANCHORS ✓
```

#### STEP 3: Identify Savior Decider and Find Its Position

```
Read the savior decider function
↓
Determine its attitude (I/E) and type (observer/decider)
↓
Find which STACK_ANCHORS position matches that requirement
↓
Place savior decider there
```

**Critical Insight**: Savior decider may go to [2], [3], or [4] depending on its attitude/type, NOT automatically to [2].

**Example**: Savior decider = Ti (introverted decider)
- STACK_ANCHORS shows [2]=ED, [3]=ID, [4]=EO
- Ti is ID → Ti goes to [3]
- But if savior decider were Te (extroverted decider) → Te is ED → Te goes to [2]

#### STEP 4: Derive [2] and [3] via Axis Opposition

```
From [1], determine the axis: observer or decider?
↓
[2]/[3] must be on the OPPOSITE axis
↓
Use inverse pairings to find the functions:
  If [1] is Si → opposite axis observer functions use Si↔Ne pairing
  If [1] is Ti → opposite axis decider functions use Ti↔Fe pairing
↓
Apply STACK_ANCHORS attitude requirements to determine function polarity
```

#### STEP 5: Determine [4] via [1]/[4] Modality Pairing

```
From [1] function and modality, look up [4] in the [1]/[4] table
↓
[4] = same axis as [1], opposite polarity, opposite modality
```

#### STEP 6: Apply All Modalities

```
From modality pair (char_1 and char_2):
↓
Apply modality anchor to sensory functions:
  char_1 determines Si/Se modality
  inverse modality applies to Ne/Ni
↓
Apply modality anchor to extroverted deciders:
  char_2 determines Te/Fe modality
  inverse modality applies to Ti/Fi
```

**Result**: All four functions now have modality markers

#### STEP 7: Map Animals to Bracket Ranges

```
For each animal in the animal stack (in formal notation order):
↓
Identify its observer/decider attitude pair (IO/EO/ID/ED)
↓
Find which two functions match that pair:
  Sleep (IO+ID): find positions with IO and ID
  Blast (IO+ED): find positions with IO and ED
  Consume (EO+ID): find positions with EO and ID
  Play (EO+ED): find positions with EO and ED
↓
Determine bracket range [X-Y] (ascending order, always)
```

#### STEP 8: Write Common Notation

```
For each animal in the animal stack priority order:

[A] Determine directionality prefix from first function's type
[B] Write bracket range [X-Y]
[C] Write standardized axis letters (NT, NF, ST, or SF)
[D] Write animal name
[E] Write modalized function pair: (m/f)Function1 + (m/f)Function2

Output: (Prefix) [Range] AxisLetters AnimalName = (m/f)Func1 + (m/f)Func2
```

---

## 7.2 Worked Example: FF - Si/Ti - SB/P(C) → Common Notation

**STEP 1**: Lead = Si (introverted observer) → STACK_ANCHORS introverted observer lead
- [1]=IO | [2]=ED | [3]=ID | [4]=EO

**STEP 2**: Si[1] matches IO requirement ✓

**STEP 3**: Savior decider = Ti (introverted decider = ID type)
- STACK_ANCHORS shows [3]=ID
- Ti[3] ✓

**STEP 4**: Axis opposition
- [1]/[3] are on decider axis (Si is observer at [1], so we need opposite axis)
- Wait, [1] is observer, so [2]/[3] are on... No, [1] is observer.
- Actually: [1][4] are observer (Si and Ne), [2][3] are decider (Fe and Ti)
- [2] = ED requirement = Fe ✓
- [3] = ID requirement = Ti ✓

**STEP 5**: [4] via [1]/[4] modality pairing
- [1] = (f)Si from FF modality
- Looking up Si with (f): [4] = (m)Ne ✓

**STEP 6**: Apply modalities
- Sensory: (f)Si, (m)Ne
- Ext-decider: (f)Fe, (m)Ti (inverse)
- Result: [1](f)Si - [2](f)Fe - [3](m)Ti - [4](m)Ne

**STEP 7**: Map animals
- Sleep (IO+ID): Si[1] + Ti[3] = [1-3] ✓
- Blast (IO+ED): Si[1] + Fe[2] = [1-2] ✓
- Play (EO+ED): Ne[4] + Fe[2] = [2-4] ✓
- Consume (EO+ID): Ne[4] + Ti[3] = [3-4] ✓

**STEP 8**: Write common notation (animal stack order SB/P(C))

```
(Oi) [1-3] ST Sleep = (f)Si + (m)Ti
(Oi) [1-2] SF Blast = (f)Si + (f)Fe
(De) [2-4] NF Play = (f)Fe + (m)Ne
(Di) [3-4] NT Consume = (m)Ti + (m)Ne
```

---

# PART 8: CONVERSION ALGORITHM: COMMON → FORMAL

## 8.1 Step-by-Step Algorithm

### INPUT: Common Notation
Four lines showing animals with ordonnance positions and modalities

### PROCESSING STEPS

#### STEP 1: Reconstruct Full Ordonnance from Common Notation

```
From common notation, each animal shows two functions at specific brackets
↓
List all four functions with their ordonnance positions and modalities
↓
Verify each function appears in exactly 2 animals
↓
Verify bracket ranges are valid: [1-2], [1-3], [2-4], [3-4]
```

**Example**: From `(Oi) [1-3] ST Sleep = (f)Si + (m)Ti`:
- Si[1] = (f)
- Ti[3] = (m)
(Continue for remaining animals to complete ordonnance)

#### STEP 2: Identify the Lead Function

```
The function at [1] is the lead function
(Most differentiated, determines STACK_ANCHORS rule)
↓
Determine: Is it observer or decider? I or E?
```

#### STEP 3: Extract Modality Anchors

```
From the modalized ordonnance:
↓
Identify all sensory function modalities (Si/Se)
↓
Identify all extroverted decider modalities (Te/Fe)
↓
These are your char_1 and char_2
```

**Example**: (f)Si, (m)Ne → sensory modality = F
- (f)Fe, (m)Ti → ext-decider modality = F
- Modality pair: FF

#### STEP 4: Identify Savior Pair Functions

```
From the animal stack notation in common notation:
↓
Read which animals are in the savior pair (first two animals)
↓
Find which two functions appear in the first animal's bracket range
↓
These are your observer/decider pair
```

**Example**: If first animal is Sleep [1-3] = Si + Ti
- Savior observer = Si
- Savior decider = Ti

#### STEP 5: Determine Animal Stack

```
From common notation, read the animals in the order they appear
↓
Write them as [A1][A2]/[A3]([A4])
↓
A1 and A2 are savior (first two animals listed)
↓
A3 is first demon, A4 is last demon (in parentheses)
```

### OUTPUT: Formal Notation

```
[Modality] - [SaverObserver/SaverDecider] - [AnimalStack]

Example: FF - Si/Ti - SB/P(C)
```

---

## 8.2 Worked Example: Common → Formal

**INPUT** (Common notation):
```
(Oi) [1-3] ST Sleep = (f)Si + (m)Ti
(Oi) [1-2] SF Blast = (f)Si + (f)Fe
(De) [2-4] NF Play = (f)Fe + (m)Ne
(Di) [3-4] NT Consume = (m)Ti + (m)Ne
```

**STEP 1**: Reconstruct ordonnance
- [1] (f)Si
- [2] (f)Fe
- [3] (m)Ti
- [4] (m)Ne

**STEP 2**: Lead function = (f)Si at [1] (introverted observer)

**STEP 3**: Extract modalities
- Sensory: (f)Si, (m)Ne → sensory modality = F
- Ext-decider: (f)Fe, (m)Ti → ext-decider modality = F
- Modality: FF

**STEP 4**: Savior pair from first animal (Sleep [1-3])
- Functions: Si + Ti
- Savior observer = Si
- Savior decider = Ti

**STEP 5**: Animal stack from order
- Sleep (first animal) → S
- Blast (second animal) → B
- Play (third animal) → P
- Consume (fourth animal) → C
- Stack: SB/P(C)

**OUTPUT**: FF - Si/Ti - SB/P(C)

---

# PART 9: MASTERING PRINCIPLES (Summary)

## 9.1 The Mechanical Decision Tree

**When you see formal notation [Modality] - [Observer/Decider] - [AnimalStack]:**

1. **Identify lead type** → Which STACK_ANCHORS rule?
2. **Apply STACK_ANCHORS** → Get position requirements [I/E, observer/decider]
3. **Place lead at [1]** → Savior observer goes here
4. **Place savior decider** → Find position matching its attitude/type
5. **Derive opposite-axis functions** → Use inverse pairings and STACK_ANCHORS requirements
6. **Apply modality anchors** → 2 anchor points determine all 4 modalities
7. **Map animals to brackets** → Find observer/decider pairs in ordonnance
8. **Write common notation** → Directionality, brackets, axis letters, animals, modalities

---

## 9.2 Critical Insights

### The Inverse Pairings Are Structural, Not Modality-Based

- Si ↔ Ne
- Se ↔ Ni
- Ti ↔ Fe
- Fi ↔ Te

**These are FIXED.** They do not change based on modality. They derive from the structure of consciousness and Jung's complementarity principle.

### [1]/[4] Modality Pairing Is Deterministic

Once [1] is fixed (function + modality), [4] is mechanically determined. **No choice involved.**

### Savior Pair Does Not Map to [1]/[2]

The savior pair tells you which two functions appear, but NOT which ordonnance positions they occupy. **Positions are determined by STACK_ANCHORS, not by "savior" status.**

### Axis Opposition Is About Function Axes, Not Attitudes

[1]/[4] axis is opposite to [2]/[3] axis means:
- If [1]/[4] are on observer axis → [2]/[3] are on decider axis
- If [1]/[4] are on decider axis → [2]/[3] are on observer axis

**This is structural, not a choice.**

### Animal Stack Reveals, Does Not Determine

The animal stack shows which observer/decider pairings exist in the ordonnance. **It does not create the ordonnance; it reflects it.**

---

# PART 10: WORKED EXAMPLES (ALL 9 DRILLED EXAMPLES)

## Example 1: MF - Ne/Te - PB/C(S)

**Ordonnance**: [1](f)Ne - [2](m)Fi - [3](f)Te - [4](m)Si

**Common Notation**:
```
(Oe) [1-3] NT Play = (f)Ne + (f)Te
(De) [3-4] ST Blast = (f)Te + (m)Si
(Oe) [1-2] NF Consume = (f)Ne + (m)Fi
(Di) [2-4] SF Sleep = (m)Fi + (m)Si
```

**Key Learning**: Extroverted observer lead with MF modality. Ne feminine, Fi masculine (inverse of Te feminine).

---

## Example 2: FM - Si/Fe - BP/S(C)

**Ordonnance**: [1](f)Si - [2](m)Fe - [3](f)Ti - [4](m)Ne

**Common Notation**:
```
(Oi) [1-2] SF Blast = (f)Si + (m)Fe
(De) [2-4] NF Play = (m)Fe + (m)Ne
(Oi) [1-3] ST Sleep = (f)Si + (f)Ti
(Di) [3-4] NT Consume = (f)Ti + (m)Ne
```

**Key Learning**: Introverted observer lead with FM modality. Si feminine, Ne masculine (inverse of Si feminine).

---

## Example 3: MM - Fe/Se - PB/C(S)

**Ordonnance**: [1](m)Fe - [2](f)Ni - [3](m)Se - [4](f)Ti

**Common Notation**:
```
(De) [1-3] SF Play = (m)Fe + (m)Se
(De) [1-2] SF Blast = (m)Fe + (f)Ni
(Oe) [3-4] ST Consume = (m)Se + (f)Ti
(Oi) [2-4] ST Sleep = (f)Ni + (f)Ti
```

**Key Learning**: Extroverted decider lead with MM modality. Axis opposition requires [2] to be introverted observer (Ni, not Si) because [1]/[3] are on sensation axis. The inverse pairing Se ↔ Ni is structural, not arbitrary.

---

## Example 4: MM - Ne/Te - PB/S(C)

**Ordonnance**: [1](f)Ne - [2](f)Fi - [3](m)Te - [4](m)Si

**Common Notation**:
```
(Oe) [1-3] NT Play = (f)Ne + (m)Te
(De) [3-4] ST Blast = (m)Te + (m)Si
(Di) [2-4] SF Sleep = (f)Fi + (m)Si
(Oe) [1-2] NF Consume = (f)Ne + (f)Fi
```

**Key Learning**: Extroverted observer lead with MM modality. Modality inversions create feminine/masculine distribution across axes. **Critical point**: For MM modality, ext-decider is masculine, so int-decider must be feminine. Fi is introverted feeling, therefore (f)Fi.

---

## Example 5: MM - Se/Ti - CS/P(B)

**Ordonnance**: [1](m)Se - [2](f)Ti - [3](m)Fe - [4](f)Ni

**Common Notation**:
```
(Oe) [1-2] ST Consume = (m)Se + (f)Ti
(Di) [2-4] ST Sleep = (f)Ti + (f)Ni
(Oe) [1-3] SF Play = (m)Se + (m)Fe
(De) [3-4] NF Blast = (m)Fe + (f)Ni
```

**Key Learning**: Extroverted observer lead (Se) but savior decider is Ti (introverted decider, not extroverted). Ti correctly goes to [2] per STACK_ANCHORS. [3] requires ED, which is opposite decider axis from Ti = Fe. Demonstrates that savior pair does NOT map to [1]/[2].

---

## Example 6: FF - Fi/Se - CP/B(S)

**Ordonnance**: [1](m)Fi - [2](f)Se - [3](m)Ni - [4](f)Te

**Common Notation**:
```
(Di) [1-2] SF Consume = (m)Fi + (f)Se
(Oe) [2-4] ST Play = (f)Se + (f)Te
(Oi) [3-4] NT Blast = (m)Ni + (f)Te
(Di) [1-3] NF Sleep = (m)Fi + (m)Ni
```

**Key Learning**: Introverted decider lead with FF modality. Axis opposition (Fi[1]/Te[4] decider ↔ Se[2]/Ni[3] observer) is clear.

---

## Example 7: FF - Fi/Se - CP/S(B)

**Ordonnance**: [1](m)Fi - [2](f)Se - [3](m)Ni - [4](f)Te

**Common Notation**:
```
(Di) [1-2] SF Consume = (m)Fi + (f)Se
(Oe) [2-4] ST Play = (f)Se + (f)Te
(Di) [1-3] NF Sleep = (m)Fi + (m)Ni
(Oi) [3-4] NT Blast = (m)Ni + (f)Te
```

**Key Learning**: Same ordonnance as Example 6, different animal stack order. Priority order changes, not structure.

---

## Example 8: FM - Ti/Se - CS/B(P)

**Ordonnance**: [1](f)Ti - [2](f)Se - [3](m)Ni - [4](m)Fe

**Common Notation**:
```
(Di) [1-2] NT Consume = (f)Ti + (f)Se
(Di) [1-3] ST Sleep = (f)Ti + (m)Ni
(Oi) [3-4] SF Blast = (m)Ni + (m)Fe
(Oe) [2-4] NF Play = (f)Se + (m)Fe
```

**Key Learning**: Introverted decider lead (Ti) with FM modality. Axis opposition shows Ti[1]/Fe[4] decider paired with Se[2]/Ni[3] observer.

---

## Example 9: FF - Si/Ti - SB/P(C)

**Ordonnance**: [1](f)Si - [2](f)Fe - [3](m)Ti - [4](m)Ne

**Common Notation**:
```
(Oi) [1-3] ST Sleep = (f)Si + (m)Ti
(Oi) [1-2] SF Blast = (f)Si + (f)Fe
(De) [2-4] NF Play = (f)Fe + (m)Ne
(Di) [3-4] NT Consume = (m)Ti + (m)Ne
```

**Key Learning**: Introverted observer lead (Si) with FF modality. Savior decider is Ti (introverted decider), correctly placed at [3] per STACK_ANCHORS.

---

# PART 11: QUICK REFERENCE CHECKLISTS

## Formal → Common Checklist

- [ ] Identify lead function type (observer/decider, I/E)
- [ ] Apply correct STACK_ANCHORS rule
- [ ] Place lead at [1], verify it matches [1] requirement
- [ ] Find savior decider's attitude/type, place it at matching STACK_ANCHORS position
- [ ] Use inverse pairings to derive remaining two functions
- [ ] Verify oscillation I/E/I/E holds
- [ ] Verify [1]/[4] and [2]/[3] relationships hold
- [ ] Apply modality anchors (char_1 and char_2)
- [ ] Map animals to bracket ranges
- [ ] Determine directionality prefix for each animal
- [ ] Write standardized axis letters (NT, NF, ST, SF)
- [ ] Write modalized function pairs
- [ ] Output in animal stack priority order

## Common → Formal Checklist

- [ ] Reconstruct full ordonnance from all four animals
- [ ] Identify [1] function (lead)
- [ ] Extract modality anchors from modalized ordonnance
- [ ] Identify savior pair (observer/decider in first animal)
- [ ] Determine animal stack from order
- [ ] Verify all functions appear in exactly 2 animals
- [ ] Verify bracket ranges valid: [1-2], [1-3], [2-4], [3-4]
- [ ] Output as [Modality] - [Observer/Decider] - [AnimalStack]

---

# PART 12: IMPLEMENTATION NOTES FOR LLMs

## System Instructions for Mechanical Application

1. **Never infer function pairings.** Use only the fixed inverse pairings:
   - Si ↔ Ne, Se ↔ Ni, Ti ↔ Fe, Fi ↔ Te

2. **Never reorder axis letters.** Standardized pairs are NT, NF, ST, SF. Order is fixed.

3. **Always apply STACK_ANCHORS mechanically.** Do not attempt to shortcut via intuition.

4. **Verify oscillation and relationship rules** on every derivation.

5. **Remember: Savior pair ≠ [1]/[2].** Savior decider may be at [3] or [4].

6. **Modality is deterministic from two anchors.** No ambiguity once char_1 and char_2 are set.

7. **Bracket ranges are limited to four options.** If a range appears that isn't [1-2], [1-3], [2-4], or [3-4], stop and verify.

8. **Animal stack order is input—use it as-is.** Do not reorder based on internal logic.

---

# PART 13: VALIDATION GATES

**Before outputting common notation, verify**:
- [ ] All four functions present with ordonnance numbers
- [ ] All four modalities (m or f) assigned
- [ ] Each function appears in exactly 2 animals
- [ ] All bracket ranges are valid
- [ ] Directionality prefixes match first function type in each range
- [ ] Axis letters are standardized (no custom ordering)
- [ ] Modality inversions follow the rules (if sensory F, then intuitive M)
- [ ] Oscillation rule holds: I/E/I/E or E/I/E/I
- [ ] [1]/[4] and [2]/[3] relationships verified

**Before outputting formal notation, verify**:
- [ ] Modality pair is valid (MF, FM, MM, or FF)
- [ ] Savior observer function matches [1]
- [ ] Savior decider function exists in ordonnance
- [ ] Animal stack animals match those in ordonnance
- [ ] Animal stack order is preserved from common notation
- [ ] All functions in ordonnance are accounted for in animals

---

# CONCLUSION: READY FOR DEPLOYMENT

This SPR contains:

✓ Complete ontological foundations (Onto-Clean framework)
✓ Jung's complementarity principle and its mechanical implications
✓ All four STACK_ANCHORS rules
✓ Complete modality system with inversion rules
✓ Fixed inverse function pairings (structural, not modality-based)
✓ [1]/[4] and [2]/[3] deterministic logic
✓ Formal notation structure and semantics
✓ Common notation structure and semantics
✓ Complete formal → common conversion algorithm
✓ Complete common → formal conversion algorithm
✓ 9 worked examples covering all four lead types and multiple modality pairs
✓ Quick reference checklists
✓ Validation gates and implementation notes

**This SPR should enable any LLM to convert between formal and common notation for any of the 512 OPS types mechanically and reliably.**

---
