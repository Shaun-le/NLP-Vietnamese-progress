# Automatic Speech Recognition

## VLSP 2018 Shared Task: Automatic Speech Recognition

* :scroll: [VLSP 2018 Shared Task: Automatic Speech Recognition Paper](https://drive.google.com/file/d/1ela9aLGYtouVBT1da91B37mADhEwxxd8/view?usp=sharing)

In the ASR task, participants were asked to transcribe automatically Vietnamese audio files into the spoken word sequences. The committee provided the test set only, while the training data for the acoustic and language models was developed by the teams themselves.

The test set was composed of 796 continuous wav files of news speech for a total duration of two hours, without any information on the sentence segmentation. The speech was recorded in a non-noisy environment, and available in three dialects: Northern, Southern and Central with respectively proportion of 50%, 40% and 10%.

### Leaderboard

<table>
  <tr>
    <th rowspan="2">Model</th>
    <th colspan="2">Score</th>
    <th rowspan="2">Paper/Source</th>
    <th rowspan="2">Code</th>
  </tr>
  <tr>
    <td>WER</td>
    <td>SER</td>
  </tr>
  <tr>
    <td>VAIS</td>
    <td>6.29</td>
    <td>75.50</td>
    <td><a href="https://drive.google.com/file/d/1buzfM07HDoyFZwjWVPeGm5GkKEmpOySn/view?usp=sharing">Do et al. VLSP'18</a></td>
    <td></td>
  </tr>
  <tr>
    <td>Viettel-CSC</td>
    <td>7.40</td>
    <td>75.38</td>
    <td><a href="https://drive.google.com/file/d/1Nhb8rYmqUK-d8Q-H9lvAOrzO8-fQjP94/view?usp=sharing">Nguyen et al. VLSP'18</a</td>
    <td></td>
  </tr>
</table>

## Miscellaneous

:scroll: **Papers**

* [Nguyen et al. SoICT'18. Development of a Vietnamese Large Vocabulary Continuous
Speech Recognition System under Noisy Conditions](https://drive.google.com/file/d/1Vqxcy11o8_HY_xItrS416vvw-e1fm6uk/view?usp=sharing)
* [Nguyen et al. O-COCOSDA'17. Development of a Vietnamese speech recognition system for Viettel call center](https://drive.google.com/file/d/1N_Q8Mq_ArKZQqP7gq3kCxGf9iQBazpci/view?usp=sharing)

:dizzy: **Libraries**
  
* 2021, [vietai/ASR](https://github.com/vietai/ASR) - Vietnamese end-to-end speech recognition using wav2vec 2.0
  
:dizzy: **Services**

* 2018, [vtcc.ai ASR](https://vtcc.ai/asr)
* 2017, [OpenFPT: Speech Recognition](http://doc.openfpt.vn/#speech-recognition)

:file_folder: **Dataset**

* [Vietnamese Speech Recognition Corpus- (Mobile)- 144 Speaker](http://kingline.speechocean.com/exchange.php?id=3758&act=view) - 76.6 hours *by Speechocean (2017)* `data` `$`
* [Vietnamese Speech Recognition Corpus-(In-Car)-300 Speakers](http://kingline.speechocean.com/exchange.php?id=3333&act=view) - 305 hours *by Speechocean (2017)* `data` `$`
* [Globalphone Vietnamese](http://catalog.elra.info/product_info.php?products_id=1144) - 22.5 hours of read speech from 15 Vietnamese online newspapers *by ELRA (2012)* `data` `$`
* [VIVOS](http://ailab.hcmus.edu.vn/vivos/) - a free Vietnamese speech corpus consisting of 15 hours of recording speech *by AILab (2017)* `data`
* [FPT-30](https://techinsight.com.vn/30-nam-fpt-tang-30-tieng-du-lieu-thu-am/) - `data`
