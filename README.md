## EvalPerf Dataset

The EvalPerf dataset includes 121 performance-exercising tasks:

* `task_id` (`str`): The task ID mapped to the original HumanEval(+) and MBPP(+) tasks
* `reference` (`List[str]`): A list of representative reference solutions (from slow to fast) with diverse performance patterns
* `pe_input` (`Any`): A performance exercising input
* `scores` (`List[float]`): Performance scores for `reference` (0-100)
