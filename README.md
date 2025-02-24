<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <!-- Meta tags for social media banners -->
  <meta name="description" content="DOVE: A Large-Scale Multi-Dimensional Predictions Dataset Towards Meaningful LLM Evaluation" />
  <meta property="og:title" content="🕊️ DOVE: A Large-Scale Multi-Dimensional Predictions Dataset Towards Meaningful LLM Evaluation" />
  <meta property="og:description" content="A dataset for studying LLM sensitivity and evaluation methodology with 300M model predictions across various prompt variations." />
  <meta property="og:url" content="https://doveevaluation.github.io/" />
  <!-- Replace with your banner image -->
  <meta property="og:image" content="static/image/your_banner_image.png" />
  <meta property="og:image:width" content="1200"/>
  <meta property="og:image:height" content="630"/>

  <meta name="twitter:title" content="🕊️ DOVE: A Large-Scale Multi-Dimensional Predictions Dataset Towards Meaningful LLM Evaluation">
  <meta name="twitter:description" content="A dataset for studying LLM sensitivity and evaluation methodology with 300M model predictions." />
  <!-- Replace with your Twitter banner image -->
  <meta name="twitter:image" content="static/images/your_twitter_banner_image.png">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="keywords" content="DOVE, LLM Evaluation, Dataset, prompt sensitivity, large-scale">
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <title>🕊️ DOVE: A Large-Scale Multi-Dimensional Predictions Dataset Towards Meaningful LLM Evaluation</title>
  <link rel="icon" type="image/x-icon" href="static/images/favicon.ico">
  <link href="https://fonts.googleapis.com/css?family=Google+Sans|Noto+Sans|Castoro" rel="stylesheet">
  <link rel="stylesheet" href="static/css/bulma.min.css">
  <link rel="stylesheet" href="static/css/bulma-carousel.min.css">
  <link rel="stylesheet" href="static/css/bulma-slider.min.css">
  <link rel="stylesheet" href="static/css/fontawesome.all.min.css">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1/css/academicons.min.css">
  <link rel="stylesheet" href="static/css/index.css">
<style>
  .highlight-word {
    background-color: #ffff00;
    padding: 0 4px;
    border-radius: 4px;
    box-shadow: 0 0 10px rgba(255, 255, 0, 0.5);
  }
  .compact-box {
    padding: 1.5rem;
    height: auto !important;
  }
  .info-footer {
    font-size: 0.9rem;
    color: #666;
  }
</style>
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://documentcloud.adobe.com/view-sdk/main.js"></script>
  <script defer src="static/js/fontawesome.all.min.js"></script>
  <script src="static/js/bulma-carousel.min.js"></script>
  <script src="static/js/bulma-slider.min.js"></script>
  <script src="static/js/index.js"></script>
</head>
<body>

  <!-- Main Hero Section -->
  <section class="hero">
    <div class="hero-body">
      <div class="container is-max-desktop">
        <div class="columns is-centered">
          <div class="column has-text-centered">
            <h1 class="title is-1 publication-title">🕊️ DOVE: A Large-Scale Multi-Dimensional Predictions Dataset<br>Towards Meaningful LLM Evaluation</h1>
            <div class="publication-links">
              <!-- Code link with GitHub icon -->
              <span class="link-block">
                <a href="https://github.com/NLPHUJI/DOVE" target="_blank" class="external-link button is-normal is-rounded is-dark">
                  <span class="icon">
                    <i class="fab fa-github"></i>
                  </span>
                  <span>Code</span>
                </a>
              </span>
              <!-- Paper link -->
              <span class="link-block">
                <a href="https://arxiv.org/abs/XXXX.XXXXX" target="_blank" class="external-link button is-normal is-rounded is-dark">
                  <span class="icon">
                    <i class="ai ai-arxiv"></i>
                  </span>
                  <span>Paper</span>
                </a>
              </span>
              <!-- Dataset link -->
              <span class="link-block">
                <a href="https://huggingface.co/datasets/nlphuji/Dove" target="_blank" class="external-link button is-normal is-rounded is-dark">
                  <span class="icon">🤗</span>
                  <span>Dataset</span>
                </a>
              </span>
              <!-- Contact link -->
              <span class="link-block">
                <a href="mailto:eliyahaba@mail.huji.ac.il" target="_blank" class="external-link button is-normal is-rounded is-dark">
                  <span class="icon">📧</span>
                  <span>Contact</span>
                </a>
              </span>
            </div>
            <div class="is-size-5 publication-authors" style="margin-top: 1rem;">
              <!-- Author names and institution -->
              <span class="author-block">
                <a href="https://github.com/eliyahabba" target="_blank">Eliya Habba</a><sup>1</sup>,
              </span>
              <span class="author-block">
                <a href="https://github.com/ofirarv" target="_blank">Ofir Arviv</a><sup>2</sup>,
              </span>
              <span class="author-block">
                <a href="https://github.com/itayitzhak" target="_blank">Itay Itzhak</a><sup>1</sup>,
              </span>
              <span class="author-block">
                <a href="https://github.com/yotamp" target="_blank">Yotam Perlitz</a><sup>2</sup>,
              </span>
              <br>
              <span class="author-block">
                <a href="https://github.com/elronb" target="_blank">Elron Bandel</a><sup>2</sup>,
              </span>
              <span class="author-block">
                <a href="https://github.com/leshemc" target="_blank">Leshem Choshen</a><sup>2</sup>,
              </span>
              <span class="author-block">
                <a href="https://github.com/michalss" target="_blank">Michal Shmueli-Scheuer</a><sup>2</sup>,
              </span>
              <span class="author-block">
                <a href="https://gabrielstanovsky.github.io/" target="_blank">Gabriel Stanovsky</a><sup>1</sup>
              </span>
              <br>
              <span class="author-block">
                <sup>1</sup>The Hebrew University of Jerusalem &nbsp;·&nbsp; <sup>2</sup>IBM Research AI
              </span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Teaser video-->
  <section class="hero teaser">
    <div class="container is-max-desktop">
      <div class="hero-body">
        <video poster="" id="tree" autoplay controls muted loop style="width: 100%; max-width: 330px; margin: 0 auto; display: block;">
          <!-- Your video here -->
          <source src="static/videos/dove.mov"
          type="video/mp4">
        </video>
        <p class="has-text-centered" style="margin-top: 1rem; font-size: 1.1em; font-weight: 400;">
          <strong>Building DOVE:</strong> To holistically explore LLM sensitivity,<br>
          we sample prompts as a walk in the space of various <em>prompt dimensions</em> (rows, above).
        </p>
      </div>
    </div>
  </section>
  <!-- End teaser video -->



<section class="section" style="background-color: #f5f5f5;">
  <div class="container is-max-desktop">
    <!-- Main Call to Action -->
    <div class="has-text-centered mb-6">
      <h2 class="title is-2">🤝 Join Our Community-wide Effort!</h2>
      <p class="subtitle is-4">Help develop meaningful protocols for systematic LLM evaluation</p>
    </div>

    <!-- Two Columns Section -->
    <div class="columns is-centered">
      <!-- First Column -->
      <div class="column">
        <div class="box compact-box">
          <h3 class="title is-4 has-text-centered">Why <span class="highlight-word">Contribute</span>? 🌟</h3>
          <div class="content">
            <ul class="has-text-weight-medium" style="margin-top: 0.5rem;">
              <li class="mb-2">Democratize the systematic study of LLM sensitivity</li>
              <li class="mb-2">Spur research into meaningful evaluation</li>
              <li class="mb-2">Enable efficient and generalizable evaluation</li>
              <li class="mb-2">Join our growing, community-driven resource</li>
            </ul>
          </div>
        </div>
      </div>

      <!-- Second Column -->
      <div class="column">
        <div class="box compact-box">
          <h3 class="title is-4 has-text-centered">How to <span class="highlight-word">Contribute</span>? 📊</h3>
          <div class="content">
            <ul class="has-text-weight-medium" style="margin-top: 0.5rem;">
              <li class="mb-2">Share model predictions across any prompt variation</li>
              <li class="mb-2">Contribute data from diverse domains and tasks</li>
              <li class="mb-2">Help expand coverage across languages</li>
              <li class="mb-2">Explore additional evaluation dimensions</li>
              <li class="mb-2">Suggest directions for future research</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
<!-- Combined Info Box -->
   <div class="box mt-5">
     <p class="has-text-centered is-size-5 mb-4">Contributors who provide significant data will be invited as co-authors on the next version of both the paper and dataset.</p>
     <p class="has-text-centered info-footer">Your data doesn't need to include every field in our <a href="https://arxiv.org/pdf/XXXX.XXXXX.pdf#page=20" class="has-text-info">Dataset Scheme</a>, but should demonstrate systematic evaluation by including model predictions with variations in at least one dimension (for example, without model’s log probabilities).</p>

     <!-- Single Call-to-Action Button -->
     <div class="has-text-centered mt-5">
       <a href="mailto:eliyahaba@mail.huji.ac.il" class="button is-primary is-medium">
         <span class="icon">
           <i class="fas fa-paper-plane"></i>
         </span>
         <span>Share Your Data</span>
       </a>
     </div>
   </div>
 </div>
</section>
  <!-- About Section -->
  <section class="section hero is-light">
    <div class="container is-max-desktop">
      <h2 class="title is-3">Abstract</h2>
      <div class="content">
        <p>
          Recent work found that LLMs are sensitive to a wide range of arbitrary prompt dimensions, including the type of delimiters, answer enumerators, instruction wording, and more. This throws into question popular single-prompt evaluation practices.
        </p>
        <p>
          In this work, we present DOVE (Dataset Of Variation Evaluation), a large-scale dataset containing prompt perturbations of various evaluation benchmarks. In contrast to previous work, we examine LLM sensitivity from a holistic perspective, and assess the joint effects of perturbations along various dimensions, resulting in thousands of perturbations per instance. We evaluate several model families against DOVE, leading to several findings, including efficient methods for choosing well-performing prompts, observing that few-shot examples reduce sensitivity, and identifying instances which are inherently hard across all perturbations.
        </p>
        <p>
          DOVE consists of more than 300M prompt perturbations and model outputs, which we make publicly available to spur a community-wide effort toward meaningful, robust, and efficient evaluation.
        </p>
        <p>
          Browse the data: <a href="https://huggingface.co/datasets/DOVevaluation/Dove" target="_blank">https://huggingface.co/datasets/DOVevaluation/Dove</a>
        </p>
      </div>
    </div>
  </section>

  <!-- Usage Section -->
  <section class="section">
    <div class="container is-max-desktop">
      <h2 class="title is-3">Usage</h2>
      <div class="content">
        <h3 class="title is-4">Basic Dataset Loading</h3>
        <pre><code>from datasets import load_dataset
from pathlib import Path

# Load a specific model/language/shots combination
def load_dove_subset(model_name, language="en", shots=0):
   base_path = f"nlphuji/Dove/{model_name}/{language}/shots_{shots}"
   return load_dataset(base_path)

# Examples
llama_en_zero = load_dove_subset("Llama-3.2-1B-Instruct", language="en", shots=0)
mistral_fr_five = load_dove_subset("Mistral-7B-Instruct-v0.3", language="fr", shots=5)</code></pre>
      </div>
    </div>
  </section>

  <!-- Project Structure Section -->
  <section class="section">
    <div class="container is-max-desktop">
      <h2 class="title is-3">Dataset Structure</h2>
      <div class="content">
        <pre><code>nlphuji/
├── Dove/
│   ├── model_name/                      # e.g., "Llama-3.2-1B-Instruct"
│   │   ├── language/                    # e.g., "en", "fr"
│   │   │   └── shots_N/                 # N = 0 for zero-shot, N > 0 for few-shot
│   │   │       ├── mmlu.abstract_algebra.parquet
│   │   │       ├── mmlu.world_religions.parquet
│   │   │       ├── ai2_arc.arc_challenge.parquet
│   │   │       ├── hellaswag.parquet
│   │   │       └── other_benchmark_files.parquet
│   └── other_models/
└── Dove_Lite/
    └── [same structure and examples with reduced metadata per instance]</code></pre>
      </div>
    </div>
  </section>

  <!-- Versions Section -->
  <section class="section">
    <div class="container is-max-desktop">
      <h2 class="title is-3">Versions 📦</h2>
      <div class="columns is-centered">
        <!-- Full Version Column -->
        <div class="column">
          <div class="box">
            <h3 class="title is-4">Full Version (4TB)</h3>
            <div class="content">
              <ul>
                <li>Complete token-level probabilities</li>
                <li>Detailed few-shot examples</li>
                <li>Comprehensive model behavior analysis</li>
              </ul>
              <div class="has-text-centered">
                <a href="https://huggingface.co/datasets/nlphuji/Dove" class="button is-primary is-outlined mt-4">
                  <span class="icon">🤗</span>
                  <span>Download Full Version</span>
                </a>
              </div>
            </div>
          </div>
        </div>

        <!-- Lite Version Column -->
        <div class="column">
          <div class="box">
            <h3 class="title is-4">Lite Version (200GB)</h3>
            <div class="content">
              <ul>
                <li>Core prompt variations</li>
                <li>Model responses and Evaluation scores</li>
                <li>Perfect for quick experimentation</li>
              </ul>
              <div class="has-text-centered">
                <a href="https://huggingface.co/datasets/nlphuji/Dove_Lite" class="button is-primary is-outlined mt-4">
                  <span class="icon">🤗</span>
                  <span>Download Lite Version</span>
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

    <!-- Citation Section -->
  <section class="section" id="BibTeX">
    <div class="container is-max-desktop content">
      <h2 class="title">Citation</h2>
      <pre><code>@article{dove2025,
 title={DOVE: A Large-Scale Multi-Dimensional Predictions Dataset Towards Meaningful LLM Evaluation},
 author={Anonymous},
 journal={arXiv preprint arXiv:XXXX.XXXXX},
 year={2025}
}</code></pre>
    </div>
  </section>


  <!-- License Section -->
  <section class="section">
    <div class="container is-max-desktop">
      <h2 class="title is-3">License</h2>
      <div class="content">
        <p>
          This dataset is licensed under the <strong>Computational Data License Agreement v2 (CDLAv2)</strong>. For full license terms, see:
          <a href="https://cdla.dev/permissive-2.0/" target="_blank">https://cdla.dev/permissive-2.0/</a>
        </p>
      </div>
    </div>
  </section>

</body>
</html>
