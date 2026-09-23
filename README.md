## 📊 RSVP-X Dataset Statistics

(https://huggingface.co/datasets/impressive-east579/RSVP)

> ### Important Note
>
> The dataset consists of **3,076 unique prompts**, where each prompt is paired with responses across the three HHH dimensions:
>
> - **Helpfulness**
> - **Harmlessness**
> - **Honesty**
>
> As a result, the final dataset contains:
>
> **3,076 Prompts × 3 Responses = 9,228 Total Samples**

---

## Table 1: Statistics Across All Four Dimensions in RSVP-X

| Dimension | \|X\| | \|\~X\| / \|X' \ Q\| | \|r_i^(o)\| | \|F+\| / \|F\| | \|R\| |
|---|---:|---:|---:|---:|---:|
| Reasoning | 476 | 827 / 145 | 682 | 520 / 162 | 520 |
| Safety | 485 | 601 / 115 | 486 | 410 / 76 | 410 |
| Value | 1,565 | 2,247 / 463 | 1,784 | 1,502 / 282 | 1,502 |
| Pluralistic | 726 | 941 / 195 | 746 | 644 / 102 | 644 |
| **Total** | **3,252** | **4,616 / 918** | **3,698** | **3,076 / 622** | **3,076** |

**Caption:**  
Statistics across all four dimensions in RSVP-X.  
Step 1 reports \|X\|.  
Steps 2 and 3 report \|\~X\| / \|X' \ Q\|.  
Step 4 reports \|r_i^(o)\| and \|F+\| / \|F\|.  
Step 5 reports finalized prompt-response pairs \|R\|.

---

## Table 2: Statistics for Reasoning Domains in RSVP-X

| Domain | \|X\| | \|\~X\| / \|X' \ Q\| | \|r_i^(o)\| | \|F+\| / \|F\| | \|R\| |
|---|---:|---:|---:|---:|---:|
| Biology | 32 | 47 / 14 | 33 | 30 / 3 | 30 |
| Chemistry | 41 | 56 / 18 | 38 | 28 / 10 | 28 |
| Computer Science | 45 | 67 / 15 | 52 | 33 / 19 | 33 |
| Engineering | 38 | 65 / 16 | 49 | 27 / 22 | 27 |
| Math | 36 | 62 / 12 | 50 | 30 / 20 | 30 |
| Physics | 33 | 41 / 3 | 38 | 28 / 10 | 28 |
| Business | 29 | 49 / 10 | 39 | 29 / 10 | 29 |
| Economics | 27 | 58 / 9 | 49 | 29 / 20 | 29 |
| Health | 48 | 79 / 15 | 64 | 63 / 1 | 63 |
| History | 47 | 45 / 7 | 38 | 28 / 10 | 28 |
| Law | 26 | 47 / 9 | 38 | 28 / 10 | 28 |
| Philosophy | 34 | 40 / 6 | 34 | 28 / 6 | 28 |
| Psychology | 21 | 36 / 4 | 32 | 28 / 4 | 28 |
| Other | 19 | 135 / 7 | 128 | 111 / 17 | 111 |
| **Total** | **476** | **827 / 145** | **682** | **520 / 162** | **520** |

---

## Table 3: Statistics for Safety Domains in RSVP-X

| Domain | \|X\| | \|\~X\| / \|X' \ Q\| | \|r_i^(o)\| | \|F+\| / \|F\| | \|R\| |
|---|---:|---:|---:|---:|---:|
| Animal Abuse | 34 | 45 / 11 | 34 | 30 / 4 | 30 |
| Child Abuse | 42 | 47 / 13 | 34 | 28 / 6 | 28 |
| Controversial Topics & Politics | 45 | 48 / 9 | 39 | 32 / 7 | 32 |
| Discrimination & Injustice | 39 | 44 / 12 | 32 | 27 / 5 | 27 |
| Drug & Weapon Use | 37 | 43 / 8 | 35 | 29 / 6 | 29 |
| Financial Crime & Theft | 31 | 41 / 5 | 36 | 29 / 7 | 29 |
| Hate Speech & Offensive Language | 28 | 40 / 6 | 34 | 29 / 5 | 29 |
| Misinformation on Ethics & Safety | 48 | 49 / 10 | 39 | 31 / 8 | 31 |
| Non-Violent Unethical Behavior | 47 | 50 / 14 | 36 | 31 / 5 | 31 |
| Privacy Violation | 26 | 38 / 4 | 34 | 28 / 6 | 28 |
| Self-Harm | 33 | 42 / 11 | 31 | 29 / 2 | 29 |
| Sexually Explicit Content | 21 | 36 / 3 | 33 | 28 / 5 | 28 |
| Terrorism & Organized Crime | 19 | 35 / 2 | 33 | 28 / 5 | 28 |
| Violence & Incitement | 35 | 43 / 7 | 36 | 31 / 5 | 31 |
| **Total** | **485** | **601 / 115** | **486** | **410 / 76** | **410** |

---

## Table 4: Statistics for Value Domains in RSVP-X

| Domain | \|X\| | \|\~X\| / \|X' \ Q\| | \|r_i^(o)\| | \|F+\| / \|F\| | \|R\| |
|---|---:|---:|---:|---:|---:|
| Ambitious | 34 | 45 / 10 | 35 | 30 / 5 | 30 |
| Influential | 28 | 41 / 8 | 33 | 28 / 5 | 28 |
| Successful | 31 | 44 / 9 | 35 | 30 / 5 | 30 |
| Capable | 27 | 40 / 7 | 33 | 28 / 5 | 28 |
| Intelligent | 45 | 48 / 11 | 37 | 31 / 6 | 31 |
| Preserve Public Image | 33 | 43 / 10 | 33 | 29 / 4 | 29 |
| Social Power | 22 | 36 / 5 | 31 | 26 / 5 | 26 |
| Authority | 18 | 35 / 3 | 32 | 26 / 6 | 26 |
| Wealth | 29 | 42 / 9 | 33 | 29 / 4 | 29 |
| Social Recognition | 47 | 49 / 12 | 37 | 31 / 6 | 31 |
| National Security | 30 | 41 / 7 | 34 | 28 / 6 | 28 |
| Sense of Belonging | 32 | 43 / 11 | 32 | 29 / 3 | 29 |
| Reciprocity of Favors | 12 | 34 / 4 | 30 | 26 / 4 | 26 |
| Cleanliness | 21 | 37 / 6 | 31 | 26 / 5 | 26 |
| Social Order | 46 | 48 / 10 | 38 | 32 / 6 | 32 |
| Family Security | 35 | 44 / 8 | 36 | 30 / 6 | 30 |
| Obedience | 28 | 41 / 9 | 32 | 28 / 4 | 28 |
| Politeness | 24 | 39 / 7 | 32 | 27 / 5 | 27 |
| Self-Discipline | 17 | 36 / 4 | 32 | 26 / 6 | 26 |
| Honoring Parents and Elders | 26 | 40 / 8 | 32 | 27 / 5 | 27 |
| Accepting One’s Lot | 23 | 38 / 6 | 32 | 26 / 6 | 26 |
| Moderation | 19 | 35 / 4 | 31 | 26 / 5 | 26 |
| Respect for Tradition | 31 | 42 / 10 | 32 | 29 / 3 | 29 |
| Humility | 16 | 34 / 3 | 31 | 26 / 5 | 26 |
| Devoutness | 29 | 42 / 11 | 31 | 28 / 3 | 28 |
| Detachment from Worldly Concerns | 15 | 33 / 2 | 31 | 26 / 5 | 26 |
| Self-Respect | 18 | 35 / 5 | 30 | 26 / 4 | 26 |
| Choosing Own Goals | 33 | 45 / 12 | 33 | 30 / 3 | 30 |
| Creativity | 47 | 49 / 13 | 36 | 31 / 5 | 31 |
| Curiosity | 14 | 36 / 2 | 34 | 26 / 8 | 26 |
| Independence | 48 | 49 / 10 | 39 | 32 / 7 | 32 |
| Freedom | 30 | 42 / 8 | 34 | 29 / 5 | 29 |
| Exciting Life | 27 | 40 / 6 | 34 | 28 / 6 | 28 |
| Varied Life | 21 | 37 / 5 | 32 | 26 / 6 | 26 |
| Daring | 25 | 39 / 8 | 31 | 27 / 4 | 27 |
| Pleasure | 34 | 45 / 9 | 36 | 30 / 6 | 30 |
| Enjoyment of Leisure | 32 | 43 / 12 | 31 | 29 / 2 | 29 |
| Beauty | 46 | 48 / 11 | 37 | 32 / 5 | 32 |
| Broad-Minded Tolerance | 29 | 41 / 10 | 31 | 28 / 3 | 28 |
| Protect Environment | 28 | 40 / 9 | 31 | 28 / 3 | 28 |
| Social Justice | 47 | 49 / 14 | 35 | 31 / 4 | 31 |
| Unity With Nature | 22 | 36 / 6 | 30 | 26 / 4 | 26 |
| Wisdom | 46 | 48 / 9 | 39 | 32 / 7 | 32 |
| World At Peace | 30 | 41 / 8 | 33 | 28 / 5 | 28 |
| Loyalty to Group | 12 | 32 / 14 | 18 | 2 / 16 | 2 |
| Responsibility | 19 | 37 / 10 | 27 | 25 / 2 | 25 |
| Mature Love | 28 | 41 / 11 | 30 | 28 / 2 | 28 |
| True Friendship | 35 | 44 / 12 | 32 | 29 / 3 | 29 |
| Honesty | 29 | 42 / 10 | 32 | 28 / 4 | 28 |
| Forgiveness | 31 | 43 / 11 | 32 | 29 / 3 | 29 |
| Spiritual Life Focus | 23 | 38 / 5 | 33 | 26 / 7 | 26 |
| Purpose in Life | 34 | 45 / 13 | 32 | 30 / 2 | 30 |
| Helpfulness | 33 | 44 / 10 | 34 | 30 / 4 | 30 |
| Equality | 14 | 36 / 3 | 33 | 26 / 7 | 26 |
| Inner Harmony | 12 | 32 / 13 | 19 | 2 / 17 | 2 |
| **Total** | **1,565** | **2,247 / 463** | **1,784** | **1,502 / 282** | **1,502** |

---

## Table 5: Statistics for Pluralistic Domains in RSVP-X

| Domain | \|X\| | \|\~X\| / \|X' \ Q\| | \|r_i^(o)\| | \|F+\| / \|F\| | \|R\| |
|---|---:|---:|---:|---:|---:|
| Global War | 34 | 45 / 10 | 35 | 31 / 4 | 31 |
| Weather | 28 | 41 / 9 | 32 | 27 / 5 | 27 |
| Holiday Planning | 26 | 40 / 8 | 32 | 28 / 4 | 28 |
| Race & Racism | 47 | 49 / 11 | 38 | 31 / 7 | 31 |
| Health Advice | 30 | 42 / 9 | 33 | 29 / 4 | 29 |
| Ethics of Killing | 29 | 41 / 7 | 34 | 29 / 5 | 29 |
| AI & ML | 22 | 36 / 6 | 30 | 26 / 4 | 26 |
| Immigration | 24 | 38 / 7 | 31 | 27 / 4 | 27 |
| Greeting | 31 | 43 / 8 | 35 | 29 / 6 | 29 |
| Income Inequality | 33 | 44 / 10 | 34 | 31 / 3 | 31 |
| Abortion | 48 | 49 / 12 | 37 | 32 / 5 | 32 |
| Animals | 46 | 48 / 9 | 39 | 32 / 7 | 32 |
| Climate Change | 35 | 44 / 9 | 35 | 30 / 5 | 30 |
| Travel | 32 | 43 / 11 | 32 | 30 / 2 | 30 |
| LGBTQ+ Identity | 29 | 41 / 8 | 33 | 28 / 5 | 28 |
| Israel-Palestine | 47 | 48 / 10 | 38 | 32 / 6 | 32 |
| Cooking | 34 | 45 / 13 | 32 | 30 / 2 | 30 |
| Elections | 23 | 37 / 5 | 32 | 26 / 6 | 26 |
| Religion | 21 | 35 / 4 | 31 | 26 / 5 | 26 |
| Job Search | 46 | 48 / 8 | 40 | 32 / 8 | 32 |
| Pop Culture | 28 | 40 / 9 | 31 | 28 / 3 | 28 |
| Relationships | 33 | 44 / 12 | 32 | 30 / 2 | 30 |
| **Total** | **726** | **941 / 195** | **746** | **644 / 102** | **644** |
