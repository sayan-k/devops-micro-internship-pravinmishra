# Week 00 - Internet and Networking

Part of the DevOps Micro Internship (DMI) Cohort 3 with Agentic AI

---

# 🧑‍💻 Task 1: Using ChatGPT as Your Learning Assistant

## Scenario

You're new to DevOps and will frequently encounter technical questions. ChatGPT can be your learning companion.

## Your Task

Write a clear ChatGPT prompt to help you understand:

> "Hello, I just started my DevOps Micro Internship from DMI Campus . I am a completely beginner in this field. So, i need your help to understand basic concepts. In the answers i need completely beginner level words and simple explanations of the topic that provide a clear thought of the topic. Also, add a very simple real life example corresponding of the topic- My first question is: What is a protocol in networking? Explain with a simple real-life example. "

Take a screenshot of your interaction showing:

* Your detailed prompt (with clear expectations)
* ChatGPT's simplified response with an example

## Screenshot

Save your screenshot in the `screenshots` folder and update the file name below.

![ Task 1 Screenshot ](screenshots\screenshot1.png)


Replace `task-1-chatgpt.png` with your actual screenshot file name.

---

## What I Learned (2–3 lines)

Like human beings computers communicates with another computers with a language and some set of rules, this set of rules is called a Protocol. Protocols have communication establishing rules and communication ending rules like humans' "Hello"(for starting a conversation) and "Good bye" (for ending the conversation). 

---

# 🌐 Task 2: Internet and Networking

## Scenario

Your friend is launching an online bookstore named **EpicReads**.

He asked you to explain how users globally can access his website hosted in Finland.

## Your Task

Write a short explanation (**100–150 words**) that includes:

* Packet Switching
* IP Address
* TCP/IP
* HTTP/HTTPS

💡 **Tip:** You may use ChatGPT (as demonstrated in Task 1) to refine your explanation.

## Answer

A client (somewhere in the world) browse in google browser about Epicreads website write-"epicreads.com". The client request is processed in DNS server for creating a link between the client and the epicreads portal. When the DNS done with processing it establishes the connection. Then the client send a message to the epicreads server to access a file. Here comes the packet switching concept- the message is divided into two or more small packets. Then these packets are transfered by the internet throuhg routers. These data packets can take different routing paths to reach the server. Here the network use TCP/IP protocols to manage the safe transfer of the message. TCP is used to rearrange the data packets that are excepted by the server with it's in order transmission characteristic. IP protocol helps to smoothly move these packets thorugh network. Now, in Finland the message is process this request using HTTPs protocol for security checking. After the response it uses HTTPs again to send the response for this request. Again packet switching is used to send the data from server to the client. TCP/IP protocols are used to secure tansfer process. When the user receive the data and after processing the data it sends an acknowledge message to the server (if it use the TCP protocol). If the client closes the browser the link with the server is closed in the internet. 

---

# 🏗️ Task 3: Application Architecture & Stack

## Scenario

EpicReads bookstore has two application versions:

### Two-Tier Application

* Frontend
* Database

### Three-Tier Application

* Frontend
* Backend
* Database

## Your Task

* Draw simple diagrams (hand-drawn or tool-based such as draw.io)
* Label each layer clearly
* List at least two common technologies or tools used for each layer
* Submit a screenshot or photo clearly showing your own drawing

## Diagram Screenshot / Photo

Save your diagram image in the `screenshots` folder and update the file name below.

![Application Architecture Diagram](screenshots\screenshot2.png)


Replace `task-3-diagram.png` with your actual diagram file name.

---

## Technologies Used

### Frontend

HTML
CSS

### Backend

Node js
Express js

### Database

MongoDB
MySQL

---

# 🌍 Task 4: Domain Name & DNS (Basic Concepts)

## Scenario

Your friend's bookstore **EpicReads** is currently accessible through:

```text
52.172.142.222:3000
```

He purchased the domain:

```text
epicreads.com
```

## Your Task

In **50–100 words**, explain in your own words:

1. What is DNS (Domain Name System)?
2. Which DNS record type should be used to connect the domain to the given IP, and why?

## Answer

Domain Name System (DNS) converts the domains name like "epicreads.com" which is easy to remember to the humans into numerical IP address understanble by the computers. So a client can only remeber the name of the website or the domain "epicreads.com" insted of the numerical IP address which is hard to remember. This DNS makes the mode of web browsing easy. DNS is basically the phonebook of the internet which is managed by International organization of the internet. 

In this process an A Record should be used as it is specifically designed to connect domain name to an IP Address. But the :3000 part is the port number managed by the computers application manager it indicates the internet channel through which the running application is communicating with the epicread.com server. 

---

# 💻 Task 5: Visual Studio Code Setup (Hands-on)

## Your Task

Install Visual Studio Code (if not already installed).

Take a screenshot of your VS Code environment showing:

* Terminal open inside VS Code
* Running a basic command:

### Windows

```powershell
dir
```

### Linux / macOS

```bash
pwd
ls
```

* Your selected VS Code theme clearly visible

⚠️ **Important:** The screenshot must show your username or another identifiable detail to confirm it is your environment.

## Screenshot

Save your screenshot in the `screenshots` folder and update the file name below.

![VS Code Setup Screenshot](screenshots\screenshot3.png)


Replace `task-5-vscode.png` with your actual screenshot file name.

---

# 🔗 Task 6: Publish Your Assignment as a LinkedIn Post

## Objective

Publishing on LinkedIn helps you:

* Build your professional online presence
* Reinforce your learning
* Document your DevOps journey publicly

## Your Task

Summarize your answers from Tasks 1–5 into a LinkedIn post.

Clearly structure your post into the following sections:

* ChatGPT
* Internet & Networking
* App Architecture
* DNS
* VS Code Setup

Use the credit note that matches your track:

Add the following credit note at the end of your post **(If you are DMI Cohort 3 student)**:

> **P.S. This post is part of the DevOps Micro Internship (DMI) with Agentic AI — Cohort 3 — by Pravin Mishra. My graded progress is public: https://dmi.pravinmishra.com/s/YOUR-GITHUB-USERNAME.html · Start your DevOps journey: https://dmi.pravinmishra.com/?utm_source=student&utm_medium=ps-linkedin&utm_campaign=cohort3**

**Tag [Pravin Mishra](https://www.linkedin.com/in/pravin-mishra-aws-trainer/) in your LinkedIn post, then tag Lead Co-Mentor — [Anjana Muthunayake](https://www.linkedin.com/in/anjana-muthunayake/).**

Add the following credit note at the end of your post **(If you are DMI Self-paced track student)**:

> **P.S. This post is part of the DevOps Micro Internship (DMI) — Self-Paced Engineer Track — by Pravin Mishra. My graded progress is public: https://dmi.pravinmishra.com/s/YOUR-GITHUB-USERNAME.html · Start your DevOps journey: https://dmi.pravinmishra.com/?utm_source=student&utm_medium=ps-linkedin&utm_campaign=self-paced**

Add the following credit note at the end of your post **(If you are DMI Campus student)**:

> **P.S. This post is part of the DevOps Micro Internship (DMI) — Campus — by Pravin Mishra. My graded progress is public: https://dmi.pravinmishra.com/s/YOUR-GITHUB-USERNAME.html · Start your DevOps journey: https://dmi.pravinmishra.com/?utm_source=student&utm_medium=ps-linkedin&utm_campaign=campus**

**Tag [Pravin Mishra](https://www.linkedin.com/in/pravin-mishra-aws-trainer/) in your LinkedIn post, then tag Lead Co-Mentor — [Anjana Muthunayake](https://www.linkedin.com/in/anjana-muthunayake/).**

Hashtags:

#DMIByPravinMishra #AgenticAI #DevOps

Replace `YOUR-GITHUB-USERNAME` with your GitHub username — that link is your public DMI progress page (your graded badge page).
---

## LinkedIn Post URL

Paste your LinkedIn post URL here:

```text
https://www.linkedin.com/posts/sayan-koley-819aa3329_dmi-devops-micro-internship-with-agentic-activity-7504893678612602880-QI-7?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFLrytUBKAINNScXy4_MPRWNHzV9CRwB3UM
```

---

## LinkedIn Post Backup Copy

Paste the full text of your LinkedIn post here:

🚀 Week 00 | My DevOps Learning Journey
I’ve completed my DevOps Micro Internship (DMI) journey, and Week 00 assignment designed by Pravin Mishra sir. It helped me build a strong foundation in Internet & Networking.

Here’s what I learned:

💬 ChatGPT
Learned how to use AI as a learning assistant to understand technical concepts in a beginner-friendly way.

🌐 Internet & Networking
Explored networking protocols, packet switching, IP addresses, TCP/IP, and HTTP/HTTPS, and understood how a website can be accessed globally.

🏗️ App Architecture
Learned the basics of 2-tier and 3-tier architecture and the role of Frontend, Backend, and Database.

🔗 DNS
Understood how DNS converts a domain name into an IP address and learned why an A record is used for an IPv4 address.

💻 VS Code Setup
Set up my development environment and practiced using the integrated terminal with basic commands.

This is just the beginning of my DevOps journey, and I’m excited to keep learning, building, and improving every week. 🚀
hashtag#DevOps hashtag#DMI hashtag#DevOpsMicroInternship hashtag#Networking hashtag#DNS hashtag#CloudComputing hashtag#LearningJourney hashtag#Technology

P.S. This post is part of the DevOps Micro Internship (DMI) — Self-Paced Engineer Track — by Pravin Mishra. My graded progress is public: https://lnkd.in/gTkisgMM · Start your DevOps journey:https://lnkd.in/g9YuUw2T 

hashtag#DMIByPravinMishra
---

# Reflection – Week 0

### What did you find easy?

The DNS, Networking Protocols (TCP/IP,HTTPs/HTTP) and packet switching concept

---

### What was difficult?

Application Architectures

---

### What will you improve next week?

Time management for assignments.

---

## 📌 About DMI & CloudAdvisory

DevOps Micro Internship (DMI) is a project-based DevOps program run by Pravin Mishra (The CloudAdvisory) focused on real-world execution, systems thinking, and career readiness.

It helps learners build strong DevOps foundations with hands-on experience.


## 📌 Resources

- 🌐 **DMI Official Website:** https://dmi.pravinmishra.com?utm_source=github&utm_medium=readme  
- 🎓 **University:** https://university.pravinmishra.com?utm_source=github&utm_medium=readme  
- 💬 **Discord Community:** https://discord.pravinmishra.com?utm_source=github&utm_medium=readme  
- 📝 **Blog:** https://dmi.pravinmishra.com/blog?utm_source=github&utm_medium=readme  
- ▶️ **YouTube Playlist (DMI Cohort 3):** https://www.youtube.com/playlist?list=PLFeSNDtI4Cho  
- 🔗 **Pravin Mishra (LinkedIn):** https://www.linkedin.com/in/pravin-mishra-aws-trainer/  
- 🏢 **CloudAdvisory (LinkedIn):** https://www.linkedin.com/company/thecloudadvisory/

---

*This submission is part of DevOps Micro Internship (DMI) Cohort 3 — Agentic AI Track*