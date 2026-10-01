# Fernando Núnez Sánchez

Applied AI Engineer & Physicist based in Spain.

My work focuses on real-time conversational voice architectures, custom streaming speech models, and multimodal geospatial systems. I combine a background in physics with modern software engineering to build robust, low-latency AI systems deployed on commodity and CPU hardware.

Previously, I served as the representative of the Spanish Innovation Agency (CDTI) in Brazil, managing international technology cooperation, bilateral R&D programs, and tech transfer.

---

### Focus Areas

- **Conversational Voice Systems & Orchestration**: Low-latency, full-duplex conversational voice agents with state-machine orchestration (LangGraph), safe interruptions (barge-in with state repair), multi-provider failover, and layered deterministic safety supervisors.
- **Natively Streaming Speech (STT & TTS)**: End-to-end streaming speech microservices for regional languages (Galician): frame-synchronous transducers (FastConformer-RNNT int8 on CPU), flow-matching synthesis (Matcha-TTS + Vocos), and native phonemic front-ends (G2P), achieving sub-second turn latency at zero cloud cost.
- **Multimodal Geospatial Intelligence**: Context-aware agentic workflows integrating numerical meteorological/marine forecasts, geospatial routing, and edge vision models for environmental and recreational decision support.
- **Physical Modeling & Renewable Energy**: Applied predictive modeling: wind generation forecasting (NWP + SCADA ensembles), off-grid PV optimization via Loss of Load Probability (LLP), and synoptic wildfire risk classification.

---

### Selected Work

- **[Loaira — Primary-Care Healthcare Voice Agent](https://github.com/nandonunez/applied-ai-portfolio/tree/main/healthcare-agent)**: Real-time conversational telephone agent for public health appointment management in Galician and Spanish. Production-ready with 9 operational tools (FHIR-lite data model), safe barge-in state reconciliation, a 9-rule safety supervisor with an LLM write critic, and a fine-tuned SLM for spoken date parsing.
- **[Galician Streaming Speech Infrastructure](https://github.com/nandonunez/applied-ai-portfolio/tree/main/healthcare-agent#speech-infrastructure)**: Bidirectional, natively streaming speech microservices for Galician running on CPU (ARM aarch64). FastConformer-Transducer (ONNX int8) STT and Matcha-TTS + Vocos with native Cotovia G2P, delivering 691 ms p50 perceived turn latency.
- **[QuePraia — Multimodal Coastal Recommendation Agent](https://github.com/nandonunez/applied-ai-portfolio#quepraia)**: Multimodal conversational agent that recommends coastal locations by fusing high-resolution marine and meteorological forecasts, tidal dynamics, coastal alerts, and real-time visual validation from public webcams via lightweight edge computer vision.
- **[Wind Production Forecasting](https://github.com/nandonunez/applied-ai-portfolio/tree/main/wind-forecasting)**: Production ML pipeline combining numerical weather reanalysis (GFS/ECMWF) with turbine-level SCADA data using gradient-boosted ensembles under temporal cross-validation.
- **[Standalone PV Sizing via LLP](https://github.com/nandonunez/applied-ai-portfolio/tree/main/pv-llp-sizing)**: Sizing and optimization framework based on Loss of Load Probability isoreliability curves using multi-year solar irradiation time series.

---

### Technical Background

- **Languages:** Python, SQL, Julia
- **Voice & Real-Time AI:** LangGraph, FastRTC / Pipecat, Sherpa-ONNX, FastConformer-RNNT, Matcha-TTS, Vocos, Silero VAD, Cotovia G2P
- **Vision & Edge ML:** Lightweight CNN / VLM distillation, ONNX Runtime, OpenCV
- **Scientific & Data:** PyTorch, scikit-learn, XGBoost, LightGBM, NumPy, pandas, xarray, rasterio, Apache Spark, PostGIS
- **Infrastructure:** Docker, uv, Git, Linux / aarch64 ARM / HPC (CESGA)

---

### Links

- **Technical Portfolio:** [Applied AI & Scientific Computing Portfolio](https://github.com/nandonunez/applied-ai-portfolio)
- **LinkedIn:** [linkedin.com/in/nandonunez](https://www.linkedin.com/in/nandonunez)
