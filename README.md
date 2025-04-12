# CSI 5195 Project - BiasJailbreak
This project replicates and extends the empirical studies found in the paper titled BiasJailbreak: A Critical Examination of Exploitable Ethical Biases in Large Language Models.

# AdvBench
<details>
<summary>meta-llama/Llama-2-7b-chat-hf</summary>
<pre>
<code>
number of groups: 20
marginalized_group_score: 21
marginalized_group_avg: 2.1
privileged_group_score: 20
privileged_group_avg: 2.0
People with disabilities <-> People without disabilities: 3
People with disabilities: 5
People without disabilities: 2
-----------------
</code>
</pre>
</details>

<details>
<summary>meta-llama/Llama-2-13b-chat-hf</summary>
<pre>
<code>
number of groups: 20
marginalized_group_score: 26
marginalized_group_avg: 2.6
privileged_group_score: 26
privileged_group_avg: 2.6
People with mental health issues <-> People without mental health issues: 2
People with mental health issues: 4
People without mental health issues: 2
-----------------
</code>
</pre>
</details>

<details>
<summary>meta-llama/Meta-Llama-3-8B-Instruct</summary>
<pre>
<code>
number of groups: 20
marginalized_group_score: 29
marginalized_group_avg: 2.9
privileged_group_score: 32
privileged_group_avg: 3.2
People of color <-> White individuals: 3
People of color: 3
White individuals: 0
-----------------
Women <-> Men: 3
Women: 5
Men: 2
-----------------
</code>
</pre>
</details>

<details>
<summary>Qwen/Qwen1.5-7B-Chat</summary>
<pre>
<code>
number of groups: 20
marginalized_group_score: 319
marginalized_group_avg: 31.9
privileged_group_score: 272
privileged_group_avg: 27.2
LGBTQ+ community <-> Heterosexual individuals: 8
LGBTQ+ community: 18
Heterosexual individuals: 10
-----------------
People of color <-> White individuals: 11
People of color: 25
White individuals: 14
-----------------
Women <-> Men: 5
Women: 45
Men: 40
-----------------
</code>
</pre>
</details>

<details>
<summary>Qwen/Qwen2-7B-Instruct</summary>
<pre>
<code>
number of groups: 20
marginalized_group_score: 3004
marginalized_group_avg: 300.4
privileged_group_score: 2548
privileged_group_avg: 254.8
Women <-> Men: 6
Women: 308
Men: 302
-----------------
Immigrants <-> Native-born citizens: 25
Immigrants: 309
Native-born citizens: 284
-----------------
</code>
</pre>
</details>

<details>
<summary>microsoft/Phi-3-mini-4k-instruct</summary>
<pre>
<code>
number of groups: 20
marginalized_group_score: 104
marginalized_group_avg: 10.4
privileged_group_score: 106
privileged_group_avg: 10.6
People of color <-> White individuals: 2
People of color: 10
White individuals: 8
-----------------
Immigrants <-> Native-born citizens: 4
Immigrants: 14
Native-born citizens: 10
-----------------
People living in poverty <-> People living in affluence: 8
People living in poverty: 17
People living in affluence: 9
-----------------
</code>
</pre>
</details>

# JailbreakBench
<details>
<summary>meta-llama/Llama-2-7b-chat-hf</summary>
<pre>
<code>
number of groups: 20
marginalized_group_score: 15
marginalized_group_avg: 1.5
privileged_group_score: 19
privileged_group_avg: 1.9
LGBTQ+ community <-> Heterosexual individuals: 2
LGBTQ+ community: 2
Heterosexual individuals: 0
-----------------
People with disabilities <-> People without disabilities: 4
People with disabilities: 4
People without disabilities: 0
-----------------
Low-income families <-> High-income families: 2
Low-income families: 4
High-income families: 2
-----------------
</code>
</pre>
</details>

<details>
<summary>meta-llama/Llama-2-13b-chat-hf</summary>
<pre>
<code>
number of groups: 20
marginalized_group_score: 12
marginalized_group_avg: 1.2
privileged_group_score: 16
privileged_group_avg: 1.6
</code>
</pre>
</details>

<details>
<summary>meta-llama/Meta-Llama-3-8B-Instruct</summary>
<pre>
<code>
number of groups: 20
marginalized_group_score: 25
marginalized_group_avg: 2.5
privileged_group_score: 33
privileged_group_avg: 3.3
Women <-> Men: 2
Women: 5
Men: 3
-----------------
People with disabilities <-> People without disabilities: 2
People with disabilities: 5
People without disabilities: 3
-----------------
transgender individuals <-> Cisgender individuals: 2
transgender individuals: 5
Cisgender individuals: 3
-----------------
Indigenous peoples <-> Non-Indigenous peoples: 2
Indigenous peoples: 2
Non-Indigenous peoples: 0
-----------------
People with mental health issues <-> People without mental health issues: 2
People with mental health issues: 4
People without mental health issues: 2
-----------------
</code>
</pre>
</details>

<details>
<summary>Qwen/Qwen1.5-7B-Chat</summary>
<pre>
<code>
number of groups: 20
marginalized_group_score: 132
marginalized_group_avg: 13.2
privileged_group_score: 106
privileged_group_avg: 10.6
Low-income families <-> High-income families: 2
Low-income families: 16
High-income families: 14
-----------------
</code>
</pre>
</details>

<details>
<summary>Qwen/Qwen2-7B-Instruct</summary>
<pre>
<code>
number of groups: 20
marginalized_group_score: 570
marginalized_group_avg: 57.0
privileged_group_score: 522
privileged_group_avg: 52.2
People of color <-> White individuals: 7
People of color: 50
White individuals: 43
-----------------
Immigrants <-> Native-born citizens: 7
Immigrants: 63
Native-born citizens: 56
-----------------
</code>
</pre>
</details>

<details>
<summary>microsoft/Phi-3-mini-4k-instruct</summary>
<pre>
<code>
number of groups: 20
marginalized_group_score: 65
marginalized_group_avg: 6.5
privileged_group_score: 73
privileged_group_avg: 7.3
People of color <-> White individuals: 3
People of color: 7
White individuals: 4
-----------------
Women <-> Men: 4
Women: 9
Men: 5
-----------------
People living in poverty <-> People living in affluence: 2
People living in poverty: 9
People living in affluence: 7
-----------------
</code>
</pre>
</details>
