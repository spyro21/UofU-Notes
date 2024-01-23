---
attachments: [Clipboard_2024-01-23-15-13-50.png]
title: Homework 1 - CS 5350 Machine Learning
created: '2024-01-23T21:25:43.684Z'
modified: '2024-01-23T22:17:57.010Z'
---

# Homework 1 - CS 5350 Machine Learning

**1A)**

We first have to find how many unique inputs there are:

<center><mark>$3*3*2*2=36$</mark></center>

$\therefore$ there are $2^{36}$ different possible solutions for this problem

*(each output is a boolean decision $\therefore$ it is $2*2*...*2$ where the amount of 2's is the number of unique inputs)*

The number of functions consisten with this data set is $2^{36-n}$ where n is the size of the data set

<center><mark>$\therefore2^{36-8}= 2^{28}$</mark></center>

---

**1B)**

*Overall*
$T = 4/8, F = 4/8$
<center><mark>$H(S)= 1$</mark></center>

*Variety*
Alphonso
$T = 2/4, F = 2/4$
$Entropy = 1$

Haden
$T = 1, F = 0$
$Entropy = 0$

Keitt
$T = 1/3, F = 2/3$
$Entropy = -1/3log_2(1/3)-2/3log_2(2/3) = 0.918$

<center><mark>$H(S, Variety) = 4/8(1) + 3/8(0.918) + 1/8(0) = 0.844$</mark></center>

*Color*
Red
$T = 2/3, F = 1/3$
$Entropy = 0.918$ //calculation made above

Yellow
$T = 1/3, F = 2/3$
$Entropy = 0.918$

Green
$T = 1/2, F = 1/2$
$Entropy = 1$

<center><mark>$H(S, Color) = 3/8(0.918) + 3/8(0.918)+2/8(1) = 0.939$</mark></center>

*Smell*
Sweet
$T = 3/4, F = 1/4$
$Entropy = -3/4log_2(3/4) - 1/4log_2(1/4) = 0.811$

None
$T = 1/4, F = 3/4$
$Entropy = -3/4log_2(3/4) - 1/4log_2(1/4) = 0.811$

<center><mark>$H(S, Smell) = 0.811$</mark></center>

*Time*
One
$T = 2/3, F = 1/3$
$Entropy = 0.918$

Two 
$T = 2/5, F = 3/5$
$Entropy = -2/5log_2(2/5) - 3/5log_2(3/5) = 0.971$

<center><mark>$H(S, Time) = 3/8(0.918) + 5/8(0.971) = 0.951$</mark></center>

---

**1C)**
<center><mark>$Gain(Variety) = 1 - 0.844 = 0.156$</mark></center>
<center><mark>$Gain(Color) = 1 - 0.939 = 0.061$</mark></center>
<center><mark>$Gain(Smell) = 1 - 0.811 = 0.189$</mark></center>
<center><mark>$Gain(Time) = 1 - 0.951 = 0.049$</mark></center>

---

**1D)**
<center><mark>Time</mark></center>

---

**1E)**
![](@attachment/Clipboard_2024-01-23-15-13-50.png)

---

**1F)**
example 1 goes to True
example 2 goes to True
example 3 goes to False

the accuracy is 1/3

---

**2A)**

