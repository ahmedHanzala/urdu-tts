<h1>Generative Urdu Speech Synthesis</h1>
  <p>
  <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License: MIT"></a>
   
<a href="https://colab.research.google.com/drive/1gGKaVaWyl6SCWIBWQehWrgHWiG1teFw4">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Inference in Colab">
</a>
 </p>


<h2>Overview</h2>
<p> This is a preview of the paper "Generative Urdu Speech Synthesis". All the weights are opensourced <a href="https://huggingface.co/zohann/urdu-tts">here.</a></p>




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
            <td><pre>[English Prompt on our Urdu Model] we are testing this model for our project.</pre> </td>
            <td>
              <audio controls>
                <source src="audios/english-only.wav" type="audio/wav">
                  Your browser does not support the audio element.
              </audio>
           </td>
        </tr>
            <tr>
            <td><pre>[English + Urdu Prompt] I'm doing good میں اچھا ہو آپ سناؤ </pre> </td>
            <td>
              <audio controls>
                <source src="audios/urdu-n-english.wav" type="audio/wav">
                  Your browser does not support the audio element.
              </audio>
           </td>
        </tr>
            <tr>
            <td><pre> seecs ایک بہت اچھا ڈیپارٹمنٹ ہے</pre> </td>
            <td>
              <audio controls>
                <source src="audios/urdu-only.mov" type="audio/wav">
                  Your browser does not support the audio element.
              </audio>
           </td>
        </tr>
            <tr>
            <td><pre>آپ کا نام کیا ہے؟</pre> </td>
            <td>
              <audio controls>
                <source src="audios/1.wav" type="audio/wav">
                  Your browser does not support the audio element.
              </audio>
           </td>
        </tr>
            <tr>
            <td><pre> كيا آپ انگريزی بولتے ہیں؟</pre> </td>
            <td>
              <audio controls>
                <source src="audios/2.wav" type="audio/wav">
                  Your browser does not support the audio element.
              </audio>
           </td>
        </tr>
              <tr>
            <td><pre> میں اردو سیکھنے کی کوشش کر رہا ہوں</pre> </td>
            <td>
              <audio controls>
                <source src="audios/3.wav" type="audio/wav">
                  Your browser does not support the audio element.
              </audio>
           </td>
        </tr>
              <tr>
            <td><pre> آپ کہاں سے ہیں؟</pre> </td>
            <td>
              <audio controls>
                <source src="audios/4.wav" type="audio/wav">
                  Your browser does not support the audio element.
              </audio>
           </td>
        </tr>
              <tr>
            <td><pre> آپ سے مل کر خوشی ہوئی</pre> </td>
            <td>
              <audio controls>
                <source src="audios/5.wav" type="audio/wav">
                  Your browser does not support the audio element.
              </audio>
           </td>
        </tr>
              <tr>
            <td><pre>!یہ مجھے بہت پَسند آیا</pre> </td>
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
    This project is licensed under the MIT License. Feel free to use and modify the code according to your needs.
