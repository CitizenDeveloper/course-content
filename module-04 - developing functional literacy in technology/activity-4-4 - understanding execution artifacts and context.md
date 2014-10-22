# context
There are several different containers for running software code.

Here are a few possibilities:
- If the software is an operating system like Microsoft Windows or Max OSX then the container is basically the hardware.
- If the software is a server-side technology then the container is usually one part of many smaller pieces that fit together to provide the service like hosting a website or responding to RESTful requests.
- If the software is a client-side technology then the container is usually a browser like Google Chrome, Mozilla Firefox and Apple Safari.
- If the software is an embedded system then the container is typically a microcontroller or microprocessor, essentially a hardware container as above.

It is important to recognize that when we talk about "code" and "programming" we're really talking about an entire ecosystem.  Being specific about where your code is running (ie. client vs. server) is the first step to learning about software development.

In this activity we'll take a closer look at execution contexts and invite you to consider where the code you use is running.

# stepwise

> [whiteboard: consider the artifacts of most programming languages (10 mins)]

- data
- decision
- loops
- flow

---

> [watch: life of an HTTP request (10 mins)]

- [Coursera Startup Engineering](https://class.coursera.org/startup-001/lecture/195)

---

> [discuss: technologies and their containers (10 mins)]

- server-side (Ruby, Python, Java, .NET)
- client-side (Javascript, HTML, CSS)

---

> [pair: build a program on the whiteboard (10 mins)]

Given an application design, identify where the parts of the system, represented by post-it notes, are likely to execute (ie. their execution context).

- Google Search
    - where do the results come from, client or server?
    - where do the instant search hints come from, client or server?
- Google Gmail
    - where do the emails come from?
    - is this a client-side or server-side application?
- Word / Pages
    - where are the documents stored?
    - where do the templates come from?

# discussion

- What applications do you use that are likely to be running a significant amount of client-side code?
- What applications do you use that are likely to be running server-side code?
- Are there any execution contexts you can think of that we're missing here?
