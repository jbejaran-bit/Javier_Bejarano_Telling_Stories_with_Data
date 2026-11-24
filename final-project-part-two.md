| [Home](https://jbejaran-bit.github.io/Javier_Bejarano_Telling_Stories_with_Data/) | [Part I — Proposal](final-project-part-one) | **Part II — Storyboard and research** | [Part III — Final project](final-project-part-three) |

# Final Project — Part II: Storyboard and User Research

## AI: A Shortcut to Answers or a Tool for Learning?

**Project status:** Revised storyboard and three draft visuals. User interviews are pending.

## 1. Draft story and storyboard

My story asks whether AI helps us understand new material or simply helps us finish tasks. I decided to narrow the original proposal to **Python programming and university physics**, two subjects that are relevant to university students. The mathematics study from Part I is no longer used in these charts.

### Chapter 1 — Can you solve it without AI?

Imagine learning a new Python library. You can ask AI to write the code or try to solve the problem yourself. Which approach helps you understand the material better? This is a hypothetical example, not a research participant.

### Chapter 2 — Python: finishing a task is not the same as learning

Anthropic's 2026 experiment involved 52 developers learning Trio, an unfamiliar Python library. After a coding task, participants took a quiz measuring their understanding.

<div style="max-width:700px;margin:24px auto;padding:24px;border:1px solid #dce4eb;border-radius:12px;">
<h3 style="margin:0 0 6px;">Developers using AI scored lower on the quiz</h3>
<p style="color:#536579;">Mean quiz score (% correct)</p>
<div style="display:flex;align-items:flex-end;justify-content:center;gap:60px;height:260px;border-bottom:1px solid #aab6c2;">
<div style="width:130px;height:67%;background:#647f91;position:relative;"><strong style="position:absolute;top:-28px;left:0;width:100%;text-align:center;font-size:20px;">67%</strong></div>
<div style="width:130px;height:50%;background:#cf803a;position:relative;"><strong style="position:absolute;top:-28px;left:0;width:100%;text-align:center;font-size:20px;">50%</strong></div>
</div>
<div style="display:flex;justify-content:center;gap:60px;text-align:center;"><span style="width:130px;">Without AI</span><span style="width:130px;">With AI</span></div>
<p style="font-weight:bold;color:#9b551d;text-align:center;margin:20px 0 8px;">17 percentage points lower with AI</p>
<small>Source: Anthropic (2026), How AI assistance impacts the formation of coding skills.</small>
</div>

The AI-assisted group scored 50% on average compared with 67% in the hand-coding group. This study concerns immediate coding skill acquisition, not long-term learning or every possible way of using AI.

### Chapter 3 — Physics: the way AI is designed matters

A randomized crossover study of 194 Harvard undergraduate physics students compared a purpose-built AI tutor with an active-learning classroom. Unlike a general coding assistant, the tutor was designed around teaching principles.

<div style="max-width:700px;margin:24px auto;padding:24px;border:1px solid #dce4eb;border-radius:12px;">
<h3 style="margin:0 0 6px;">A purpose-built AI tutor improved learning gains</h3>
<p style="color:#536579;">Median learning gain relative to the active-learning class</p>
<div style="display:flex;align-items:center;gap:12px;margin:24px 0;"><span style="width:150px;">Classroom</span><div style="width:30%;height:42px;background:#647f91;border-radius:4px;"></div><strong>1×</strong></div>
<div style="display:flex;align-items:center;gap:12px;margin:24px 0;"><span style="width:150px;">AI tutor</span><div style="width:60%;height:42px;background:#32856e;border-radius:4px;"></div><strong>&gt;2×</strong></div>
<small>Source: Kestin et al. (2025), Scientific Reports. The classroom gain is normalized to 1; the AI result is a reported lower bound, not an exact ratio.</small>
</div>

The authors report more than twice the median learning gain with the AI tutor. This is a different experiment and outcome from the Python quiz; the numbers cannot be compared directly.

### Chapter 4 — Learning time

<div style="max-width:700px;margin:24px auto;padding:24px;border:1px solid #dce4eb;border-radius:12px;">
<h3 style="margin:0 0 8px;">The physics tutor also took less time than the allotted class activity</h3>
<p style="color:#536579;">Minutes</p>
<div style="display:flex;justify-content:space-around;text-align:center;margin:24px 0;gap:12px;"><div style="flex:1;background:#edf6f3;padding:22px;border-radius:8px;"><strong style="font-size:38px;color:#28705c;">49</strong><p>AI tutor<br>Median time</p></div><div style="flex:1;background:#f1f4f7;padding:22px;border-radius:8px;"><strong style="font-size:38px;color:#526779;">60</strong><p>Classroom<br>Allotted time</p></div></div>
<small>Source: Kestin et al. (2025). Median measured tutor time versus scheduled classroom activity time; not two measured medians.</small>
</div>

The tutor's median measured time was 49 minutes, compared with 60 minutes allotted to the classroom activity. This is context for the learning result, not a precise estimate of individual time savings.

### Chapter 5 — What should students do?

Use AI to ask questions, get explanations, and practice. Afterward, try a new problem independently. These are practical suggestions inspired by the studies, not a claim that one approach is optimal for everyone.

**Storyboard plan:** An opening question, the Python quiz chart, the physics learning-gain chart, the time comparison, and a short conclusion. The final medium is planned as a scrolling Shorthand story.

## 2. Data and chart development

| Source | Data used in this draft |
| --- | --- |
| [Anthropic (2026)](https://www.anthropic.com/research/AI-assistance-coding-skills) | Published group mean quiz scores, 67% and 50% |
| [Kestin et al. (2025)](https://doi.org/10.1038/s41598-025-97652-6) | Published median learning-gain comparison and time statistics |

[Working CSV of published results](data/ai-learning-published-results.csv) contains the source values for the quiz and time comparison. The relative learning-gain graphic uses the published statement of more than twice the median gain, not an invented exact value. I am using published aggregate results, not claiming to have independently analyzed the raw physics or coding records. The studies use different participants, tasks and measurements, so I present them separately.

## 3. User research protocol

### Goal and intended audience

I want to find out whether students can understand the difference between **getting answers with AI** and **learning to solve problems without AI**. I also want to test whether the charts and the flow of the story are clear without needing a detailed explanation from me.

### Recruitment plan

I plan to interview three people: a PhD student, a master's student, and a high school educator. The two students represent my intended audience, while the educator offers a complementary teaching perspective. I will ask them individually for anonymous feedback. Participation is voluntary.

### Interview script

**Opening:** “I am creating a short data story about AI and studying. I would like your feedback on the early draft, not on your knowledge of statistics. You can be critical. I will report your feedback anonymously.”

1. What is the main message you get from the graphs?
2. Did any of the results surprise you?
3. Which graph was the easiest to understand?
4. Was anything confusing or difficult to understand?
5. What would you change or improve?

**Optional follow-up prompts:** “What made you think that?” “Which chart is easiest to understand?” “Would the conclusion make you change anything about how you study?”

I will show the same draft sequence to every participant, let them speak before explaining the intended message, and take short anonymous notes. I will not suggest answers or treat feedback as research evidence about the effectiveness of AI.

## 4. Interview findings — to complete after three actual interviews

**No interviews have been reported or documented yet.** The table below is a recording sheet, not invented research findings. I will add actual anonymous comments and short verbatim quotes after each conversation.

| Feedback topic | Interview 1 | Interview 2 | Interview 3 |
| --- | --- | --- | --- |
| Participant description (general only) | Not yet interviewed | Not yet interviewed | Not yet interviewed |
| Interpretation of Python quiz chart | Pending | Pending | Pending |
| Interpretation of physics charts | Pending | Pending | Pending |
| Confusing labels or story transitions | Pending | Pending | Pending |
| Most useful suggested change | Pending | Pending | Pending |
| Short anonymous quote (if consented) | Pending | Pending | Pending |

### Research synthesis — pending

After at least three interviews, I will identify which observations are repeated, which differ, and what changes the feedback supports. I will distinguish what participants **actually said** from my own interpretation. I will remove all personally identifiable information before publishing.

## 5. Proposed improvements for Part III

These are **initial design priorities based on reviewing the draft**, **not interview findings**. I will revise them after I receive genuine feedback.

| Design question to test | Possible improvement if interviews support it |
| --- | --- |
| Do readers understand the difference between the Python quiz and physics learning gains? | Add an explanatory subtitle before the second chart |
| Can readers interpret the percentages quickly? | Keep direct labels, add a one-line definition of what the scores measure |
| Is the distinction between measured tutor time and allotted classroom time clear? | Clarify the time labels and avoid claiming a precise time saving |
| Is the conclusion too strong? | Make clear that the charts show descriptive averages and the study is not universal |
| Is the student scenario mistaken for a real participant? | Clearly mark it **hypothetical** in the opening |

## 6. References and transparency

- Anthropic (2026). [How AI assistance impacts the formation of coding skills](https://www.anthropic.com/research/AI-assistance-coding-skills).
- Kestin et al. (2025). [AI tutoring outperforms in-class active learning](https://doi.org/10.1038/s41598-025-97652-6). Scientific Reports.
- [Part I proposal](final-project-part-one).

**AI acknowledgment:** I used ChatGPT to help restructure the story, create HTML charts from published aggregate results, and draft the interview protocol. I will conduct the actual interviews and verify the results and final designs. No interviews or feedback were generated by AI.
