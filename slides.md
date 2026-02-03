---
theme: seriph

background: https://cover.sli.dev

title: "Math Conclave One"
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: fade-out
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
ts: true
favicon: /Maxfav.png
dowload: true
---

## Math Conclave One 

## 2026

# Introduction

Welcome to Math Conclave!

<!-- Slide 1 -->

---
layout: center
---

<Youtube id="cWGZ2mOivBQ" width="850" height="450" />

---
dragPos:
  foo:
---

<v-drag pos="foo" text-3xl>
  <carbon:arrow-up />
  Use the v-drag component to have a draggable container!
</v-drag>
    
---
layout: two-cols-header
---

Our Goals for this meeting:

::left::

<v-clicks> 
  
- Examine CAASPP Math Blueprints
- Determine Assessment Target prioroities
- Correlate Assessment Target Priorities to Standards
- Identify *power* standards
- Pick a power standard to focus on next time

</v-clicks>

::right::

```mermaid {theme: redux, look: neo}
  flowchart TB 
          n2.3["ID Lesson for Next Meeting"]
          n2.2["ID Major PowerStandards"]
          n2.1["Examine Blueprints"]

      n2.1 --> n2.2
      n2.2 --> n2.3
```

---
class: scrollable
---

<div class="fancy-table-container">
  <table class="fancy-table">
    <thead>
      <tr>
        <th>Claim</th>
        <th>Content Category</th>
        <th>Assessment Targets</th>
        <th>DOK</th>
        <th>CAT</th>
        <th>PT</th>
        <th>Total Items</th>
      </tr>
     </thead>
    <tbody>
      <tr>
        <td rowspan="16">Concepts and Procedures<br> **at least 4 CAT items at DOK 2 or higher</td>
        <td rowspan="11">Priority Cluster</td>
        <td>D. Interpret the stucture of expressions</td>
        <td>1,2</td>
        <td rowspan="2">1-2</td>
        <td rowspan="16">0</td>
        <td rowspan="16">11</td>
      </tr>
      <tr>
        <td>E. Write expresssions in equivalent forms to solve problems.</td>
        <td>1,2</td>
      </tr>
      <tr>
        <td>F. Perform arithemetic operations on polynomials.</td>
        <td>2</td>
        <td>0-1</td>
      </tr>
      <tr>
        <td>G. Create equations that describe numbers or relationships</td>
        <td>1,2</td>
        <td rowspan="3">2</td>
      </tr>
      <tr>
        <td>H. Understand solving equations as a process of reasoning and explain the reasoning</td>
        <td>1,2</td>
      </tr>
      <tr>
        <td>I. Solve equations and inequalities in one variable.</td>
        <td>1,2></td>
      </tr>
      <tr>
        <td>J. Represent and solve equations and einequalities graphically</td>
        <td>1,2></td>
        <td>0-2</td>
      </tr>
      <tr>
        <td>K. Understand the concept of a function and use function notation</td>
        <td>1,2></td>
        <td>0-2</td>
      </tr>
      <tr>
        <td>L. Interpret functions that arise in applications in terms of a context</td>
        <td>1,2</td>
        <td rowspan="3">2</td>
      </tr>
      <tr>
        <td>M. Analyze functions using different representations</td>
        <td>1,2,3</td>
      </tr>
      <tr>
        <td>N. Build a function that models a relationship between two quantities.</td>
        <td>2</td>
      </tr>
      <tr>
        <td rowspan="5">Supporting Cluster</td>
        <td>O. Define trigonometric ratios and solve problems involving right triangles</td>
        <td>1,2</td>
        <td>0-2</td>
      </tr>
      <tr>
        <td>P. Summarize represent, and interpret date on a single count or measurement variable.</td>
        <td>2</td>
        <td>0-2</td>
      </tr>
      <tr>
        <td>A. Extend the properties of exponents to rational exponents.</td>
        <td>1,2</td>
        <td rowspan="2">0-1</td>
      </tr> 
      <tr>
        <td>B. Use properties of rational and irrational numbers</td>
        <td>1,2</td>
      </tr>
      <tr>
        <td>C. Reason quantitatively and use units to solve problems.</td>
        <td>1,2</td>
        <td>0-1</td>
      </tr>
      <tr>
        <td rowspan="6">2. Problem Solving <br> 4. Modeling and Data Analysis<br>**at least 1 CAT item at DOK3 or higher (combined 2&4)</td>
        <td rowspan="2">Problem Solving (drawn across content domains)</td>
        <td>A. Apply mathematics to solve well-posed problems arising in everyday life, society, and the workplace.</td>
        <td>2, 3</td>
        <td>0-1</td>
        <td rowspan="2">1–2</td>
        <td rowspan="6">5–7</td>
      </tr>
      <tr>
        <td>B. Select and use appropriate tools strategically.<br>C. Interpret results in the context of a situation.<br>D. Identify important quantities in a practical situation and map their relationships (e.g., using diagrams, two-way tables, graphs, flow charts, or formulas).</td>
        <td>1, 2, 3</td>
        <td>0-1</td>
      </tr>
      <tr>
        <td rowspan="4">Modeling and Data Analysis (drawn across content domains)</td>
        <td>A. Apply mathematics to solve problems arising in everyday life, society, and the workplace.<br>D. Interpret results in the context of a situation.</td>
        <td>2, 3</td>
        <td>0-1</td>
        <td rowspan="4">1–3</td>
      </tr>
      <tr>
        <td>B. Construct, autonomously, chains of reasoning to justify mathematical models used, interpretations made, and solutions proposed for a complex problem.<br>E. Analyze the adequacy of and make improvements to an existing model or develop a mathematical model of a real phenomenon.</td>
        <td>2, 3, 4</td>
        <td>0-1</td>
      </tr>
      <tr>
        <td>C. State logical assumptions being used.<br>F. Identify important quantities in a practical situation and map their relationships (e.g., using diagrams, two-way tables, graphs, flow charts, or formulas).</td>
        <td>1, 2, 3 </td>
        <td>0-1</td>
      </tr>
      <tr>
        <td>G. Identify, analyze, and synthesize relevant external resources to pose or solve problems.</td>
        <td>3,4</td>
        <td>0</td>
      </tr>
      <tr>
        <td rowspan="3">3. Communicating Reasoning<br>**at least 1 CAT item at DOK 3 or higher)</td>
        <td rowspan="3">Communicating Reasoning (drawn across content domains)</td>
        <td>A. Test propositions or conjectures with specific examples.<br>D. Use the technique of breaking an argument into cases.</td>
        <td>2, 3</td>
        <td>1-2</td>
        <td rowspan="3">0-2</td>
        <td rowspan="3">4-6</td>
      </tr>
      <tr>
        <td>B. Construct, autonomously, chains of reasoning that will justify or refute propositions or conjectures.<br>E. Distinguish correct logic or reasoning from that which is flawed, and—if there is a flaw in the argument—explain what it is.</td>
        <td>2, 3, 4</td>
        <td>1-2</td>
      </tr>
      <tr>
        <td>C. State logical assumptions being used.<br>F. Base arguments on concrete referents such as objects, drawings, diagrams, and actions.<br>G. At later grades, determine conditions under which an argument does and does not apply. (For example, area increases with perimeter for squares, but not for all plane figures.)</td>
        <td>2, 3</td>
        <td>1</td>
      </tr>
    </tbody>
  </table>
  </div>

---
layout: image-right
image: /ma1.jpg
---

## Math Reasoning?

Which Assessment Targets are MOST used? What DOK level do they fall on? Should we graph this?

---
class: scrollable fancy-table
---
# Concepts and Procedures

|Target|0-1|0-2|1|1-2|1-3|2|DOK|
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|1A. Extend the properties of exponents to rational exponents.|1||||||2|
|1B. Use properties of rational and irrational numbers.|1||||||2|
|1C. Reason quantitatively and use units to solve problems|1||||||2|
|1D. Interpret the structure of expressions.||||1|||2|
|1E. Write expressions in equivalent forms to solve problems.||||1|||2|
|1F. Perform arithmetic operations on polynomials.|1||||||2|
|1G. Create equations that describe numbers or relationships.||||||1|2|
|1H. Understand solving equations as a process of reasoning and explain the reasoning.||||||1|2|
|1I. Solve equations and inequalities in one variable.||||||1|2|
|1J. Represent and solve equations and inequalities graphically.||1|||||2|
|1K. Understand the concept of a function and use function notation.||1|||||2|
|1L. Interpret functions that arise in applications in terms of a context.||||||1|2|
|1M. Analyze functions using different representations.||||||1|3|
|1N. Build a function that models a relationship between two quantities.||||||1|2|
|1O. Define trigonometric ratios and solve problems involving right triangles.||1|||||2|
|1P. Summarize, represent, and interpret data on a single count or measurement variable.||1|||||2|

---
class: fancy-table
---

# 2. Problem Solving

|Target|0-1|0-2|1|1-2|1-3|2|DOK|
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|2A. Apply mathematics to solve well-posed problems arising in everyday life, society, and the||1||||||1||||||3|
|2B. Select and use appropriate tools strategically.||1||||||1||||||3|
|2C. Interpret results in the context of a situation.||1||||||1||||||3|
|2D. Identify important quantities in a practical situation and map their relationships (e.g., using diagrams, two-way tables, graphs, flow charts, or formulas).||1||||||1||||||3|

---
class: scrollable fancy-table
---

# 4. Modeling and Data Analysis

|Target|0-1|0-2|1|1-2|1-3|2|DOK|
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|4A. Apply mathematics to solve problems arising in everyday life, society, and the workplace.||1||||||||1||||3|
|4D. Interpret results in the context of a situation.||1||||||||1||||3|
|4B. Construct, autonomously, chains of reasoning to justify mathematical models used, interpretations||1||||||||1||||4|
|made, and solutions proposed for a complex problem. made, and solutions proposed for a complex problem.||1||||||||1||||4|
|4E. Analyze the adequacy of and make improvements to an existing model or develop a mathematical model of a real phenomenon. model of a real phenomenon.||1||||||||1||||4|
|4C. State logical assumptions being used.||1||||||||1||||3|
|4F. Identify important quantities in a practical situation and map their relationships (e.g., using diagrams, two-way tables, graphs, flow charts, or formulas).||1||||||||1||||3|
|4G. Identify, analyze, and synthesize relevant external resources to pose or solve problems. 3, 4 0||||||||||1||||4|

---
class: scrollable fancy-table
---

# 3. Communicating Reasoning

|Target|0-1|0-2|1|1-2|1-3|2|DOK|
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|3A. Test propositions or conjectures with specific examples.||||1||||1||||||3|
|3D. Use the technique of breaking an argument into cases.||||1||||1||||||3|
|3B. Construct, autonomously, chains of reasoning that will justify or refute propositions or conjectures.||||1||||1||||||4|
|3E. Distinguish correct logic or reasoning from that which is flawed, and—if there is a flaw in the argument—explain what it is.||||1||||1||||||4|
|3C. State logical assumptions being used.||||1||1||||||||3|
|3F. Base arguments on concrete referents such as objects, drawings, diagrams, and actions.||||1||1||||||||3|
|3G. At later grades, determine conditions under which an argument does and does not apply. (For example, area increases with perimeter for squares, but not for all plane figures.)||||1||1||||||||3|

---
layout: two-cols
---

# Next Meeting and Subsequent Meetings

::right::

```mermaid {theme: redux, look: neo}
  flowchart TB
    s3["All Subsequent Meetings"]
    n3["Present Lesson"]
    nz["nz"]
    n4["Critique"]
    n5["compare"]
    ny["ny"]
    n6["Evaluate Conection to Blueprint"]
    n7["ID next Major Power Standard Focus"]

    n3 --- nz
    nz --> n4
    nz --> n5
    n4 --- ny
    n5 --- ny
    ny --> n6
    n6 --> n7
    n7 --> n3

 
    nz@{ shape: f-circ }
    ny@{ shape: f-circ }
    style s3 stroke:none
```

---
layout: end
---




































































































































































