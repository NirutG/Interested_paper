Paper : https://aclanthology.org/2022.naacl-main.63/

<table class="tg">
<thead>
  <tr>
    <th class="tg-0pky"><span style="font-weight:bold">Title</span></th>
    <th class="tg-0pky"><span style="font-weight:bold">Textless Speech-to-Speech Translation on Real Data</span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0pky" rowspan="3"><span style="font-weight:bold">Challenge</span></td>
    <td class="tg-0pky">They present a textless speech-to-speech translation (S2ST) system that can translate speech<br>from one language into another language and can be built without the need of any text data.<br></td>
  </tr>
  <tr>
    <td class="tg-0pky">1. Model multispeaker target speech</td>
  </tr>
  <tr>
    <td class="tg-0pky">2. Train the system with real-world S2ST data</td>
  </tr>
  <tr>
    <td class="tg-fymr" rowspan="3"><span style="font-weight:bold">Key Related Work</span></td>
    <td class="tg-0pky">1. Direct S2ST</td>
  </tr>
  <tr>
    <td class="tg-0pky">2. S2ST data</td>
  </tr>
  <tr>
    <td class="tg-0pky">3. Speech normalization technique</td>
  </tr>
  <tr>
    <td class="tg-0pky"><span style="font-weight:bold">Solution</span></td>
    <td class="tg-0pky">Self-supervised unit-based speech normalization technique with finetunes a pre-train speech<br>encoder with paired audios from multiple speakers and a single reference speaker to reduce <br>the variations due to accents, while preserving the lexical content.</td>
  </tr>
  <tr>
    <td class="tg-0pky" rowspan="3"><span style="font-weight:bold">Results</span></td>
    <td class="tg-0pky">1. Textless S2ST, S2ST with supervised data : First, compared with the basic setup, the baseline with target speaker embedding<br>can give a1.2.2 BLEU improvement on three language pairs</td>
  </tr>
  <tr>
    <td class="tg-0lax">2. Analysis on the speech normalizer : Norm-unit from a speech normalizer finetuned on 1-hr data achieves similar WER<br>as orig-unit, indicating that the normalization process does not change the content of the speech.</td>
  </tr>
  <tr>
    <td class="tg-0lax">3. Analysis of mined data : Each pair of aligned speech in the mined data has an associated semantic similarity score.</td>
  </tr>
  <tr>
    <td class="tg-0pky"><span style="font-weight:bold">Conclusion</span></td>
    <td class="tg-0pky">A textless S2ST system can be trained with real target speech data. The key to the success is a self-supervised unit-based<br>speech normalization process, which reduces variations in the mult-speaker target speech while retaining the lexical content.</td>
  </tr>
  <tr>
    <td class="tg-0pky"><span style="font-weight:bold">Future work</span></td>
    <td class="tg-0pky">They plan to investigate more textless approaches to improve model performance such as self-<br>supervised pre-training. All the experiments and ASR evaluation are conducted with publicdatasets or open-sourced models.<br></td>
  </tr>
</tbody>
</table>
