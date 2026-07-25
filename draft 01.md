# The Knowledge–Practice Gap in Islamic Ritual Observance: A Cross-Sectional Study of Wudu Knowledge, Visible Practice, and Mosque-Level Teaching Exposure in Riyadh

**Status:** Draft proposal — pre-pilot
**Author:** Omar
**Location scope:** Riyadh, Kingdom of Saudi Arabia

---

## 1. Background and Rationale

Knowledge-Attitude-Practice (KAP) study designs are well established in Saudi public health and social science literature — applied to domains such as infection control, diabetes, oral health, and medication use. No comparable instrument has been systematically applied to **Islamic ritual knowledge and practice** in the Saudi context, despite validated precedents elsewhere:

- **KPMIR** (Knowledge-Practice Measure of Islamic Religiosity) — 100-item scale, US Muslim students, found knowledge scores correlated with years of Islamic schooling (α = .92).
- **HIRS96** (Hatta Islamic Religiosity Scale) — Malaysia, splits knowledge (15 items) and practice (10 items) into separate scored constructs.
- Broader Muslim Religiosity Scales (e.g., Mohd Mahudin et al., 2016) treat belief, practice, and experience as distinct dimensions.

**Personal observation motivating this study:** anecdotal experience suggests that visible markers of sunnah practice (beard, regular attendance, etc.) may correlate with — but do not fully explain — correct procedural knowledge of obligatory acts such as wudu (e.g., istinshaq / nasal rinsing). Additionally, informal observation suggests that mosques where imams incorporate regular post-salah reminders or structured teaching may produce congregants with measurably higher knowledge scores, independent of individual practice/compliance level.

This is framed explicitly as a **personal observation motivating the research question**, not as an established finding. No claimed statistic (e.g. "70% of...") is used without being the study's own measured output.

## 2. Research Gap

No existing published KAP-style instrument measures the relationship between:
1. Individual religious knowledge (specifically procedural fiqh knowledge, e.g. correct wudu execution)
2. Individual visible practice/compliance markers
3. Mosque-level teaching exposure (imam-provided religious education, formal or informal)

...within a single integrated design, in the Saudi/Riyadh context.

## 3. Research Questions

**RQ1:** What is the level of correct knowledge of obligatory and sunnah wudu procedures among Muslim mosque-goers in Riyadh?

**RQ2:** Is there a measurable relationship between visible sunnah-practice markers and correct ritual knowledge?

**RQ3:** Does mosque-level imam teaching exposure (frequency/format of religious instruction) predict individual knowledge scores, independent of individual practice level?

**RQ4:** Do knowledge and practice scores vary by nationality/language group, controlling for education and mosque?

## 4. Hypotheses

- **H1:** Practice-compliance score positively correlates with wudu-knowledge score.
- **H2:** Mosque-level teaching exposure (imam variable) positively predicts individual knowledge scores, after controlling for individual practice level and demographics.
- **H3:** Non-Arabic-speaking respondents will show lower knowledge scores than Arabic-speaking respondents, independent of practice level, due to language access to source material rather than religious commitment differences.

## 5. Study Design

**Type:** Cross-sectional, two-level (individual nested within mosque) survey study.

**Population:** Adult Muslim men attending congregational prayer at mosques in Riyadh.
*(Note: scope currently limited to men due to fieldwork access via mosque prayer halls; women's data collection would require a separate access strategy — flag as a limitation or a phase-2 extension.)*

## 6. Sampling Strategy

### 6.1 Geographic sampling
Riyadh is divided into **15 sub-municipalities (baladiyahs)** covering ~150+ neighborhoods. Rather than attempting full neighborhood coverage (impractical for a single researcher), sampling will be **stratified by baladiyah**:

- Select **2 mosques per baladiyah** (~30 mosques total)
  - 1 larger/central jami' mosque
  - 1 smaller neighborhood masjid
- This preserves geographic and socioeconomic diversity (old vs. new districts, north–south income gradient, expat-dense vs. Saudi-dense areas) without requiring ~150 site visits.

### 6.2 Timing of data collection
Spread across **Dhuhr, Asr, Maghrib, and Jumu'ah** prayers — not Jumu'ah alone, which biases toward more religiously engaged attendees and inflates practice/knowledge scores.

### 6.3 Sample size
Using Cochran's formula (95% CI, ±5% margin, p = 0.5 conservative):
- Baseline requirement: **n ≈ 385**
- Adjusted for cluster design effect (1.5–2x, since respondents within a mosque are not fully independent): **target n ≈ 600–700**
- Per mosque: ~20 completed surveys × 30 mosques = 600

## 7. Variables

### 7.1 Individual-level (respondent survey)
| Variable | Type | Notes |
|---|---|---|
| Wudu knowledge score | Outcome | Multiple-choice/scenario items on fard + sunnah acts, incl. istinshaq |
| Visible practice index | Predictor | Composite: beard, garment length, mosque attendance frequency, siwak use |
| Nationality/language group | Covariate | Grouped: Saudi / GCC / Arab expat / Non-Arab Muslim expat |
| Age | Covariate | |
| Education level | Covariate | |
| Years attending current mosque | Covariate | Exposure duration to imam's teaching style |

### 7.2 Mosque-level (imam questionnaire — one per mosque)
| Variable | Type | Notes |
|---|---|---|
| Teaching frequency | Predictor | None / Occasional (post-salah reminders) / Regular structured program |
| Teaching format | Predictor | Hadith-only mention / Short lesson / Dedicated weekly halaqah |
| Topic scope | Predictor | Fiqh-focused / General / Mixed |
| Duration of practice | Covariate | Years this mosque has maintained the teaching habit |

## 8. Instruments

Two linked instruments to be developed:
1. **Respondent survey** — demographics, visible-practice checklist, wudu knowledge items (scenario-based, not just recall), optionally adapted from KPMIR/HIRS96 item structures.
2. **Imam questionnaire** — short structured interview (5–10 min), coded into the categorical variables above, not free narrative.

*(Draft item sets to be developed in a follow-up document once pilot testing confirms question clarity.)*

## 9. Analysis Plan

Because individual observations are nested within mosques (non-independent), a **hierarchical/multilevel linear model (HLM)** is appropriate rather than simple OLS regression:

- Level 1 (individual): knowledge score ~ practice index + nationality group + age + education
- Level 2 (mosque): + imam teaching frequency/format as mosque-level predictors
- Report both individual-level effects and mosque-level (contextual) effects separately.

## 10. Ethical Considerations

- Requires ethics/IRB review (university-affiliated or independent board) even though the survey is anonymous — topic involves religious practice and could be sensitive.
- Mosque access: informal imam agreement may not be sufficient for structured research; recommend clearing data collection through the **Ministry of Islamic Affairs** or relevant municipal religious affairs office rather than mosque-by-mosque only.
- Question framing must avoid judgmental tone (e.g., "do you comply with X" framed neutrally, not as testing piety).
- Informed consent required from all respondents; imam questionnaire responses should be reported at mosque-level/anonymized, not attributed by name in publication.

## 11. Limitations (to state explicitly in the paper)

- Cross-sectional design shows correlation, not causal direction, between practice and knowledge.
- Convenience/cluster sampling of mosque attendees excludes non-mosque-going Muslims entirely — findings apply to mosque-attending population only.
- Gender scope currently limited to men (fieldwork access constraint).
- Self-reported practice measures (e.g., "years attending") may have recall/social-desirability bias.

## 11A. Fiqh Foundation — Establishing the "Correct Answer Key" (Worked Example: Istinshaq)

A KAP survey cannot score knowledge items without first establishing, through proper fiqh methodology (evidence from Qur'an → Sunnah → Ijma' → madhhab comparison → tarjih), what the correct answer actually is. This section is a worked example for **istinshaq** (nasal rinsing), demonstrating the process to be repeated for every knowledge item in the final instrument.

### 11A.1 Definition

**Wudu (linguistic):** derived from *al-wadaa'ah* — cleanliness, radiance, comeliness.
**Wudu (technical/shar'i):** an act of worship (ta'abbud) to Allah consisting of washing specified body parts in a specified manner.

### 11A.2 The Ruling on Istinshaq — Is It Obligatory or Sunnah?

This is the critical point for instrument design: **the obligation status of istinshaq is a genuine point of scholarly difference between the four madhahib**, not a settled fact with one right answer independent of school.

**Position: Istinshaq (and madmadah) are obligatory (wajib) acts of wudu.**
- Held by the Hanbali madhhab, a group of the Salaf, some Zahiris, and adopted by Ibn Taymiyyah, Ibn al-Qayyim, al-Shawkani, Ibn Baz, al-Albani, and Ibn 'Uthaymin.
- **Qur'anic basis:** the general command in Surah al-Ma'idah 6, "O you who believe, when you rise for prayer, wash your faces..." — the mouth and nose are argued to fall within "the face" for this purpose.
- **Sunnah basis:** the well-known hadith describing the Prophet's ﷺ wudu via 'Abdullah ibn Zayd (narrated with the sequence: rinsed the mouth, sniffed water and blew it out, three times, then washed the face) — and the explicit command reported from Abu Hurairah: *"When one of you performs wudu, let him put water in his nose, then blow it out."*
- **Reasoning:** every detailed description of the Prophet's ﷺ wudu includes madmadah and istinshaq, and his consistent practice (mudawamah) on an act, when it stands as a bayan (clarification) of a Qur'anic command, indicates obligation.

**Note for instrument design:** the Hanafi, Maliki, and Shafi'i madhahib generally hold istinshaq to be a strongly emphasized sunnah (sunnah mu'akkadah), not wajib — meaning wudu is technically valid without it in their view, though omitting it is disliked/sinful-adjacent depending on the school.

**Practical resolution for a Saudi-context survey:** Saudi Arabia's official fatwa bodies (dominated by the Hanbali-influenced position of scholars like Ibn Baz and Ibn 'Uthaymin cited above) treat istinshaq as **wajib**. For scoring purposes in a Riyadh-based instrument, this is the appropriate answer key — but the questionnaire should be worded to ask "what is the ruling according to the position most commonly taught in Saudi Arabia" rather than implying it is the only valid position across the Muslim world, since a Hanafi/Maliki/Shafi'i respondent answering "sunnah" is not factually wrong — they are correctly stating their madhhab's view. This distinction should be explicitly built into the item (e.g. as a note or by asking "wajib or sunnah *according to the majority view taught in KSA*") to avoid mis-scoring respondents from other madhahib as "lacking knowledge" when they are actually knowledgeable but from a different school.

### 11A.3 The Correct Method (Sifah) — This Part Is Not Disputed the Same Way

Separate from the wujub/sunnah debate, the **method** of performing istinshaq correctly, once performed, is more consistently agreed upon and is the more useful item for a knowledge test:

- **Combine madmadah and istinshaq from the same handful of water**: take one scoop, use it for both the mouth and nose, repeated three times total — this is the position of the Shafi'i and Hanbali madhahib, one Maliki view (chosen by al-Maziri, Ibn Rushd al-Jadd), and adopted by Ibn Daqiq al-'Eid, Ibn Taymiyyah, Ibn al-Qayyim, Ibn Baz, and Ibn 'Uthaymin.
- **Evidence:** the same 'Abdullah ibn Zayd hadith describing the Prophet's ﷺ wudu: *"He rinsed his mouth and sniffed water into his nose and blew it out, three times, with three scoops of water"* — with another narration specifying *"he rinsed and sniffed from a single handful, doing that three times."*

**This is the stronger candidate for a knowledge-test item** ("How many times should nasal rinsing be performed, and should it be combined with mouth-rinsing or done separately?") since it's less entangled in cross-madhhab dispute than the wajib/sunnah question, and is closer to your original observation about people not knowing "the correct method."

## 11B. Fiqh Foundation — Worked Example 2: Washing the Beard

This is the second original observation motivating the study ("70% who pray have shaved beards / don't know beard-washing rules") — worth separating clearly from the istinshaq item since it turns out to be a **two-part rule**, not a single fact, which matters for how the survey item is worded.

### 11B.1 The Ruling — Thin vs. Thick Beard (Point of Consensus)

Unlike istinshaq's wajib/sunnah dispute, this specific rule **is agreed upon by all four madhahib** — a genuinely settled point, which makes it a clean, unambiguous knowledge-test item:

- **If the beard is thin/sparse** (light enough that the skin underneath is visible through it): the worshipper must wash **both** the visible hair **and** the skin beneath it.
- **If the beard is thick** (skin not visible through it): only the **outer/visible surface** of the beard hair must be washed — reaching the skin underneath is not required.

**Evidence:**
- **Qur'an:** the general command to "wash your faces" (5:6) — the face is defined as the area of *muwajahah* (what faces someone directly); once hair covers that area, the "facing" surface shifts to the visible hair itself.
- **Sunnah:** hadith describing the Prophet's ﷺ wudu as performed "once" (marratan marratan — one scoop per part) via Ibn 'Abbas. The reasoning given: the Prophet ﷺ had a thick beard, and a single scoop could not possibly have washed both the outer hair and the skin beneath a thick beard — so his practice itself demonstrates that only the visible surface was required for thick beards.
- **Analogy:** the eyes are undisputedly part of the face, yet only the visible eyelids need washing, not underneath them — the same logic extends to thick facial hair.

**This is directly usable as-is for a knowledge item**, e.g.: *"If a man has a thick beard, is he required to wash the skin underneath it during wudu?"* (Correct answer: No — only the visible hair.) This is unlikely to be affected by madhhab differences, since it's one of the points explicitly noted as agreed upon by all four schools.

### 11B.2 A Second, Genuinely Disputed Sub-Question: Hair That Extends Below the Face

There's a related but separate point of real khilaf worth knowing about if you want a harder/bonus item: hair that **grows down past the natural boundary of the face** (e.g. a long beard extending well below the chin).

**Position 1 (majority — Maliki, the more correct Shafi'i view, Hanbali):** the visible surface of this overflow hair must also be washed; it's treated as a continuation ("tabi'") of what's already part of the face.

**Position 2 (Hanafi, one Shafi'i view, one Hanbali narration preferred by Ibn Rajab):** not obligatory, since that hair is technically outside the defined boundary of the face and shouldn't be equated with hair still growing within it.

**For instrument design:** if included at all, this should be a separate, clearly-flagged "advanced" item, scored the same way as istinshaq's wajib/sunnah item (i.e., noting it depends on madhhab, with the Hanbali-leaning KSA-taught position as the default key) — not folded into the main thin/thick beard item, which is cleaner and consensus-based.

## 11C. Template for Remaining Knowledge Items

Two more items are now sourced and ready to be written up using the same four-step process when you're ready:
- **Wiping the head (mash al-ra's):** whether the whole head must be wiped vs. part of it (a genuine khilaf — Maliki/Hanbali/some Shafi'i require the whole head; other views allow partial), the correct method (front-to-back-to-front motion, one pass, no repetition — this part is closer to consensus), and whether the ears are wiped as part of the head or separately.
- **Wiping the ears:** whether it's sunnah (Hanafi/Maliki/Shafi'i) or wajib (Hanbali) — another wajib/sunnah-type dispute like istinshaq — plus the agreed-upon method (index fingers inside the ear canal, thumbs on the outer ear).

Every remaining item should go through this same four-step process before being finalized:
1. State the ruling and which madhhab(s) hold it
2. Cite the Qur'anic/Sunnah evidence
3. Note whether it's a point of consensus (ijma') or khilaf (difference) — consensus items make cleaner knowledge-test questions; disputed items need madhhab-aware wording
4. Decide the scoring key based on the position officially taught/fielded in KSA, while flagging genuine cross-madhhab differences so the instrument doesn't penalize correct-but-different-madhhab answers

## 11D. Master Fiqh Answer-Key Reference Table

Consolidated from all sourced material to date. Use this as the master reference when finalizing knowledge-test items — items marked **"Consensus"** make clean, unambiguous questions; items marked **"Khilaf"** need madhhab-aware wording (as discussed for istinshaq's wajib/sunnah status) so the instrument doesn't mis-score a respondent who is correctly following a different madhhab.

| # | Topic | Ruling | Status | Notes for item design |
|---|---|---|---|---|
| 1 | Washing the face | Fard | Consensus | Base obligation, uncontroversial |
| 2 | Beard: thin → wash skin beneath; thick → outer hair only | Fard (as described) | Consensus | Strong candidate — clean item |
| 3 | Washing overflow beard hair (mustarsil) below chin | Disputed | Khilaf | Majority (Maliki/Shafi'i-sahih/Hanbali) require it; Hanafi + one view don't |
| 4 | Madmadah + Istinshaq (the acts themselves) | Wajib vs. Sunnah mu'akkadah | Khilaf | KSA-taught (Ibn Baz/Uthaymin) position: wajib |
| 5 | Method: combine mouth+nose rinse from one scoop, 3x | Sunnah | Near-consensus | Best method-knowledge item (per earlier discussion) |
| 6 | Washing hands/arms to and including elbows | Fard | Consensus | |
| 7 | Wiping the whole head vs. part of it | Whole head required (per some) | Khilaf | Maliki(mashhur)/Hanbali(sahih)/some Shafi'i require whole; others allow partial |
| 8 | Method of head-wipe: front→back→front, one pass | Sunnah | Near-consensus (majority) | Good clean method item |
| 9 | Wiping the ears | Sunnah vs. Wajib | Khilaf | Hanafi/Maliki/Shafi'i: sunnah; Hanbali (+ Ibn Baz/Uthaymin): wajib |
| 10 | Method of ear-wipe: index fingers inside canal, thumbs outside | Sunnah | Consensus (4 madhahib) | Clean method item |
| 11 | Wiping ears with same water as head (no new water) | Sunnah | Majority position | |
| 12 | Wiping over a turban ('imamah) instead of the head | Permitted | Majority of sahabah/tabi'in + Hanbali(mashhur)/Zahiri | Not universal — worth noting as a "did you know" item rather than pass/fail |
| 13 | Wiping over a woman's khimar | Disputed | Khilaf | Jumhur disallow; Hanbali/Zahiri allow |
| 14 | Wiping over a cap (qalansuwah) | Not valid | Consensus (4 madhahib) | |
| 15 | Washing the feet to the ankles | Fard | Consensus | |
| 16 | Tartib — performing limbs in the Qur'anic order | Fard (per some) | Khilaf | Shafi'i/Hanbali/Ibn Hazm/Ibn Baz/Uthaymin: fard; Hanafi/Maliki(mashhur): not required |
| 17 | Muwalat — no significant gap/drying between limbs | Fard (per some) | Khilaf | Maliki(mashhur)/Hanbali: fard; Hanafi/Shafi'i: not required |
| 18 | Tasmiyah (saying "Bismillah") at the start | Sunnah | Near-consensus (jumhur) | Good general-knowledge item |
| 19 | Siwak (tooth-stick) before/during wudu | Sunnah | — | |
| 20 | Washing hands 3x at the very start (non-sleeper) | Sunnah | Consensus | |
| 21 | Mubalaghah — thorough rinsing of mouth/nose (except when fasting) | Sunnah | Consensus (4 madhahib) | Good item — includes the fasting exception, a useful nuance to test |
| 22 | Takhlil (running fingers through) a thick beard | Mustahab | Jumhur | |
| 23 | Takhlil of fingers/toes | Wajib if water otherwise blocked; else mustahab | Jumhur | Conditional rule — good "it depends" item |
| 24 | Method of finger takhlil: interlacing hands | Sunnah | Jumhur | |
| 25 | Moving a tight ring if it blocks water | Wajib if blocks water; else mustahab | Jumhur | |
| 26 | Istinthar (expelling water from nose after istinshaq) | Sunnah | Consensus (4 madhahib) | |
| 27 | Method of istinthar: with the left hand | Sunnah | — | |
| 28 | Tathlith — washing each part 3 times | Sunnah | Consensus (in general) | |
| 29 | Dalk — rubbing limbs while washing, not just pouring | Mustahab | Jumhur | |
| 30 | Tayammun — starting with the right side | Mustahab | Consensus/Ijma' | High-value item — directly tests the "70% miss small sunnahs" hypothesis |
| 31 | Exceeding 3 washes per limb | Makruh (disliked) | Consensus (4 madhahib) | Good "over-doing it" item — many assume more=better |
| 32 | Du'a (shahadah) after completing wudu | Sunnah | — | Very well-known; expect high correct-answer rate — useful as a "ceiling" calibration item |
| 33 | Praying 2 rak'ahs after wudu | Mustahab | Jumhur (Hanafi/Shafi'i/Hanbali) | |
| 34 | Talking during wudu | Permitted (mubah) | Consensus (4 madhahib) | Good "myth-busting" item — many assume silence is required |
| 35 | Getting help from someone else (e.g. pouring water) | Permitted (mubah) | Hanbali + others | |
| 36 | Drying limbs after wudu (tanshif) | Permitted (mubah) | Consensus (4 madhahib, Shafi'i-asahh) | |
| 37 | Making du'a at each individual limb while washing it | **Not prescribed** | Hanbali/Shafi'i + others | Good "innovation-check" item — tests whether people add unprescribed acts |
| 38 | Wiping the neck | **Not prescribed** | Jumhur (Maliki/Shafi'i/Hanbali + one Hanafi view) | Widely practiced misconception in many communities — high-value item |
| 39 | Deliberately extending the wash beyond the required area ("ghurrah/tahjil" extension) | **Not prescribed** | Maliki + one Hanbali riwayah + Ibn Taymiyyah/Baz/Uthaymin | Tests a specific folk belief tied to the "shining light" hadith about wudu marks on Judgment Day |

**Refined hypothesis note (per author clarification):** the original observation is not that visibly-practicing individuals know beard rules better — it's that individuals **lacking a visible practice marker (e.g., no beard)** are hypothesized to be more likely to lack correct knowledge of a *separate* ritual detail: the wajib/sunnah status of istinshaq. In other words, beard presence functions as a general proxy for religious practice engagement, predicted to correlate with knowledge accuracy on an unrelated fiqh item — this is the correlation the H1/H2 hypotheses in Section 4 are testing, and it should be framed this way in the final write-up rather than as "practicing people know their own practice's rules better."

## 11E. Additional Sourced Items (Author-Identified)

Two further knowledge-check candidates, verified against fatwa sources (binbaz.org.sa, islamweb.net):

| # | Topic | Ruling | Status | Notes |
|---|---|---|---|---|
| 40 | Forgetting to say "Bismillah" (tasmiyah) at the start of wudu | Wudu remains valid; no need to repeat | Consensus (follows from #18 — tasmiyah is sunnah, not wajib) | Good misconception-check item — many assume omission invalidates wudu |
| 41 | Does **obligatory** ghusl (janabah, end of menses/nifas) replace the need for a separate wudu? | Yes — if the person intends to lift both the major and minor impurity together, the minor is subsumed within the major | Majority position (Ibn Baz, Ibn 'Uthaymin, jumhur) | The *sunnah* (preferred) method is still to perform a full prayer-wudu before completing the ghusl, as the Prophet ﷺ did — but skipping it and intending both at once is still valid per most scholars |
| 42 | Does **sunnah/mustahab** ghusl (e.g. Friday ghusl, cooling-off ghusl) replace wudu? | **No** — a separate wudu is still required, since no hadath (ritual impurity) is being lifted | Clear, near-consensus position | Common point of confusion — a strong candidate item precisely because the correct answer runs opposite to the common assumption that "any full-body wash covers wudu" |

| 43 | Method of obligatory ghusl (janabah, etc.) | Minimum valid: intention + water covering entire body (hair + skin). Complete/preferred method: wash away impurity → perform full prayer-wudu (feet may be delayed to the end) → pour water over head 3x working into roots → pour over right side, then left → wash feet last if delayed | Minimum = fard (consensus); full sequence = sunnah/mustahab, not itself obligatory | Sourced from Aisha's and Maimunah's descriptions of the Prophet's ﷺ ghusl. Good item precisely because people may assume the *structured* method (wudu-in-the-middle) is itself required, when only intention + full-body coverage is actually fard — everything else is the preferred/complete form |

**Important nuance for item #41/#42 wording:**

 these two must be presented as a linked pair (or as a single item with sub-conditions) in the survey, since the correct answer depends entirely on *which type* of ghusl is meant. A flat "does ghusl replace wudu — yes/no" item would be unscoreable as written; it needs to specify obligatory-vs-sunnah ghusl to have a single correct answer.

**Highest-value items for a first-draft instrument** (mix of consensus items for reliable scoring + a couple of "myth-busting" items likely to show real gaps): #2 (beard), #5 (istinshaq method), #8 (head-wipe method), #21 (mubalaghah + fasting exception), #30 (tayammun/starting right), #31 (exceeding 3x), #34 (talking permitted), #37 (dua at each limb — not prescribed), #38 (wiping neck — not prescribed), #40 (basmala omission), #41/#42 (ghusl-replaces-wudu, linked pair).

This table is the shared answer key both your respondent survey and your own scoring rubric should be built from — worth keeping as a living reference as you draft actual item wording.

## 12. Pilot Study (Recommended Before Full Fielding)

Before full data collection:
- Run a small pilot (20–30 respondents, 2–3 mosques) to:
  - Test question clarity and completion time
  - Get a rough estimate of the knowledge-practice relationship to confirm the hypothesis direction is worth pursuing at scale
  - Refine the imam questionnaire categories based on real variation observed

## 13. Next Steps

- [ ] Draft respondent survey items (adapt from KPMIR/HIRS96 where possible)
- [ ] Draft imam questionnaire
- [ ] Identify ethics review pathway
- [ ] Identify Ministry of Islamic Affairs / municipal contact for mosque access approval
- [ ] Run pilot at 2–3 mosques
- [ ] Refine instruments based on pilot
- [ ] Field full study across 30 mosques

---

## 14. الملحق: النصوص العربية الأصلية للأدلة الشرعية (آيات وأحاديث)

هذا الملحق يجمع النصوص العربية الأصلية للأدلة المستخدمة في بناء "مفتاح الإجابات الفقهي" (القسم 11A–11E)، مرتبة بحسب رقم البند في الجدول الرئيسي (القسم 11D)، مع ذكر المصدر.

### آية الوضوء الأساسية (تُستخدم كدليل لأغلب البنود)

﴿ يَا أَيُّهَا الَّذِينَ آمَنُوا إِذَا قُمْتُمْ إِلَى الصَّلَاةِ فَاغْسِلُوا وُجُوهَكُمْ وَأَيْدِيَكُمْ إِلَى الْمَرَافِقِ وَامْسَحُوا بِرُءُوسِكُمْ وَأَرْجُلَكُمْ إِلَى الْكَعْبَيْنِ وَإِن كُنتُمْ جُنُبًا فَاطَّهَّرُوا ﴾ [المائدة: 6]

المصدر: https://dorar.net/feqhia/236

### البند 2 و3 — غسل اللحية

عَنِ ابْنِ عَبَّاسٍ رَضِيَ اللهُ عَنْهُمَا، قَالَ: ((تَوَضَّأَ النَّبِيُّ صَلَّى اللهُ عَلَيْهِ وَسَلَّمَ مَرَّةً مَرَّةً)).

المصدر: https://dorar.net/feqhia/258

### البند 4 و5 — حكم المضمضة والاستنشاق وصفتهما

عَنْ عَبْدِ اللهِ بْنِ زَيْدٍ رَضِيَ اللهُ عَنْهُ فِي وَصْفِ وُضُوءِ النَّبِيِّ صَلَّى اللهُ عَلَيْهِ وَسَلَّمَ: ((فَمَضْمَضَ وَاسْتَنْشَقَ وَاسْتَنْثَرَ ثَلَاثًا بِثَلَاثِ غَرَفَاتٍ مِنْ مَاءٍ))، وَفِي رِوَايَةٍ: ((مَضْمَضَ وَاسْتَنْشَقَ مِنْ كَفٍّ وَاحِدَةٍ، فَفَعَلَ ذَلِكَ ثَلَاثًا)).

عَنْ أَبِي هُرَيْرَةَ رَضِيَ اللهُ عَنْهُ: أَنَّ رَسُولَ اللهِ صَلَّى اللهُ عَلَيْهِ وَسَلَّمَ قَالَ: ((إِذَا تَوَضَّأَ أَحَدُكُمْ فَلْيَجْعَلْ فِي أَنْفِهِ، ثُمَّ لِيَنْثِرْ)).

المصدر: https://dorar.net/feqhia/258

### البند 8 — صفة مسح الرأس

عَنْ عَمْرِو بْنِ يَحْيَى الْمَازِنِيِّ عَنْ أَبِيهِ، قَالَ: ((شَهِدْتُ عَمْرَو بْنَ أَبِي حَسَنٍ سَأَلَ عَبْدَ اللهِ بْنَ زَيْدٍ عَنْ وُضُوءِ النَّبِيِّ صَلَّى اللهُ عَلَيْهِ وَسَلَّمَ؟ فَدَعَا بِتَوْرٍ مِنْ مَاءٍ، فَتَوَضَّأَ لَهُمْ وُضُوءَ رَسُولِ اللهِ صَلَّى اللهُ عَلَيْهِ وَسَلَّمَ... ثُمَّ أَدْخَلَ يَدَهُ فِي التَّوْرِ فَمَسَحَ رَأْسَهُ، فَأَقْبَلَ بِهِمَا وَأَدْبَرَ مَرَّةً وَاحِدَةً، ثُمَّ غَسَلَ رِجْلَيْهِ)).

المصدر: https://dorar.net/feqhia/271

### البند 9، 10، 11 — مسح الأذنين

عَنِ ابْنِ عَبَّاسٍ رَضِيَ اللهُ عَنْهُمَا: ((أَنَّ رَسُولَ اللهِ صَلَّى اللهُ عَلَيْهِ وَسَلَّمَ مَسَحَ أُذُنَيْهِ دَاخِلَهُمَا بِالسَّبَّابَتَيْنِ، وَخَالَفَ إِبْهَامَيْهِ إِلَى ظَاهِرِ أُذُنَيْهِ، فَمَسَحَ ظَاهِرَهُمَا وَبَاطِنَهُمَا)).

عَنْ عَبْدِ اللهِ بْنِ عُمَرَ رَضِيَ اللهُ عَنْهُمَا: (الْأُذُنَانِ مِنَ الرَّأْسِ).

المصدر: https://dorar.net/feqhia/273 و https://dorar.net/feqhia/277

### البند 21 — المبالغة في المضمضة والاستنشاق

عَنْ لَقِيطِ بْنِ صَبِرَةَ رَضِيَ اللهُ عَنْهُ، قَالَ: ((قُلْتُ: يَا رَسُولَ اللهِ، أَخْبِرْنِي عَنِ الْوُضُوءِ، قَالَ: أَسْبِغِ الْوُضُوءَ، وَخَلِّلْ بَيْنَ الْأَصَابِعِ، وَبَالِغْ فِي الِاسْتِنْشَاقِ إِلَّا أَنْ تَكُونَ صَائِمًا)).

المصدر: https://dorar.net/feqhia/301

### البند 30 — التيامن

عَنْ أَبِي هُرَيْرَةَ رَضِيَ اللهُ عَنْهُ قَالَ: قَالَ رَسُولُ اللهِ صَلَّى اللهُ عَلَيْهِ وَسَلَّمَ: ((إِذَا لَبِسْتُمْ وَإِذَا تَوَضَّأْتُمْ فَابْدَؤُوا بِأَيَامِنِكُمْ)).

عَنْ عَائِشَةَ رَضِيَ اللهُ عَنْهَا قَالَتْ: ((كَانَ النَّبِيُّ صَلَّى اللهُ عَلَيْهِ وَسَلَّمَ يُعْجِبُهُ التَّيَمُّنُ فِي تَنَعُّلِهِ وَتَرَجُّلِهِ وَطُهُورِهِ، وَفِي شَأْنِهِ كُلِّهِ)).

المصدر: https://dorar.net/feqhia/307

### البند 31 — كراهة الزيادة على الثلاث

عَنْ عَمْرِو بْنِ شُعَيْبٍ، عَنْ أَبِيهِ، عَنْ جَدِّهِ، قَالَ: ((جَاءَ أَعْرَابِيٌّ إِلَى النَّبِيِّ صَلَّى اللهُ عَلَيْهِ وَسَلَّمَ يَسْأَلُهُ عَنِ الْوُضُوءِ، فَأَرَاهُ الْوُضُوءَ ثَلَاثًا، ثُمَّ قَالَ: هَكَذَا الْوُضُوءُ، فَمَنْ زَادَ عَلَى هَذَا فَقَدْ أَسَاءَ وَتَعَدَّى وَظَلَمَ)).

المصدر: https://dorar.net/feqhia/311

### البند 34 — إباحة الكلام أثناء الوضوء

عَنْ أُمِّ هَانِئٍ بِنْتِ أَبِي طَالِبٍ رَضِيَ اللهُ عَنْهَا، أَنَّهَا قَالَتْ: ((ذَهَبْتُ إِلَى رَسُولِ اللهِ صَلَّى اللهُ عَلَيْهِ وَسَلَّمَ عَامَ الْفَتْحِ، فَوَجَدْتُهُ يَغْتَسِلُ... فَسَلَّمْتُ عَلَيْهِ، فَقَالَ: مَنْ هَذِهِ؟ فَقُلْتُ: أَنَا أُمُّ هَانِئٍ بِنْتُ أَبِي طَالِبٍ، فَقَالَ: مَرْحَبًا بِأُمِّ هَانِئٍ)).

المصدر: https://dorar.net/feqhia/317

### البند 37 — عدم مشروعية الدعاء عند كل عضو

الأصل في هذا عدم الورود عن رسول الله صلى الله عليه وسلم ولا عن أحد من الصحابة والتابعين؛ وهو مذهب الحنابلة والشافعية، واختيار ابن القيم والصنعاني وابن باز وابن عثيمين.

المصدر: https://dorar.net/feqhia/319

### البند 38 — عدم مشروعية مسح العنق

الدليل: أن الله تعالى لم يأمر به، وأن الأحاديث الواردة في وصف وضوء النبي صلى الله عليه وسلم مفصّلة، ولم يرد في شيء منها مسح العنق؛ والأصل في العبادات التوقيف وعدم المشروعية.

المصدر: https://dorar.net/feqhia/319

### البند 40 — حكم نسيان التسمية

عَنِ ابْنِ عَبَّاسٍ رَضِيَ اللهُ عَنْهُمَا، يَبْلُغُ النَّبِيَّ صَلَّى اللهُ عَلَيْهِ وَسَلَّمَ قَالَ: ((لَوْ أَنَّ أَحَدَكُمْ إِذَا أَتَى أَهْلَهُ قَالَ: بِسْمِ اللهِ، اللَّهُمَّ جَنِّبْنَا الشَّيْطَانَ وَجَنِّبِ الشَّيْطَانَ مَا رَزَقْتَنَا، فَقُضِيَ بَيْنَهُمَا وَلَدٌ لَمْ يَضُرَّهُ)) — وهذا دليل استحباب التسمية قياسًا، لا وجوبها، وعليه فلا يلزم إعادة الوضوء عند نسيانها.

المصدر: https://dorar.net/feqhia/295

### البند 41 و42 — إجزاء الغسل الواجب عن الوضوء، وعدم إجزاء الغسل المسنون

﴿ وَإِن كُنتُمْ جُنُبًا فَاطَّهَّرُوا ﴾ [المائدة: 6]

قال الشيخ ابن باز رحمه الله: "أما إذا كان الغسل عن جنابة أو حيض أو نفاس ونوى المغتسل الطهارتين دخلت الصغرى في الكبرى؛ لقول النبي صلى الله عليه وسلم: إنما الأعمال بالنيات، وإنما لكل امرئ ما نوى".

وقال أيضًا: "أما إذا كان الغسل مستحبًّا؛ كغسل الجمعة، أو للتبرد، فإنه لا يكفيه عن الوضوء؛ بل لا بد من الوضوء قبله أو بعده؛ لقوله صلى الله عليه وسلم: لا يقبل الله صلاة أحدكم إذا أحدث حتى يتوضأ".

المصدر: https://binbaz.org.sa/fatwas/3810

### البند 43 — صفة الغسل من الجنابة

عَنْ عَائِشَةَ رَضِيَ اللهُ عَنْهَا، قَالَتْ: ((أُدْنِيَ لِرَسُولِ اللهِ صَلَّى اللهُ عَلَيْهِ وَسَلَّمَ غُسْلُهُ مِنَ الْجَنَابَةِ، فَغَسَلَ كَفَّيْهِ مَرَّتَيْنِ أَوْ ثَلَاثًا، ثُمَّ أَدْخَلَ يَدَهُ فِي الْإِنَاءِ، ثُمَّ أَفْرَغَ بِهِ عَلَى فَرْجِهِ وَغَسَلَ بِشِمَالِهِ، ثُمَّ ضَرَبَ بِشِمَالِهِ الْأَرْضَ فَدَلَكَهَا دَلْكًا شَدِيدًا، ثُمَّ تَوَضَّأَ وُضُوءَهُ لِلصَّلَاةِ، ثُمَّ أَفْرَغَ عَلَى رَأْسِهِ ثَلَاثَ حَفَنَاتٍ مِلْءَ كَفِّهِ، ثُمَّ غَسَلَ سَائِرَ جَسَدِهِ)) — متفق عليه.

المصدر: https://www.islamweb.net/ar/fatwa/6133

---

*هذا الملحق مُعَدٌّ ليكون مرجعًا للنصوص الأصلية عند صياغة أسئلة الاستبانة النهائية، وللتأكد من دقة النقل والأمانة العلمية في الاقتباس، بحسب منهجية كتابة البحث الفقهي المتبعة في هذا المشروع.*

---

*This document is a working draft intended to evolve. Personal observations noted in Section 1 are explicitly framed as motivation, not established findings, and are not to be cited as fact in the final paper without empirical support from this study's own data.*
