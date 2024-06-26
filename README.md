# Experimental evaluation of LLM-based domain modeling assistants

This repository contains a set of evaluation domains and their domain descriptions that can be used for the evaluation of an LLM-based domain modeling assistant that automates various domain modelins steps such as discovering classes in the domain description or discovering attributes of the given class or associations connecting this class.

* "manual evaluation domains" directory contains the domains that can be used for the evaluation
* "prompting domains" directory contains a simple domain that can be used as an example used for N-shot prompting
* "front-end evaluation domains" directory contains domain descriptions that can be used for user-based UI/UX evaluation.

For further details about the evaluation methodology, see the paper [1].

"evaluation results" directory contains results of the evaluation based on the methodology from [1] and using the provided domain descriptions in "manual evaluation domains".
The results contain the evaluated prompt templates for suggesting classes, attributes and associations, their manual evaluation, and the resulting detailed measures of precision, recall and F1 scores.

[1] Submitted. TBA.