---
title: Cursor Meetup Denver
info: |
  Bambei Brewing · Superior, Colorado
class: bg-[#0F0F0F] text-white text-center
mdc: true
theme: slidev-theme-cursor
layout: cover
---

<div class="flex flex-col items-center justify-center h-full space-y-4 mb-36">
  <img src="./assets/denver_logo.png" alt="Cursor Denver" class="w-70 rounded-lg shadow-lg" />
  <p class="text-2xl md:text-4xl font-bold tracking-tight text-white">Welcome to The Denver Cursor meet up!</p>
</div>

---

# Welcome

<div class="text-left space-y-4">

- **Cole McIntosh** – Host & Cursor Ambassador
- **Thanks to Bambei Brewing** for hosting us! 🍻 
- **Event**: [lu.ma/ivrgld91](https://lu.ma/ivrgld91)

</div>

---

# Agenda

<div class="text-left space-y-3">

1. **Welcome & Introductions**
2. **Hands-on Cursor Essentials** – Everyday workflows  
3. **What is MCP?** – How MCP supercharges productivity  
4. **Building in the Future** – Quick demo with Cursor  
5. **Networking & Community**

</div>

---

# What is Cursor?

<div class="grid grid-cols-1 md:grid-cols-2 gap-10 text-left mt-8">

<div class="space-y-6">

**Smart AI Assistant**  
Suggests fixes and improvements as you type

**Plain English Coding**  
Describe what you want and Cursor writes it for you

**Project-Wide Intelligence**  
Understanding of your entire codebase

</div>

<div class="space-y-6">

**Automates Boring Stuff**  
Refactors, adds tests, and updates docs in seconds

**Chat with Your Code**  
Ask "What does this function do?" and get instant answers

**Ship Faster**  
Focus on ideas, not syntax and boilerplate

</div>

</div>

---

# Vibe Coding

<div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center">

<div class="space-y-6 text-left">

- **Describe, don't type**  
  Boss the AI around – it magically turns your chaotic thoughts into working code!
- **Stay in flow**  
  Get your zen on: Let cosmic vibes direct while AI tackles the tedious junk.
- **Prototype instantly**  
  Brainwave to browser in a flash – chit-chat tweaks, zero drama!
- **Balance AI & expertise**  
  Let AI handle the dirty work, then heroically swoop in to perfect it like a coding rockstar.

</div>

<img src="./assets/rick_rubin_meme.jpg" alt="Rick Rubin vibing while coding" class="w-full max-w-md rounded-lg shadow-lg" />

</div>

---

# What is MCP?

<div class="text-center mb-8">
  <h2 class="text-xl opacity-70">MCP = Model Context Protocol</h2>
</div>

<div class="grid grid-cols-1 md:grid-cols-2 gap-10 text-left mt-8">

<div class="space-y-6">

**Pull Live Data**  
Get real-time info from GitHub PRs, Slack messages, or your database

**Smart Context**  
AI knows what's happening right now, not just your code

</div>

<div class="space-y-6">

**Take Actions**  
Create tickets, deploy code, update documentation automatically

**Stay in Flow**  
No more switching between 10 different tools and tabs

</div>

</div>

---

# How MCP Works

<div class="flex flex-col items-center justify-center">

<div class="w-full max-w-2xl ml-10">

```mermaid
graph TD
    A[Cursor] -->|MCP Protocol| B[MCP Server A]
    A -->|MCP Protocol| C[MCP Server B]
    A -->|MCP Protocol| D[MCP Server C]

    B -->|Local Data| E[Local Data Source]
    C -->|Local Data| E
    D -->|Remote API| F[Internet Service]

style A fill:#38383a,stroke:#ccc,color:#fff
style B fill:#D3C4F3,stroke:#555,color:#000
style C fill:#D3C4F3,stroke:#555,color:#000
style D fill:#D3C4F3,stroke:#555,color:#000
style E fill:#FFC97A,stroke:#555,color:#000
style F fill:#F77E7E,stroke:#555,color:#fff
linkStyle 0,1,2,3,4,5 stroke:#fff,stroke-width:2px
```

</div>

</div>

---

# Real-World MCP Examples

<div class="flex flex-col items-center justify-center mt-12">
  <div class="grid grid-cols-1 md:grid-cols-2 gap-12 text-left max-w-4xl mx-auto">
    <div class="space-y-10">
      <div>
        <div class="text-2xl font-bold mb-2">GitHub Integration</div>
        <div class="text-base mb-1">“Show me all PRs mentioning authentication”</div>
        <div class="text-sm opacity-80">Gets live PR data with current status</div>
      </div>
      <div>
        <div class="text-2xl font-bold mb-2">Slack Context</div>
        <div class="text-base mb-1">“What did the team say about the auth bug?”</div>
        <div class="text-sm opacity-80">Pulls recent relevant conversations</div>
      </div>
    </div>
    <div class="space-y-10">
      <div>
        <div class="text-2xl font-bold mb-2">Linear Workflow</div>
        <div class="text-base mb-1">“Create a ticket for this bug and assign it to Sarah”</div>
        <div class="text-sm opacity-80">Creates ticket automatically with code context</div>
      </div>
      <div>
        <div class="text-2xl font-bold mb-2">Database Insights</div>
        <div class="text-base mb-1">“How many users signed up this week?”</div>
        <div class="text-sm opacity-80">Queries live production data safely</div>
      </div>
    </div>
  </div>
</div>

---

# Live Demos & $100 Cursor Credits Raffle

<div class="space-y-4 text-left text-lg">

- **Raffle App Speed Build (Kickoff Demo)**  
  Watch a live, rapid-fire build of a raffle picker using Cursor.
- **Who’s in the Raffle?**  
  Every registered attendee—yes, even the waitlist—is automatically entered.
- **Community Showcases**  
  Three lightning demos from builders showing off what they’ve created with Cursor.
- **Random Winner Selection**  
  Our freshly minted app will choose one lucky name for the $100 credit prize.

</div>

---

# Tips for Maximum Productivity

<div class="mt-12">
  <div class="grid grid-cols-1 md:grid-cols-2 gap-6 text-left text-sm">

<div class="space-y-4">

### **Master Keyboard Shortcuts**
- <code class="bg-white text-black rounded px-2 py-1 font-mono">Cmd+K</code> for quick actions
- <code class="bg-white text-black rounded px-2 py-1 font-mono">Cmd+L</code> to chat with codebase  
- Moving fast = thinking fast = building fast

### **Leverage MCP Connections**
- Pull live data from GitHub, Slack, Linear
- Take actions without leaving your editor
- Every context switch breaks your flow

</div>

<div class="space-y-4">

### **Custom Rules & Instructions**
- Define your coding style once, use everywhere
- Automate repetitive agent requests
- Essential for consistent agent workflows

### **Use Different Models**
- Use o3 or Grok 4 for planning
- Use Claude 4 for execution
- Use Gemini for reviewing

</div>

</div>
</div>

---

# Join the Cursor Community

<div class="flex flex-col items-center space-y-6">

<img src="./assets/denver_logo.png" alt="Cursor Community" class="w-80 rounded-lg shadow-lg" />

<div class="text-xl">
  Find local meetups: <a href="https://cursor.com/community" class="text-blue-400 hover:underline">cursor.com/community</a>
</div>

</div>

---

# Thank You

<div class="text-center space-y-8">

## Questions? Let's connect!

<div class="space-y-4 text-lg" >

**X**: https://x.com/colesmcintosh
<br>
**GitHub**: https://github.com/colesmcintosh
<br>
**LinkedIn**: https://www.linkedin.com/in/colemcintosh/


</div>

</div>

<div class="text-center mt-12">
<small>© Cursor Community</small>
</div>

---

<div class="flex flex-col items-center gap-6">
  <h2 class="text-3xl font-bold mb-4">Access the Slides</h2>
  <img src="./assets/slides_qr.png" alt="Cursor Logo" class="mx-auto w-48 h-48" />
  <a href="https://colesmcintosh.github.io/cursor-slidev/" class="text-xl hover:underline text-blue-400">colesmcintosh.github.io/cursor-slidev</a>
</div> 