# MATCHMAKING MARKET DATA — STRUCTURED INTELLIGENCE ASSET
> **Filter Scope:** Age 24–28 | Height 5'0"–5'6" | Caste: Brahmin  
> **Total Market Size:** 3,318 profiles  
> **Platform Type:** Matrimonial matchmaking (Indian-origin, multi-geography)  
> **Asset Status:** PERMANENT REFERENCE — Do not reprocess raw_data.md  
> **Generated:** 2026  

---

## TABLE OF CONTENTS
1. [How to Read This File](#1-how-to-read-this-file)
2. [Market Overview](#2-market-overview)
3. [Marital Status](#3-marital-status)
4. [Mother Tongue](#4-mother-tongue)
5. [Caste Context (Adjacent Markets)](#5-caste-context-adjacent-markets)
6. [Sub-Caste (Active Market Distribution)](#6-sub-caste-active-market-distribution)
7. [Geography — Residential](#7-geography--residential)
8. [Geography — Native / Origin](#8-geography--native--origin)
9. [Education](#9-education)
10. [Career & Profession](#10-career--profession)
11. [Family Financial Status](#11-family-financial-status)
12. [Lifestyle](#12-lifestyle)
13. [Horoscope Layer](#13-horoscope-layer)
14. [Cross-Cut Insights](#14-cross-cut-insights)
15. [Strategic Matrix](#15-strategic-matrix)
16. [Tags Index](#16-tags-index)

---

## 1. HOW TO READ THIS FILE

### Schema Explanation
Each category section contains:
- **Raw counts** — absolute numbers from the platform
- **% of total** — share of the 3,318 base
- **Rank** — ordinal rank within category
- **Cumulative %** — Pareto-style accumulation
- **Tag** — signal quality marker (see Tags Index)
- **Meta Insight** — what the number actually means strategically

### Category Relationships
```
3,318 profiles (Base)
├── ALL are Brahmin (confirmed by sub-caste data — all entries are Brahmin sub-types)
├── ALL are Age 24–28 (filter applied)
├── ALL are Height 5'0"–5'6" (filter applied)
├── Geography splits into TWO datasets:
│   ├── RESIDENTIAL (where they currently live)
│   └── NATIVE/ORIGIN (where they're from)
├── Education splits into:
│   ├── Field of study
│   └── Highest degree level
└── Horoscope splits into:
    ├── Mangal status
    ├── Rashi (zodiac sign)
    ├── Nadi (one of three: Adya/Madhya/Antya)
    └── Nakshatra (lunar mansion, 27 total)
```

### Data Caveats
| Caveat | Detail |
|--------|--------|
| **Caste section anomaly** | "Brahmin: 3318" in caste panel = active filter confirmation; other castes (Maratha 1160, etc.) = adjacent market alternatives from same age/height pool |
| **Geography duplication** | Residential Country ≠ Native Country; some NRIs list both. Total counts across geo layers don't sum to 3,318 due to data entry variations |
| **State naming inconsistencies** | "England", "UK", "Uk" treated as UK; "USA", "USA15", "United States" merged; "London" treated as city/state depending on context |
| **Sub-caste completeness** | 3,099/3,318 (93.4%) have sub-caste data; 219 (6.6%) not specified |
| **Nakshatra completeness** | 2,853/3,318 (86.0%) have Nakshatra data shown |
| **Nadi completeness** | ~2,737/3,318 (82.5%) have Nadi data |
| **Occupation vs. Working Field** | Two separate fields capturing job type differently; some double-counting possible |
| **Diet total** | 2,148+587+386+138+1 = 3,260; 58 profiles likely didn't fill this field |

### Compression Rules Applied
- Cities with count = 1 retained in long-tail summary but excluded from derived analytics tables
- State entries that are clearly country names (e.g., "Germany" as a state) flagged and re-attributed to Country layer
- Sub-caste entries: All entries retained; grouped by family (e.g., "Deshastha Rigwedi" + "Deshastha Yajurwedi" = Deshastha cluster)
- No data removed — only tagged as LONG_TAIL where count < 5 and < 0.2% of total

---

## 2. MARKET OVERVIEW

| Metric | Value |
|--------|-------|
| **Total Market Size** | 3,318 |
| **Caste** | 100% Brahmin |
| **India Resident** | 3,050 (91.9%) |
| **NRI / Overseas** | 268 (8.1%) |
| **Maharashtra-based** | 2,751 (90.2% of India-resident) |
| **Pune alone** | 1,082 (35.5% of India-resident) |
| **Never Married** | 3,318 (99.6% of marital status data) |
| **Post-Graduate or higher** | 1,984 (59.8%) |
| **STEM educated** | ~1,772 (53.4%) |
| **Non-smokers** | 3,260 (98.2%) |
| **Non-drinkers** | 3,028 (91.3%) |
| **Vegetarian** | 2,148 (64.7%) |
| **Upper Middle Class or above** | 1,777 (53.6%) |
| **Deshastha (R+Y) sub-caste** | 2,066 (62.3%) |
| **Top city concentration (Pune)** | 32.6% of total market |

### KEY PARETO TRUTH
> **80% of this market is:** Brahmin-Deshastha, Maharashtra-resident, Pune/Mumbai/Nagpur-based, STEM-educated, Private Sector/MNC professional, Upper Middle Class, Vegetarian, Non-smoking female aged 24–28.

---

## 3. MARITAL STATUS

| # | Status | Count | % of Total | Rank | Cumulative % | Tag |
|---|--------|-------|------------|------|--------------|-----|
| 1 | Never Married | 3,318 | 99.6% | 1 | 99.6% | HIGH_SIGNAL |
| 2 | Divorced | 14 | 0.4% | 2 | 100.0% | NICHE_CLUSTER |
| 3 | Awaiting Divorce / Legally Separated | 1 | 0.03% | 3 | 100.0% | LONG_TAIL |
| | **Total** | **3,333** | — | — | — | — |

> **Note:** Total (3,333) slightly exceeds base (3,318) — likely a platform facet count where some profiles are multi-categorized or include adjacent pool.

**Meta Insight:** This is a purely fresh-start market. The 14 divorced profiles (0.4%) form a distinct, underserved micro-segment with likely different expectations and faster decision-making velocity.

**Strategic Implication:** Positioning for divorced profiles requires entirely different messaging. The 3,318-strong never-married segment is the primary market with standard courtship timelines.

---

## 4. MOTHER TONGUE

| # | Language | Count | % of Total | Rank | Cumulative % | Tag |
|---|----------|-------|------------|------|--------------|-----|
| 1 | Marathi | 3,318 | 97.6% | 1 | 97.6% | HIGH_SIGNAL / SATURATED |
| 2 | Kannada | 39 | 1.1% | 2 | 98.7% | NICHE_CLUSTER |
| 3 | Kokani (Konkani) | 21 | 0.6% | 3 | 99.3% | NICHE_CLUSTER |
| 4 | Hindi | 10 | 0.3% | 4 | 99.6% | LONG_TAIL |
| 5 | Bengali | 2 | 0.06% | 5 | 99.7% | LONG_TAIL |
| 6 | English | 2 | 0.06% | 6 | 99.8% | LONG_TAIL |
| 7 | Telugu | 2 | 0.06% | 7 | 99.8% | LONG_TAIL |
| 8 | Kutchi | 1 | 0.03% | 8 | — | LONG_TAIL |
| 9 | Marwari | 1 | 0.03% | 9 | — | LONG_TAIL |
| 10 | Rajasthani | 1 | 0.03% | 10 | — | LONG_TAIL |
| 11 | Tamil | 1 | 0.03% | 11 | — | LONG_TAIL |
| | **Shown Total** | **3,398** | — | — | — | — |

**Meta Insight:** This is essentially a Marathi-speaking market. The Kannada (39) and Konkani (21) minorities likely represent Karnataka-settled or Goan Brahmin profiles. The non-Marathi segment (~80 profiles) is a coherent linguistic minority with potentially distinct community expectations.

---

## 5. CASTE CONTEXT (ADJACENT MARKETS)

> **Important:** The entire active dataset (3,318 profiles) is Brahmin. The table below shows what the platform would return if the caste filter were switched — representing the **adjacent marriage market landscape** from the same age/height pool.

| # | Caste | If-Filtered Count | % vs Brahmin Market | Rank | Tag |
|---|-------|-------------------|---------------------|------|-----|
| 1 | **Brahmin (active)** | **3,318** | 100% | 1 | HIGH_SIGNAL |
| 2 | Maratha | 1,160 | 35.0% | 2 | SATURATED |
| 3 | Kunbi | 129 | 3.9% | 3 | NICHE_CLUSTER |
| 4 | Mali | 106 | 3.2% | 4 | NICHE_CLUSTER |
| 5 | Shimpi | 90 | 2.7% | 5 | NICHE_CLUSTER |
| 6 | CKP | 83 | 2.5% | 6 | NICHE_CLUSTER |
| 7 | Teli | 75 | 2.3% | 7 | NICHE_CLUSTER |
| 8 | Chambhar | 71 | 2.1% | 8 | NICHE_CLUSTER |
| 9 | Vaishya Vani | 70 | 2.1% | 9 | NICHE_CLUSTER |
| 10 | Sonar | 65 | 2.0% | 10 | NICHE_CLUSTER |
| 11 | Buddhist | 62 | 1.9% | 11 | NICHE_CLUSTER |
| 12 | Lingayat | 61 | 1.8% | 12 | NICHE_CLUSTER |
| 13 | Bhandari | 46 | 1.4% | 13 | NICHE_CLUSTER |
| 14 | Dhangar | 46 | 1.4% | 14 | NICHE_CLUSTER |
| 15 | Mahar | 42 | 1.3% | 15 | NICHE_CLUSTER |
| 16 | Leva Patil | 40 | 1.2% | 16 | LONG_TAIL |
| 17 | Gurav | 32 | 1.0% | 17 | LONG_TAIL |
| 18 | Jain | 30 | 0.9% | 18 | PREMIUM |
| 19 | Nhavi | 29 | 0.9% | 19 | LONG_TAIL |
| 20 | Sutar | 29 | 0.9% | 20 | LONG_TAIL |
| — | *50+ additional castes* | *<28 each* | *<0.8% each* | — | LONG_TAIL |

**Meta Insight:** Brahmin market (3,318) is 2.9× larger than the next biggest segment (Maratha 1,160) in this age/height filter. This indicates Brahmin women are disproportionately represented on this platform within the filtered range, making this a dense, highly competitive within-caste marriage search.

**Strategic Implication:** The Brahmin market IS the market in this slice. Maratha at 1,160 is a viable adjacent segment for profile owners open to inter-caste matches.

---

## 6. SUB-CASTE (ACTIVE MARKET DISTRIBUTION)

> All 3,318 profiles are Brahmin. Sub-caste reflects the internal community distribution.

| # | Sub-Caste | Count | % of Total | Rank | Cumulative % | Tag |
|---|-----------|-------|------------|------|--------------|-----|
| 1 | Deshastha Rigwedi | 1,241 | 37.4% | 1 | 37.4% | HIGH_SIGNAL / SATURATED |
| 2 | Deshastha Yajurwedi | 825 | 24.9% | 2 | 62.3% | HIGH_SIGNAL |
| 3 | Kokanastha (Chitpavan) | 559 | 16.8% | 3 | 79.1% | HIGH_SIGNAL |
| 4 | Karhade | 161 | 4.9% | 4 | 84.0% | NICHE_CLUSTER |
| 5 | Brahmin (unspecified) | 119 | 3.6% | 5 | 87.6% | NICHE_CLUSTER |
| 6 | Goud Saraswat Brahmin (GSB) | 98 | 3.0% | 6 | 90.5% | PREMIUM |
| 7 | Brahmin Vaishnav | 29 | 0.9% | 7 | 91.4% | NICHE_CLUSTER |
| 8 | Devrukhe Brahmin | 22 | 0.7% | 8 | 92.1% | NICHE_CLUSTER |
| 9 | Kanva | 18 | 0.5% | 9 | 92.6% | LONG_TAIL |
| 10 | Kannada Brahmins | 8 | 0.2% | 10 | 92.9% | LONG_TAIL |
| 11 | Lad Brahmin | 8 | 0.2% | 11 | 93.1% | LONG_TAIL |
| 12 | Parashar | 5 | 0.2% | 12 | 93.2% | LONG_TAIL |
| 13 | Bengali Brahmin | 2 | 0.06% | 13 | 93.3% | LONG_TAIL |
| 14 | Shaiva Brahmin | 2 | 0.06% | 14 | 93.3% | LONG_TAIL |
| 15 | ChitrapurSaraswat Brahmin | 1 | 0.03% | 15 | — | LONG_TAIL |
| 16 | Sanadhya Brahmin | 1 | 0.03% | 16 | — | LONG_TAIL |
| — | **Not specified** | **219** | **6.6%** | — | — | NICHE_CLUSTER |
| | **TOTAL** | **3,318** | **100%** | | | |

### Sub-Caste Cluster Summary
| Cluster | Sub-castes | Total Count | % Market |
|---------|-----------|-------------|----------|
| **Deshastha** | Rigwedi + Yajurwedi | 2,066 | 62.3% |
| **Kokanastha** | Chitpavan | 559 | 16.8% |
| **Karhade** | Karhade | 161 | 4.9% |
| **GSB** | GSB + ChitrapurSaraswat | 99 | 3.0% |
| **Vaishnav** | Brahmin Vaishnav | 29 | 0.9% |
| **South Indian** | Kannada, Kanva, Bengali | 26 | 0.8% |
| **Unspecified/Other** | — | 338 | 10.2% |

**Meta Insight:**  
- **Deshastha dominance is overwhelming.** 6 in 10 profiles are Deshastha, making this effectively a Deshastha matrimonial pool with Kokanastha as a strong secondary bloc.
- **Kokanastha (Chitpavan) cluster** (559 = 16.8%) is historically associated with Pune, intelligence, and progressive values — their city-level distribution likely skews toward Pune/Mumbai/Nagpur.
- **GSB** (98 = 3%) is the coastal-origin, often business-oriented Brahmin cluster. Small but coherent and typically urban/NRI-leaning.
- **The 4-sub-caste Pareto:** Top 4 sub-castes (Deshastha R, Deshastha Y, Kokanastha, Karhade) cover 84% of the market.

**Strategic Implication:** Any profile/campaign optimized for Deshastha compatibility covers 62% of the addressable market. Kokanastha profiles form a distinct secondary cluster with different cultural expectations (more reform-oriented, higher career ambition signaling).

---

## 7. GEOGRAPHY — RESIDENTIAL

### 7A. Residential Country
| # | Country | Count | % of Total | Rank | Cumulative % | Tag |
|---|---------|-------|------------|------|--------------|-----|
| 1 | India | 3,050 | 91.9% | 1 | 91.9% | HIGH_SIGNAL / SATURATED |
| 2 | USA / America | 137 | 4.1% | 2 | 96.0% | PREMIUM |
| 3 | United Kingdom | 41 | 1.2% | 3 | 97.3% | PREMIUM |
| 4 | Canada | 20 | 0.6% | 4 | 97.9% | PREMIUM |
| 5 | Germany | 18 | 0.5% | 5 | 98.4% | NICHE_CLUSTER |
| 6 | Australia | 17 | 0.5% | 6 | 98.9% | NICHE_CLUSTER |
| 7 | U.A.E. | 8 | 0.2% | 7 | 99.1% | NICHE_CLUSTER |
| 8 | Ireland | 3 | 0.09% | 8 | 99.2% | LONG_TAIL |
| 9 | Singapore | 3 | 0.09% | 9 | 99.3% | LONG_TAIL |
| 10 | England | 2 | 0.06% | 10 | — | LONG_TAIL (UK duplicate) |
| 11 | Japan | 2 | 0.06% | 11 | — | LONG_TAIL |
| 12 | The Netherlands | 2 | 0.06% | 12 | — | LONG_TAIL |
| 13–18 | Belgium, Denmark, Finland, France, Malaysia, South Korea | 1 each | <0.03% | — | — | LONG_TAIL |

**NRI Total (Residential): ~268 profiles (8.1%)**

### 7B. Residential State (Top 20)
| # | State | Count | % India-Resident | Tag |
|---|-------|-------|-----------------|-----|
| 1 | Maharashtra | 2,751 | 90.2% | HIGH_SIGNAL / SATURATED |
| 2 | Madhya Pradesh | 95 | 3.1% | NICHE_CLUSTER |
| 3 | Karnataka | 69 | 2.3% | NICHE_CLUSTER |
| 4 | Gujarat | 67 | 2.2% | NICHE_CLUSTER |
| 5 | Telangana | 28 | 0.9% | LONG_TAIL |
| 6 | California (USA) | 20 | — | PREMIUM |
| 7 | England (UK) | 15 | — | PREMIUM |
| 8 | Ontario (Canada) | 15 | — | NICHE_CLUSTER |
| 9 | Texas (USA) | 15 | — | NICHE_CLUSTER |
| 10 | USA (generic) | 15 | — | NICHE_CLUSTER |
| 11 | Washington (USA) | 13 | — | NICHE_CLUSTER |
| 12 | New Jersey (USA) | 12 | — | NICHE_CLUSTER |
| 13 | London (UK) | 11 | — | PREMIUM |
| 14 | Massachusetts (USA) | 11 | — | PREMIUM |
| 15 | New York (USA) | 10 | — | PREMIUM |
| 16 | Chhattisgarh | 9 | 0.3% | LONG_TAIL |
| 17 | UK (generic) | 8 | — | LONG_TAIL |
| 18 | Dubai | 7 | — | NICHE_CLUSTER |
| 19 | Delhi | 6 | 0.2% | LONG_TAIL |
| 20 | Haryana | 6 | 0.2% | LONG_TAIL |

### 7C. Residential City (Top 30)
| # | City | Count | % of Total | % India-Resident | Rank | Cumulative % | Tag |
|---|------|-------|------------|-----------------|------|--------------|-----|
| 1 | **Pune** | 1,082 | 32.6% | 35.5% | 1 | 32.6% | HIGH_SIGNAL / SATURATED |
| 2 | Mumbai | 247 | 7.4% | 8.1% | 2 | 40.0% | HIGH_SIGNAL |
| 3 | Nagpur | 195 | 5.9% | 6.4% | 3 | 45.9% | HIGH_SIGNAL |
| 4 | Chhatrapati Sambhajinagar (Aurangabad) | 161 | 4.9% | 5.3% | 4 | 50.7% | HIGH_SIGNAL |
| 5 | Thane | 123 | 3.7% | 4.0% | 5 | 54.4% | HIGH_SIGNAL |
| 6 | Nashik | 114 | 3.4% | 3.7% | 6 | 57.9% | NICHE_CLUSTER |
| 7 | Kolhapur | 58 | 1.7% | 1.9% | 7 | 59.6% | NICHE_CLUSTER |
| 8 | Bengaluru | 49 | 1.5% | 1.6% | 8 | 61.1% | NICHE_CLUSTER |
| 9 | Dombivli | 43 | 1.3% | 1.4% | 9 | 62.4% | NICHE_CLUSTER |
| 10 | Pimpri-Chinchwad | 43 | 1.3% | 1.4% | 10 | 63.7% | NICHE_CLUSTER |
| 11 | Indore | 40 | 1.2% | 1.3% | 11 | 64.9% | NICHE_CLUSTER |
| 12 | Sangli | 40 | 1.2% | 1.3% | 12 | 66.1% | NICHE_CLUSTER |
| 13 | Solapur | 40 | 1.2% | 1.3% | 13 | 67.3% | NICHE_CLUSTER |
| 14 | Kalyan | 36 | 1.1% | 1.2% | 14 | 68.4% | NICHE_CLUSTER |
| 15 | Vadodara | 36 | 1.1% | 1.2% | 15 | 69.5% | NICHE_CLUSTER |
| 16 | Latur | 35 | 1.1% | 1.1% | 16 | 70.5% | NICHE_CLUSTER |
| 17 | Hyderabad | 32 | 1.0% | 1.0% | 17 | 71.5% | NICHE_CLUSTER |
| 18 | Nanded | 31 | 0.9% | 1.0% | 18 | 72.5% | LONG_TAIL |
| 19 | Amravati | 30 | 0.9% | 1.0% | 19 | 73.4% | LONG_TAIL |
| 20 | Ahilyanagar | 29 | 0.9% | 1.0% | 20 | 74.2% | LONG_TAIL |
| 21 | Akola | 24 | 0.7% | 0.8% | 21 | 75.0% | LONG_TAIL |
| 22 | Jalgaon | 24 | 0.7% | 0.8% | 22 | 75.7% | LONG_TAIL |
| 23 | Navi Mumbai | 22 | 0.7% | 0.7% | 23 | 76.4% | LONG_TAIL |
| 24 | Parbhani | 21 | 0.6% | 0.7% | 24 | 77.0% | LONG_TAIL |
| 25 | USA (generic) | 15 | 0.5% | — | 25 | 77.5% | LONG_TAIL |
| 26 | Karad | 17 | 0.5% | 0.6% | 26 | 78.0% | LONG_TAIL |
| 27 | Satara | 17 | 0.5% | 0.6% | 27 | 78.5% | LONG_TAIL |
| 28 | Bhopal | 16 | 0.5% | 0.5% | 28 | 79.0% | LONG_TAIL |
| 29 | Ratnagiri | 16 | 0.5% | 0.5% | 29 | 79.5% | LONG_TAIL |
| 30 | London | 13 | 0.4% | — | 30 | 79.9% | PREMIUM |

### Pune-Mumbai Corridor Analysis
| Area | Count | % Total |
|------|-------|---------|
| Pune city | 1,082 | 32.6% |
| Pimpri-Chinchwad | 43 | 1.3% |
| Mumbai | 247 | 7.4% |
| Thane | 123 | 3.7% |
| Dombivli | 43 | 1.3% |
| Navi Mumbai | 22 | 0.7% |
| Kalyan | 36 | 1.1% |
| **Corridor Total** | **~1,596** | **~48.1%** |

> Nearly half the market lives in the Mumbai–Pune corridor.

---

## 8. GEOGRAPHY — NATIVE / ORIGIN

> "Country/State/City" fields (as opposed to "Residential") represent home origin.

### 8A. Native Country
| # | Country | Count | % Total | vs. Residential | Tag |
|---|---------|-------|---------|-----------------|-----|
| 1 | India | 2,765 | 83.3% | −285 vs residential | HIGH_SIGNAL |
| 2 | USA / America | 266 | 8.0% | +129 vs residential | PREMIUM |
| 3 | United Kingdom | 81 | 2.4% | +40 vs residential | PREMIUM |
| 4 | Germany | 34 | 1.0% | +16 vs residential | NICHE_CLUSTER |
| 5 | Australia | 33 | 1.0% | +16 vs residential | NICHE_CLUSTER |
| 6 | Canada | 33 | 1.0% | +13 vs residential | NICHE_CLUSTER |
| 7 | Ireland | 12 | 0.4% | +9 vs residential | LONG_TAIL |
| 8 | Japan | 5 | 0.2% | +3 vs residential | LONG_TAIL |
| 9 | U.A.E. | 5 | 0.2% | −3 vs residential | LONG_TAIL |
| 10 | Singapore | 4 | 0.1% | +1 vs residential | LONG_TAIL |
| — | Italy, New Zealand, Poland, South Korea, Netherlands | 2 each | — | — | LONG_TAIL |
| — | Belgium, Denmark, Finland, Malaysia, Turkey | 1 each | — | — | LONG_TAIL |

**Key Divergence: USA native (266) >> USA residential (137)**  
→ ~129 profiles claim USA origin but don't currently live there. This likely represents Return NRIs — people who were raised/educated in the US but have come back to India, a highly desirable demographic segment.

### 8B. Native State (Top 20)
| # | State | Count | vs. Residential Count | Tag |
|---|-------|-------|----------------------|-----|
| 1 | Maharashtra | 2,386 | −365 from residential | HIGH_SIGNAL |
| 2 | Karnataka | 167 | +98 from residential | NICHE_CLUSTER |
| 3 | Telangana | 64 | +36 from residential | NICHE_CLUSTER |
| 4 | Gujarat | 50 | +−17 from residential | NICHE_CLUSTER |
| 5 | California | 46 | +26 from residential | PREMIUM |
| 6 | England | 46 | +31 from residential | PREMIUM |
| 7 | New York | 30 | +20 from residential | PREMIUM |
| 8 | Madhya Pradesh | 27 | −68 from residential | LONG_TAIL |
| 9 | Ontario | 25 | +10 from residential | NICHE_CLUSTER |
| 10 | Texas | 25 | +10 from residential | NICHE_CLUSTER |
| 11 | Massachusetts | 23 | +12 from residential | PREMIUM |
| 12 | Washington | 23 | +10 from residential | NICHE_CLUSTER |
| 13 | London | 18 | +7 from residential | PREMIUM |
| 14 | New Jersey | 18 | +6 from residential | NICHE_CLUSTER |
| 15 | Delhi | 15 | +9 from residential | NICHE_CLUSTER |
| 16 | Tamil Nadu | 13 | +10 from residential | NICHE_CLUSTER |
| 17 | Victoria | 13 | +8 from residential | LONG_TAIL |
| 18 | Haryana | 11 | +5 from residential | LONG_TAIL |
| 19 | Leinster (Ireland) | 10 | +8 from residential | LONG_TAIL |
| 20 | Illinois | 8 | +3 from residential | LONG_TAIL |

### 8C. Native City (Top 30)
| # | City | Count | % Total | vs. Residential | Tag |
|---|------|-------|---------|----------------|-----|
| 1 | **Pune** | 1,372 | 41.3% | +290 vs residential | HIGH_SIGNAL |
| 2 | Mumbai | 468 | 14.1% | +221 vs residential | HIGH_SIGNAL |
| 3 | Bengaluru | 159 | 4.8% | +110 vs residential | PREMIUM |
| 4 | Nagpur | 102 | 3.1% | −93 vs residential | NICHE_CLUSTER |
| 5 | Aurangabad | 65 | 2.0% | −96 vs residential | NICHE_CLUSTER |
| 6 | Hyderabad | 65 | 2.0% | +33 vs residential | NICHE_CLUSTER |
| 7 | Navi Mumbai | 55 | 1.7% | +33 vs residential | NICHE_CLUSTER |
| 8 | Thane | 47 | 1.4% | −76 vs residential | NICHE_CLUSTER |
| 9 | Nashik | 42 | 1.3% | −72 vs residential | NICHE_CLUSTER |
| 10 | London | 31 | 0.9% | +18 vs residential | PREMIUM |
| 11 | Kolhapur | 26 | 0.8% | −32 vs residential | LONG_TAIL |
| 12 | New York City | 26 | 0.8% | +21 vs residential | PREMIUM |
| 13 | Boston | 20 | 0.6% | +9 vs residential | PREMIUM |
| 14 | Ahmedabad | 19 | 0.6% | +5 vs residential | LONG_TAIL |
| 15 | Vadodara | 19 | 0.6% | −17 vs residential | LONG_TAIL |
| 16 | Indore | 17 | 0.5% | −23 vs residential | LONG_TAIL |
| 17 | Solapur | 17 | 0.5% | −23 vs residential | LONG_TAIL |
| 18 | Toronto | 17 | 0.5% | +9 vs residential | PREMIUM |
| 19 | Sangli | 15 | 0.5% | −25 vs residential | LONG_TAIL |
| 20 | Chennai | 13 | 0.4% | +11 vs residential | NICHE_CLUSTER |
| 21 | Melbourne | 13 | 0.4% | +8 vs residential | PREMIUM |
| 22 | Dallas | 12 | 0.4% | +5 vs residential | NICHE_CLUSTER |
| 23 | Seattle | 12 | 0.4% | +2 vs residential | NICHE_CLUSTER |
| 24 | Sydney | 12 | 0.4% | +7 vs residential | PREMIUM |
| 25 | Ahilyanagar | 11 | 0.3% | — | LONG_TAIL |
| 26 | Dublin | 11 | 0.3% | +8 vs residential | LONG_TAIL |
| 27 | Pimpri-Chinchwad | 11 | 0.3% | −32 vs residential | LONG_TAIL |
| 28 | Austin | 10 | 0.3% | +7 vs residential | NICHE_CLUSTER |
| 29 | Kalyan | 9 | 0.3% | −27 vs residential | LONG_TAIL |
| 30 | Ratnagiri | 9 | 0.3% | −7 vs residential | LONG_TAIL |

**Key Divergence Insight:**  
- **Pune native (1,372) >> Pune resident (1,082):** ~290 Pune-origin profiles now live elsewhere — likely in Bengaluru, NCR, abroad, or Mumbai  
- **Mumbai native (468) >> Mumbai resident (247):** ~221 Mumbai-origin profiles dispersed to other cities/countries (tech corridors, NRI)  
- **Bengaluru: native 159 << resident 49 (origin), BUT native 159 >> residential 49:** Bengaluru is ATTRACTING profiles from other native cities

---

## 9. EDUCATION

### 9A. By Field
| # | Field | Count | % Total | Rank | Cumulative % | Tag |
|---|-------|-------|---------|------|--------------|-----|
| 1 | Engineering / Technology | 781 | 23.5% | 1 | 23.5% | HIGH_SIGNAL / SATURATED |
| 2 | Computer / IT | 430 | 13.0% | 2 | 36.5% | HIGH_SIGNAL |
| 3 | Medicine | 350 | 10.5% | 3 | 47.0% | HIGH_SIGNAL |
| 4 | Management | 311 | 9.4% | 4 | 56.4% | HIGH_SIGNAL |
| 5 | Science | 211 | 6.4% | 5 | 62.7% | NICHE_CLUSTER |
| 6 | Commerce | 194 | 5.8% | 6 | 68.6% | NICHE_CLUSTER |
| 7 | Others | 156 | 4.7% | 7 | 73.3% | NICHE_CLUSTER |
| 8 | Finance | 142 | 4.3% | 8 | 77.6% | NICHE_CLUSTER |
| 9 | Architecture | 133 | 4.0% | 9 | 81.6% | NICHE_CLUSTER |
| 10 | Law | 120 | 3.6% | 10 | 85.2% | NICHE_CLUSTER |
| 11 | CA / ICWA / CS / CFA | 101 | 3.0% | 11 | 88.2% | NICHE_CLUSTER |
| 12 | Arts | 94 | 2.8% | 12 | 91.1% | NICHE_CLUSTER |
| 13 | Pharmacology | 44 | 1.3% | 13 | 92.4% | LONG_TAIL |
| 14 | Advertising / Marketing | 43 | 1.3% | 14 | 93.7% | LONG_TAIL |
| 15 | Nursing / Health Science | 35 | 1.1% | 15 | 94.7% | LONG_TAIL |
| 16 | Social Sciences | 33 | 1.0% | 16 | 95.7% | LONG_TAIL |
| 17 | Hospitality / Hotel Management | 27 | 0.8% | 17 | 96.5% | LONG_TAIL |
| 18 | Fine Arts | 23 | 0.7% | 18 | 97.2% | LONG_TAIL |
| 19 | Journalism / Mass Media | 22 | 0.7% | 19 | 97.9% | LONG_TAIL |
| 20 | Education | 18 | 0.5% | 20 | 98.4% | LONG_TAIL |
| 21 | Fashion | 15 | 0.5% | 21 | 98.9% | LONG_TAIL |
| 22 | Visual Effects / Animation | 11 | 0.3% | 22 | 99.2% | LONG_TAIL |
| 23 | Administrative Services | 6 | 0.2% | 23 | 99.4% | LONG_TAIL |
| 24 | Home Science | 5 | 0.2% | 24 | 99.6% | LONG_TAIL |
| 25 | UPSC / MPSC | 3 | 0.09% | 25 | 99.7% | LONG_TAIL |
| 26 | Aviation / Pilot | 2 | 0.06% | 26 | 99.8% | LONG_TAIL |

**Education Cluster Summary:**
| Cluster | Fields | Total | % |
|---------|--------|-------|---|
| STEM | Engineering + Computer + Medicine + Science | 1,772 | 53.4% |
| Business | Management + Commerce + Finance + CA | 748 | 22.5% |
| Creative/Professional | Architecture + Arts + Law + Advertising + Fine Arts | 413 | 12.4% |
| Health | Nursing + Pharmacology | 79 | 2.4% |
| Other | Remaining | 298 | 9.0% |

### 9B. By Degree Level
| # | Level | Count | % Total | Rank | Cumulative % | Tag |
|---|-------|-------|---------|------|--------------|-----|
| 1 | Post Graduate | 1,699 | 51.2% | 1 | 51.2% | HIGH_SIGNAL |
| 2 | Graduate | 1,286 | 38.8% | 2 | 90.0% | HIGH_SIGNAL |
| 3 | International Degree | 270 | 8.1% | 3 | 98.1% | PREMIUM |
| 4 | Undergraduate | 29 | 0.9% | 4 | 99.0% | LONG_TAIL |
| 5 | PhD | 15 | 0.5% | 5 | 99.4% | UNDEREXPLORED |
| 6 | Diploma | 11 | 0.3% | 6 | 99.7% | LONG_TAIL |

**Meta Insight:** 51.2% are Post-Graduate — well above the national average. Combined with 8.1% International Degree holders, roughly 60% of this market has graduate-level or higher education, making this an exceptionally qualified cohort.

**Strategic Implication:** For a partner seeking educational compatibility, this market is elite by population-level standards. PhD (15) is surprisingly low — high achievers may not be on matrimonial platforms yet.

---

## 10. CAREER & PROFESSION

### 10A. Working Field
| # | Field | Count | % Total | Rank | Cumulative % | Tag |
|---|-------|-------|---------|------|--------------|-----|
| 1 | Private Sector | 1,553 | 46.8% | 1 | 46.8% | HIGH_SIGNAL / SATURATED |
| 2 | MNC | 660 | 19.9% | 2 | 66.7% | HIGH_SIGNAL |
| 3 | Professional | 301 | 9.1% | 3 | 75.8% | NICHE_CLUSTER |
| 4 | Student | 185 | 5.6% | 4 | 81.3% | NICHE_CLUSTER |
| 5 | Business / Self Employed | 145 | 4.4% | 5 | 85.7% | NICHE_CLUSTER |
| 6 | Other | 141 | 4.2% | 6 | 90.0% | NICHE_CLUSTER |
| 7 | Govt. / Public | 100 | 3.0% | 7 | 93.0% | NICHE_CLUSTER |
| 8 | Research | 92 | 2.8% | 8 | 95.8% | UNDEREXPLORED |
| 9 | Jobseeker | 66 | 2.0% | 9 | 97.7% | LONG_TAIL |
| 10 | Scientist | 10 | 0.3% | 10 | 98.0% | UNDEREXPLORED |
| 11 | Military / Defense | 2 | 0.06% | 11 | 98.1% | LONG_TAIL |

**Private + MNC = 2,213 (66.7%)** — overwhelmingly corporate professional market.

### 10B. Occupation
| # | Occupation | Count | % Total | Rank | Cumulative % | Tag |
|---|-----------|-------|---------|------|--------------|-----|
| 1 | Employee | 1,241 | 37.4% | 1 | 37.4% | HIGH_SIGNAL |
| 2 | Engineer / Architect | 543 | 16.4% | 2 | 53.8% | HIGH_SIGNAL |
| 3 | Doctor | 223 | 6.7% | 3 | 60.5% | PREMIUM |
| 4 | Other | 182 | 5.5% | 4 | 66.0% | — |
| 5 | Professionals | 149 | 4.5% | 5 | 70.5% | NICHE_CLUSTER |
| 6 | Student | 124 | 3.7% | 6 | 74.2% | NICHE_CLUSTER |
| 7 | Architect | 91 | 2.7% | 7 | 76.9% | NICHE_CLUSTER |
| 8 | Consultant | 85 | 2.6% | 8 | 79.5% | NICHE_CLUSTER |
| 9 | Lawyer | 81 | 2.4% | 9 | 81.9% | PREMIUM |
| 10 | CA / ICWA / CS | 79 | 2.4% | 10 | 84.3% | PREMIUM |
| 11 | Jobseeker | 71 | 2.1% | 11 | 86.4% | LONG_TAIL |
| 12 | Professor / Teacher | 70 | 2.1% | 12 | 88.5% | NICHE_CLUSTER |
| 13 | Dentist | 62 | 1.9% | 13 | 90.4% | PREMIUM |
| 14 | Self Employed | 53 | 1.6% | 14 | 91.9% | NICHE_CLUSTER |
| 15 | Business | 51 | 1.5% | 15 | 93.5% | NICHE_CLUSTER |
| 16 | Service + Business | 48 | 1.4% | 16 | 94.9% | NICHE_CLUSTER |
| 17 | Research Fellow | 43 | 1.3% | 17 | 96.2% | UNDEREXPLORED |
| 18 | Artist | 26 | 0.8% | 18 | 97.0% | LONG_TAIL |
| 19 | Gov. Servant | 25 | 0.8% | 19 | 97.7% | LONG_TAIL |
| 20 | Journalist / Reporter | 6 | 0.2% | 20 | 97.9% | LONG_TAIL |
| 21 | Military Services | 2 | 0.06% | 21 | — | LONG_TAIL |

**Professional Cluster Summary:**
| Cluster | Occupations | Count | % |
|---------|------------|-------|---|
| Medical | Doctor + Dentist | 285 | 8.6% |
| Legal/Financial | Lawyer + CA | 160 | 4.8% |
| Engineering | Engineer/Architect + Architect | 634 | 19.1% |
| Corporate | Employee + Consultant + S+B | 1,374 | 41.4% |
| Academic | Professor/Teacher + Research Fellow + Student | 237 | 7.1% |

---

## 11. FAMILY FINANCIAL STATUS

| # | Status | Count | % Total | Rank | Cumulative % | Tag |
|---|--------|-------|---------|------|--------------|-----|
| 1 | Upper Middle Class | 1,559 | 47.0% | 1 | 47.0% | HIGH_SIGNAL |
| 2 | Middle Class | 1,097 | 33.1% | 2 | 80.0% | HIGH_SIGNAL |
| 3 | Do Not Want to Disclose | 291 | 8.8% | 3 | 88.8% | NICHE_CLUSTER |
| 4 | Affluent | 185 | 5.6% | 4 | 94.4% | PREMIUM |
| 5 | Elite Class | 33 | 1.0% | 5 | 95.4% | PREMIUM / UNDEREXPLORED |
| 6 | Lower Middle Class | 7 | 0.2% | 6 | 95.6% | LONG_TAIL |
| — | Not Disclosed / Not Shown | 146 | 4.4% | — | — | — |

**Wealth Tier Summary:**
| Tier | Count | % Classified |
|------|-------|-------------|
| Upper (Elite + Affluent + Upper Middle) | 1,777 | 61.7% |
| Middle | 1,097 | 38.1% |
| Lower Middle | 7 | 0.2% |
*Base for % classified: 2,881 (excluding undisclosed)*

**Meta Insight:** This is a decidedly upper-middle-class market. "Elite Class" (33 = 1%) is a small but significant cluster — likely urban, NRI, or business families. The 291 who chose "Do Not Want to Disclose" are statistically likely to be affluent (social signaling behavior).

---

## 12. LIFESTYLE

### 12A. Diet
| # | Diet Type | Count | % Total | Rank | Cumulative % | Tag |
|---|-----------|-------|---------|------|--------------|-----|
| 1 | Vegetarian | 2,148 | 64.7% | 1 | 64.7% | HIGH_SIGNAL |
| 2 | Non-Veg Occasionally | 587 | 17.7% | 2 | 82.4% | NICHE_CLUSTER |
| 3 | Eggetarian | 386 | 11.6% | 3 | 94.0% | NICHE_CLUSTER |
| 4 | Non-Veg Frequently | 138 | 4.2% | 4 | 98.2% | LONG_TAIL |
| 5 | Others (Jain / Vegan) | 1 | 0.03% | 5 | — | LONG_TAIL |
| — | Not filled | 58 | 1.7% | — | — | — |

**Effectively Non-Veg (Occ + Freq) = 725 (21.9%)**  
**Vegetarian-spectrum (Veg + Eggetarian) = 2,534 (76.4%)**

### 12B. Smoking
| Status | Count | % Total | Tag |
|--------|-------|---------|-----|
| No | 3,260 | 98.2% | HIGH_SIGNAL |
| (Data not shown for Yes) | ~58 | ~1.8% | LONG_TAIL |

### 12C. Alcohol
| Status | Count | % Total | Rank | Tag |
|--------|-------|---------|------|-----|
| No | 3,028 | 91.3% | 1 | HIGH_SIGNAL |
| Occasionally | 227 | 6.8% | 2 | NICHE_CLUSTER |
| Yes | 5 | 0.2% | 3 | LONG_TAIL |
| Not filled | 58 | 1.7% | — | — |

**Meta Insight:** Lifestyle data shows a deeply conservative profile by Indian urban standards. 64.7% vegetarian + 98.2% non-smoker + 91.3% non-drinker creates a "traditional Brahmin lifestyle" dominant cluster. The 6.8% occasional drinker segment is the liberal urban outlier pocket — likely Kokanastha-dominated, Bengaluru/Mumbai-based, MNC-employed.

---

## 13. HOROSCOPE LAYER

### 13A. Mangal (Mars) Status
| # | Status | Count | % Total | Rank | Cumulative % | Tag |
|---|--------|-------|---------|------|--------------|-----|
| 1 | No (Non-Manglik) | 1,940 | 58.5% | 1 | 58.5% | HIGH_SIGNAL |
| 2 | Yes — Saumya | 339 | 10.2% | 2 | 68.7% | NICHE_CLUSTER |
| 3 | Don't Know | 146 | 4.4% | 3 | 73.1% | NICHE_CLUSTER |
| 4 | Yes — Nirdosh | 143 | 4.3% | 4 | 77.4% | NICHE_CLUSTER |
| 5 | Yes | 98 | 3.0% | 5 | 80.4% | NICHE_CLUSTER |
| 6 | Not Available | 24 | 0.7% | 6 | 81.1% | LONG_TAIL |
| — | Not filled | 628 | 18.9% | — | — | — |

**Manglik summary:**  
- Definitely Non-Manglik: 1,940 (58.5%)  
- Definite Manglik (Saumya + Nirdosh + Yes): 580 (17.5%)  
- Unknown / Partial: 798 (24.0%)

### 13B. Rashi (Zodiac Sign)
| # | Rashi | Count | % Total | Rank | vs. Expected (277.5) | Tag |
|---|-------|-------|---------|------|---------------------|-----|
| 1 | Dhanu (Sagittarius) | 302 | 9.1% | 1 | +24.5 | NICHE_CLUSTER |
| 2 | Makar (Capricorn) | 288 | 8.7% | 2 | +10.5 | NICHE_CLUSTER |
| 3 | Vrushchik (Scorpio) | 288 | 8.7% | 3 | +10.5 | NICHE_CLUSTER |
| 4 | Tula (Libra) | 283 | 8.5% | 4 | +5.5 | NICHE_CLUSTER |
| 5 | Sinha (Leo) | 273 | 8.2% | 5 | −4.5 | NICHE_CLUSTER |
| 6 | Kumbh (Aquarius) | 266 | 8.0% | 6 | −11.5 | NICHE_CLUSTER |
| 7 | Mithun (Gemini) | 253 | 7.6% | 7 | −24.5 | NICHE_CLUSTER |
| 8 | Meen (Pisces) | 252 | 7.6% | 8 | −25.5 | NICHE_CLUSTER |
| 9 | Karka (Cancer) | 249 | 7.5% | 9 | −28.5 | NICHE_CLUSTER |
| 10 | Kanya (Virgo) | 239 | 7.2% | 10 | −38.5 | NICHE_CLUSTER |
| 11 | Vrushabh (Taurus) | 235 | 7.1% | 11 | −42.5 | NICHE_CLUSTER |
| 12 | Mesh (Aries) | 222 | 6.7% | 12 | −55.5 | NICHE_CLUSTER |
| — | Not Available | 5 | 0.2% | — | — | LONG_TAIL |
| | **Total** | **3,150** | — | | | |

**Variance range: 302 – 222 = 80 (25.9% spread from mean)**  
Distribution is remarkably even — no single Rashi dominates. Dhanu leads by a modest margin.

### 13C. Nadi
| # | Nadi | Count | % of Filled | Rank | Tag |
|---|------|-------|-------------|------|-----|
| 1 | Madhya | 928 | 33.9% | 1 | HIGH_SIGNAL |
| 2 | Antya | 918 | 33.5% | 2 | HIGH_SIGNAL |
| 3 | Adya | 891 | 32.5% | 3 | HIGH_SIGNAL |
| — | Not Available | 12 | — | — | LONG_TAIL |
| — | Not Filled | ~569 | — | — | — |
| | **Filled Total** | **~2,749** | | | |

**Near-perfectly tripartite distribution** — Nadi matching (same Nadi = incompatibility in tradition) affects 33% of any given pool.

### 13D. Nakshatra (Top 27 Shown)
| # | Nakshatra | Count | % Filled | Rank | Tag |
|---|-----------|-------|----------|------|-----|
| 1 | Swati | 127 | 4.5% | 1 | HIGH_SIGNAL |
| 2 | Anuradha | 125 | 4.4% | 2 | HIGH_SIGNAL |
| 3 | Mul | 124 | 4.3% | 3 | HIGH_SIGNAL |
| 4 | Shravan | 120 | 4.2% | 4 | NICHE_CLUSTER |
| 5 | Rohini | 119 | 4.2% | 5 | NICHE_CLUSTER |
| 6 | Jyeshtha | 118 | 4.1% | 6 | NICHE_CLUSTER |
| 7 | Purvashadha | 118 | 4.1% | 7 | NICHE_CLUSTER |
| 8 | Purva | 115 | 4.0% | 8 | NICHE_CLUSTER |
| 9 | Uttarashadha | 111 | 3.9% | 9 | NICHE_CLUSTER |
| 10 | Ashlesha | 110 | 3.9% | 10 | NICHE_CLUSTER |
| 11 | Dhanishtha | 107 | 3.8% | 11 | NICHE_CLUSTER |
| 12 | Shatataraka | 107 | 3.8% | 12 | NICHE_CLUSTER |
| 13 | Pushya | 104 | 3.6% | 13 | NICHE_CLUSTER |
| 14 | Chitra | 103 | 3.6% | 14 | NICHE_CLUSTER |
| 15 | Ashwini | 102 | 3.6% | 15 | NICHE_CLUSTER |
| 16 | Mruga | 102 | 3.6% | 16 | NICHE_CLUSTER |
| 17 | Vishakha | 102 | 3.6% | 17 | NICHE_CLUSTER |
| 18 | Magha | 101 | 3.5% | 18 | NICHE_CLUSTER |
| 19 | Punarvasu | 101 | 3.5% | 19 | NICHE_CLUSTER |
| 20 | Ardra | 100 | 3.5% | 20 | NICHE_CLUSTER |
| 21 | Hasta | 98 | 3.4% | 21 | NICHE_CLUSTER |
| 22 | Revati | 98 | 3.4% | 22 | NICHE_CLUSTER |
| 23 | Kritika | 95 | 3.3% | 23 | NICHE_CLUSTER |
| 24 | Purvabhadrapada | 93 | 3.3% | 24 | NICHE_CLUSTER |
| 25 | Uttarabhadrapada | 93 | 3.3% | 25 | NICHE_CLUSTER |
| 26 | Uttara | 81 | 2.8% | 26 | NICHE_CLUSTER |
| 27 | Bharani | 79 | 2.8% | 27 | NICHE_CLUSTER |
| | **Total shown** | **2,853** | | | |

Expected per Nakshatra (if uniform): 2,853/27 ≈ 105.7  
Swati leads (127 = 20% above expected). Bharani/Uttara are lowest shown.

---

## 14. CROSS-CUT INSIGHTS

### 14A. Urban Brahmin Clusters
| Cluster | Definition | Est. Size | Signal |
|---------|-----------|-----------|--------|
| **Pune Tech Brahmin** | Pune-resident + Engineering/IT education + Private/MNC | ~380–450 | VERY HIGH |
| **Mumbai Finance Brahmin** | Mumbai-resident + Finance/CA/Management | ~85–110 | HIGH |
| **Bengaluru Migration Cluster** | Bengaluru-resident (native from Pune/Mumbai) + MNC/Tech | ~40–60 | HIGH |
| **NRI USA Premium** | USA-resident + Post-Graduate + MNC | ~80–100 | PREMIUM |
| **Return NRI** | India-resident + USA/UK native origin + Tech | ~100–150 | PREMIUM |
| **Medical Professional** | Doctor/Dentist (285) + Medicine education (350) | ~250–285 | PREMIUM |
| **GSB Coastal Elite** | GSB sub-caste (98) + likely Mumbai/Goa/NRI | ~70–90 | PREMIUM |
| **Kokanastha Liberal** | Kokanastha (559) + Occ. drinker (227) + Urban | ~100–150 | UNDEREXPLORED |

### 14B. Key Cross-Cut Ratios
| Insight | Data |
|---------|------|
| Engineering educated (1,211) but only 543 call themselves Engineers | 55% pivot to "Employee" or management roles |
| Medicine educated (350) but 285 medical professionals identified | 81% conversion — medicine is a committed path |
| Law educated (120) but only 81 lawyers | 32% didn't enter law practice or redefined career |
| Post-Graduate (1,699) + MNC/Professional (961) = probable overlap | ~700–800 MNC professionals are post-graduate |
| Student (185 working field) + Student (124 occupation) = ~150 overlap | ~150 truly still studying; 35–60 "student" may be self-described |

### 14C. NRI Opportunity Map
| Country | Residential | Native | Delta | Interpretation |
|---------|-------------|--------|-------|----------------|
| USA | 137 | 266 | +129 native | 129 Return-NRIs back in India |
| UK | 41 | 81 | +40 native | 40 UK-raised, now India-based |
| Germany | 18 | 34 | +16 native | 16 Germany-origin returnees |
| Australia | 17 | 33 | +16 native | 16 Australia-origin returnees |

**Estimated Return NRI pool: ~200–220 profiles** — highly desirable segment, likely upper-middle class, internationally educated, Indian-values-anchored.

---

## 15. STRATEGIC MATRIX

### Where Competition is Highest (Saturated Zones)
| Zone | Profiles | Why Saturated |
|------|---------|---------------|
| Deshastha + Pune + Engineering | ~350–400 | Most common profile type — hardest to stand out |
| Maharashtra-resident + Never Married + Veg | ~2,000+ | Base majority — undifferentiated |
| Post-Grad + Private Sector + Upper Middle | ~800–1,000 | Bread-and-butter segment |

### Where Leverage Exists (Underexplored Zones)
| Zone | Profiles | Why Valuable |
|------|---------|-------------|
| Return NRI (USA/UK-origin, India-resident) | ~200 | High ambition, globally shaped, India-committed |
| Medical professionals (Doctor + Dentist) | 285 | High stability, well-defined life-timeline, premium status |
| Research / Scientist | 102 | Underrepresented on platforms, high intellect signal |
| Kokanastha + Liberal lifestyle (occ. drink) | ~100 | Urban, progressive, often overlooked in conservative filters |
| GSB cluster | 98 | Coastal, business-oriented, diaspora-connected |
| PhD holders | 15 | Tiny but extreme outlier quality signal |

### Positioning Recommendations
| If you optimize for... | Expected outcome |
|----------------------|-----------------|
| Deshastha Rigwedi match | Access to 37.4% of market (1,241 profiles) — maximum volume |
| Pune geography preference | 32.6% of total in one city — density advantage |
| STEM compatibility | 53.4% coverage — high intellectual match rate |
| Post-graduate education | 59.8% coverage |
| Non-manglik preference | 58.5% compatibility baseline |
| Same Nadi (Adya filter) | Eliminates 33% of pool (Madhya + Antya) — reduces to ~900 compatible |
| Vegetarian lifestyle | 64.7% match vs. 35.3% mismatch — conservative safe play |
| MNC/professional career | 19.9% core, but private sector adds another 46.8% |

---

## 16. TAGS INDEX

| Tag | Meaning | Applied To |
|-----|---------|-----------|
| `HIGH_SIGNAL` | Top 1–3 in category, >15% share, strong strategic relevance | Deshastha, Pune, Maharashtra, Marathi, Private Sector, Veg, Non-smoker, Post-Grad, Engineering |
| `SATURATED` | Dominant but over-competed — diminishing differentiation | Brahmin filter, Maharashtra, Pune, Never Married |
| `PREMIUM` | Small in count but high quality/status signal | GSB, USA-NRI, Doctor/Lawyer, Elite Class, International Degree, London, New York |
| `NICHE_CLUSTER` | Coherent, meaningful sub-group (5–15% range or culturally distinct) | Kokanastha, Karhade, MNC, Medicine, Management, Ahmedabad, Hyderabad |
| `UNDEREXPLORED` | Low platform visibility but high potential value | Research fellows, Scientists, PhD, Return NRIs, Kokanastha liberal cluster |
| `LONG_TAIL` | Count < 20 or < 0.6% of total; retain for completeness but low actionability | Most small cities, rare castes, fringe languages |

---

*End of Market Data Asset — Version 1.0 — Generated April 2026*
*Source: raw_data.md | Filter: Age 24–28, Height 5'0"–5'6", Caste: Brahmin*
