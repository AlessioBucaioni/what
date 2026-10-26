# Codebook: themes and codes



Seven themes and 25 approved codes. Evidence references retain their IDs; I3 source text is withheld.



## Themes



### T01 Acceleration redistributes architectural effort and can expand demand

Participants describe quicker production and exploration, while effort shifts toward specifying, understanding, reviewing and coordinating work; the time saved can support additional ambitions and workload rather than simply reduce work.

Core codes: K01, K02, K15, K18

Supporting codes: None



The central pattern is a changed distribution of effort. Producing a first artifact or exploring an implementation becomes easier in several accounts, but that artifact still has to be made appropriate and understandable. I7 describes planning and review becoming more prominent as generation shortens the build phase. I4 describes faster arrivals of work requiring review; I8 connects additional ideas with additional workload. These accounts make acceleration an input into architectural work rather than an uncomplicated end-to-end outcome.

The wider possibility is increased ambition: recovering undocumented architecture, attempting modernization, trying alternatives and discarding a first implementation become more feasible. Some participants expect administrative effort to shrink or stakeholder engagement to increase. Those future reallocations remain separate from reported present practices. The theme therefore joins initial speed, correction costs, shifted attention and demand growth without claiming that every participant experiences every part of the pattern.

T01 concerns the allocation and volume of effort. The reliability of steering knowledge is T02; who answers for outcomes is T03; contextual judgment and risk significance are T07; designing delivery is T05; learning and meaningful work are T06.

I3 reports a complex generated solution that took more effort to understand than direct production (E012) and explicitly calls for end-to-end experiments (E008). I10 describes a quicker first attempt despite incorrectness (E188). These qualify universal efficiency claims while supporting the broader redistribution pattern.

K01 alone would yield a benefit summary. Comparing it with K02/K15/K18 produces an organizing explanation of where work goes after generation becomes cheaper. Failure and increased workload are part of the pattern, rather than exceptions to be removed. Legacy modernization is retained as a variation in what becomes feasible, not forced into a separate theme.

### T02 Architectural knowledge becomes a means of steering and checking AI-assisted work

Architecture knowledge is valued not only as documentation for people but as context, constraints and checkable intent for agents; making it explicit does not ensure that it is complete, usable or reliably applied.

Core codes: K05, K09, K10, K25

Supporting codes: None



The organizing concept is the changing use of architectural knowledge. Participants describe recovering knowledge from code, sharing it within teams, and making decisions and principles consumable at the relevant points of an agent workflow. I7 describes engineers inspecting previously opaque layers with AI help. I9 reports colleagues using architectural decision records to constrain generation. I1 describes the difficulty of turning a file of instructions into reliable agent behavior. This connects access to knowledge with its operational use.

The challenge extends beyond writing more documentation. I12 distinguishes tacit experience from even extensive written records; I13 distinguishes written requirements from the drivers of architectural judgment. I11 raises diversity and gaps in architectural representations. These accounts suggest that knowledge can be documented yet remain incomplete for machine use, or be machine-readable yet insufficiently enforced. The proposed control pattern is an analytic synthesis of these accounts, not a validated assurance architecture.

T02 concerns the availability, representation and agent use of architectural knowledge. T03 concerns review, acceptance and answerability. T07 concerns the contextual interpretation and risk judgment attributed value beyond representation. T05 concerns stages, coordination and organizational arrangements rather than a knowledge artifact alone.

I4-S2 appraises help at every level (E068), qualifying a uniform implementation-versus-strategy capability gradient. I12 warns that excessive constraints can reduce useful capability (E245). Tacit judgment in E243 qualifies the idea that comprehensive documents alone solve the control problem.

K10 retention/retrieval, K09 steering and K25 representation remain distinct approved codes. They form a theme because their relationship explains why knowledge changes from a passive record into a resource for directing and scrutinizing agents. K05 contributes a condition: local implementation assistance can be useful while whole-system architectural reasoning remains contested.

### T03 Delegating execution leaves human oversight and answerability in place

Participants distinguish AI performing tasks from people reviewing, accepting and remaining answerable for outcomes. Human decision control is retained in several accounts, while who can meaningfully take responsibility remains contested and conditional.

Core codes: K04

Supporting codes: K03



The organizing claim concerns the allocation of control and answerability, rather than the value of expertise. I8 separates AI execution from human accountability and locates the latter with engineers. I7 describes protected changes requiring architect review and a human review gate before production. I12 distinguishes accountable role-holders from those carrying out tasks, and reports architects using AI for alternatives while keeping decisions under human control. These accounts do not imply that every responsible person holds the architect title.

Verification provides a mechanism through which oversight is exercised, but verification methods and responsibility remain distinct. I4-S1 checks AI-assisted assessments personally; I2 tests and corrects generated programs; I10 describes an architectural review regardless of how implementation was produced. AI can also participate in checking. K03 therefore supports the theme without turning every checking practice into evidence of a particular accountability allocation.

The allocation is neither universal nor settled. I10 describes existing team responsibility and a conditional tension: orchestration can make taking responsibility harder while increasing the perceived need for it. I11 wants human sign-off retained; that is a preference, not a forecast. Validated explanations and cheaper checks are imagined as conditions that could reduce human involvement. Participant claims about accountability are treated as role interpretations, not independently verified legal duties.

T03 asks who reviews, approves or answers for AI-assisted outcomes. T07 asks why contextual architectural expertise is valued. T02 concerns the knowledge supplied for steering and checking; T04 concerns task distribution, professional interaction and role boundaries; T06 concerns developing the capacities used in oversight. Review, decision authority and accountability are not interchangeable.

I10 describes existing team responsibility rather than a sole architect owner (E190). AI-assisted verification occurs (E224), and I12 considers the testing regimen independent of who wrote the code (E242). E197 raises a conditional responsibility problem; E214 is a wish to retain sign-off; E203 conditions reduced human involvement on correct, validated explanations and cheaper checks.

Narrowed from v0.3 T03 in response to the author’s critique. K04 provides the central allocation claim; K03 contributes assurance mechanisms as a supporting code. The value claims and risk-significance properties move to T07. A person can remain answerable without thereby demonstrating special value, and a valued expert need not hold formal sign-off authority. The six-code predecessor is preserved in v0.3.

### T04 Architectural work can become more distributed without a uniform disappearance of the architect role

Participants distinguish architecture as work from architect as a title: some describe broader engineer ownership and altered interaction, while others retain dedicated architects and established role boundaries.

Core codes: K12, K13, K21

Supporting codes: None



The organizing distinction is between the architectural function and its organizational location. I6 describes engineers partially taking over exploration; I8 describes an engineering owner spanning design, implementation and testing, and reduced routine communication. I13 interprets engineering work moving closer to architectural responsibilities while resisting the interviewer’s suggestion of a new role. I7 describes AI being referred to as a colleague. These accounts show several possible forms of redistribution and mediation, not one model of replacing architects.

Access to knowledge, apparent competence, task ownership and decision authority can change differently. I1 discusses superficial AI-supported influence but says the authority effect has not happened to them. I4 reports uncritical junior submissions rather than juniors challenging seniors. I10 reports no observed role reallocation in an already collaborative senior setting. I12 reports retained roles and no perceived decrease in hiring, with greater convergence between product management and development than between architects and developers. These contrasts are integral to the theme’s claim of uneven redistribution.

T04 concerns who performs architecture work and how professional interaction, influence and role arrangements vary. T03 concerns allocation of approval and answerability; T07 the attributed value of contextual expertise; T05 the delivery process as a design object. A job-title observation alone does not establish changed work or authority.

I10 did not observe role reallocation (E191); I12 does not see reduced architect/developer hiring (E240). I8 lacks a reliable pre-AI comparison within the current company. I13 does not offer a concrete first-hand bypass case (E255). External layoff/rehiring rumors (E148/E175/E176) are not used to establish an employment trend.

K12/K13/K21 cannot be reduced to a single authority variable: apparent influence, communication and work ownership are different properties. The theme draws them together through the architecture-function versus architect-role distinction. Contrary cases prevent a title-disappearance narrative and show why existing organizational arrangements matter.

### T05 AI-assisted delivery becomes an architectural design problem

Beyond architecting the target software, participants describe or envisage shaping the delivery arrangement itself: coordinating people and agents, setting permissions and boundaries, sequencing work, sharing feedback and managing the terms and costs of AI use.

Core codes: K11, K22, K26

Supporting codes: None



The organizing concept is an expanded object of architectural attention: the system that builds the software. I6 articulates the combination of people and AI as an organizational design concern. I10 describes current manual work decomposition that places engineers in charge of agents, while imagining staged agent orchestration. I7 reports centralized review criteria updated through a team feedback loop. Those mechanisms concern the arrangement of delivery, rather than merely supplying one agent with instructions.

Delivery arrangements are also bounded by adoption permissions, organizational readiness and commercial terms. I3 describes client-specific approved use; I4 describes an enterprise proxy and questions about remuneration and tool-cost allocation; I6 reports policy work and cost stewardship. These are enabling and constraining conditions, not evidence of a universally expanded mandate. Several collaborative or orchestration capabilities remain desired or hypothetical, and I7 questions vendor-prescribed processes rather than reporting a settled model. K22 contributes a narrower material/commercial property; its hearsay about rehiring costs is not used to establish outcomes.

T05 concerns process architecture and the organizational/material conditions of using AI. T02 concerns knowledge supplied to agents; T04 redistribution among professional roles. Embedding an AI feature in a delivered product is P01, a related but different architectural object.

I6 reports limited team-level adoption in an immature context (E112). I7’s team feedback loop (E149) contrasts with unmet collaboration wishes (E125/E205). I12 warns that constraints can suppress capability (E245). I10’s orchestration examples and I4’s upstream role account are largely prospective; they do not prove a fully autonomous delivery system exists.

K26 would be too narrow as a stand-alone one-code theme. Combining it with the organizational and material conditions in K11/K22 yields a process-design theme. Governance alone would be a topic summary; the central claim is that permissions, coordination, staging and AI use are part of the architectural object being shaped. T04 remains separate because a different process can coexist with stable job titles.

### T06 Sustaining expertise and agency becomes a problem of work and learning design

Participants connect continued human involvement with opportunities to develop judgment and retain purpose, creativity and enjoyable work; AI assistance can support learning and enjoyment as well as raise concerns about review-only work and access to experience.

Core codes: K19, K20

Supporting codes: None



The organizing concern is how the human contribution can be reproduced and sustained when generation is delegated. Participants ask how newcomers gain the experience needed to assess unfamiliar designs, and describe mentoring, critical questioning, explanations and team review. I5 demonstrates errors in teaching; I4-S1 prompts for explanations and challenges; I10 describes gradually more open-ended team-reviewed work. These accounts propose or practice ways to support judgment without demonstrating their long-term learning outcomes.

The issue also concerns the character of work. I7 reports colleagues enjoying creation more than review and advocates retaining enjoyable tasks for people; I5 values purpose, agency and creativity. The positive cases matter: I7 reports learning from a discarded generated solution, I5 sees exploration as supporting creativity, and I13 describes rediscovering the joy of coding. The theme therefore identifies a work-design problem, not inevitable deskilling or alienation. Practical prompting proficiency is one property of adaptation, not a substitute for architectural judgment.

T06 concerns developing and sustaining expertise, agency and meaningful participation. T03 concerns exercising oversight and allocating answerability; T07 the value attributed to contextual judgment; T01 workload and effort; T04 staffing and task ownership. A learning activity alone does not establish successful skill acquisition.

I4-S2 argues that training principles remain unchanged (E082). I10 hopes learning through review can reduce the need to write every line manually (E201), qualifying the struggle-only view in E107. I7 reports learning from a discarded solution (E273), and I13 reports renewed enjoyment (E264). Future erosion and morale loss are not measured outcomes.

K19 and K20 remain separate codes because capability formation differs from purpose and enjoyment. They form a theme through the design of continued human participation: retaining oversight requires attending to what people can learn and what work they are asked to do. The evidence supports a concern and alternative pathways, not a causal demonstration that agency improves correctness.

### T07 Architectural value lies in contextual judgment and risk stewardship

Participants attribute architectural value to interpreting business and system context, weighing consequential trade-offs, negotiating stakeholder needs and reasoning about risks that generated artifacts alone may not capture. Some see cheaper technical reversal as shifting attention toward business consequences, while stakeholder purpose is described as continuing.

Core codes: K27, K24, K23

Supporting codes: K08



The organizing question is what makes an architectural contribution worthwhile in AI-intensive development. I8 emphasizes domain knowledge and understanding what the system does. I1 retains human negotiation of stakeholder trade-offs; I2 describes prioritizing alternatives as a current limit in preliminary testing; I6 describes clarifying the important decisions and options as valued. I9 links business interpretation to architectural requirements. These are situated attributions of value, rather than measurements of human superiority or increases in formal authority.

Risk stewardship explains which judgments participants consider consequential. I13 interprets easier rewriting as reducing the significance of some technology choices while making real business needs and different risks more important. I1 and I10 qualify the inference that reversal is universally cheap: non-code work, long product lifetimes and regression control still matter. Reversibility is therefore a condition shaping perceived significance, not a finding that technical architecture has become unimportant.

Contextual judgment also involves reasoning that an artifact may fail to represent. I13 describes moral, ethical and business considerations beyond written requirements. I6 questions whether automatically generated safety documentation preserves the reflection that writing was meant to prompt. These accounts identify a valued reasoning contribution; they do not establish unsafe outcomes or legal obligations. K08 supplies continuity in stakeholder purpose and architectural method. It supports the value claim without becoming a separate claim about who is accountable.

The theme allows AI assistance in judgment: I13 suggests that AI can help quantify trade-offs, and conditional accounts of validated explanations leave future human involvement open. The distinction is between producing an option or artifact and judging its significance in context, without claiming that only humans could ever make such judgments.

T07 concerns attributed value and the basis for contextual judgment, not formal accountability or sign-off (T03). T02 concerns the representation and operational use of knowledge, whereas T07 concerns judging meaning and significance with that knowledge. T06 concerns sustaining the capacities for such contribution. K08 is a supporting continuity code, not an assertion that all architectural methods are unchanged.

AI can assist trade-offs (E253). Validated explanations could change human involvement (E203). Rewriting is not universally cheap or suitable (E060/E195/E198). E049 expresses desired preservation of purpose; E019/E020/E174 are professional interpretations. Attributed centrality (E256) is not demonstrated increased authority or measured comparative performance.

New theme separated from v0.3 T03. K27 supplies contextual judgment and risk stewardship; K24 explains a condition changing perceived architectural significance; K23 develops the value of reflective reasoning rather than documents alone. K08 supports continuity in purpose. Each develops the same value claim; none is used to infer formal authority. T03 and T07 can share a contextual excerpt for different, explicitly stated analytic purposes. They are related, not mutually entailing.

### X01 Role trajectories remain conditional on capability and adoption

Changing appraised usefulness, continuing skepticism and conditional future capabilities qualify the direction and pace of the thematic structure. The analysis does not establish a common adoption-stage model or a fixed future role.

Core codes: K16, K17

Supporting codes: None



Treating capability and adoption as a cross-cutting qualifier avoids a generic future/adoption theme that duplicates substantive claims. Specific conditions remain traceable, with explicit contextual contributions to RQ1 and RQ4.

### P01 Architecting AI-containing products is a related extension of architectural work

Participants connect AI-containing products with nondeterminism, security, assurance and new technical expertise. This concerns architecture of the delivered product, distinct from using AI to develop it.

Core codes: K14

Supporting codes: None



The formal methodology places architecting AI-enabled systems at the periphery of the study. Retain this finding visibly, but do not force a one-code product theme into the central account of GenAI-assisted architectural work.

## Codes



### K01 Accelerated production and exploration

Participants describe or appraise faster production and exploration of architectural or technical material, including advice, research code, specifications, documentation, technical options and codebase understanding.

Include: Reported production/exploration and explicit opinions about these benefits. Preserve task, organizational context and account type; speed claims need no implication of measured gains.

Exclude: Net efficiency and correction costs belong to K02; verification processes to K03. Do not assume all artifact types or projects become faster.

Qualifications: The original contextual qualifications still apply. I4 extends investigation to large undocumented systems and describes specification generation; I6 reports technology-option exploration. I5’s documentation claims are opinions, not industrial outcomes. K02/K18 qualify speed benefits.

Theme: T01

Evidence IDs: E001, E002, E003, E004, E067, E068, E076, E078, E079, E099, E100, E105, E108, E111, E136, E144, E158, E173, E188, E211, E231, E239, E274



### K02 Qualified efficiency gains

Perceived initial speed gains may be offset or left uncertain by interpreting, correcting and validating generated output; a complex solution can cost more effort than direct work.

Include: Initial generation speed alongside accuracy or end-to-end-effort qualifications, and reported unsuccessful complex-output attempts.

Exclude: Do not infer measured end-to-end gains. Verification activity itself is K03; responsibility for review is K04.

Qualifications: E007 is a colleague report with the participant’s own appraisal, including an unmeasured 80% estimate. E012 is a direct failed-use case; both are retained within this broader code.

Theme: T01

Evidence IDs: E007, E008, E012, E103, E133, E143, E188



### K03 Verification around AI-assisted work

AI-assisted work involves verification and refinement: GenAI can cross-check human work, while people or assisted workflows check generated output, architectural alignment and behavior. Reported checking, proposed assurance mechanisms and future expectations remain distinct.

Include: Second opinions, tests and correction; architecture-level/team review, conformance/traceability checks, fitness functions and runtime observations; distinguish proposed automated assurance from reported operational use. Checking includes scrutiny of the evidence behind generated answers and perceived limitations of AI-based checking, such as agreement with the questioner. Preserve specific failure modes as properties; they do not demonstrate calibrated trust or a reliable checking mechanism.

Exclude: Responsibility/approval is K04; encoding reasoning so it can be checked is K25; no suggestion or nested-AI checking scheme establishes proven safety or correctness.

Qualifications: Earlier current/normative/future checking distinctions remain. I10 describes staged team reviews; I9 proposes fitness functions/observability and I11 proposes traceability or nested checking. I12 argues the same testing regimen can apply to human/AI code; these are not independent safety guarantees.

Theme: T03

Evidence IDs: E005, E006, E009, E010, E011, E048, E075, E076, E078, E083, E087, E091, E097, E103, E126, E149, E159, E160, E179, E200, E206, E211, E216, E218, E224, E235, E242, E265, E272



### K04 Human oversight and responsibility for AI-assisted outcomes

Participants assign checking, approval, risk acceptance and responsibility for AI-assisted outcomes to people, while describing delegated execution and concerns about overreliance.

Include: Reviewers, human approval gates, stated retained responsibility/accountability, risk acceptance and clearly labelled overreliance concerns.

Exclude: Checking methods are K03. Do not turn participant responsibility or liability assertions into verified law, formal universal accountability, or established responsibility transfer.

Qualifications: The original qualifications on oversight and accepted risk still apply. I7 reports a company human-review gate; I8 states retained human accountability with AI execution. I6’s liability statement is a participant stance, not a legal finding. I4’s uncritical junior submission is direct, unlike earlier I2 hearsay.

Theme: T03

Evidence IDs: E016, E029, E062, E072, E075, E081, E098, E121, E130, E132, E139, E152, E153, E156, E168, E171, E185, E190, E197, E214, E217, E228, E229, E251, E259



### K05 Uneven impact across architectural work

GenAI is perceived to have greater impact or capability near implementation detail than in architectural direction, strategy and difficult quality decisions.

Include: Experience of detailed agent findings and appraisals comparing implementation-facing and strategic work.

Exclude: Do not infer a universal or measured capability gradient. Human option judgment is K27; future capability contingencies K16.

Qualifications: The assessment is explicitly experience-bound. E004 retains useful codebase understanding as a qualification. I1 does not assert a straight-line relationship.

Theme: T02

Evidence IDs: E004, E016, E017, E018, E063, E068, E091, E102, E189, E212, E215, E236



### K08 Continuity of architectural purpose and method

Participants describe, desire or expect continuity in architectural purpose, usefulness criteria and core design activities despite changing tools, while allowing tool reliance and organizational arrangements to change.

Include: Artifact usefulness, requirements/business-goal frameworks, desired stakeholder fulfilment, and forecasts of continuing high-level design.

Exclude: Do not treat desired or expected continuity as observed practice, or imply every method and organizational arrangement remains unchanged.

Qualifications: E049 is a desired future; E053 an expected future. E054–E056 qualify continuity with growing tool reliance, replacement skepticism and conditional organizational change. Context-dependent frameworks are not universal processes.

Theme: T07

Evidence IDs: E019, E020, E049, E053, E054, E055, E056, E101, E130, E137, E151, E168, E170, E174, E178, E190, E232



### K09 Explicit architectural knowledge for steering agents

Explicit architectural intent, decisions and principles, made usable at appropriate agent-workflow points, are proposed as conditions for retaining control over autonomous development.

Include: Recommended explicit knowledge, workflow injection, and reported difficulty making simple file-based instructions effective.

Exclude: Do not infer validated control mechanisms. Knowledge retention/retrieval and expert interaction are K10. Feasibility/limits of encoding architectural reasoning are K25; actual conformance checking is K03. Constraints may also limit useful capability, so do not presume tighter is always better.

Qualifications: The account combines conditional advice and limited experimentation. Explicit intent and reliable application are related but remain distinguishable requirements.

Theme: T02

Evidence IDs: E038, E039, E040, E041, E080, E084, E085, E101, E140, E159, E170, E172, E173, E179, E192, E194, E202, E221, E232, E235, E236, E237, E245, E246, E274



### K10 Retaining, retrieving and using architectural knowledge

Participants describe or envisage preserving, reconstructing, linking, retrieving and using architectural knowledge, including expert interaction and team knowledge access or circulation.

Include: Private/in-house retrieval, tacit considerations, undocumented-system reconstruction, expert knowledge tools, team access and knowledge-sharing through review.

Exclude: Do not assume retrieved code explains all business rationale or that all tools are GenAI. Explicit agent constraints are K09; tasks/role transfer K21.

Qualifications: Earlier private knowledge proposals remain hypothetical/expected; E044 attribution is author confirmed under D006. I4-S3 and I7 provide current knowledge-reconstruction/sharing accounts. I8’s search example is company information of unspecified type. Accessible knowledge need not transfer review authority.

Theme: T02

Evidence IDs: E042, E043, E044, E061, E078, E127, E131, E137, E149, E158, E181, E205, E207, E215, E237, E243



### K11 Governance and organizational conditions of adoption

Safety context, permissions, policies, organizational readiness and architectural governance work shape adoption, alongside desired future AI regulation or standards.

Include: Restricted artifacts, enterprise permissions/proxies, client agreements, organizational maturity, policy drafting and adoption rules, plus clearly distinguished future formalization views.

Exclude: Do not infer an absolute ban, changing client authority, or verified legal requirements. Outcomes oversight is K04.

Qualifications: The client and safety conditions still apply. I6 reports writing AI policy and limited team adoption in an immature setting; I7 reports organizational policy and review gates. Compliance claims remain participant accounts, not audits. Costs/remuneration are K22.

Theme: T05

Evidence IDs: E013, E014, E027, E028, E057, E058, E069, E090, E108, E112, E118, E119, E139, E185, E195, E199, E208, E223, E233, E242, E261



### K12 Influence and authority in AI-assisted work

AI-assisted apparent competence and one-sided briefing are perceived as affecting influence in architectural discussion; architects lacking current delivery-tool expertise are advised to learn from and defer to delivery teams.

Include: Perceived superficial technical influence, conditional political scenarios and advice about architect/team boundaries.

Exclude: Do not assert demonstrated authority redistribution. Expectations and personal communication are K13; oversight responsibility K04.

Qualifications: I1 expressly says the authority/accountability effect has not happened to them (E025). Deferring to teams is conditional advice (E030), not reported delegation. The unclear contradictory clause in P0022 remains unused.

Theme: T04

Evidence IDs: E024, E025, E026, E030, E072, E138, E193, E230, E251, E255



### K13 Changing expectations and relationships

Participants describe continuity or change in communication, professional relationships, perceived AI participation in teams and expectations of collaborators, including maintaining a personal voice, agent-use expectations and individual versus shared working contexts.

Include: Personal communication choices, perceived relational continuity and role-dependent expectations of others’ tool use.

Exclude: Do not infer universal adoption or others’ expectations of the architect. Authority/influence concerns are K12.

Qualifications: I1’s expectations vary between code-facing and senior colleagues. Their reported continuity is self-assessed and does not establish colleagues’ views.

Theme: T04

Evidence IDs: E021, E022, E023, E070, E112, E113, E125, E127, E135, E149, E157, E162, E182, E205, E226, E239



### K14 Architectural value of integrating GenAI into systems

Architectural expertise is perceived as particularly valuable when embedding nondeterministic GenAI features in deterministic systems because of stakeholder, quality and trade-off complexity.

Include: Conditional value claims specifically about AI features in the product/system.

Exclude: Distinguish using GenAI to develop software. Do not infer a universal or demonstrated increase in architect value.

Qualifications: E033 is a conditional opinion; E034 qualifies its scope with continuity in strategic architectural value. The C020-to-K14 succession is an author-requested ID transition, not a multi-code merge.

Theme: P01

Evidence IDs: E033, E034, E089, E090, E114, E152, E244



### K15 Reallocation of architectural effort and modernization choices

Participants report or anticipate shifts from building to planning or reviewing, relief from busywork and wider improvement ambitions, and changed legacy-system analysis, migration or renovate-or-rebuild choices.

Include: Reported and expected changes in task emphasis; architectural refactoring/migration; conditional modernization economics; maintain account types and temporal distinctions.

Exclude: Do not infer current change from forecasts, completed modernization from a possibility, or zero-cost rebuilding. Demand/volume bottlenecks are K18; rebuild hype K27.

Qualifications: I1’s earlier account of modernization and effort reallocation was speculative. I4-S3 now reports bounded client migrations; I7 describes refactoring and planning/review emphasis in their own organization; I5 industry review-shift statements are second-hand. No measured end-to-end efficiency is established.

Theme: T01

Evidence IDs: E045, E046, E047, E059, E060, E079, E085, E088, E094, E136, E140, E144, E186, E196, E198, E202, E204, E231, E234, E247, E260, E262



### K16 Contingency of the future role

Expectations about automation and the future architect role depend on uncertain architectural model capability, access to contextual knowledge, and whether outputs and explanations can be represented and checked reliably.

Include: Uncertain future architectural automation; capability, trustworthy explanation or rigorous-representation conditions that might change human involvement.

Exclude: Do not treat possibilities as predictions of occurrence or present capability. Adoption stance is K17.

Qualifications: Earlier I1 capability speculation remains. I10 asks for correct, validated explanations and cheaper checking; I11 highlights domain knowledge and representation gaps. These are conditions/interpretations, not observed replacement or validated forecasting.

Theme: X01

Evidence IDs: E050, E051, E052, E146, E166, E183, E203, E219, E222, E246



### K17 Adoption trajectory and stance

Participants describe how their stance toward GenAI formed or changed, including gradual acceptance associated with perceived capabilities and continuing skepticism.

Include: Self-described gradual uptake, revised skepticism, enthusiasm and contrasting continuing skepticism.

Exclude: Do not impose a universal adoption-stage model or verified model-release chronology; future capability contingency is K16.

Qualifications: I1’s enthusiasm and I2’s continuing skepticism are both retained. The C036-to-K17 succession is an author-requested ID transition, not a multi-code merge.

Theme: X01

Evidence IDs: E064, E065, E066, E084, E092, E134, E167, E184, E187, E208, E209, E264



### K18 Validation capacity and expanding workload

Participants describe or anticipate production and demand growing faster than human capacity to review, understand and coordinate outputs, creating workload or validation bottlenecks.

Include: Volume of generated artifacts or projects; demand expansion; mentally costly review; expected prioritization or AI-assisted checking to handle capacity.

Exclude: Individual output-correction efficiency is K02; which tasks receive effort is K15. Do not infer clinical harm or measured throughput.

Qualifications: Reported current burden, opinions and future triage remain separate. I8’s smaller team is contextual, not proof AI caused staffing reduction.

Theme: T01

Evidence IDs: E073, E074, E077, E086, E087, E094, E115, E126, E140, E141, E155, E161, E162, E180



### K19 Developing and sustaining professional judgment

Participants describe or advocate developing and sustaining the judgment and practical proficiency needed for AI-assisted architectural work, through experience, explanation, critical thinking, mentoring and learning AI tools, while questioning how newcomers acquire those capabilities.

Include: Learning/mentoring practices, teaching skepticism, future skill formation, access to experience, and the breadth needed to judge unfamiliar designs.

Exclude: Checking one output is K03; professional agency is K20; staffing arrangements are K21. Do not assume AI inevitably erodes skills or that teaching achieves its intended outcomes.

Qualifications: I5’s teaching is direct practice; future erosion and learning claims are interpretations. I4-S2 emphasizes continuity in training principles, and I4-S1 uses AI explanations as a learning resource.

Theme: T06

Evidence IDs: E072, E081, E082, E083, E096, E097, E098, E106, E107, E122, E123, E145, E148, E163, E164, E173, E177, E200, E201, E244, E250, E265, E273, E276



### K20 Preserving agency creativity and rewarding work

Participants value purpose, agency, creativity and enjoyable problem solving, and question work allocation that gives AI creation while humans inherit disliked review.

Include: Purpose/agency and human-oriented allocation; creativity through exploration; reported colleague preferences; conditional review-only concern and direct renewed enjoyment of AI-assisted work.

Exclude: No inference of measured morale decline or experienced psychological harm. Skill formation is K19; workload capacity K18.

Qualifications: Earlier concern and creativity-supporting accounts remain. I13 reports rediscovering coding enjoyment, a positive case that prevents reducing this code to loss of purpose. Broad claims about unhappy engineers are not treated as measured morale outcomes.

Theme: T06

Evidence IDs: E104, E105, E106, E141, E142, E150, E254, E264



### K21 Redistributing architectural work roles and staffing

Participants describe or envisage architectural tasks spreading across engineers or alternative roles, changing team staffing and expectations, while retaining architecture work or review gates in some settings.

Include: Partial transfer of exploration, broad lifecycle ownership, headcount reports, job-title interpretations, complex-product role conditions, and speculative role-specialized agents.

Exclude: Do not infer AI caused every title or staffing change. Apparent influence is K12; knowledge access without role transfer is K10; skill acquisition is K19.

Qualifications: I8 lacks a reliable prior company-role comparison. I6 title trends are perceptions, not vacancy data. I7’s external layoff/re-hire story is hearsay; their own platform retains architect gates.

Theme: T04

Evidence IDs: E088, E095, E116, E117, E138, E146, E147, E148, E151, E154, E155, E156, E163, E164, E175, E176, E191, E196, E225, E226, E227, E240, E241, E247, E248, E249, E259



### K22 Commercial expectations and AI cost stewardship

Participants connect AI-assisted work to questions about professional remuneration, allocation of tool costs and responsibility for controlling AI expenditure.

Include: Client questions about payment, opinions on passing on LLM costs, and architect cost-control responsibilities.

Exclude: Do not infer fees actually fell or savings were measured. Near-zero rebuild narratives are K27; general market/geopolitical predictions remain contextual material.

Qualifications: I4 reports remuneration questions, not agreed fee changes. I6 describes cost stewardship as part of architectural responsibility without budgets or measured outcomes.

Theme: T05

Evidence IDs: E070, E071, E119, E175, E176



### K23 Safety and ethical reasoning beyond generated documents

Participants question whether generated compliance documents preserve the human reflection they were meant to support, and argue for contextual safety, ethical and lawful reasoning rather than paperwork alone.

Include: Documentation as evidence of reasoning, societal responsibility, contextual ethics education and domain-dependent uncertainty or acceptable predictability.

Exclude: Not legal guidance or proof of unsafe outcomes. Adoption permission is K11; general quality-risk correction K27; professional learning K19.

Qualifications: Predominantly I6’s interpretation; national stereotypes and unverifiable legal assertions are not treated as facts. Avoiding societal harm remains an expressed condition on embracing uncertainty.

Theme: T07

Evidence IDs: E073, E109, E110, E121, E122, E123, E124, E223, E242, E275



### K24 Reassessing architectural significance through reversibility

Participants reconsider which decisions are architecturally significant when AI is perceived to make implementations cheaper to reverse, shifting emphasis toward business needs and risks that cannot simply be coded away.

Include: Perceived reduced risk of reversible technology choices; business-risk emphasis; conditional cheap re-architecture qualified by tractability, product lifetime or compliance.

Exclude: Modernization task choices are K15; commercial fees/cost stewardship K22. Do not infer all technical decisions are now cheap, safe or insignificant.

Qualifications: I13 supplies the central interpretation and future business emphasis. I10’s cheap-rewrite possibility is conditional; long-lived products and compliance qualify it. Earlier I1 cautions about non-coding rebuilding costs (E060).

Theme: T07

Evidence IDs: E060, E195, E198, E257, E258, E260



### K25 Machine-representable and verifiable architectural reasoning

Participants treat the ability to encode architectural concepts, context and quality concerns in rigorous, machine-usable and checkable representations as a condition for reliable agent assistance and the extent of future human involvement.

Include: Representation diversity/gaps, normalized model concepts, testable intent, inspectable explanations and machine-usable standards discussions; retain whether use is experimental, hypothetical or normative.

Exclude: Supplying known architectural constraints to steer workflows is K09; actually checking work is K03. Do not claim a comprehensive formal language, proven correctness, or deployed machine-readable standard.

Qualifications: I11’s home-model experiments and standards discussion coexist with speculative assurance/role claims. I10 conditions reduced human involvement on validated explanations. I12/I13 emphasize tacit drivers not automatically captured by written documentation.

Theme: T02

Evidence IDs: E199, E203, E210, E213, E216, E217, E218, E219, E220, E221, E222, E235, E243, E252



### K26 Architecting the AI-assisted delivery process

Participants describe, propose or question the architectural design of the software delivery process in which people and AI agents work together, including work decomposition, agent orchestration, staged handoffs and shared team execution or feedback mechanisms.

Include: Code passages where the arrangement of delivery work is itself the object of design: dividing and integrating work, coordinating agents and people, sequencing design and implementation, or constructing shared execution and feedback contexts. Distinguish current arrangements, limited experiments, desired capabilities and forecasts.

Exclude: Supplying architectural intent to an agent alone is K09; making that intent representable is K25; checking an output is K03; time allocation is K15; role or headcount redistribution alone is K21; interpersonal expectations alone are K13; embedding AI in the delivered product is K14. A mere mention of multiple agents is insufficient.

Qualifications: This is an analytical category, not evidence of a new formal job role or a generally deployed autonomous delivery system. I6’s organizational-design claim and I10’s direct work-decomposition account must not be collapsed into their desired or speculative orchestration futures. I7 provides a bounded existing team feedback mechanism. RQ mappings follow the v0.8 convention and should be checked against the study’s final RQ wording.

Theme: T05

Evidence IDs: E088, E125, E149, E204, E205, E267, E268, E269, E270, E271



### K27 Contextual architectural judgment and risk stewardship

Participants locate human architectural value in judging contextual appropriateness, prioritizing alternatives, negotiating trade-offs and maintaining attention to system risks and quality concerns when AI-enabled speed or rebuild narratives obscure them.

Include: Context-sensitive design choices, business/domain interpretation and stakeholder negotiation; architectural risk framing, omitted quality attributes, maintainability concerns and qualification of simplistic acceleration or rebuilding claims. Preserve ordinary option judgment, interpersonal negotiation and speed/hype correction as distinct dimensions.

Exclude: A generic output error or failed implementation alone is insufficient. Checking procedures are K03; accepting responsibility is K04; efficiency costs are K02; reflective safety/ethical reasoning is K23; a changed interpretation of architectural significance through reversibility remains K24.

Qualifications: All predecessor account-type and scope qualifications remain. Ordinary option judgment, stakeholder negotiation and speed/hype correction remain distinct dimensions. Suspected scalability, a heard rebuild claim, future debt and no observed disregard are not flattened into observed risk-remediation outcomes.

Theme: T07

Evidence IDs: E015, E031, E032, E035, E036, E037, E080, E093, E120, E132, E165, E178, E180, E181, E186, E193, E207, E229, E238, E241, E243, E245, E252, E253, E254, E256, E257

