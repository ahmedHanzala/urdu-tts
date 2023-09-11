<h1> A Urdu Voice Cloning using Tortoise-tts</h1>
  <p>
  <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License: MIT"></a>
</a>
<a href="https://colab.research.google.com/drive/1g_VHQQvl-23tT635uz57isbcvsYEvyZR?usp=sharing">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">
</a>
<a href="https://colab.research.google.com/drive/1FGm_OxAi6f3y8_JExqOqcCyFK2cn6YQu?usp=sharing">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">
</a>
  <a href="https://colab.research.google.com/drive/1gGKaVaWyl6SCWIBWQehWrgHWiG1teFw4?usp=sharing">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">
  </a>
 </p>
 <h2>ANNOUNCEMENT</h2>
 ill be soon uploading the models to huggingface hopefully by the start of next month 

<h2>Overview</h2>
<p>This project aims on text-to-speech and cloning voices with indian accents (as most models for tts or voice cloning are trained on English voices and perform very poorly on south-asian or indian accents). This is a fork from the tortoise-tts model and DL-Art-School trainer </p>
NOTE: This repository is incomplete. I have for now shared my results, ill update this README and add usage, training info, and other documentations. The training files and others also have not been pushed yet and the repo is incomplete. So it might be difficult for a layman to use (working on doing that soon), but for people familiar with the tortoise arcitecture this would work.
</p>
    
<h2>Features</h2>
    <ul>
      <li><strong>South-Asian Accent Voice Cloning:</strong> tortoise-tts better captures european and american accents but when a non native speaker voice is cloned it americanizes that voice and completely fails. This model has been finetuned on a south-asian accent dataset, so it performs very well in cloning voices with a south-asian accent.
        to better capture and reproduce Indian accents, enabling accurate voice cloning for a variety of Indian English accents. It offers improved voice quality and natural-sounding speech synthesis for a more authentic experience.</li>
      <li><strong>Urdu Text-to-Speech:</strong> The model also includes support for Urdu text-to-speech, it can understand the arabic-urdu script and produce speech in urdu based on the text. </li>
    </ul>
    <h2> Results and Comparisons</h2>
    

<pre><code><strong>Prompt:</strong> we are testing this model for our project.</code></pre>
  
<h3>Tortoise-tts cloning an indian accent</h3>

https://github.com/ahmedHanzala/urdu-voice-cloning/assets/105395393/fae434cb-df10-4b58-8b7d-6e4c50115e32

<h3>Our finetuned Model</h3>
  
https://github.com/ahmedHanzala/urdu-voice-cloning/assets/105395393/05ca7d27-87fd-4001-b62e-26ee71a76d5b


<h2> Urdu script and urdu text-to-speech testing </h2>

<pre><code><strong>Prompt:</strong> seecs ایک بہت اچھا ڈیپارٹمنٹ ہے</code></pre>

<h3>On Tortoise-tts base model</h3>

https://github.com/ahmedHanzala/urdu-voice-cloning/assets/105395393/31dcefce-fc8d-436e-8c16-11d60de140b7

<h3>On our finetuned Model</h3>

https://github.com/ahmedHanzala/urdu-voice-cloning/assets/105395393/5394a4b4-d685-4e87-a254-7ea9436c3545


<h2>Refference</h2>
<ul>
  <li> https://github.com/152334H/DL-Art-School</li>
  <li> https://github.com/neonbjb/tortoise-tts</li>
  </ul>
<h2>License</h2>
    <p>This project is licensed under the <a href="LICENSE">MIT License</a>. Feel free to use and modify the code according to your needs.</p>
  </html>
