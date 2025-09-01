# Before You Read

This repo hosts a proposal to improve the accountability of our academic review system.  

- 📌 **Core idea**: Multi-year submission bans for irresponsible reviewers.  
- 💬 **Discussion**: Please share your thoughts (especially limitations and risks).  
- ⭐ **Support**: If you agree with the proposal, consider starring this repo to signal support.  
- 🔗 **Full proposal**: See below.

# Fixing the Broken ML Review System: A Proposal for Reviewer Accountability

## 1. Motivation: The Current Crisis in Academic Review

The machine learning conference review system is fundamentally broken, creating an unsustainable environment that threatens the integrity of our scientific community. Since submission volumes continue to grow exponentially, we face an increasingly dire situation where the quality of reviews has deteriorated to unacceptable levels.

### The Core Problem

The principle of "great power comes with great responsibility" has been abandoned in our review system. Reviewers have tremendous power over researchers' careers, determining whether papers are accepted at prestigious venues, yet operate without meaningful accountability. This power imbalance has created a system full of irresponsible behavior, including late reviews, inadequately justified scores, and complete non-engagement with the rebuttal process.

### The Gresham's Law Effect

Perhaps most troubling is the emergence of a Gresham's Law dynamic: responsible reviewers, repeatedly frustrated by receiving poor reviews for their own submissions, either leave the field or become irresponsible reviewers themselves as the only way to create "fair trade." This creates a vicious cycle where the proportion of irresponsible reviewers increases year over year, accelerating the system's decline.

### The Gambling Problem

The current system has devolved into a lottery where paper acceptance depends largely on reviewer assignment rather than scientific merit. Authors increasingly treat submissions as "gambling opportunities," exploiting the system to obtain free reviews while hoping for favorable reviewer assignments. This undermines the fundamental purpose of peer review as a quality assurance mechanism.

### Why Action is Urgently Needed

Without immediate intervention, we risk complete breakdown of the peer review system that underpins scientific progress in machine learning. The mandatory review requirements linking authorship to reviewing, designed to create a sustainable, reciprocal system, cannot function effectively without accountability mechanisms. The intellectual rewards of receiving quality reviews for one's own work are meaningless when those reviews are consistently inadequate.

## 2. Recent Attempts at Reviewer Accountability

Several major conferences have recently implemented policies to address reviewer misconduct, representing the first systematic attempts to introduce accountability into the peer review process.

### Desk Rejection Policies Across Conferences

Multiple conferences in 2025 adopted desk rejection policies for papers authored by irresponsible reviewers: CVPR 2025 ([19 papers rejected](https://x.com/CVPR/status/1894853624200863958)), ICCV 2025 ([29 papers](https://x.com/ICCVConference/status/1937933918918815890)), NeurIPS 2025, and the upcoming ICLR 2026. Besides, ICML 2025 has also mentioned the desk rejection policy in the call for paper, but there is no official information about how the policy is implemented. There is only one unofficial [LinkedIn post](https://www.linkedin.com/posts/omerbp_seems-like-the-icml-program-chairs-have-found-activity-7310555232818675712-f7Z1/) about 1 desk rejection case.

### EMNLP 2025's Enhanced Approach

EMNLP 2025 took a more comprehensive approach by extending consequences beyond a single conference. Their system includes a ban that applies both to the current conference and the next ARR cycle ([ARR incentives policy](https://aclrollingreview.org/incentives2025)). They also established [clear guidelines](https://2025.emnlp.org/reviewer-policies/) defining irresponsible reviewer behavior. Despite these enhanced measures, they ultimately [desk-rejected 69 papers](https://2025.emnlp.org/desk-rejection/).

### Analysis of Current Limitations: The NeurIPS 2025 Case

While these efforts represent progress, NeurIPS 2025's experience reveals fundamental limitations in current approaches that apply to all single-conference penalty systems:

#### Loophole 1: Low-Stakes Gambling

The desk rejection penalty merely reduces acceptance probability without imposing serious consequences. Authors can still "gamble" with the system, submitting papers to obtain free reviews and hoping for favorable outcomes, with only modest downside risk.

#### Loophole 2: The Withdrawal Escape Hatch

Reviewers who have already withdrawn their submissions face no consequences from desk rejection policies. This was evident during NeurIPS 2025's discussion phase, where extending deadlines and re-emphasizing penalties failed to engage many silent reviewers who had likely already withdrawn their papers.

#### Loophole 3: Insufficient Oversight Capacity

The sheer volume of submissions makes comprehensive quality control impossible. Despite Area Chairs being tasked with filtering low-quality reviews before release, incidents like the infamous "who is Adam" review demonstrate that many problematic cases slip through due to insufficient oversight resources.

### Lessons Learned

These conference-specific penalties, while a step forward, cannot address the systemic nature of the problem. Even EMNLP's extended approach covering two review cycles remains insufficient given the multi-year nature of academic careers. More comprehensive, multi-conference coordination with stronger deterrents is necessary to create meaningful change in reviewer behavior.

## 3. Proposed Solution: Multi-Conference Accountability Framework

We propose implementing a coordinated accountability system across the three premier ML conferences (NeurIPS, ICML, and ICLR) that imposes meaningful consequences for irresponsible reviewing behavior. Crucially, this system requires maintaining the mandatory review requirement that links authors and reviewers. This connection is the foundation of our proposed accountability framework, without it, the reciprocal nature of the system breaks down and sanctions lose their rational basis.

### Core Sanction Mechanism

**Multi-year conference exclusion**: Reviewers found guilty of serious misconduct would be banned from participating in all three conferences (either as authors or reviewers) for 1-3 years (exact duration to be determined through community discussion).

**Rationale**: Since academic careers in ML depend heavily on publications at these venues (PhD graduation requirements, tenure decisions), this creates a strong deterrent that matches the power reviewers have over others' careers.

### Clear Guidelines for Irresponsible Behavior

To ensure fair implementation, we must establish measurable, unambiguous criteria for misconduct. The following represent key examples of clearly identifiable violations, though additional criteria can be developed through community input:

**Timeline Violations**:

- Late review submission without AC approval
- Non-engagement in rebuttal discussion phase
- Emergency exceptions require clear AC communication and, in disputed cases, documentation. Reviewer will be provided with an "Emergency" button on the system, similar to [ARR](https://aclrollingreview.org/reviewerguidelines#emergency).

**Unjustified Scoring**:

- Providing scores without adequate justification that aligns with conference scoring guidelines (e.g., NeurIPS 2025 defines score 2 as "technical flaws, weak evaluation, inadequate reproducibility" - reviewers must identify specific instances of these issues)
- Maintaining scores after acknowledging that concerns have been resolved without adjusting scores upward when appropriate (e.g., responding with "My concerns have been resolved, but I maintain my score" without providing new justification)

These rules represent basic standards for a healthy academic community, similar to how laws define minimal moral standards in society. Even if we initially focus on punishing only the most obvious cases, this approach can send a powerful message to other reviewers engaging in subtler forms of misconduct that are harder to detect. The threat of potential sanctions and the possibility of additional rules being added to guidelines in future years will encourage reviewers to reconsider their behavior before submitting irresponsible reviews.

Additional guidance on responsible reviewing practices can be found in established reviewer policies, such as those outlined by [EMNLP 2025](https://2025.emnlp.org/reviewer-policies/).

### Implementation Process

#### Before the Review Period

- **Guideline Updates**: PCs update the official guidelines and clearly mention the new policy and the definition of irresponsible reviewer.
- **Review Quality Committee Formation**: PCs invite responsible people to form the Review Quality Committee (RQC). Members of the RQC should be familiar with the guideline and have good knowledge about how to write a good review. Potential candidates can be drawn from the best reviewers from past conferences.
- **Reviewer Assignment and Acknowledgment**: Authors who submit their paper to the conferences need to assign one author from the author list to serve as the reviewer. The chosen reviewer needs to acknowledge on the system that they have read carefully about the reviewer guideline and fully aware of the consequences of irresponsible behaviors. Papers that fail to finish these steps before the review period starts will be desk-rejected immediately. There will be a buffer of a few days between the submission deadline and the starting of review period for late submissions to complete the procedure.

#### During the Review Period

The irresponsible behaviors can appear in all the processes, so the RQC needs to operate throughout the review period. In general, a decision for sanction follows four steps: reviewer is flagged → reminder and warning is sent to the flagged reviewers by ACs → review fail to respond will be escalated to RQC for judging → decision concluded by the RQC, and if the decision is sanction, the sanction takes effect immediately.

**Flagging the Reviewer** There will be three ways to flag the reviewers:

- Automatic flagging for delayed reviews and rebuttal-discussion without emergency justification.
- The ACs can flag the reviewer based on their judgment.
- The authors can also report the reviewer on their side but with a lower weight. For a reviewer, if more than 50% of the reviews they provided are reported by the authors, they will then be flagged.

When doing the flag or report, a set of options will be available, e.g. late response, to classify the type of irresponsible behaviors.

**Reminder and Warning** Once the reviewer is flagged, ACs need to remind the reviewer to complete their task properly within a period of time and warn about the potential consequence if fail to do so. A template of this reminder should be available to the AC beforehand to ease their job.

**Escalated to RQC** If the flagged reviewer fails to complete their task properly even after the reminder and warning, AC can choose to escalate the case to the RQC. RQC will decide, based on the information available so far, whether the reviewer is entitled for a sanction.

**Sanction Taking Effect** If the RQC decides to make a sanction, it takes effect immediately:

- The papers associated with the sanctioned reviewer will be desk-rejected immediately, and all the authors involved in these papers will be notified about this decision and the cause of this decision.
- The reviews that this reviewer provided will be marked on the system, and the ACs will be instructed to take these reviews with caution or ignore the reviews.
- The account of the sanctioned reviewer will be marked and prevented from submitting during the sanction period.

#### After the Review Period

To facilitate the fairness of such system, we should make the process transparent. PCs and the RQC need to provide a detailed document about all the sanctioned cases during this conference regarding the decision process and make the document public after the review period. Ideally, this document will demonstrate the determination of the conference and showcase the fairness of the system. Of course, the community can form discussion regarding the results and in edge cases make appeal if they find injustice. The discussion will be considered as feedback for the guideline of the next conference.

## 4. Potential Limitations and Considerations

### Increased Reviewer Burden Concerns

**Concern**: Stricter enforcement might seem to place additional burden on reviewers, requiring them to spend more time and effort on their reviews.

**Response**: This concern misunderstands both the nature of reciprocal systems and the long-term benefits of quality improvement. First, in a reciprocal review system, the additional effort is simply the price reviewers pay to receive high-quality reviews for their own work. Second, stricter standards will primarily affect irresponsible reviewers in the short term—those already providing quality reviews will see no additional burden since they are already meeting these standards. Third, and most importantly, enforcing quality standards will reduce the overall reviewing effort in the long run. Currently, conferences require 4-5 reviews per paper because reviews are too noisy and contain many low-quality assessments. If all reviewers provide high-quality reviews, 2-3 reviews would be sufficient to accurately judge paper quality, reducing the total reviewing load across the community.

### The Chilling Effect Risk

**Concern**: Overly harsh enforcement might discourage constructive criticism, leading reviewers to provide superficial, non-controversial reviews to avoid flagging.

**Mitigation**: Transparent decision-making with clear rationales and community oversight should distinguish between legitimate critical reviews and irresponsible behavior. The guidelines must explicitly protect rigorous but fair criticism.

### Implementation Challenges

**Cross-Conference Coordination**: Requires unprecedented cooperation between conference organizers and potentially complex legal and policy frameworks.

**Resource Requirements**: Establishing specialized review committees and transparency systems demands significant community volunteer hours.

**Edge Case Complexity**: Real misconduct cases often involve nuanced situations not easily captured by simple rules.

### Non-Author Reviewer Accountability

**Concern**: The accountability system cannot be applied to reviewers who are truly volunteering, i.e., those who don't have submissions to the conference and thus cannot be sanctioned through multi-year submission ban.

**Response**: This concern can be addressed from two perspectives:

- **Limited Need for External Volunteers**: The reciprocal review system should be self-sustaining. If every paper provides one reviewer to review n papers, then every paper can receive n reviews. This means we need few or no external volunteers to compensate for low-quality reviews.
- **Indirect Sanctions Still Apply**: While we cannot ban their authorship, we can still prevent sanctioned volunteers from reviewing for several years. Since every submission needs to provide a reviewer, if a sanctioned volunteer wants to submit papers to future conferences, they need someone else in the author list to serve as the reviewer, making submission slightly more difficult.

### Area Chair Accountability Gap

**Concern**: Area Chairs play a critical role in the decision process but currently serve on a voluntary basis, making it difficult to hold them accountable for misconduct.

**Potential Solutions**: Two approaches could address this limitation:

- **Financial Compensation**: While paying all reviewers is impractical due to their large numbers, compensating Area Chairs could be feasible using conference registration fees. This would create a professional obligation framework for AC responsibilities. 
- **Mandatory AC Duty**: Similar to mandatory reviewer requirements, we could implement a system where researchers accumulate AC obligations based on their submission history. For example, for every 10 papers submitted across conferences, authors would be required to serve as AC once. This would link the AC role to authorship, enabling similar accountability measures when ACs behave irresponsibly.

### System Gaming

**New Loopholes**: Determined bad actors will likely find ways to circumvent new rules, requiring constant system evolution.

**False Flagging**: Authors might abuse flagging systems to retaliate against legitimate negative reviews.

## 5. Conclusion and Next Steps

This proposal represents a perspective from within the research community on addressing a critical problem. The complexity of implementing such a system across multiple conferences and international institutions requires extensive community consultation, legal review, and pilot testing.

The machine learning community faces a choice: continue accepting the deterioration of our review system or take decisive action to restore accountability and scientific integrity. While this proposal may require significant refinement through broader community input, the urgency of the situation demands that we begin this conversation immediately with community-wide discussion and feedback collection.

_Note: This proposal reflects perspectives from within the AI research community and requires extensive community discussion, policy expertise, and legal consultation before implementation. LLM is used to reorganize and polish the raw text._

## Acknowledgment

I would like to thank (in alphabetical order) Alexandros Paraschos, Guangyao Zhai, Marvin Alles, Michelle Plötner, Patrick van der Smagt, Philip Becker-Ehmck, Renzi Wang for their helpful discussion during the preparation of this proposal.  