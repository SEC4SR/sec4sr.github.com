
<!-- # SEC4SR
## A SECurity analysis platform for Speaker Recognition
### under construction. stay tuned! :)  -->

# Notice
Our paper is under review now. 

To keep anonymous, currently all the code links in this webpage point to our anonymous repository in [Anonymous Github](https://anonymous.4open.science/faq). 

We will release the true link of our Github repository when the review process is over.

# About
This is the official webpage for paper ***Defending against Audio Adversarial Examples on Speaker Recognition Systems***. 

In this paper, we systematically investigate transformation and adversarial training based defenses for speaker recognition systems (SRSs) 
and thoroughly evaluate their effectiveness using both non-adaptive and adaptive attacks under the same settings. 

In summary, we make the following main contributions:
- We perform the largest-scale evaluation of defenses against adversarial attacks in the speaker recognition
domain, involving **23** defenses and **15** attacks. Our study provides lots of useful insights and findings that could advance research on adversarial examples in this domain and assist the maintainers of SRSs to deploy suitable defense solutions to enhance their systems.
- We propose a new type of feature-level transformations
dedicated for speaker recognition, called **Feature Compression** (**FeCo**). Though it solely cannot defeat white-box adaptive attacks, it is effective against black-box adaptive attacks and definitely enhances the robustness of adversarially trained models against white-box adaptive attacks.
- We develop **SEC4SR**, the first platform for systematic
and comprehensive evaluation of different adversarial
attacks and defenses in the speaker recognition domain. It features mainstream SRSs, proper voice datasets, white-box and black-box attacks, techniques for mounting adaptive attacks, evaluation metrics and diverse defense solutions. We release our platform to foster further research in this direction.

# Empirical Study Result
## Transformation against Non-adaptive Attacks
<center>
    <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
    src="figure/evaluation-1.jpg">
    <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 2px;"></div>
</center>

## Transformation against Adaptive Attacks
<center>
    <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
    src="figure/evaluation-2.jpg">
    <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 2px;"></div>
</center>

## Transformation+Adversarial-Training against Adaptive Attacks
<center>
    <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
    src="figure/evaluation-3.jpg">
    <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 2px;"></div>
</center>

# Additional Results (not appear in the paper)
## *Appendix C. Tuning the Parameters of Transformations*
<center>
    <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
    src="figure/appendix-B-1-1.jpg">
    <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 2px;"></div>
</center>

<center>
    <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
    src="figure/appendix-B-1-2.jpg">
    <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 2px;"></div>
</center>

<center>
    <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
    src="figure/appendix-B-1-3.jpg">
    <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 2px;"></div>
</center>

<center>
    <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
    src="figure/appendix-B-2-1.jpg">
    <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 2px;"></div>
</center>

<center>
    <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
    src="figure/appendix-B-2-2.jpg">
    <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 2px;"></div>
</center>

<center>
    <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
    src="figure/appendix-B-2-3.jpg">
    <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 2px;"></div>
</center>

# Audio Files
We provides our audio files for percetibility measurement and other purposes.

- [Original audios (Spk10_test)](https://drive.google.com/uc?id=1WctqJtP5Es74-U7y3cFXqfHi7JkDz6g5&export=download)

- [Adversarial audios produced by non-adaptive attacks](https://drive.google.com/uc?id=1CAOwwLsVYibEVdNXTwPVSIWP40Amuhr8&export=download)

- Adversarial audios produced by adaptive attacks against different defenses:

    - Time-domain defenses: [[QT]](https://drive.google.com/uc?id=1f9hAYRO1MIm-NNRdKmM44OAokPbMVs_z&export=download) [[AT]](https://drive.google.com/uc?id=1pDhJQFHk7puH7NFRzWBykLkwt-gQEFRr&export=download) [[AS]](https://drive.google.com/uc?id=1d7znPoTCkKQ-rzQrnrfZP1IxRZ7jOx4f&export=download) [[MS]](https://drive.google.com/uc?id=1TzuggGx3Xgb1czcGBv6Zq2KZzMygsvNd&export=download)

    - Frequency-domain defenses: [[DS]](https://drive.google.com/uc?id=1iVFUA2nej9xu7W0Y759TtssvEjy9R7G0&export=download) [[LPF]](https://drive.google.com/uc?id=1Xg-fYEMDxAM0VkOX7gL0mQnOFHwyi-AS&export=download) [[BPF]](https://drive.google.com/uc?id=1bFgy94zh3xKRLlo5zpo1PgLS6EZrxnBw&export=download)

    - Speech compression defenses: [[OPUS]](https://drive.google.com/uc?id=1qXvmigK5NfJdtV2GKSu-L9bm_29xlM5y&export=download) [[SPEEX]](https://drive.google.com/uc?id=13sqxpAtOOAdbAgj-tvexv3iEoV3kGbgW&export=download) [[AMR]](https://drive.google.com/uc?id=13nm9JoBlf-uj09tN9HaDOfhV0dG875r4&export=download) [[AAC-V]](https://drive.google.com/uc?id=1i2ZajGzABNuZNryy7RicSWWgRYnLVasr&export=download) [[AAC-C]](https://drive.google.com/uc?id=1UFXk2zNJ7SN5sn-83HCnFpozRlidMGWU&export=download) [[MP3-V]](https://drive.google.com/uc?id=1JyPp6Ya7ncSjeEHtnX8EZC7HJ5iVdR23&export=download) [[MP3-C]](https://drive.google.com/uc?id=1NiYKKMtwAL2JHoMLl83h1fjGloDbV_4G&export=download)

    - Feature-level defense: [[FeCo]](https://drive.google.com/uc?id=1bwz9WuDpv94tj77Zx_tJU_lwjQdwGZA7&export=download)
 
For adversarial audios, after unzip, the directory *A-B/X/X-Y/Z* means the audios are crafted by the attack X with the attack paramter Y against the defense A with the defense parameter B on the speaker Z. 
For example, *FeCo-ok-kmeans-raw-0_2-L2/FGSM/FGSM-0_002-50/1998* means the audios are crafted by FGSM attack with $\varepsilon=0.002$ and EOT_size $r=50$ against the defense FeCo with the defense parameter $cl_m=kmeans$ and $cl_r=0.2$ on the speaker 1998. 

# Platform: SEC4SR
To perform the above empirical study, we establish a **SEC**urity evaluation platform **FOR** **S**peaker **R**ecognition (SEC4SR). 

Want to re-produce our experimental results, do something new with our platform, or even extend SEC4SR? 
<!-- Go to [Code for SEC4SR](https://github.com/SEC4SR/SEC4SR) for detailed instructions. -->
Go to [Code for SEC4SR](https://anonymous.4open.science/r/SEC4SR-AD54) for detailed instructions.
