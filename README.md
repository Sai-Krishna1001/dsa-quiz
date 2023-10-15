# 🚀 DSA Marvels: Explore the Wonders of Algorithms! 🚀

### **Welcome to the DSA Adventure! 🎉** Prepare to embark on an **exhilarating journey** through the captivating world of **Data Structures and Algorithms. 🌟**

## 🌲🔮 Prepare for the DSA Expedition:🎉🌟

### Gear up for an **odyssey** filled with **mind-bending challenges**, **perplexing puzzles**, and a dash of **whimsy** as we **unravel the hidden gems of data structures and algorithms. 🤯** Along this magical path, you'll cross paths with **mischievous data fairies 🧚**, tackle **algorithmic enigmas 🧩**, and experience the **thrill of conquering the coding cosmos. 🚀**

### Are you ready to **boldly go where no coder has gone before?** Join the DSA Adventure and let the quest for **knowledge and laughter** begin! 🎯🌠😄

## 😄 Question 1: The Enigmatic Time Complexity

**Prepare to be amazed by the magical world of time complexity! Can you decipher the time complexity of this perplexing algorithm?** 🎩⏳

```java
int sum = 0;
for (int i = 1; i <= n; i *= 2) {
    for (int j = 1; j <= n; j++) {
        sum++;
    }
}
```
**What is the time complexity of this code snippet?** ⌛🧩

Options:

A. 🧙‍♂️ O(n^2)

B. 🔮 O(n log n)

C. 🌟 O(n)

D. 🕰️ O(1)

<details>
<summary>Answer</summary>
  Option B. 🔮 O(n log n)
</details>

<details>
<summary>Explanation</summary>

In the provided code, there are two nested loops. The outer loop runs from 1 to n by doubling i in each iteration, and the inner loop runs from 1 to n.

The outer loop runs approximately log₂(n) times because i doubles in each iteration.
The inner loop runs n times.
As a result, the total number of operations is approximately n * log₂(n), which simplifies to O(n log n).

So, the correct time complexity is O(n log n), making Option B, 🔮 O(n log n, the correct answer.

You've got it! Your understanding of time complexity is truly magical. 🔮🔍🎩
</details>

## 😄 Question 2: The Time Complexity Riddle
**Prepare to be amazed by the magical world of time complexity! Can you decipher the time complexity of this perplexing algorithm?** 🎩⏳

```java
int n = 64;
int count = 0;
for (int i = 0; i < n; i++) {
    for (int j = 0; j < n; j++) {
        count++;
    }
}
```
**What is the time complexity of this code snippet?** ⌛🧩
Options:

A. 🕰️ O(1)

B. 🎩 O(n)

C. 📦 O(n^2)

D. 🌟 O(log n)

<details>
  <summary>Answer</summary>
  
  Option C. 📦 O(n^2)

</details>

<details>
  <summary>Explanation</summary>
  
  In this code, there are two nested loops, each running n times. This results in a total of n * n = n^2 iterations. Therefore, the time complexity of this code is O(n^2).

</details>

## 😄 Question 3: The Elusive Linked List

**Dive into the enigmatic world of linked lists and face the challenge of the elusive linked list! Can you unlock its secrets?** 🧐🔗

**Consider a singly linked list with the following structure:**
`
| 5 | -> | 8 | -> | 12 | -> | 18 |
`

**Now, here's the task:**

**You are given a reference to the head of this linked list, and you need to insert a new node with the value 10 between the nodes with values 8 and 12. After the insertion, the list should look like this:**

`
| 5 | -> | 8 | -> | 10 | -> | 12 | -> | 18 |
`


**What is the key step to perform this insertion?**

Options:

A. 🕰️ Create a new node with the value 10, change its next pointer to point to the node with value 12, and update the next pointer of the node with value 8 to point to the new node.

B. 🧩 Create a new node with the value 10 and change its next pointer to point to the node with value 8.

C. 🌟 Create a new node with the value 10, change its next pointer to point to the node with value 12, and update the next pointer of the node with value 8 to point to the new node.

D. 😅 Create a new node with the value 10, change its next pointer to point to the node with value 12, and update the next pointer of the node with value 8 to point to the new node, then update the next pointer of the node with value 12 to point to the new node.

<details>
  <summary>Answer</summary>

  Option C. 🪄 Create a new node with the value 10, change its next pointer to point to the node with value 12, and update the next pointer of the node with value 8 to point to the new node.

</details>

<details>
  <summary>Explanation</summary>

  To insert a new node with the value 10 between the nodes with values 8 and 12, you should:

  1. Create a new node with the value 10.
  2. Change the next pointer of this new node to point to the node with value 12.
  3. Update the next pointer of the node with value 8 to point to the new node.

  This way, the new node with value 10 becomes part of the linked list in the correct position, as shown in the desired list structure. 🪄🔗🎩

  Option C is the correct step for performing this insertion. Well done!

</details>



