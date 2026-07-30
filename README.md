## Hello, Hola, Привет 👋

I'm **Nikita** — I train models, and then I build everything that has to exist around them
so they actually run for somebody other than me.

BSc in Computer Science, Don State Technical University · Russian Federation.
Python most days. GLSL on the days a path tracer refuses to converge.

[![HuggingFace](https://img.shields.io/badge/HuggingFace-@Ar4ikov-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/Ar4ikov)
[![Kaggle](https://img.shields.io/badge/Kaggle-@ar4ikov-20BEFF?style=flat-square&logo=kaggle&logoColor=white)](https://kaggle.com/ar4ikov)

---

### What I actually work on

**Speech, emotion, and voice.** Most of my research time goes into audio and multimodal models —
recognising emotion from speech in real time, and synthesising Russian speech that doesn't sound
like a 2015 TTS demo. This is the part of ML I keep coming back to: the data is messy, the labels
are subjective, and the evaluation is genuinely hard. Fine-tuning transformers on it is the easy half.

**LLM pipelines that have to survive contact with production.** OCR in front, an LLM in the middle,
a document that a real business depends on coming out the other end. The interesting problems there
aren't prompts — they're retries, idempotency, queue backpressure, versioning the model *and* the
data together, and what happens at 3 a.m. when the extraction quietly starts returning garbage.

**The unglamorous infrastructure underneath.** Async APIs, brokers, containers, deployment.
I like that a model is only as good as the boring plumbing that keeps it fed and observable, and
I'd rather own that plumbing than hand it over and hope.

**And, currently, ray tracing in Minecraft.** See below — it has nothing to do with the rest of
this list, which is exactly why it's there.

---

### Open projects

* **[Aniemore](https://github.com/Aniemore/Aniemore)** — an open library for real-time speech
  emotion recognition using a multimodal approach. Audio and text together, because tone alone
  lies and words alone lie differently.
* **[OpenJourney](https://github.com/Ar4ikov/OpenJourney-discord)** — a Discord bot wiring Stable
  Diffusion to a GPT-2 I trained specifically to write image prompts. Turns out the hard part of
  image generation is asking for the right thing.

### Built, but living behind an NDA

* **Document Automation System** — an OCR + LLM pipeline processing documents end-to-end for a
  logistics company. Real throughput, real consequences for getting a number wrong.
* **Chtec** — a speech-synthesis prototype built on [StyleTTS 2](https://arxiv.org/abs/2306.07691)
  for voice cloning in Russian. Cloning a voice in a language the model wasn't designed around is
  where most of the work went.

---

### The stack, since you're going to ask

`PyTorch` · `HuggingFace` (transformers / datasets / accelerate / peft) · `pandas` · `polars` ·
`sklearn` · `lightgbm` · `catboost` · `langchain` · `gigachain` · `langfuse` · `plotly` · `seaborn`
`FastAPI` · `Pydantic` · `FastStream` · `RabbitMQ` · `Redis` · `PostgreSQL` · `MySQL`
`Docker` · `Compose` · `Swarm` · `DVC` · `k8s` · `ArgoCD` · `Helm`

Tools are the least interesting thing on a profile, so that's all they get. I pick them up when a
problem needs them and I'm happy to learn whatever the next problem needs — especially if it comes
with large-scale infrastructure attached.

---

![](https://github-readme-stats.vercel.app/api?username=Ar4ikov&hide=contribs&count_private=true&show_icons=true&theme=gruvbox&hide_border=true&include_all_commits=true&hide_title=true&bg_color=45,17b2e3,1363b6&text_color=ffffff&icon_color=ffffff)
![](https://github-readme-stats.vercel.app/api/top-langs/?username=Ar4ikov&layout=compact&theme=gruvbox&hide_border=truehide_title=true&bg_color=45,17b2e3,1363b6&text_color=ffffff&icon_color=ffffff&title_color=ffffff&font_size=20)

![](https://komarev.com/ghpvc/?username=Ar4ikov)

Pinned repositories are below. Thank you and enjoy ❤️
