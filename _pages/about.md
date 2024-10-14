---
permalink: /
title: "Taylor Sorensen (he/him)"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Hi! My name is Taylor Sorensen. I'm a Computer Science PhD student at the [University of Washington](https://www.cs.washington.edu), where I'm fortunate to be advised by [Yejin Choi](https://homes.cs.washington.edu/~yejin/). I research natural language processing (NLP) and artificial intelligence (AI) and am especially interested in [pluralistic alignment](https://arxiv.org/abs/2402.05070), large language models, and NLP for social good. I'm also a student researcher at Google DeepMind researching pluralistic alignment with the VOICES team.

Publications
======
Publications are listed in reverse chronological order. For a list of all publications, see [my google scholar profile](https://scholar.google.com/citations?hl=en&pli=1&user=dWaTwM4AAAAJ).

- _Can Language Models Reason about Individualistic Human Values and Preferences?_  
  Liwei Jiang, **Taylor Sorensen**, Sydney Levin, Yejin Choi  
  **In review**  
  [Paper](https://arxiv.org/abs/2410.03868)

- _Modular Pluralism: Pluralistic Alignment via Multi-LLM Collaboration_  
  Shangbin Feng, **Taylor Sorensen**, Yuhan Liu, Jillian Fisher, Chan Young Park, Yejin Choi, Yulia Tsvetkov  
  **EMNLP 2024**  
  [Paper](https://arxiv.org/abs/2406.15951)

- _A Roadmap to Pluralistic Alignment_  
  **Taylor Sorensen**, Jared Moore, Jillian Fisher, Mitchell Gordon, Niloofar Mireshghallah, Christopher Michael Rytting, Andre Ye, Liwei Jiang, Ximing Lu, Nouha Dziri, Tim Althoff, Yejin Choi  
  **ICML 2024 Position Paper**  
  [Paper](https://arxiv.org/abs/2402.05070), Featured in [Jack Clark's Import AI](https://importai.substack.com/p/import-ai-360-guessing-emotions-drone)  and [Interconnects](https://www.interconnects.ai/p/reinventing-llm-alignment), [Invited Talk](https://www.youtube.com/watch?v=lEoBNBfNklI)

- _Leveraging AI for democratic discourse: Chat interventions can improve online political conversations at scale_  
  Lisa P. Argyle, Christopher A. Bail, Ethan C. Busby, Joshua R. Gubler, Thomas Howe, Christopher Rytting, **Taylor Sorensen**, David Wingate  
  **Published in PNAS**  
  [Paper](https://www.pnas.org/doi/10.1073/pnas.2311627120), [Science Journal for Kids Adaptation](https://www.sciencejournalforkids.org/articles/how-can-ai-make-online-chats-kinder/)

- _Value Kaleidoscope: Engaging AI with Pluralistic Human Values, Rights, and Duties_  
  **Taylor Sorensen**, Liwei Jiang, Jena Hwang, Sydney Levine, Valentina Pyatkin, Peter West, Nouha Dziri, Ximing Lu, Kavel Rao, Chandra Bhagavatula, Maarten Sap, John Tasioulas, Yejin Choi  
  **AAAI 2024**  _Oral (top 3% of submissions)_    
  [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/29970), [Presentation](https://underline.io/lecture/93113-value-kaleidoscope-engaging-ai-with-pluralistic-human-values-rights-and-duties), [Demo](https://kaleido.allen.ai/), [Code](https://github.com/tsor13/kaleido), [Dataset](https://huggingface.co/datasets/tsor13/ValuePrism), [Model](https://huggingface.co/tsor13/kaleido-xl), [Invited Talk](https://www.youtube.com/watch?v=lEoBNBfNklI)

<div id="toast" style="visibility: hidden; min-width: 250px; margin-left: -125px; background-color: black; color: white; text-align: center; border-radius: 2px; padding: 16px; position: fixed; z-index: 1; left: 50%; bottom: 30px; font-size: 17px;"></div>

<script>
function copyToClipboard(text) {
  navigator.clipboard.writeText(text).then(function() {
    showToast(text);
  }, function(err) {
    console.error('Could not copy text: ', err);
  });
}

function showToast(text) {
  var toast = document.getElementById("toast");
  // toast.textContent = 'Citation copied to clipboard: ' + text; // Display the copied text
  toast.textContent = 'Citation copied to clipboard!'; // Display the copied text
  toast.style.visibility = "visible";
  setTimeout(function(){ toast.style.visibility = "hidden"; }, 1000);
}
</script>


- _NovaCOMET: Open Commonsense Foundation Models with Symbolic Knowledge Distillation_  
  Peter West, Ronan Bras, **Taylor Sorensen**, Bill Lin, Liwei Jiang, Ximing Lu, Khyathi Chandu, Jack Hessel, Ashutosh Baheti, Chandra Bhagavatula, Yejin Choi  
  **Findings of EMNLP 2023**   
  [Paper](https://aclanthology.org/2023.findings-emnlp.80/)

- _Impossible Distillation: from Low-Quality Model to High-Quality Dataset & Model for Summarization and Paraphrasing_  
  Jaehun Jung, Peter West, Liwei Jiang, Faeze Brahman, Ximing Lu, Jillian Fisher, **Taylor Sorensen**, Yejin Choi  
  **NAACL 2024**  
  [Paper](https://arxiv.org/abs/2305.16635)

- _Towards Coding Social Science Datasets with Language Models_  
  Christopher Michael Rytting, **Taylor Sorensen**, Lisa Argyle, Ethan Busby, Nancy Fulda, Joshua Gubler, David Wingate  
  **Arxiv Preprint**  
  [Paper](https://arxiv.org/abs/2306.02177)

- _Prompt Compression and Contrastive Conditioning for Controllability and Toxicity Reduction in Language Models_  
  David Wingate, Mohammad Shoeybi, **Taylor Sorensen**  
  **Findings of EMNLP 2022**   
  [Paper](https://aclanthology.org/2022.findings-emnlp.412/), [Code](https://github.com/BYU-PCCL/prompt-compression-contrastive-coding)

- _An Information-theoretic Approach to Prompt Engineering Without Ground Truth Labels_  
  **Taylor Sorensen**, Joshua Robinson, Christopher Michael Rytting, Alexander Glenn Shaw, Kyle Jeffrey Rogers, Alexia Pauline Delorey, Mahmoud Khalil, Nancy Fulda, David Wingate  
  **ACL 2022**  
  [Paper](https://aclanthology.org/2022.acl-long.60/), [Code](https://github.com/BYU-PCCL/information-theoretic-prompts), [Presentation](https://underline.io/events/284/sessions/10759/lecture/50282-long-an-information-theoretic-approach-to-prompt-engineering-without-ground-truth-labels)

- _Nl-augmenter: A framework for task-sensitive natural language augmentation_  
  Kaustubh D Dhole, Varun Gangal, Sebastian Gehrmann, ..., **Taylor Sorensen** et al.  
  **Arxiv Preprint**  
  [Paper](https://arxiv.org/pdf/2112.02721.pdf), [Code](https://github.com/GEM-benchmark/NL-Augmenter)

- _Using first principles for deep learning and model-based control of soft robots_  
  Curtis C Johnson, Tyler Quackenbush, **Taylor Sorensen**, David Wingate, Marc D Killpack  
  **Frontiers in Robotics and AI**  
  [Paper](https://www.frontiersin.org/articles/10.3389/frobt.2021.654398/full), [Code](https://github.com/BYU-PCCL/DL-MPC)

Invited Talks
======
- University College London _Aligning AI with Pluralistic Human Values._ Sep 2024
- Vienna Alignment Workshop _Pluralistic Alignment._ July 2024
- IBM Research _AI and Pluralistic Human Values._ March 2024
- BuzzRobot AI Community _Aligning AI with Pluralistic Human Values._ May 2024 [Recording](https://www.youtube.com/watch?v=lEoBNBfNklI)


======
Website last updated: Oct 14, 2024