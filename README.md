# James Chen

**Software Engineering · Applied AI · Machine Learning**

I'm Chih-Chun (James) Chen, an M.S. Computer Science student at Brigham Young University in Provo, Utah. I build applications and study how to evaluate and improve language-model behavior.

**Open to full-time Software Engineering and AI/ML Engineering roles.**

[Connect on LinkedIn](https://www.linkedin.com/in/chen1226/) · [Browse all repositories](https://github.com/jimmy19981226?tab=repositories)

## Start with these projects

For **backend, full-stack, or mobile engineering**, start with AI Stock Studio. For **AI/ML engineering or research**, start with the evaluation framework and Bayesian trajectory selection. Each repository links its design choices to code, tests, and current limitations.

### [AI Stock Studio](https://github.com/jimmy19981226/stock-tracker)

**Personal project · Python / FastAPI · SwiftUI · React · SQLAlchemy**

A Taiwan/US portfolio application with a native iOS client, a read-only web dashboard, and an AI assistant. Backend services apply Taiwan moving-average and US FIFO accounting; assistant tools propose changes that the user reviews before saving.

Inspect the accounting regression cases, the separation between AI proposals and record writes, and recovery after a mobile chat disconnect.

[Product screenshots](https://github.com/jimmy19981226/stock-tracker#product-tour) · [Engineering decisions](https://github.com/jimmy19981226/stock-tracker#engineering-decisions) · [Code review guide](https://github.com/jimmy19981226/stock-tracker#review-guide)

### [Agentic LLM Reliability Benchmarks](https://github.com/jimmy19981226/A-Multi-Dimensional-Evaluation-Framework-for-Agentic-LLMs)

**Research implementation · Python · PyTorch · Transformers**

A framework comparing base and instruction-tuned models across conversation, tool planning, safety, and task fidelity. It validates judge outputs, records run metadata, and exports per-example results and summaries. CPU tests exercise reporting without running the large models.

The study's presentation-reported results are clearly separated from software validation; independent score reproduction remains pending.

[Evaluation design](https://github.com/jimmy19981226/A-Multi-Dimensional-Evaluation-Framework-for-Agentic-LLMs#evaluation-design) · [Results and evidence audit](https://github.com/jimmy19981226/A-Multi-Dimensional-Evaluation-Framework-for-Agentic-LLMs/blob/main/docs/RESULTS.md)

### [Bayesian Trajectory Selection](https://github.com/jimmy19981226/bayesian-trajectory-selection)

**Research · NumPy · MC dropout · Mutual information · PEFT/LoRA**

A study of uncertainty-based selection of teacher-generated math reasoning data. Includes a laptop demo, a reconstructed training pipeline, and tests for numerical scoring, candidate selection, and tiny-model behavior.

The archived paper reports small accuracy differences. Original results have not been independently reproduced; the repository documents missing artifacts and reconstruction choices.

[Offline demo](https://github.com/jimmy19981226/bayesian-trajectory-selection#quick-start) · [Method](https://github.com/jimmy19981226/bayesian-trajectory-selection/blob/main/docs/METHOD.md) · [Evidence and limitations](https://github.com/jimmy19981226/bayesian-trajectory-selection/blob/main/docs/RESULTS.md)

### [AI Audio Transcriber](https://github.com/jimmy19981226/ai-audio-transcriber)

**Fork and extensions · Python · faster-whisper · Gradio**

Local speech recognition followed by LLM cleanup, summaries, translation, and document export. This fork extends [kennionblack's upstream project](https://github.com/kennionblack/ai-audio-transcriber) with bounded agent execution, explicit failure propagation, and regression tests.

[Example output](https://github.com/jimmy19981226/ai-audio-transcriber#example-workflow) · [Reliability review guide](https://github.com/jimmy19981226/ai-audio-transcriber#review-guide)

### [CalmCloud](https://github.com/jimmy19981226/CalmCloud)

**Android client prototype · Kotlin · Retrofit · JUnit**

Mood, sleep, and stress tracking with visual summaries and an optional chat interface. The repository demonstrates Android screen/network integration and testable conversation request construction. Its backend and chat proxy are external dependencies.

[Architecture and setup](https://github.com/jimmy19981226/CalmCloud#architecture) · [Client review guide](https://github.com/jimmy19981226/CalmCloud#review-guide)

## Technical focus

- **Applications:** Python, FastAPI, SwiftUI, React, Kotlin, Retrofit, SQLite, PostgreSQL.
- **AI/ML:** PyTorch, Transformers, NumPy, PEFT/LoRA, tool calling, model evaluation, uncertainty estimation.
- **Verification:** pytest, unittest, JUnit, native iOS tests, GitHub Actions, synthetic fixtures, and reproducible run metadata.

My project documentation emphasizes what runs today, how it is tested, and where the evidence stops. Forks retain upstream credit, and research results retain their source and reproduction status.
