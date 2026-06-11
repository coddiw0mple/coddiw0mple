<!---
coddiw0mple/coddiw0mple is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

```cpp
// Every order gets matched eventually. Time priority matters.

#include <ambition>

namespace divith {

struct Profile {
    static constexpr auto name     = "Divith Phogat";
    static constexpr auto role     = "Applications Developer @ Oracle (Enterprise Risk & Finance)";
    static constexpr auto based_in = "Bengaluru, India";
    static constexpr auto chasing  = "low-latency systems & quant engineering";

    // What I do at work: distributed systems that have to be correct,
    // not just fast — release pipelines, ORDS/Flask APIs, message queues
    // on Autonomous DB, and root-causing state that cascades across envs.

    Order<Limit> currently_building[] = {
        {"exchange-sim",          "C++ matching engine + LOB; benchmarking std::map vs flat array on p99 latency under Poisson order flow"},
        {"rl-trading-frictions",  "Learning trading policies under realistic market frictions"},
    };

    Order<Filled> shipped[] = {
        {"GeneAI",   "Chrome/Firefox extension for rewrite/summarize/Q&A — 6k+ downloads, ~240 active users"},
        {"Research", "3 papers (ICICCT/CIS/ICON '23): medical CV, speech-to-speech MT, Telugu POS w/ QLoRA"},
    };

    Skills stack = {
        .languages = {"C++", "Rust", "Python", "Java"},
        .systems   = {"low-latency C++", "Flask/FastAPI", "Docker", "Kubernetes", "ORDS"},
        .ml_ai     = {"PyTorch", "LLM finetuning", "RAG", "embeddings", "CV/NLP"},
        .data      = {"PostgreSQL", "MongoDB", "Redis", "Firestore"},
    };

    // Trade-off I keep relearning: the obvious data structure is rarely
    // the fast one. Measure, profile, then argue about big-O.
    [[nodiscard]] auto north_star() { return "make markets faster, one microsecond at a time"; }
};

}  // namespace divith
```

<sub>📫 divithphogat@gmail.com · always happy to talk order books, matching engines, and ML systems.</sub>
