Paper : https://www.researchgate.net/publication/293807031_Wake-Up-Word_Speech_Recognition/

<table class="tg">
<thead>
  <tr>
    <th class="tg-0pky"><span style="font-weight:bold">Title</span></th>
    <th class="tg-0pky">Wake-Up-Word Speech Recognition</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0pky" rowspan="2"><span style="font-weight:bold">Challenge</span></td>
    <td class="tg-0pky">Speech is one of the most natural forms of communications between people. Spoken language has the unique property, <br>naturally learned as part of human development.</td>
  </tr>
  <tr>
    <td class="tg-0pky">- Spoken language learning process applied to digital computing systems.</td>
  </tr>
  <tr>
    <td class="tg-fymr" rowspan="11"><span style="font-weight:bold">Key Related Work</span></td>
    <td class="tg-0pky">1. ASR( Automatic Speech Recognition )</td>
  </tr>
  <tr>
    <td class="tg-0pky">2. HMI( Human Machine Interaction )</td>
  </tr>
  <tr>
    <td class="tg-0pky">3. WUW( Wake-Up-Word )</td>
  </tr>
  <tr>
    <td class="tg-0lax">4. VAD( Voice Activity Detector )</td>
  </tr>
  <tr>
    <td class="tg-0lax">5. SVM( Support Vector Machines )</td>
  </tr>
  <tr>
    <td class="tg-0lax">6. OOV( Out-of-Vocabulary )</td>
  </tr>
  <tr>
    <td class="tg-0lax">7. MFCC( Mel-Filtered Cepstral Coefficients )</td>
  </tr>
  <tr>
    <td class="tg-0lax">8. LPC( Linear Predictive Coding coefficients )</td>
  </tr>
  <tr>
    <td class="tg-0lax">9. HMM( Hidden Markov Models )</td>
  </tr>
  <tr>
    <td class="tg-0lax">10. Windowing : Stage slices the input signal into discrete time segments.</td>
  </tr>
  <tr>
    <td class="tg-0lax">11. DFT( Discrete Fourier Transform )</td>
  </tr>
  <tr>
    <td class="tg-0pky" rowspan="4"><span style="font-weight:bold">Solution</span></td>
    <td class="tg-0pky">1. WUW Front End</td>
  </tr>
  <tr>
    <td class="tg-0lax">2. Voice Activity Detection classification</td>
  </tr>
  <tr>
    <td class="tg-0lax">3. WUW Back End - plain HMM scores</td>
  </tr>
  <tr>
    <td class="tg-0lax">4. SVM parameters</td>
  </tr>
  <tr>
    <td class="tg-0pky" rowspan="3"><span style="font-weight:bold">Results</span></td>
    <td class="tg-0pky">1. The word list is sorted by increasing Total Error Rates for the usual, standard “Score 1”, classifier and broken into two groups for clarity.</td>
  </tr>
  <tr>
    <td class="tg-0pky">2. the RERR gains for each method, the average RERR gain across all words considered in the TIMIT test set.</td>
  </tr>
  <tr>
    <td class="tg-0pky">3. An average Relative Error Rate Reduction of 532% using Two-Class SVM Scoring with the Duration feature.</td>
  </tr>
  <tr>
    <td class="tg-0pky"><span style="font-weight:bold">Conclusion</span></td>
    <td class="tg-0pky">The WUW-SR system developed in this work provides for efficient and highly accurate speaker independent recognitions at performance levels not achievable by current state of the art recognizers.<br></td>
  </tr>
</tbody>
</table>
