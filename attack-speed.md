# Attack Speed

#### Description

Our system is based on Fist Fighting. The higher your skill, the faster your attacks will be.

To calculate your actual attack speed, you need to understand the following values.

#### Global Variables

<mark style="color:green;">normalSpeed</mark> = **2000**\ <mark style="color:red;">multiplierSpeedOnFist</mark> = **20**\ <mark style="color:orange;">**MaxAttackSpeed**</mark> = **250ms**\
**Formula**\ <mark style="color:blue;">totalAttackSpeed</mark> = (<mark style="color:green;">normalSpeed</mark> - (<mark style="color:purple;">**fistSkill**</mark> \* <mark style="color:red;">**multiplierSpeedOnFist**</mark> ))<br>

{% hint style="danger" %}
Please note that your <mark style="color:blue;">actual attack speed</mark> cannot exceed the <mark style="color:orange;">**MaxAttackSpeed**</mark>.
{% endhint %}
