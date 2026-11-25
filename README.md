<img src="https://raw.githubusercontent.com/aarush323/aarush323/main/assets/whoami.svg" alt="whoami — aarush oak, agentic systems & backend infrastructure" width="800" />

### aarush oak

agentic systems & backend infrastructure · pict '28 · pune

i build agentic systems and the backend infrastructure around them—from agentic retrieval, context management, and post-training to low-latency services, optimization algorithms, and sandboxed verification loops.

- **previously (ai intern):** owned and built a product's backend and agentic stack. engineered agentic retrieval over postgresql, dynamic tool routing, and context management, alongside decoupled background compute (async task queues, worker pools, and caching) to run parallel optimization algorithms without blocking live apis.

### projects

| repo | what it does | stack |
|---|---|---|
| [**heimdall**](https://github.com/prathameshk421/Heimdall) | automated pr verification & merge gate running red-first tests inside rootless podman sandboxes | `go` `podman` `postgresql` |
| [**loadline**](https://github.com/aarush323/LoadLine) | capacity agent that runs `k6` load tests in docker, patches bottlenecks, and opens a pr only if metrics improve | `python` `pydantic ai` `k6` `docker` |
| [**markoblitz**](https://github.com/Namz10/markoblitz) | adversarial payment-fraud simulator & detection pipeline (`0.9985` pr-auc, `0.032%` fpr on time-cut holdout) | `python` `postgresql` |
| [**foresight**](https://github.com/aarush323/Foresight) | multi-agent predictive fleet maintenance & root-cause analysis over real-time telemetry streams | `python` `langgraph` `fastapi` |

### stack

- **agentic & ml:** `python` · `agentic retrieval (rag + sql)` · `context management` · `lora / sft / grpo` · `langgraph` · `pydantic ai` · `vector dbs` · `evals`
- **backend & infra:** `go` · `c++` · `fastapi` · `postgresql` · `kafka` · `redis` · `docker` · `kubernetes` · `podman`

### highlights

- **lexsi hackathon (top 10% — top 35 / ~400 teams):** post-trained `tiny-aya-global` (3.35b) with lora (`sft` + `grpo`) for frugal multi-turn sqlite tool-calling (`frugal-analyst`)
- **amazon ml challenge '26 (rank 677 / ~24,000 teams):** fine-tuned entity resolution pipeline (`0.984` f0.5 across 1.7m × 10m multilingual records)
- **barclays hack-o-hire '26:** top 10 national finalist (multi-agent pre-delinquency engine with `langgraph`, `lightgbm/gru`, `kafka`, and `redis` sse)

[linkedin](https://www.linkedin.com/in/aarush-oak/) · [x](https://x.com/mrx123444) · [huggingface](https://huggingface.co/aarush323) · [leetcode](https://leetcode.com/u/wreck323/) · [email](mailto:oakaarush@gmail.com)
