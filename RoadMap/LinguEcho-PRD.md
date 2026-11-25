# LinguEcho Product Requirements Document

**Status:** Draft for customer discovery and pilot planning  
**Date:** 25 November 2026  
**Product:** LinguEcho  
**Working positioning:** Watch. Echo. Improve.

## 1. Product summary

LinguEcho helps people practise speaking a second language by shadowing short videos of a real person speaking. Learners can see the speaker's face and mouth, follow synchronized text, record themselves, and receive encouraging, actionable feedback.

The initial business hypothesis is to offer LinguEcho to language teachers and small language schools as a way to assign speaking practice between lessons. The longer-term vision includes a direct-to-consumer product and a library of progressively harder courses in multiple languages.

This document combines the founder's vision with proposed pilot decisions. US English and European Portuguese are required pilot teaching languages. Prices, targets, timing, and technical approaches are **hypotheses**, not validated facts or commitments.

## 2. Problem and opportunity

Language learners may have limited opportunities to speak between lessons. Even when they practise alone, they may not know which pronunciation or rhythm issue to focus on, or whether they are improving. Teachers may find it difficult to assign and monitor individual speaking practice without adding substantial marking time.

These are hypotheses to validate through interviews and pilots. The product should support clear, understandable communication, not require learners to eliminate their accents or imitate a particular speaker perfectly.

### Alternatives and differentiation

Schools and learners already have other ways to practise speaking. The comparison below is a hypothesis to check in discovery; verify each alternative's current features, languages, and price before using a comparison in sales.

| Alternative | Why a school may think it is enough | What to verify |
|---|---|---|
| General language apps and coursebook apps (for example Duolingo or a publisher's platform) | Already in use; the outreach plan expects this objection | Whether they offer speaking practice a teacher can assign and see completed |
| Pronunciation apps with automated feedback (for example ELSA Speak or Speechling) | Learners already get feedback on their speech | Languages and locales covered, in particular European Portuguese; teacher or school features; price |
| Free shadowing with online video or podcasts | No cost | Whether learners actually do it without assignment, feedback, or follow-up |
| Voice-note homework marked by the teacher | No new tool | Teacher marking time and how often it is assigned |
| No speaking homework | No effort | Whether this is a problem the school would pay to solve |

**Differentiation hypothesis:** teacher-assigned speaking practice with visible completion, a real speaker's face with synchronized text, content reviewed for the specific locale (including European Portuguese), and one evidence-supported next step instead of a score.

## 3. Goals and non-goals

### Product goals

1. Make it easy for a learner to watch, listen, repeat, and try again.
2. Provide specific feedback that highlights a genuine strength and, when supported by evidence, one useful next step.
3. Help learners form a regular speaking-practice habit.
4. Let teachers assign practice and see whether learners have completed it.
5. Test whether schools and teachers will pay for continued use.

### Business goal

Test a path to **$3,000 in monthly recurring revenue (MRR) by the end of year one**. This is a target, not a forecast. MRR is recurring contract revenue normalized to one month, before expenses and taxes; a one-off pilot payment does not count as recurring revenue.

Two points must be settled before this target is used for planning (open decision 10):

- **Gross or net:** if the goal is the founder's income after costs and taxes, the gross MRR required is higher by the delivery costs in Section 12 plus tax.
- **Currency:** the goal is stated in US dollars and the pilot prices in euros. Choose one reporting currency and state the conversion rate used.

### Initial non-goals

- Launching two complete courses of 50-100 videos each for every language.
- Supporting every language, accent, age group, or school curriculum.
- Guaranteeing a specific learning outcome or replacing teachers.
- Building a full learning management system or enterprise integrations before pilot demand is established.
- Releasing installable iOS or Android apps during the browser-based pilot.
- Providing medical, speech therapy, or diagnostic assessments.
- Offering retelling exercises or a printed shadowing journal during the pilot. Both appear in the outreach plan; see "Consistency with sales materials" in Section 12.

## 4. Users and buyers

| User | Need | Role |
|---|---|---|
| Adult language learner | Safe, understandable speaking practice and an achievable next step | Primary product user |
| Language teacher | Assign short speaking exercises and see who practised | Assigns practice and influences adoption |
| School owner or academic director | Valuable learning support that fits the school's budget and workflow | Pilot decision-maker and potential buyer |
| LinguEcho pilot operator | Set up content, support schools, and manage feedback review | Internal administrator |
| Feedback reviewer | Check AI-drafted feedback quickly, with the recording, script, and assessment signals in view | Qualified teacher of the target locale, engaged by LinguEcho; one needed for each track (Section 8) |
| Independent teacher | Same as a language teacher, without a school administrator | Teacher and buyer in one; secondary segment (Section 9) |

**Proposed first segment:** adult learners at small private language schools, initially approached in Portugal. Recruit classes across the pilot for both US English (`en-US`) and European Portuguese (`pt-PT`). Select a starting proficiency level for each track after discovery.

**Variety of English to confirm:** the English track is US English, but the outreach plan prioritizes schools that prepare students for Cambridge exams, which may teach and expect British English. Ask in discovery which variety each school teaches and whether US English content is acceptable (open decision 11). Do not present `en-US` clips or feedback as British English.

## 5. Product principles

- **Understandability over accent conformity:** prioritize issues likely to affect communication and accept legitimate pronunciation variation.
- **Encouraging, not generic:** praise must refer to something actually observed.
- **One useful next step:** avoid overwhelming learners with a long list of errors.
- **Evidence over certainty:** do not invent improvements, confidently diagnose uncertain audio, or claim capabilities the assessment cannot support.
- **Human-centered:** teachers remain in control, and learners can hear and repeat the original speaker.
- **Accessible and low-friction:** short sessions, readable text, and a usable experience on phones and computers.
- **Privacy by design:** collect only what is needed and clearly explain how recordings are handled.

## 6. Scope and release phases

**Platform requirement:** LinguEcho must be available to learners on the web and as installable apps for iOS and Android. The pilot is web-only, including on mobile; the installable apps follow the pilot.

### Phase 0: Discovery and demonstration

**Purpose:** confirm the problem and demand before building a full product.

- Interview approximately 10 teachers or school decision-makers in one segment, using the existing discovery guide.
- Create a demo using three original or properly licensed clips in total, with at least one clip for each pilot language.
- Demonstrate the learner loop and a teacher report; mockups and manually produced feedback are acceptable if clearly disclosed.
- Test a four-week pilot offer and an explicit price for continued use.

**Exit criteria:** decide whether to build the pilot using the Phase 0 rule in Section 11, agreed before the interviews start.

### Phase 1: Minimum viable pilot

**Required teaching tracks:** US English (`en-US`) and European Portuguese (`pt-PT`). Both must offer the core practice loop: watch a speaker in the target locale with synchronized text, shadow, submit a separate recording, and receive feedback. These are the languages taught in the pilot. The language of the interface and of written feedback is a separate decision (L13).

**Proposed scope:** one starting proficiency level per track, enough short clips to cover the agreed assignment cadence, and 2-3 school pilots in total. Each school pilot runs for four weeks with one class of up to 15 adult learners, subject to recruitment and agreement. Both tracks must be represented across the pilot; individual schools do not need to run both.

**Clip count:** the current pilot offer asks a teacher to assign two clips a week for four weeks, which needs 8 clips for each track, 16 across both. If production capacity does not allow that, reduce the offer to one clip a week (4 for each track, 8 in total) before pilot agreements are signed, rather than repeating clips or launching short. Each assignment covers one assessed segment of a clip.

The pilot must support the learner and teacher workflows in Sections 7-9 and evaluate AI speech assessment on separately recorded attempts. Some operations, including content setup, assignment, feedback review, reporting, and billing, may be manual or assisted. Start with AI results reviewed by a LinguEcho feedback reviewer, who is a qualified teacher of the target locale and not the learner's class teacher (see "Review workflow and capacity" in Section 8). Disclose whether feedback was generated by AI, reviewed by a LinguEcho reviewer, or provided by the learner's own teacher. Learners access the pilot in supported browsers on iOS, Android, and desktop without installing an app.

### Phase 2: Post-pilot product

Release installable iOS and Android learner apps alongside the web app. Verify the core learner flow on each platform: play a clip with synchronized text, shadow the speaker, record and submit a separate attempt, view feedback, and retry or continue.

Only after pilot evidence supports further investment:

- Improve automation and feedback quality.
- Expand the content library and difficulty progression.
- Add teacher self-service features where there is proven need.
- Test additional languages and learner groups.
- Explore a direct-to-consumer subscription and optional retelling exercises.

### Long-term vision

For each supported language, offer at least a basic and an advanced course, each with approximately 50-100 videos arranged in increasing difficulty. Confirm appropriate levels, content lengths, and curriculum with teachers and learners before production.

### Pilot timeline and resourcing

The outreach plan sells pilots that start in the January term, a few weeks after the date of this document. No start date, owner, or budget is recorded yet. Work back from each school's agreed start date:

| When | Milestone |
|---|---|
| 5 weeks before start | Discovery interviews complete; Phase 0 decision made (Section 11). |
| 4 weeks before start | Pilot agreements signed on terms consistent with this document; clip scripts approved by a teacher for each locale; feedback reviewers engaged. |
| 3 weeks before start | Clips recorded, timed, and reviewed; speech provider benchmarked on sample recordings for each locale. |
| 2 weeks before start | Learner flow tested on pilot devices and browsers; privacy notice, data-processing terms, and retention period final. |
| 1 week before start | Launch readiness checklist complete; classes set up; teachers briefed. |
| Weeks 1-4 | Pilot runs; teacher report delivered on the agreed schedule. |
| Within 1 week after | Results meeting, school summary (T6), and continuation offer. |

If the checklist cannot be completed in time, move the start date rather than launching without reviewed content, a tested recording flow, or privacy arrangements. The outreach plan identifies September as the next term window.

**What must work in the product, and what may be manual:**

| Must work in the product | May be manual or assisted in the pilot |
|---|---|
| Clip playback with synchronized highlighting, segment replay, speed control, and the Translate button | Class setup and invitations |
| Recording, replay of the attempt, and upload | Assignment, due-date, and feedback-ready messages |
| Sign-in that keeps learners, classes, and schools separate | Feedback review and release |
| Feedback display and feedback status | Teacher report and school summary |
| | Content publishing and billing |

**Roles that need a named owner, available hours, and a budget before pilots are signed (open decision 12):** product build; clip production for each locale, including a speaker and a content reviewer; feedback review for `en-US` and for `pt-PT`; pilot operations and learner support; privacy and contract advice.

## 7. Learner experience

### Primary flow

1. The learner opens an assigned clip and sees its title, level, and short instruction.
2. The learner watches a speaker whose face and mouth are clearly visible and reads the accompanying target-language text.
3. The displayed words are highlighted in time with speech.
4. The learner can press a Translate button to see a translation of the text, and press it again to hide it.
5. The learner selects or is guided to a short segment and shadows the speaker while the video plays and the words highlight in sync.
6. To get feedback, the learner listens to the reference and then records the same segment with the reference audio off.
7. The learner sees the submission and feedback status, and can replay their attempt and the reference. When feedback is ready, the learner can practise the suggested next step and retry.
8. The learner sees completed practice and an achievable next action.

### Learner requirements and acceptance criteria

| ID | Requirement | Acceptance criteria for the pilot |
|---|---|---|
| L1 | Watch and follow | An assigned clip plays with readable target-language text. Word highlighting follows the spoken words, including after pause or replay. A content reviewer verifies timing before publication. |
| L2 | See the speaker | Each published clip has sufficient lighting, framing, and video quality for a reviewer to see the speaker's face and mouth during the intended practice segments. |
| L3 | Repeat a segment | The learner can replay a short segment without restarting the entire lesson and can see which text belongs to it. |
| L4 | Record and retry | The learner can record the selected segment without reference audio playing, listen to the attempt, and retry. If microphone access is denied or recording or submission fails, the interface explains what to do next and does not mark the failed attempt as submitted. |
| L5 | Receive feedback | For a usable recording, the learner receives the feedback described in Section 8, whether produced manually or by a tested system. The source of feedback is disclosed. |
| L6 | Handle uncertainty | If the recording cannot be assessed reliably, the learner is told why when known and invited to record again. The product does not invent an assessment. |
| L7 | See practice progress | The learner can see which assigned activities have a completed attempt and what to do next. Completion is defined in Section 11. |
| L8 | Basic access | The pilot works on agreed, tested browsers on iOS, Android, and desktop. Text is readable, controls have accessible labels, and core controls can be used without relying on color alone. The supported browser and OS versions and accessibility review are decided before pilot launch. |
| L9 | Shadow along | The first lesson demonstrates how to speak along with the reference using the speaker's mouth movements, timing, and stress. The learner can shadow a selected segment with synchronized highlighting and replay it without restarting the lesson. Shadowing does not require recording and is unscored in the pilot. |
| L10 | Track feedback status | After a usable attempt is submitted, the learner can tell whether feedback is pending, ready, or unavailable. Pending feedback shows the agreed turnaround; unavailable feedback explains the next step. A feedback delivery failure does not erase a usable submission. |
| L11 | Control playback | The learner can slow the reference for a segment and return to normal speed, and highlighting stays in time with speech at each offered speed. The learner can hide and show the text. The speeds offered are decided after checking audio quality on pilot devices. |
| L12 | Join and get set up | A learner joins the correct class from an invitation and signs in with their own account. Before the first recording, the learner sees the privacy notice and how to withdraw. A first-run check confirms the microphone works and advises headphones for speaking along and a quiet place for recording. The sign-in method is decided before pilot launch. |
| L13 | Understand instructions and feedback | Instructions, error messages, and written feedback are in a language the learner can read at their level, decided for each track before launch. Words and phrases being practised stay in the target language. Starting hypothesis to confirm in discovery: Portuguese for the `en-US` track and English for the `pt-PT` track. |
| L14 | Know when to return | The learner is told when feedback is ready and when an assigned activity is due, through a channel agreed with the school, such as email or the teacher's class channel. Sending these messages manually is acceptable in the pilot. |
| L15 | Know the feedback limit | The learner can re-record as often as they like before submitting. For each assigned segment, the first usable submission and at most one retry after feedback are sent for reviewed feedback (Section 8). The learner is told this before submitting and can keep practising and replaying further attempts without feedback. |
| L16 | Translate the text | Each clip has a Translate button that shows a translation of the displayed text, and the learner can hide it again. The translation is shown in the learner's language, decided for each track (L13), and the target-language text stays visible. Translations are reviewed by a teacher or qualified content reviewer before publication (Section 10); machine translation is not shown unreviewed. Using Translate does not affect completion or feedback, and the control has an accessible label. |
Playing, pausing, highlighting, and recording should be tested on actual pilot devices and connection conditions. No specific synchronization tolerance is committed until it has been tested and agreed.

### Technical limits to decide and test before launch

- **Recording length:** a maximum recording and segment length that fits the speech provider's audio-length limits for the chosen assessment mode.
- **Recording format:** browsers on iOS, Android, and desktop do not all record in the same format. Confirm what each supported browser produces, what the provider accepts, and any conversion needed.
- **Poor connections:** a recording stays available on the device until the upload is confirmed, and the learner can send it again without re-recording.
- **Video delivery:** where clips are hosted, how quickly they start, and how much data they use on a mobile connection.

## 8. Feedback requirements

### Feedback format

For each assessed attempt, show:

1. **What went well:** one specific, evidence-supported observation.
2. **What improved:** one specific comparison only when a usable prior attempt on the same segment was made under comparable conditions and there is reliable evidence of improvement.
3. **One next focus:** when a reliable and meaningful issue is identified, name the affected word or phrase, describe what to try, and link back to the relevant reference segment.

If there is no comparable earlier attempt, omit the improvement statement. If an assessable attempt reveals no meaningful issue, reinforce what worked instead of inventing a correction. If the evidence is too limited to identify a strength or next focus reliably, explain the limitation and offer a retry or teacher review. Avoid numerical precision or certainty that the underlying assessment cannot justify.

**Illustrative feedback, conditional on actual evidence:**

> **Good:** You clearly said the final sound in "help."  
> **Improved:** Your pause before the second phrase was clearer than in your previous attempt.  
> **Try next:** In "asked," practise including the final consonant. Listen once, then try the phrase again.

### Areas to assess

- Pronunciation and completeness of sounds and words.
- Pace, pauses, emphasis and stress.
- Pitch, intonation, rhythm, and the melody of phrases.

Assess an area only if the selected method supports it for the target language and locale and has been checked with pilot learners. A written transcript alone is not evidence that a sound, pause, or intonation was produced correctly.

### AI speech assessment

- **First candidate for both tracks:** [Azure AI Speech Pronunciation Assessment](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/how-to-pronunciation-assessment), in scripted mode. Microsoft [lists both `en-US` and `pt-PT` for pronunciation assessment](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/language-support?tabs=pronunciation-assessment). Provide the learner's recording, the segment's exact text, and the segment's locale. Use only supported, validated signals as evidence, not as learner-facing scores. This assesses the attempt against the script, not against the actor's pitch or timing.
- **Language and feature limits:** Microsoft documents prosody assessment for `en-US` only. Do not promise individual stress, pitch, or pause diagnoses from an overall prosody score. Validate `pt-PT` pronunciation feedback with a qualified European Portuguese teacher; do not substitute Brazilian Portuguese (`pt-BR`). Where a dimension such as prosody is unsupported or unvalidated, provide teacher feedback when available or explain the limitation. If Azure misses the quality bar for either track, benchmark an alternative on the same recordings after confirming it supports the required locale and assessment features.
- **Feedback generation:** Map supported signals to the written format above using reviewed templates. A text model is optional and may rephrase grounded findings, but it must not infer pronunciation errors or improvements from a transcript or add findings that the speech assessment does not support. Filter out differences that teachers judge to be acceptable variants rather than treating provider accuracy scores as measures of intelligibility.
- **Pilot recording mode:** Learners shadow during playback, then record a clean attempt with the reference audio off. The AI assesses that attempt after submission, not the live speak-along. Evaluate direct shadowing assessment separately before offering it; test for reference audio leaking into the recording, including a playback-only clip that must not receive learner feedback.

### Choosing the next focus

Judge how readily a listener can recognize the intended word or phrase, not how closely the learner copies the reference speaker's accent. Use the following as a starting heuristic to validate with teachers, not an absolute ranking:

1. **High:** omitted sounds or words that could change or obscure meaning.
2. **Medium:** consonant substitutions or distortions that make words harder to recognize.
3. **Low:** small pronunciation differences with little effect on understanding; do not make these the next focus unless there is a meaningful clarity benefit.

Context matters: pace, pauses, stress, pitch, and intonation can take priority when they affect clarity or meaning more than a sound error. Natural reductions, connected speech, and legitimate accent variations are not errors merely because they differ from the reference speaker.

### Review workflow and capacity

- **Who reviews:** a feedback reviewer engaged by LinguEcho, who is a qualified teacher of the target locale. One is needed for `en-US` and one for `pt-PT`. The pilot operator reviews only for a locale they are qualified to teach. The learner's class teacher is not the reviewer by default, because teachers do not see recordings or individual feedback (T4).
- **What is reviewed:** all learner-facing feedback, until a feedback dimension meets the agreed quality bar for unreviewed use.
- **Limit on reviewed attempts:** for each assigned segment, the first usable submission and at most one retry after feedback (L15). The retry is what makes the "What improved" comparison possible.
- **Expected volume:** with 2-3 classes of up to 15 learners and two clips a week for four weeks, the pilot creates up to 240-360 assigned learner-activity pairs, so up to 480-720 reviewed attempts if every learner submits and retries. Actual volume depends on completion.
- **Turnaround:** proposed as two working days from submission, so feedback arrives before the next assigned clip. Confirm with reviewers and schools, and show the agreed turnaround to learners (L10).
- **If the queue falls behind:** keep the attempt marked as pending and tell learners the revised time. Do not release unreviewed feedback to catch up.
- **Record the effort:** log reviewer minutes for each reviewed attempt to support the unit economics in Section 12.

### Quality and safety checks

- A qualified teacher reviews a sample of feedback across representative pilot learners, accents, devices, and recording conditions.
- Record where feedback is correct, unsupported, misleading, or unhelpful; agree on an acceptable quality threshold before using unreviewed automation.
- Before enabling unreviewed AI feedback, compare the written feedback with teacher judgments on representative clips and recordings. Check for false corrections of acceptable accents, missed meaningful omissions, unsupported prosody claims, and appropriate handling of unusable audio. Agree on the quality bar, turnaround, and cost per attempt before launch and verify provider region, retention, and processing terms before sending learner audio. If the quality bar is not met for a feedback dimension, keep that dimension teacher-reviewed or do not present it.
- Let learners or teachers flag incorrect or unhelpful feedback for review.
- Feedback is educational guidance, not a clinical assessment or a promise of perfect pronunciation.

## 9. Teacher and school experience

| ID | Requirement | Acceptance criteria for the pilot |
|---|---|---|
| T1 | Class setup | A pilot operator or teacher can create a class, invite agreed participants, and associate them with the correct school. Manual setup is acceptable. |
| T2 | Assign practice | A teacher or pilot operator can assign a clip or segment to a class and communicate the due date. |
| T3 | Monitor activity | A teacher can see each assignment's due date and whether each learner submitted on time, submitted late, or has not yet submitted, with the submission date where applicable. Submission status is separate from feedback status. A manually prepared report is acceptable if delivered on the agreed schedule. |
| T4 | Respect access boundaries | A teacher sees only authorized classes and learner information. By default, teachers can see completion information but not raw recordings or individual feedback. Any broader access must be agreed with the school, limited to authorized roles, and disclosed to learners before recording. LinguEcho feedback reviewers are a separate authorized role whose access is limited to the attempts they review; this is also disclosed to learners before recording. Learners cannot see other learners' recordings or reports. |
| T5 | Review issues | A teacher can report an inaccurate assessment or content issue to the pilot operator and receive a response. |
| T6 | Support the buyer | At the end of the pilot, the school receives a summary of usage, teacher feedback, and the proposed continuation offer. |

The initial dashboard need not include grades, detailed pronunciation analytics, attendance integration, or automated claims about learner improvement.

**Independent teachers:** Section 12 names independent teachers as a target, but the requirements above assume a school. If an independent teacher joins the pilot, the teacher is the buyer and the contracting party for the pilot agreement and data-processing terms, the school in T1 and T4 is the teacher's own practice, and the T6 summary goes to the teacher. The default for the first pilot is schools only (open decision 17).

## 10. Content requirements

- Each pilot clip must be self-produced or used under a license that permits the intended commercial use, distribution, and any editing. Secure appropriate performer, likeness, and other relevant rights.
- Each clip has a reviewed transcript, segment boundaries, word timing, a reviewed translation for the Translate button (L16), target language and locale, level, and title. Each lesson has one practical communication objective and one speaking focus, such as asking someone to repeat a question politely while practising word stress. Explain the meaning or key vocabulary when the target learners may not understand the script.
- European Portuguese clips use speakers modelling European Portuguese and scripts reviewed for vocabulary, spelling, and natural speech in Portugal. Apply the same locale-specific review to US English clips.
- A teacher or qualified content reviewer checks wording, naturalness, synchronization, face visibility, and suitability for the intended learners before publication.
- Short, practical segments are preferred; determine appropriate length with pilot users rather than setting a fixed duration now.
- Validate the pilot lesson sequence with a teacher. In full courses, increase difficulty deliberately through sentence length, vocabulary, natural speaking speed, and the complexity of rhythm and intonation. Validate sequencing and level labels with teachers.
- Do not assume third-party films, television, music, or online videos can be reused without the necessary permissions.
- Pilot and demo clips show a real person speaking, as the product summary states. Do not use AI-generated speakers: the learner is asked to follow the speaker's mouth, so the mouth movements must be real.
- Plan production for the clip count in Section 6. For each locale, budget the speaker, recording, transcript, word timing, and review time for every clip before committing to an assignment cadence.

## 11. Motivation, measurement, and pilot evaluation

### Motivation features

- Show a small weekly practice goal agreed with the teacher.
- Show completed activities and progress toward that goal.
- After an attempt, show one clear next action: retry the phrase, continue to the next segment, or return to the weekly practice goal.
- Recognize completed practice and evidence-supported improvement separately. Missing a practice day does not reset or erase completed progress.
- Consider motivational reminders only after testing their usefulness and obtaining any required permissions. The feedback-ready and due-date messages in L14 are service messages, not reminders. Do not make a streak the only measure of progress or shame learners for missing practice.

### Proposed pilot measures

Set the measurement period, baseline, targets, and responsibilities with each school before the pilot starts. Report learner practice and feedback quality separately for `en-US` and `pt-PT`, with sample sizes.

| Measure | Definition | How to use it |
|---|---|---|
| Activation | Number of enrolled learners who submit at least one usable attempt / number of enrolled learners | Check onboarding and first-use friction. |
| Weekly practice | Number of enrolled learners who submit usable attempts on at least two distinct days in a pilot week / number of enrolled learners | Understand repeat use; report each week separately. Two days is a test target, not proof of learning. |
| Assignment completion | Number of assigned learner-activity pairs with at least one usable submitted attempt by the due date / number of assigned learner-activity pairs | Compare against the school's agreed baseline where a comparable baseline exists. |
| Feedback quality | Number of reviewed feedback items judged accurate and actionable / total reviewed feedback items | Review a documented sample; also record unsupported or harmful feedback. |
| Confidence | Before/after learner self-rating on an agreed 1-5 scale, reported for learners who complete both surveys | Explore perceived confidence, not proven speaking improvement. |
| Speaking improvement (exploratory) | Compare initial and final usable recordings on the same short prompt using a teacher-reviewed clarity and prosody rubric; report how many learners had usable pairs | Explore improvement on the practised prompt. If feasible, add a similar unfamiliar prompt at the end to see whether learners apply the skill beyond a rehearsed line. Do not treat results as proof of general improvement. |
| Continuation | Number of schools that pay for an agreed continuation / number of schools that complete the pilot | Test willingness to pay; distinguish interest from actual payment. |
| MRR | Sum of active recurring contract amounts normalized to one month | Track progress against the business target, excluding one-off pilot fees. |
| Review effort and turnaround | Reviewer minutes for each reviewed attempt; number of reviewed feedback items released within the agreed turnaround / total reviewed feedback items | Check whether human review is sustainable; feeds the unit economics in Section 12. |
| Delivery cost | Total cost of delivering the pilot to a class for a month / number of enrolled learners | Compare with the continuation price for each learner. |

**Completion definition:** a learner submits at least one usable recording for the assigned segment. Watching a video or shadowing without submitting a recording does not count as completion. Record the date of the first usable submission for on-time reporting, independent of whether feedback is pending, ready, or unavailable.

Agree on pilot success criteria in advance. A small pilot can expose usability and demand issues, but it does not by itself prove general learning effectiveness or school retention benefits.

### Go/no-go thresholds

Set thresholds before the results are known. The values below are starting proposals, not validated benchmarks; replace them with the figures agreed with each school. Where a school has a comparable baseline, the threshold is an improvement on that baseline.

**Phase 0 (build the pilot or not):**

| Result | Decision |
|---|---|
| The same speaking-practice problem comes up in at least 4 of about 10 interviews, and at least 2 schools sign a pilot with a stated continuation price, covering both tracks | Build and run the pilot. |
| Only 1 school signs, or only one track is covered | Change the segment and interview again before building. |
| No school signs | Revisit the problem or the offer; do not build. |

**Phase 1 (invest further or not):**

| Measure | Starting proposal |
|---|---|
| Activation | At least 70% of enrolled learners. |
| Weekly practice | At least 40% of enrolled learners in the final pilot week. |
| Assignment completion | At least 50%, and above the school's baseline where one exists. |
| Review turnaround | At least 90% of reviewed feedback released within the agreed turnaround. |
| Continuation | At least 1 school pays for an agreed continuation. |
| Delivery cost | Below the continuation price for each learner, or a tested plan to get there. |

Continue to Phase 2 only if the continuation and delivery cost thresholds are both met. If learners practise but no school pays, the problem is the offer or the buyer; if a school would pay but learners do not practise, the problem is the product. Decide the response to each before the pilot starts.

Enabling unreviewed AI feedback is a separate gate, set for each locale and feedback dimension under "Quality and safety checks" in Section 8.

## 12. Business model and go-to-market hypotheses

### Initial approach: B2B

Approach small private language schools and independent teachers directly. Start with discovery, then offer a scoped four-week class pilot with a clear end date, agreed success measures, and a continuation price.

The existing outreach plan proposes a free or **EUR 49** pilot and a starting hypothesis of **EUR 2-5 per student per month** for the app. Test these amounts; they are not established market prices. A free pilot may help learning but is weaker evidence of willingness to pay than a paid continuation.

### Later approach: B2C

Consider direct subscriptions after confirming that learners independently return to practise and that acquisition and support costs are sustainable. Consumer pricing and acquisition channels are not yet decided.

### Revenue illustrations

Before expenses and taxes, $3,000 MRR could correspond to 20 schools paying $150 per month, 600 paid student seats at $5 per month, or 200 consumers paying $15 per month. These are arithmetic examples, not validated prices or forecasts. Term or annual contracts must be normalized to monthly recurring amounts.

At the outreach plan's price of EUR 2-5 for each student each month, EUR 3,000 MRR would need 600-1,500 paid seats, or 40-100 classes of 15. This shows the scale the school route requires; it is not a forecast.

### Unit economics

No delivery cost has been measured yet. Before quoting a continuation price, estimate the monthly cost of serving one class and compare it with what the class pays.

| Cost | Driver | Status |
|---|---|---|
| Feedback review | Reviewed attempts x reviewer minutes x reviewer rate | Expected to be the largest cost; measure minutes for each attempt in the pilot. |
| Speech assessment | Amount of assessed audio x provider price | Confirm current provider pricing. |
| Video and recording hosting | Clip plays, stored recordings, and retention period | Estimate after choosing providers. |
| Clip production | Speaker, recording, transcript, timing, and review for each clip, in each locale | One-off; get a cost before committing to the clip count. |
| Support and school operations | Operator hours for each school each week | Record during the pilot. |
| Payments and invoicing | Fees and accounting | Confirm. |

**Illustration of the review cost:** a class of 15 at EUR 2-5 for each student each month pays EUR 30-75 a month. At two clips a week it produces up to 120 first attempts in four weeks. If review takes 2-3 minutes for each attempt, which is an assumption to measure, that is 4-6 hours of reviewer time. Review alone then breaks even only if reviewer time costs less than about EUR 5-19 an hour, before any other cost and before reviewed retries, which could double the hours.

If measured review time confirms this, reviewing every attempt cannot continue at this price. The options to test are: automate the feedback dimensions that pass the quality bar, review only a sample, reduce the number of reviewed attempts, or charge more, for example the outreach plan's per-term prices.

### Consistency with sales materials

The outreach plan and its pilot agreement currently promise things this document defers or rules out. Resolve each one before a pilot agreement is sent. Until then, this document governs what the pilot delivers.

| Topic | Outreach plan | This document | To resolve |
|---|---|---|---|
| Data location | States that data is stored in the EU | Do not promise EU-only storage unless the complete data flow supports it (Section 13) | Confirm the data flow first, or remove the promise. |
| Minors | Lists teens and kids as student types and includes parental consent for under-18s | Adults only (Section 13) | Remove the under-18 clause and exclude those classes, or review requirements for minors. |
| Retelling and printed journal | In the pitch, demo, pricing packages, and pilot agreement | Not in pilot scope (Section 3) | Remove from the pilot offer, or add requirements here. |
| Feedback | Described as AI feedback | Reviewed by a LinguEcho reviewer before release, with a turnaround (Section 8) | Describe the feedback as AI-assisted and teacher-reviewed, and state the turnaround. |
| Teacher time | States that it saves time | Measure rather than assume time saved (Section 14) | Present as something the pilot measures. |
| Demo footage | Allows AI-generated clips | Real speakers only (Section 10) | Use real speakers in the demo. |
| Languages | Pick one language first | Two required tracks (Section 6) | Recruit for both tracks, or change the requirement. |
| Number of pilots | Target of 3 signed pilots | 2-3 pilots, at least 2 to proceed (Sections 6 and 11) | Use one rule in both documents. |
| Clips | Two clips assigned each week | Clip count sized to the cadence (Section 6) | Confirm 16 clips can be produced, or offer one clip a week. |

## 13. Privacy, security, and operational requirements

- Treat voice recordings and associated learner data as sensitive personal information in product design. Identify applicable legal obligations with qualified advice, including GDPR where relevant; do not assume voice recordings are automatically biometric special-category data in every use case.
- Before collecting recordings, provide clear information about purpose, access, service providers, storage location, retention, deletion, and applicable rights. Establish the appropriate legal basis and required school agreements; consent is not automatically the correct basis for every processing activity.
- Limit the initial pilot to adults unless requirements for minors are separately reviewed and implemented.
- Restrict access by role and school, protect data in transit and at rest using suitable controls, and test the access boundaries.
- Choose providers and storage locations before launch; verify contractual terms and any cross-border transfers. Do not promise EU-only storage unless the complete data flow supports it.
- Define and communicate a specific retention period and deletion process before pilot launch, including how a participant or school can request deletion and what happens to backups.
- Do not use recordings for model training or unrelated purposes unless this has been separately assessed, disclosed, and authorized as required.
- Record failures and provide a support contact. Have a process for handling data incidents and access or deletion requests.
- Engage feedback reviewers under confidentiality and data-processing terms. Limit their access to the attempts assigned to them, and name the reviewer role in the privacy notice.
- Collect only the contact details needed for sign-in and for the service messages in L14, and say how they are used.
- Tell learners how to withdraw from the pilot and what happens to their recordings when they do.

## 14. Risks and mitigations

| Risk | Impact | Mitigation |
|---|---|---|
| Inaccurate or unfair feedback | Learners lose trust or practise the wrong thing | Start with human review, test representative recordings, disclose uncertainty, and limit automated claims. |
| Low repeat use | Schools see little value | Measure weekly practice, interview drop-offs, and test short assignments and supportive goals. |
| Schools like the idea but do not pay | No viable business | Agree on a continuation price early and measure paid conversions. |
| Content is costly or rights are unclear | Launch delays or legal exposure | Produce a small original library first and document all rights. |
| Speech capabilities vary by language | Inconsistent or unsupported feedback | Validate each language, locale, and assessment dimension before launch. |
| Teacher workload increases | Teachers stop assigning practice | Observe the pilot workflow and keep assignments and reporting simple; measure rather than assume time saved. |
| Privacy or security failures | Harm to learners and loss of trust | Minimize data, restrict access, review provider terms, and define retention and incident procedures before the pilot. |
| Human review costs more than schools pay | The pilot works but the business does not | Limit reviewed attempts, log reviewer minutes, and test the options in Section 12 before quoting a continuation price. |
| US English does not match what schools teach | Schools that teach British English decline or ask for different content | Ask in discovery; before adding or switching to British English, confirm the provider's support for that locale and each feedback dimension. |
| Too little capacity for sales, content, build, review, and support in the same weeks | Late or unready launch | Name an owner for each role in Section 6, and run fewer pilots rather than launch unready. |
| Missing the term start | The pilot slips to the next term | Agree dates early and follow the timeline in Section 6; move the start rather than launch without the readiness checklist. |
| Recording behaves differently across mobile browsers | Failed or unusable recordings on first use | Test on real pilot devices, run the first-run microphone check, and keep the recording until upload is confirmed. |
| Dependence on one speech provider | A price, feature, or terms change, or an outage, stops feedback | Keep the benchmark repeatable so an alternative can be evaluated, and keep reviewer feedback as the fallback. |
| Sales materials promise more than the pilot delivers | Loss of trust and contractual exposure | Resolve the items under "Consistency with sales materials" in Section 12 before agreements are sent. |

## 15. Open decisions and discovery questions

1. Which starting proficiency level and school segment should be recruited for each of the two confirmed tracks?
2. Which teacher or school role approves the pilot and controls the budget?
3. How much will schools actually pay, for how many students, and on what billing cycle?
4. Which practice outcomes and teacher workflows matter most to buyers?
5. Which AI speech provider and feedback dimensions work for each pilot locale, and what teacher-reviewed quality, turnaround, and cost targets must the provider meet?
6. What content length, difficulty progression, and weekly practice goal do learners sustain?
7. What retention period, provider arrangements, legal basis, and security controls are appropriate for the pilot?
8. Which browsers and OS versions must the pilot support on iOS, Android, and desktop?
9. Should retelling, teacher-authored content, a printed journal, or B2C subscriptions be prioritized after the pilot?
10. Is the $3,000 goal gross monthly recurring revenue or personal income after costs and taxes, and in which currency is it reported?
11. Which variety of English do target schools teach and want, and does `en-US` remain the right first English track?
12. What is the pilot start date, and who builds the product, produces clips, and reviews feedback for each locale, with how many hours and what budget?
13. How many reviewed attempts for each segment, what turnaround, and what reviewer cost for each attempt are sustainable?
14. Which language should the interface and written feedback use for each track and level?
15. How do learners sign in, and through which channel are they told that feedback is ready or an assignment is due?
16. Which go/no-go thresholds apply to each pilot, and what delivery cost for each learner makes the continuation price viable?
17. Are independent teachers without a school included in the first pilot?
18. Which outreach promises are withdrawn, and which become requirements in this document (Section 12)?
19. Which alternatives do schools and learners already use, and what would make them choose LinguEcho instead?

## 16. Launch readiness checklist

- [ ] Starting levels selected and pilot classes recruited across both US English and European Portuguese.
- [ ] Clips and performer rights documented; transcripts and timings reviewed.
- [ ] Recording, replay, highlighting, error handling, and reporting tested on agreed devices.
- [ ] On supported browsers on iOS, Android, and desktop, a learner can shadow with synchronized text, submit a separate recording, see its feedback status, and find the next practice step. The teacher report shows the correct submission status without exposing the recording or individual feedback by default.
- [ ] Core practice and the correct script and assessment locale verified for both tracks. AI speech provider evaluated against teacher judgments separately for each locale; only validated dimensions are eligible for unreviewed feedback. The feedback source, fallback, and escalation path are clear to learners.
- [ ] School agreements, privacy notice, appropriate data-processing arrangements, retention period, and support contact in place.
- [ ] Pilot dates, assignments, success measures, reporting schedule, and proposed continuation price agreed.
- [ ] Baseline and pilot measurement collection prepared.
- [ ] Pilot start date confirmed and an owner named for each role in Section 6.
- [ ] Clip count for each track covers the agreed assignment cadence.
- [ ] Feedback reviewer engaged for each locale; the reviewed-attempt limit and turnaround are agreed and shown to learners.
- [ ] Interface and feedback language decided for each track.
- [ ] Sign-in, first-run microphone check, and feedback-ready and due-date messages tested.
- [ ] Translate button shows a reviewed translation in the agreed language for every clip, and hides it again.
- [ ] Playback speed, recording length, recording format, and upload on a poor connection tested on agreed devices.
- [ ] Outreach plan, pilot agreement, and demo consistent with this document.
- [ ] Go/no-go thresholds recorded and delivery cost tracking in place.

## 17. Related documents

- [Customer discovery interview guide](./Linguecho-Customer-Discovery-Interview.pdf)
- [7-day B2B school outreach plan](./7-day-b2b-school-outreach-plan.md)
- [Portugal language-school list](./language-schools-portugal.csv)
