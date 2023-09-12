<h1>Generative Urdu Speech Synthesis</h1>

 <a href="https://huggingface.co/zohann/urdu-tts" target="_blank">
        <button>
            <img src="https://huggingface.co/front/assets/hugging_face_logo.svg" alt="Hugging Face Logo" width="100">
        </button>
    </a>
    
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


<h2>Overview</h2>
<p>This project aims on text-to-speech and cloning voices with indian accents (as most models for tts or voice cloning are trained on English voices and perform very poorly on south-asian or indian accents). This is a fork from the tortoise-tts model and DL-Art-School trainer </p>
NOTE: This repository is incomplete. I have for now shared my results, ill update this README and add usage, training info, and other documentations. The training files and others also have not been pushed yet and the repo is incomplete. So it might be difficult for a layman to use (working on doing that soon), but for people familiar with the tortoise arcitecture this would work.
</p>
    

<h2> Audio Samples </h2>

  <table border="1">
        <thead>
            <tr>
                <th>Prompt</th>
                <th>Audio</th>
            </tr>
        </thead>
        <tbody>
          <tr>
            <td><pre><code> [English Prompt on our Urdu Model] we are testing this model for our project.</code></pre> </td>
            <td>
              <audio controls>
                <source src="audios/english-only.wav" type="audio/wav">
                  Your browser does not support the audio element.
              </audio>
           </td>
        </tr>
            <tr>
            <td><pre><code>[English + Urdu Prompt] I'm doing good میں اچھا ہو آپ سناؤ </code></pre> </td>
            <td>
              <audio controls>
                <source src="audios/urdu-n-english.wav" type="audio/wav">
                  Your browser does not support the audio element.
              </audio>
           </td>
        </tr>
            <tr>
            <td><pre><code> seecs ایک بہت اچھا ڈیپارٹمنٹ ہے </code></pre> </td>
            <td>
              <audio controls>
                <source src="audios/urdu-only.mov" type="audio/wav">
                  Your browser does not support the audio element.
              </audio>
           </td>
        </tr>
            <tr>
            <td><pre><code> آپ کا نام کیا ہے؟</code></pre> </td>
            <td>
              <audio controls>
                <source src="audios/1.wav" type="audio/wav">
                  Your browser does not support the audio element.
              </audio>
           </td>
        </tr>
            <tr>
            <td><pre><code> كيا آپ انگريزی بولتے ہیں؟</code></pre> </td>
            <td>
              <audio controls>
                <source src="audios/2.wav" type="audio/wav">
                  Your browser does not support the audio element.
              </audio>
           </td>
        </tr>
              <tr>
            <td><pre><code> میں اردو سیکھنے کی کوشش کر رہا ہوں</code></pre> </td>
            <td>
              <audio controls>
                <source src="audios/3.wav" type="audio/wav">
                  Your browser does not support the audio element.
              </audio>
           </td>
        </tr>
              <tr>
            <td><pre><code> آپ کہاں سے ہیں؟</code></pre> </td>
            <td>
              <audio controls>
                <source src="audios/4.wav" type="audio/wav">
                  Your browser does not support the audio element.
              </audio>
           </td>
        </tr>
              <tr>
            <td><pre><code> آپ سے مل کر خوشی ہوئی</code></pre> </td>
            <td>
              <audio controls>
                <source src="audios/5.wav" type="audio/wav">
                  Your browser does not support the audio element.
              </audio>
           </td>
        </tr>
              <tr>
            <td><pre><code>!یہ مجھے بہت پَسند آیا</code></pre> </td>
            <td>
              <audio controls>
                <source src="audios/7.wav" type="audio/wav">
                  Your browser does not support the audio element.
              </audio>
           </td>
        </tr>
        </tbody>
  </table>



<h2>Refference</h2>
<ul>
  <li> https://github.com/152334H/DL-Art-School</li>
  <li> https://github.com/neonbjb/tortoise-tts</li>
  </ul>
<h2>License</h2>
    <p>This project is licensed under the <a href="LICENSE">MIT License</a>. Feel free to use and modify the code according to your needs.</p>
  </html>
