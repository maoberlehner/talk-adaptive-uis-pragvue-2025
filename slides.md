---
theme: apple-basic
layout: statement
colorSchema: light
highlighter: shiki
drawings:
  persist: false
---

# <span class="accent">Adaptive</span> User<br>Interfaces with AI

<div class="leading-12">
What if your UI could build itself?
</div>

---
layout: statement
---

<img src="/images/gpt-35.png" style="width:640px">

---
layout: statement
---

<video>
  <source src="/images/story2app.mp4" type="video/mp4" />
</video>

---
layout: statement
---

<video>
  <source src="/images/v0.mov" type="video/mp4" />
</video>

---
layout: statement
---

<h1><span class="accent">How Intelligent</span><br>Are LLMs Really?</h1>

---
layout: statement
---

<img src="/images/blunder.webp" style="width:840px">

---
layout: statement
---

<h1><span class="accent">Spec-Driven</span><br>Development</h1>

---
layout: intro
---

<ol class="leading-17">
  <li>Establish project principles</li>
  <li v-click>Create project specifications</li>
  <li v-click>Functional specification clarification</li>
  <li v-click>Generate a plan</li>
</ol>

<small style="position:absolute;bottom:3rem;"><a href="https://github.com/github/spec-kit">github.com/github/spec-kit</a></small>

---
layout: intro
---

<h1>Poject specifications</h1>

<p style="font-size:0.85rem;line-height:1.75;margin-top:1.5rem">Develop Taskify, a team productivity platform. It should allow users to create projects, add team members, assign tasks, comment and move tasks between boards in Kanban style. In this initial phase for this feature, let's call it "Create Taskify," let's have multiple users but the users will be declared ahead of time, predefined. I want five users in two different categories, one product manager and four engineers. Let's create three different sample projects. Let's have the standard Kanban columns for the status of each task, such as "To Do," "In Progress," "In Review," and "Done." There will be no login for this application as this is just the very first testing thing to ensure that our basic features are set up. For each task in the UI for a task card, you should be able to change the current status of the task between the different columns in the Kanban work board. You should be able to leave an unlimited number of comments for a particular card. You should be able to, from that task card, assign one of the valid users. When you first launch Taskify, it's going to give you a list of the five users to pick from. There will be no password required. When you click on a user, you go into the main view, which displays the list of projects. When you click on a project, you open the Kanban board for that project. You're going to see the columns. You'll be able to drag and drop cards back and forth between different columns. You will see any cards that are assigned to you, the currently logged in user, in a different color from all the other ones, so you can quickly see yours. You can edit any comments that you make, but you can't edit comments that other people made. You can delete any comments that you made, but you can't delete comments anybody else made.</p>

---
layout: intro
---

<h1>Specification clarification</h1>

<p style="font-size:0.85rem;line-height:1.75;margin-top:1.5rem">For each sample project or project that you create there should be a variable number of tasks between 5 and 15 tasks for each one randomly distributed into different states of completion. Make sure that there's at least one task in each stage of completion. Read the review and acceptance checklist, and check off each item in the checklist if the feature spec meets the criteria. Leave it empty if it does not.</p>

---
layout: intro
---

<h1>Generate a plan</h1>

<p style="font-size:0.85rem;line-height:1.75;margin-top:1.5rem">We are going to generate this using .NET Aspire, using Postgres as the database. The frontend should use Blazor server with drag-and-drop task boards, real-time updates. There should be a REST API created with a projects API, tasks API, and a notifications API. I want you to go through the implementation plan and implementation details, looking for areas that could benefit from additional research as .NET Aspire is a rapidly changing library. For those areas that you identify that require further research, I want you to update the research document with additional details about the specific versions that we are going to be using in this Taskify application and spawn parallel research tasks to clarify any details using research from the web. I think we need to break this down into a series of steps. First, identify a list of tasks that you would need to do during implementation that you're not sure of or would benefit from further research. Write down a list of those tasks. And then for each one of these tasks, I want you to spin up a separate research task so that the net results is we are researching all of those very specific tasks in parallel. What I saw you doing was it looks like you were researching .NET Aspire in general and I don't think that's gonna do much for us in this case. That's way too untargeted research. The research needs to help you solve a specific targeted question.</p>

---
layout: intro
---

<h1>Validate the plan</h1>

<p style="font-size:0.85rem;line-height:1.75;margin-top:1.5rem">Now I want you to go and audit the implementation plan and the implementation detail files. Read through it with an eye on determining whether or not there is a sequence of tasks that you need to be doing that are obvious from reading this. Because I don't know if there's enough here. For example, when I look at the core implementation, it would be useful to reference the appropriate places in the implementation details where it can find the information as it walks through each step in the core implementation or in the refinement.</p>

---
layout: statement
---

<h1>LLMs: A New<br><span class="accent">Input Modality</span></h1>

---
layout: intro-image-right
image: /images/modality-structured-text.webp
---

# Structured Text
## Enter an exact command;<br>get a deterministic result.

---
layout: intro-image-right
image: /images/modality-ui.webp
---

# User Interfaces
## Click an exact button;<br>get a deterministic result.

---
layout: intro-image-right
image: /images/modality-structured-voice.webp
---

# ”Structured” Voice
## Say the right keywords;<br>get a deterministic result.

---
layout: intro-image-right
image: /images/modality-unstructured-text.webp
---

# Unstructured Text
## Say it however you want;<br>get a non-deterministic<br>but mostly correct result.

---
layout: intro
---

<ul class="leading-17">
  <li>Not (very) intelligent</li>
  <li v-click>Good at understanding specs</li>
</ul>

---
layout: statement
---

<h1><span class="accent">Spec-Driven</span><br>UI Generation!</h1>

---
layout: statement
---

<img src="/images/component-spec.webp" style="width:640px">

---
layout: statement
---

<img src="/images/streaming-spec4.webp" style="width:640px">

---
layout: statement
---

<h1>How to Make<br>AI Apps <span class="accent">Fast?</span></h1>

---
layout: intro
---

<ol class="leading-17">
  <li>Utilize caching</li>
  <li v-click>Add skeleton loading</li>
  <li v-click>Choose a fast model</li>
  <li v-click>Enable streaming</li>
</ol>

---
layout: statement
---

<img src="/images/streaming1.webp" style="width:640px">

---
layout: statement
---

<img src="/images/streaming2.webp" style="width:640px">

---
layout: statement
---

<img src="/images/streaming3.webp" style="width:640px">

---
layout: statement
---

<img src="/images/streaming4.webp" style="width:640px">

---
layout: statement
---

<img src="/images/streaming5.webp" style="width:640px">

---
layout: statement
---

<img src="/images/streaming-spec1.webp" style="width:640px">

---
layout: statement
---

<img src="/images/streaming-spec2.webp" style="width:640px">

---
layout: statement
---

<img src="/images/streaming-spec3.webp" style="width:640px">

---
layout: statement
---

<img src="/images/streaming-spec4.webp" style="width:640px">

---
layout: intro
---

<ul class="leading-17">
  <li>Not (very) intelligent</li>
  <li v-click>Good at understanding specs</li>
</ul>

---
layout: statement
---

<h1><span class="accent">Leverage LLMs'<br>Strengths</span> Be Wary<br>of their Weaknesses</h1>

---
layout: intro
---

<div class="leading-8">
  <span class="font-extrabold">Markus Oberlehner</span><br>
  <span style="font-size:0.5em;">DX Engineer @ Storyblok</span>
</div>

<img src="/images/qr.svg" style="width:280px;position:absolute;top:36px;right:36px;">

<div class="leading-17 mt-10">
  🦋 <a href="https://bsky.app/profile/markus.oberlehner.net">@markus.oberlehner.net</a><br>
  📚 <a href="https://goodvuetests.com">goodvuetests.com</a><br><br>
  <small><a href="https://github.com/maoberlehner/talk-adaptive-uis-pragvue-2025-demo">github.com/maoberlehner/talk-adaptive-uis-pragvue-2025-demo</a></small>
</div>
