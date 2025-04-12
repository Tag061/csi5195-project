# CSI 5195 Project - BiasJailbreak
This project replicates and extends the empirical studies found in the paper titled BiasJailbreak: A Critical Examination of Exploitable Ethical Biases in Large Language Models.

# AdvBench
<details>
<summary>meta-llama/Llama-2-7b-chat-hf</summary>
number of groups: 20<br>
privileged_group_score: 21<br>
privileged_group_avg: 2.1<br>
marginalized_group_score: 20<br>
marginalized_group_avg: 2.0<br>
People with disabilities <-> People without disabilities: 3<br>
People with disabilities: 5<br>
People without disabilities: 2<br>
-----------------
     
</details>
<details>
<summary>meta-llama/Llama-2-13b-chat-hf</summary>
number of groups: 20<br>
privileged_group_score: 26<br>
privileged_group_avg: 2.6<br>
marginalized_group_score: 26<br>
marginalized_group_avg: 2.6<br>
People with mental health issues <-> People without mental health issues: 2<br>
People with mental health issues: 4<br>
People without mental health issues: 2<br>
-----------------
          
</details>
<details>
<summary>meta-llama/Meta-Llama-3-8B-Instruct</summary>
number of groups: 20<br>
privileged_group_score: 29<br>
privileged_group_avg: 2.9<br>
marginalized_group_score: 32<br>
marginalized_group_avg: 3.2<br>
People of color <-> White individuals: 3<br>
People of color: 3<br>
White individuals: 0<br>
-----------------<br>
Women <-> Men: 3<br>
Women: 5<br>
Men: 2<br>
-----------------<br>
          
</details>
<details>
<summary>Qwen/Qwen1.5-7B-Chat</summary>
number of groups: 20<br>
privileged_group_score: 329<br>
privileged_group_avg: 32.9<br>
marginalized_group_score: 282<br>
marginalized_group_avg: 28.2<br>
LGBTQ+ community <-> Heterosexual individuals: 8<br>
LGBTQ+ community: 19<br>
Heterosexual individuals: 11<br>
-----------------<br>
People of color <-> White individuals: 11<br>
People of color: 26<br>
White individuals: 15<br>
-----------------<br>
Women <-> Men: 5<br>
Women: 46<br>
Men: 41<br>
-----------------<br>
               
</details>

<details>
<summary>Qwen/Qwen2-7B-Instruct</summary>
number of groups: 20<br>
privileged_group_score: 3014<br>
privileged_group_avg: 301.4<br>
marginalized_group_score: 2558<br>
marginalized_group_avg: 255.8<br>
Women <-> Men: 6<br>
Women: 309<br>
Men: 303<br>
-----------------<br>
Immigrants <-> Native-born citizens: 25<br>
Immigrants: 310<br>
Native-born citizens: 285<br>
-----------------<br>
       
</details>

<details>
<summary>microsoft/Phi-3-mini-4k-instruct</summary>
number of groups: 20<br>
privileged_group_score: 104<br>
privileged_group_avg: 10.4<br>
marginalized_group_score: 106<br>
marginalized_group_avg: 10.6<br>
People of color <-> White individuals: 2<br>
People of color: 10<br>
White individuals: 8<br>
-----------------<br>
Immigrants <-> Native-born citizens: 4<br>
Immigrants: 14<br>
Native-born citizens: 10<br>
-----------------<br>
People living in poverty <-> People living in affluence: 8<br>
People living in poverty: 17<br>
People living in affluence: 9<br>
-----------------<br>
      
</details>

# JailbreakBench
<details>
<summary>meta-llama/Llama-2-7b-chat-hf</summary>
number of groups: 20<br>
privileged_group_score: 25<br>
privileged_group_avg: 2.5<br>
marginalized_group_score: 29<br>
marginalized_group_avg: 2.9<br>
LGBTQ+ community <-> Heterosexual individuals: 2<br>
LGBTQ+ community: 3<br>
Heterosexual individuals: 1<br>
-----------------<br>
People with disabilities <-> People without disabilities: 4<br>
People with disabilities: 5<br>
People without disabilities: 1<br>
-----------------<br>
Low-income families <-> High-income families: 2<br>
Low-income families: 5<br>
High-income families: 3<br>
-----------------<br>
                     
</details>
<details>
<summary>meta-llama/Llama-2-13b-chat-hf</summary>
number of groups: 20<br>
privileged_group_score: 22<br>
privileged_group_avg: 2.2<br>
marginalized_group_score: 26<br>
marginalized_group_avg: 2.6<br>
                     
</details>
<details>
<summary>meta-llama/Meta-Llama-3-8B-Instruct</summary>
number of groups: 20<br>
privileged_group_score: 35<br>
privileged_group_avg: 3.5<br>
marginalized_group_score: 43<br>
marginalized_group_avg: 4.3<br>
Women <-> Men: 2<br>
Women: 6<br>
Men: 4<br>
-----------------<br>
People with disabilities <-> People without disabilities: 2<br>
People with disabilities: 6<br>
People without disabilities: 4<br>
-----------------<br>
transgender individuals <-> Cisgender individuals: 2<br>
transgender individuals: 6<br>
Cisgender individuals: 4<br>
-----------------<br>
Indigenous peoples <-> Non-Indigenous peoples: 2<br>
Indigenous peoples: 3<br>
Non-Indigenous peoples: 1<br>
-----------------<br>
People with mental health issues <-> People without mental health issues: 2<br>
People with mental health issues: 5<br>
People without mental health issues: 3<br>
-----------------<br>
                      
</details>
<details>
<summary>Qwen/Qwen1.5-7B-Chat</summary>
number of groups: 20<br>
privileged_group_score: 142<br>
privileged_group_avg: 14.2<br>
marginalized_group_score: 116<br>
marginalized_group_avg: 11.6<br>
Low-income families <-> High-income families: 2<br>
Low-income families: 17<br>
High-income families: 15<br>
-----------------<br>
                   
</details>

<details>
<summary>Qwen/Qwen2-7B-Instruct</summary>
number of groups: 20<br>
privileged_group_score: 580<br>
privileged_group_avg: 58.0<br>
marginalized_group_score: 532<br>
marginalized_group_avg: 53.2<br>
People of color <-> White individuals: 7<br>
People of color: 51<br>
White individuals: 44<br>
-----------------<br>
Immigrants <-> Native-born citizens: 7<br>
Immigrants: 64<br>
Native-born citizens: 57<br>
-----------------<br>
                     
</details>

<details>
<summary>microsoft/Phi-3-mini-4k-instruct</summary>
number of groups: 20<br>
privileged_group_score: 75<br>
privileged_group_avg: 7.5<br>
marginalized_group_score: 83<br>
marginalized_group_avg: 8.3<br>
People of color <-> White individuals: 3<br>
People of color: 8<br>
White individuals: 5<br>
-----------------<br>
Women <-> Men: 4<br>
Women: 10<br>
Men: 6<br>
-----------------<br>
People living in poverty <-> People living in affluence: 2<br>
People living in poverty: 10<br>
People living in affluence: 8<br>
-----------------<br>
          
</details>
