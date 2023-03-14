Paper : https://arxiv.org/pdf/1706.03762.pdf

<table class="tg">
<thead>
  <tr>
    <th class="tg-0pky"><span style="font-weight:bold">Title</span></th>
    <th class="tg-0pky">Attention Is All You Need</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0pky" rowspan="2"><span style="font-weight:bold">Challenge</span></td>
    <td class="tg-0pky">1. Traditional sequence-to-sequence models based on recurrent and convolutional networks have limitions in parallelization and <br>modeling long-rang dependencies.</td>
  </tr>
  <tr>
    <td class="tg-0pky">2. The use of hand-crafted features and prior knowledge in these models can hinder their generalization capabilities.</td>
  </tr>
  <tr>
    <td class="tg-0pky" rowspan="2"><span style="font-weight:bold">Key Related Work</span></td>
    <td class="tg-0pky">1. Recurrent neural networks (RNNs) and convolutional neural networks (CNNs) for sequence modeling.</td>
  </tr>
  <tr>
    <td class="tg-0pky">2. Attention mechanisms, particularly in image captioning and neural machine translation.</td>
  </tr>
  <tr>
    <td class="tg-0pky" rowspan="3"><span style="font-weight:bold">Solution</span></td>
    <td class="tg-0pky">1. A novel architecture for sequence modeling based solely on attention mechanisms, called the Transformer.</td>
  </tr>
  <tr>
    <td class="tg-0pky">2. The Transformer uses a multi-headed self-attention mechanism to capture dependencies between all positions in the input and output sequences in parallel.</td>
  </tr>
  <tr>
    <td class="tg-0pky">3. The Transformer also uses position-wise fully connected feed-forward networks to process the input and output sequences.</td>
  </tr>
  <tr>
    <td class="tg-0pky" rowspan="2"><span style="font-weight:bold">Results</span></td>
    <td class="tg-0pky">1. The Transformer outperformed the previous state-of-the-art models on the WMT 2014 English-German and English-French translation tasks, achieving BLEU scores of 28.4 and 41.0, respectively.</td>
  </tr>
  <tr>
    <td class="tg-0pky">2. The Transformer also achieved competitive results on the English- Czech and English-Latvian translation tasks.</td>
  </tr>
  <tr>
    <td class="tg-0pky" rowspan="2"><span style="font-weight:bold">Conclusion</span></td>
    <td class="tg-0pky">1. The paper presented a novel architecture based solely on attention mechanisms for sequence modeling, which does not require the use of RNNs or CNNs.</td>
  </tr>
  <tr>
    <td class="tg-0pky">2. The Transformer achieved state-of-the-art results on several machine translation tasks, demonstrating the effectiveness of the attention mechanism.</td>
  </tr>
</tbody>
</table>
