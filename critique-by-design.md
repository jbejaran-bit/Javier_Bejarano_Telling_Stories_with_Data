| [Home](https://jbejaran-bit.github.io/Javier_Bejarano_Telling_Stories_with_Data/) | [Data viz examples](dataviz-examples) | [Critique by design](critique-by-design) | [Final project I](final-project-part-one) | [Final project II](final-project-part-two) | [Final project III](final-project-part-three) |

# Critique and Redesign: NOAA's Greenhouse Gas Index

## Step 1: Original visualization

**Original source:** [NOAA Annual Greenhouse Gas Index (AGGI)](https://gml.noaa.gov/aggi/aggi.html) (see the AGGI visualizations on the NOAA page).

I selected NOAA's greenhouse gas index because I wanted to better understand how the warming influence of long-lived greenhouse gases has changed. I was interested in comparing recent years with 1990 rather than trying to explain all greenhouse gas measurements at once. The NOAA visualization contains useful scientific information, but I wanted to make its main message understandable to someone without a scientific background.

NOAA uses 1990 as the reference year, with an index of 1.00. A value of around 1.56 in 2025 means the warming influence measured by this index is around 56% higher than in 1990. It **does not** mean Earth's temperature has increased by 56%.

## Step 2: Critique of the original chart

One strength of the original NOAA visualization is the amount of historical context it provides. It helps readers see how different greenhouse gases contribute to the overall warming influence, and the scientific source is clearly identified.

I think it is harder for a general audience to understand the main comparison immediately because it includes several measurements and more than one vertical scale. A reader has to decide which line and which axis matter for the question they are trying to answer. The intended audience could include scientists, policymakers, students, and readers interested in climate change, but those groups may need different levels of detail.

My redesign focuses on one question: how much higher is the overall greenhouse gas index than it was in 1990? The original is more useful for examining several related measurements, while my simpler chart is more useful for communicating this particular comparison.

**Stephen Few's evaluation form:** [Course critique form](https://forms.gle/cKLcf5prjyzXJX9x9) — complete separately as required by the assignment.

### Reflecting on Stephen Few's method and the Good Charts matrix

I found Stephen Few's Data Visualization Effectiveness Profile useful because it made me evaluate individual aspects of the NOAA chart, such as completeness, perceptibility, and intuitiveness, instead of simply deciding whether I liked the design. For example, I rated the chart highly for usefulness and completeness because it provides valuable scientific context, but lower for perceptibility and intuitiveness because the multiple lines and two vertical scales take longer to understand.

The *Good Charts* matrix takes a broader approach by considering design execution and contextual awareness. I think it is useful for asking whether a chart fits its audience and purpose, while Few's profile helps me identify exactly which qualities need improvement. One limitation of scoring either method is that a number alone cannot explain the reasoning behind a design choice. I found it more useful to explain why I gave a score and how that observation influenced my redesign.

For this project, both approaches pointed me toward the same decision: keep the original scientific source and historical context available, but build a simpler chart for readers who mainly want to understand the increase relative to 1990.

## Step 3: Paper sketch and initial design

I began with a hand-drawn line chart showing the greenhouse gas index from 1979 onward. My three intended changes were:

1. Focus on one overall index line rather than the multiple measurements in the source visualization.
2. Emphasize 1990 = 1.00 as the reference, so readers understand what the index values mean.
3. Label the latest value so the size of the increase is clear without requiring readers to estimate it from the axis.

**Paper-sketch photo:** [Add photo of my original hand-drawn sketch here before final submission.]

## Step 4: Feedback and revisions

I showed my proposed design in our in-class critique. One suggestion raised during the discussion was to consider adding more lines, as in the original NOAA visualization. I considered this but decided to keep just the index line because adding other measurements would make the specific comparison with 1990 harder to see.

**Individual feedback still to document:** [Add two short, anonymized accounts from two people who actually reviewed the sketch, including what each person said. Do not include names.]

I used the discussion to rethink how to show the comparison clearly. Rather than adding more lines, I kept the overall trend and added an orange horizontal line at 1.00, a marked reference point at 1990, and a label showing the final value. These changes explain the significance of the line rather than adding information unrelated to the main question.

## Step 5: Final visualization

### How Much Has the Greenhouse Gas Index Increased Compared with 1990?

<iframe title="NOAA greenhouse gas index redesign" aria-label="Line chart showing the NOAA greenhouse gas index from 1979 to 2025" id="datawrapper-chart-LfzIX" src="https://datawrapper.dwcdn.net/LfzIX/1/" scrolling="no" frameborder="0" style="width: 100%; min-width: 100% !important; border: none;" height="430" data-external="1"></iframe>

[Open the published Datawrapper chart](https://datawrapper.dwcdn.net/LfzIX/1/)

I made the final visualization in Datawrapper using annual NOAA AGGI data. The line shows the overall pattern across time. I added the horizontal reference line at 1.00 and marked 1990 to show where the comparison begins. The 2025 annotation identifies the index of approximately 1.56 and the 56% increase relative to 1990.

I chose not to fill the area below the line because the main point is the **change relative to the reference year**, not the accumulated area. I kept the trend line blue and used orange for the baseline so the comparison stands out. The result is intentionally narrower than NOAA's original chart: it sacrifices some scientific detail in exchange for a quicker, clearer answer to one question.

## Sources

- [NOAA Global Monitoring Laboratory — Annual Greenhouse Gas Index](https://gml.noaa.gov/aggi/aggi.html)
- [Final visualization created with Datawrapper](https://datawrapper.dwcdn.net/LfzIX/1/)

## AI acknowledgement

I used ChatGPT to understand the assignment, help prepare and format the NOAA data for Datawrapper, troubleshoot chart settings, and organize and revise my written explanation. I made the design decisions and built the visualization in Datawrapper. I reviewed the final chart and its labels.
