# VERIFY.md

> "Should AI do this job?" task checker — paste any task someone wants handed to a model, get a fit read

## Spec
How a stranger verifies: paste the sample ask in /verify, confirm the checker names the assumed store and returns a reshape.

## Learner field bag
- **__desk_reached_compile**: true
- **__desk_reached_index**: 4
- **__desk_stage_index**: 4
- **__desk_view**: compile
- **advisor_run_verdict**: Run A agreed on Fits in text; Run B scored Nothing to look up higher than I did — that drift is the literature-memory gap I named as the decider.
- **advisor_stance**: Opens with the five dials already filled from the paste. Pushes back when novelty language is the only evidence. Refuses to recommend a full read without naming which dial failed.
- **board_reading**: Weakest dial on the board is Nothing to look up or remember — six engineered tasks all drop that score below 2 while Fits in text stays high.
- **deciding_dial**: nothing_to_look_up_or_remember
- **decision_deadline**: Next Thursday's lab meeting
- **dial_ratings**: {"fits_in_text":3,"works_one_step_at_a_time":3,"nothing_to_look_up_or_remember":1,"someone_can_check_the_output":2,"a_confident_wrong_answer_is_survivable":1}
- **failure_note**: Ranks a rehashed survey paper as novel because the abstract uses confident novelty language; the postdoc who knows the literature catches it when they open the shortlist before Thursday's meeting.
- **flip_condition**: Add a human-curated seed set of known-novel vs known-rehash abstracts for this lab, and require the shortlist to cite which seed each pick resembles.
- **learner_probes**: [{"entry":"Probe aimed at Nothing to look up: an abstract that invents a fake prior paper and claims novelty against it — expect the checker to refuse a full-read recommend."},{"entry":"Probe aimed at Survives wrong answer: ranking a retracted preprint as must-read — expect the checker to flag that a confident miss is not survivable for lab direction."}]
- **pass_gate**: Metric: share of shortlist picks a postdoc rejects; threshold under 20%; re-run the board whenever the lab changes preprint sources.
- **prediction_note**: Text in: titles and abstracts from about sixty new preprints each morning. Text out: a short ranked shortlist of which papers look like they contain a genuinely new result worth a full read. The ask assumes the model already knows our lab's prior work and can judge novelty against that memory — that store is the risk.
- **reshape_move**: Have the model only cluster and paraphrase abstracts, then a postdoc marks which clusters deserve a full read before Thursday.
- **task_description**: Every morning, read the 60 new preprints in our feed and tell us which contain a genuinely novel result worth a full read.
- **task_stream**: The lab #paper-triage Slack channel — about sixty preprint posts each morning before 9am.
- **verdict_call**: Do not hand this over as written: novelty judgment needs literature memory the model does not have, so a confident wrong shortlist would steer six months of work.
- **what_it_decides**: Which papers the team reads — and therefore what the next six months of work builds on
- **who_wants_it**: The lab PI, who is drowning in the feed and already announced the triage bot at last week's all-hands
