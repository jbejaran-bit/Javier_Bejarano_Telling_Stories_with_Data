| [Home](https://jbejaran-bit.github.io/Javier_Bejarano_Telling_Stories_with_Data/) | [Part I — Proposal](final-project-part-one) | **Part II — Storyboard and research** | [Part III — Final project](final-project-part-three) |

# Final Project — Part II: Storyboard and User Research

## AI: A Shortcut to Answers or a Tool for Learning?

**Project status:** Revised storyboard and three draft visuals. Feedback from one peer recorded; two interviews remain.

## 1. Draft story and storyboard

My story asks whether AI helps us understand new material or simply helps us finish tasks. I decided to narrow the original proposal to **Python programming and university physics**, two subjects that are relevant to university students. The mathematics study from Part I is no longer used in these charts.

### Chapter 1 — Can you solve it without AI?

Imagine learning a new Python library. You can ask AI to write the code or try to solve the problem yourself. Which approach helps you understand the material better? This is a hypothetical example, not a research participant.

### Chapter 2 — Python: finishing a task is not the same as learning

Anthropic's 2026 randomized experiment involved 52 software developers learning Trio, a Python library they had never used. One group could use an AI coding assistant; the other wrote code without AI. Both groups completed coding tasks and then took a quiz **without AI** to test their understanding. [Study source](https://www.anthropic.com/research/AI-assistance-coding-skills).

<div style="max-width:700px;margin:24px auto;padding:24px;border:1px solid #dce4eb;border-radius:12px;">
<h3 style="margin:0 0 6px;">Developers using AI scored lower on the quiz</h3>
<p style="color:#536579;">Mean score on the independent Python quiz (% correct)</p>
<div style="display:flex;align-items:flex-end;justify-content:center;gap:60px;height:260px;border-bottom:1px solid #aab6c2;">
<div style="width:130px;height:67%;background:#647f91;position:relative;"><strong style="position:absolute;top:-28px;left:0;width:100%;text-align:center;font-size:20px;">67%</strong></div>
<div style="width:130px;height:50%;background:#cf803a;position:relative;"><strong style="position:absolute;top:-28px;left:0;width:100%;text-align:center;font-size:20px;">50%</strong></div>
</div>
<div style="display:flex;justify-content:center;gap:60px;text-align:center;"><span style="width:130px;">Coded without AI</span><span style="width:130px;">Coded with AI</span></div>
<p style="font-weight:bold;color:#9b551d;text-align:center;margin:20px 0 8px;">17 percentage points lower with AI</p>
<small>Source: Anthropic (2026), How AI assistance impacts the formation of coding skills.</small>
</div>

The AI-assisted group scored 50% on average compared with 67% in the hand-coding group. This study concerns immediate coding skill acquisition, not long-term learning or every possible way of using AI.

### Chapter 3 — Physics: the way AI is designed matters

In a Harvard introductory physics course, 194 eligible students took part in a randomized crossover experiment. Existing small classroom peer groups were randomly assigned to one of two learning sequences. For one lesson, students attended an instructor-led active-learning class; for the other, they used a purpose-built AI tutor outside class instead.

<div style="max-width:700px;margin:24px auto;padding:20px;border:1px solid #dce4eb;border-radius:12px;">
<h3 style="text-align:center;margin:0 0 8px;">How the physics experiment worked</h3>
<p style="text-align:center;"><strong>194 students</strong><br>Random assignment by small peer group</p>
<table style="width:100%;text-align:center;border-collapse:separate;border-spacing:6px;">
<thead><tr><th>Lesson</th><th>Sequence A</th><th>Sequence B</th></tr></thead>
<tbody>
<tr><td>Lesson 1</td><td style="background:#e7eef5;color:#243d55;padding:16px;">In-person class</td><td style="background:#e3f2eb;color:#205e49;padding:16px;">AI tutor</td></tr>
<tr><td>Lesson 2</td><td style="background:#e3f2eb;color:#205e49;padding:16px;">AI tutor</td><td style="background:#e7eef5;color:#243d55;padding:16px;">In-person class</td></tr>
</tbody></table>
<p style="text-align:center;margin:16px 0;"><strong>For each lesson:</strong><br>Pre-test → Learning activity → Post-test</p>
<small>Source: Kestin et al. (2025), experimental methods. Sequence labels are illustrative.</small>
</div>

**What is being compared?** The improvement in quiz scores after each teaching method. Random assignment helps separate the effect of instruction from students' initial ability or preferences. This was a comparison of two specific physics lessons, not students who chose to skip class for an entire semester. The tutor was designed to teach the course material, rather than simply provide answers. [Study source](https://doi.org/10.1038/s41598-025-97652-6).

<div style="max-width:700px;margin:24px auto;padding:24px;border:1px solid #dce4eb;border-radius:12px;">
<h3 style="margin:0 0 6px;">A purpose-built AI tutor improved learning gains</h3>
<p style="color:#536579;">Median improvement from pre-test to post-test (classroom = 1×)</p>
<div style="display:flex;align-items:center;gap:12px;margin:24px 0;"><span style="width:150px;">Classroom</span><div style="width:30%;height:42px;background:#647f91;border-radius:4px;"></div><strong>1×</strong></div>
<div style="display:flex;align-items:center;gap:12px;margin:24px 0;"><span style="width:150px;">AI tutor</span><div style="width:60%;height:42px;background:#32856e;border-radius:4px;"></div><strong>&gt;2×</strong></div>
<small>Source: Kestin et al. (2025), Scientific Reports. The classroom gain is normalized to 1; the AI result is a reported lower bound, not an exact ratio.</small>
</div>

The authors report more than twice the median learning gain with the AI tutor. This means improvement on the lesson quizzes, not twice the overall grade or twice the long-term knowledge. This is a different experiment and outcome from the Python quiz; the numbers cannot be compared directly.

### Chapter 4 — Learning time

<div style="max-width:700px;margin:24px auto;padding:24px;border:1px solid #dce4eb;border-radius:12px;">
<h3 style="margin:0 0 8px;">How much time was spent or allocated to the physics lesson?</h3>
<p style="color:#536579;">Minutes</p>
<div style="display:flex;justify-content:space-around;text-align:center;margin:24px 0;gap:12px;"><div style="flex:1;background:#edf6f3;padding:22px;border-radius:8px;"><strong style="font-size:38px;color:#28705c;">49</strong><p>AI tutor<br>Median time</p></div><div style="flex:1;background:#f1f4f7;padding:22px;border-radius:8px;"><strong style="font-size:38px;color:#526779;">60</strong><p>Classroom<br>Allotted time</p></div></div>
<small>Source: Kestin et al. (2025). Median measured tutor time versus scheduled classroom activity time; not two measured medians.</small>
</div>

The tutor's median measured time was 49 minutes, compared with 60 minutes allotted to the classroom activity. This is context for the learning result, not a precise estimate of individual time savings.

### Chapter 5 — What should students do?

Use AI to ask questions, get explanations, and practice. Afterward, try a new problem independently. These are practical suggestions inspired by the studies, not a claim that one approach is optimal for everyone.

**Storyboard plan:** An opening question, the Python quiz chart, the physics randomized-experiment diagram, the learning-gain chart, the time comparison, and a short conclusion. The final medium is planned as a scrolling Shorthand story.

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

## 4. Interview findings

### Interview 1 — Student peer

The first participant thought the visualizations looked decent overall but raised two important questions about the physics study. The feedback below is paraphrased from the participant's comments.

| Feedback topic | Interview 1 — Student peer | Interview 2 | Interview 3 |
| --- | --- | --- | --- |
| Overall impression | The visualizations look pretty decent. | Pending | Pending |
| Confusing result | How was the reported 2× increase in learning measured? | Pending | Pending |
| Missing comparison | What if students studied independently without AI instead of attending class? | Pending | Pending |
| Alternative explanation | The difference could reflect the effectiveness of classroom instruction rather than the benefit of AI alone. | Pending | Pending |

### Research synthesis — preliminary

This feedback suggests that the physics visualization needs to define learning gain more clearly. The participant also identified a limitation: the experiment compared AI tutoring with active-learning instruction, but did not include an independent-study group without AI. The comparison therefore does not isolate the contribution of AI from other differences in the learning environment. It also does not establish that the instructor was ineffective.

I will compare these observations with the remaining two interviews before drawing conclusions about common or conflicting feedback.

## 5. Proposed improvements for Part III

| Research finding or design question | Anticipated improvement |
| --- | --- |
| Interview 1: The meaning of the 2× learning gain was unclear. | Show the actual pre-test baseline and post-test scores, clearly define the gain calculation, and explain the ratio. |
| Interview 1: There is no independent-study group without AI. | Explicitly identify this missing comparison and explain what the experiment cannot establish. |
| Interview 1: Classroom effectiveness could explain part of the difference. | Avoid claiming AI is universally better than instructors; distinguish the tested learning methods from AI's isolated contribution. |
| Initial design review: Tutor time and classroom allotted time are different measures. | Retain clear labels and avoid claiming precise individual time savings. |

The first three changes are based on the actual peer feedback. Further changes will be identified after the other interviews.

## 6. References and transparency

- Anthropic (2026). [How AI assistance impacts the formation of coding skills](https://www.anthropic.com/research/AI-assistance-coding-skills).
- Kestin et al. (2025). [AI tutoring outperforms in-class active learning](https://doi.org/10.1038/s41598-025-97652-6). Scientific Reports.
- [Part I proposal](final-project-part-one).

**AI acknowledgment:** I used ChatGPT to help restructure the story, create HTML charts and an experimental-design diagram from published research, and draft the interview protocol. I will conduct the actual interviews and verify the results and final designs. No interviews or feedback were generated by AI.
