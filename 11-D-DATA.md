# Data

The fuel for AI models, ranging from raw corpora to user feedback.

## Research Layer

- Benchmark Datasets – standardized datasets for model evaluation (e.g., MNIST, CIFAR-10, ImageNet, GLUE, SuperGLUE).
- Task-specific datasets – e.g., SQUAD for QA, Coco for image captioning.
- Synthetic Data – generated data for controlled experimentation and model debugging.

## Foundation Layer

- Web-Scale Text Corpora – large-scale crawls (e.g., Common Crawl, Wikipedia).
- Multimodal Data – text-image/audio datasets for models like CLIP or Gemini.
- Alignment Labels – human preference data (for RLHF), toxicity annotations, and content classification.

## Platform Layer

- Model Artifacts – serialized model weights, tokenizers, configs.
- Metrics – benchmark scores, latency profiles, and cost metrics.
- Inference Metadata – logs of queries, responses, latencies, and system performance.

## Builder Layer

- Enterprise Knowledge Bases – wikis, Confluence pages, Notion docs, Slack threads.
- Vector Databases – semantic indexes built from enterprise or domain documents (e.g., Pinecone).
- Tool Context Data – results returned by API calls or function executions.
- Long-Term Memory Stores – previous interactions and agent state histories.

## Application Layer

- User Data – text prompts, uploaded files, interaction logs.
- Domain Data – internal business documents, customer support transcripts, CRM records.
- Contextual Data Bindings – organization-specific knowledge linked into app logic.
- Feedback Data – user corrections, ratings, and fine-tuning feedback.

## Operation Layer

- Telemetry Streams – logs from model inference, latency, and resource usage.
- User Feedback Data – thumbs-up/down, corrections, and explicit error reports.
- Evaluation Data – curated test sets and golden labels for regression testing.

## Distribution Layer
- User Growth Metrics – adoption rates, active users, retention curves.
- Channel Analytics – app store impressions, API call volume, campaign performance.
- Revenue Data – subscription and API billing metrics.
- $A/B$ Testing Results – behavioral data comparing different rollout strategies.

## User Layer

- User Preferences – saved configs, domains, or instructions.
- Behavioral Analytics – usage frequency, engagement metrics, and satisfaction signals.
- Feedback & Ratings – direct user corrections and qualitative comments.
- Prompt Histories – previous queries and responses used for contextual continuity.