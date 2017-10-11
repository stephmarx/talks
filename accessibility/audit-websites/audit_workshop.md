footer: Let's Learn to Audit Websites | @sublimemarch

# [fit] Web Accessibility and You:
# [fit] Let's Learn to Audit Websites

### with Stephanie Slattery

---

# [fit] Welcome!

^ In this workshop, we'll be discussing accessibility on the web and learning how to audit websites. My name is Stephanie Slattery, I'll be leading this workshop.

---

# [fit] Who am I?
- Front End Web Developer
- Work for Adage Technologies in Chicago
- Graduate of Illinois Tech and Dev Bootcamp

^ FED - means that I work with client-side code: html, css, javascript, as well as thinking about UI and UX
^ Adage - web, mobile, and ecommerce consulting firm, we're an ASP.NET shop that works with a wide variety of clients across manufacturing associations, performing arts, healthcare, and hospitality. (examples: Houston Ballet, Chicago Symphony Orchestra, Seattle Opera, Boston Symphony Orchestra) Some clients in the NYC area include the Metropolitan Opera and the New York City Center
^ graduate of IIT with a psych degree and most of a physics degree, ask me about that some other time
^ not a lawyer! if you're here for legal a11y reasons, talk to your lawyer


---

# This workshop is accessible!

^ let me know if i'm speaking too quickly, too quietly, you can't read a slide, i'm not making any sense, etc
^ slides are up on my website right now

---

# [fit] github.com/stephmarx/a11y-workshop

---

# [fit] Who are you?
- Name
- Pronouns
- Something you'd like to get out of this workshop

---

# What do we know about accessibility?

^ What do you think of when you hear "accessibility"?
^ What do you already know about accessibility?
^ On the web or generally

---

# Agenda

- What is accessibility? Why do we care?
- What is an audit? Why would we do one?
- How do we do an audit?
- Let's audit some websites!

---

# [fit] What is accessibility?

## The design of products, devices, services, or environments for people who experience disabilities.

^ It's the practice of removing barriers that might prevent people with disabilities from accessing the above.

^ to understand accessibility, we need to understand disability. five general categories of disabilities we need to think about when designing for the web
^ not an exhaustive list, think of this as a starting point for understanding

---

# [fit] Categories of disabilities
- visual

^ blindness, low-vision, color-blindness


---

# [fit] Categories of disabilities
- visual
- hearing

^ deafness and hard-of-hearing

---

# [fit] Categories of disabilities
- visual
- hearing
- motor

^ Parkinson’s, cerebral palsy, muscular dystrophy: cause inability to use a mouse, slow response time, limited fine motor control

---

# [fit] Categories of disabilities
- visual
- hearing
- motor
- cognitive

^ Dyslexia, global developmental delay, autism, Down’s syndrome,  learning disabilities, distractibility, inability to remember or focus on large amounts of information

---


# [fit] Categories of disabilities
- visual
- hearing
- motor
- cognitive
- seizure

^ seizures caused by strobing, flickering, or flashing effects

---

# Accessibility helps everyone!

^ each of the major categories requires certain types of adaptations in the design of web content. most of the time, these adaptations benefit nearly everyone, not just people with disabilities.
  - helpful illustrations! clear navigation!
  - captions are needed for deaf users, and can be helpful to people who view a video without audio (maybe in an office without headphones)

---

# [fit] Why make an accessible site?

- To improve the lives of people with disabilities

^ we have an ethical duty to help all users of our websites

---

# [fit] Why make an accessible site?

- To improve the lives of people with disabilities
- To capitalize on a wider audience or consumer base


^ 1 in 5 americans have a disability. no sensible person could make an ethical or economical argument for potentially excluding 20% of their audience. you wouldn't design a website to not work on 20% of browsers used by your audience, would you?  

---

# [fit] Why make an accessible site?

- To improve the lives of people with disabilities
- To capitalize on a wider audience or consumer base
- To avoid lawsuits or bad press


---


# Major Laws

# Rehabilitation Act of 1973

^ Rehabilitation Act of 1973
^ This law prohibits discrimination on the basis of disability in programs run by federal agencies, programs that receive financial assistance from the federal government, in federal employment, and in the employment practices of federal contractors. In 1998, Congress amended this act with Section 508 to require federal agencies to provide accessible electronic resources and information technology to people with disabilities. Currently, this doesn’t require private websites that don’t receive government funding to be accessible, although the law is evolving as cases go on.


---

# Major Laws

# Americans with Disabilities Act (1990)

^ Americans with Disabilities Act
^ This US labor law prohibits discrimination on the basis of disability and created accessibility requirements for public services and accommodations. The ADA doesn’t directly mention the web, but works to ensure that people with disabilities have equal opportunities. The Department of Justice is currently developing regulations to address web accessibility, although several notable cases regarding the ADA have made it clear that the ADA’s authority pertains to websites, even business that are web-only.

^ many international laws

---

# How do we know if a website is accessible?

^ Although there are several laws that are generally considered to govern web accessibility in the US, none of them actually define the specifics of how a website can be determined to be accessible. In court cases, the Web Content Accessibility Guidelines (WCAG) are used to determine if a website is compliant with the ADA and Section 508.

---

# Web Content Accessibility Guidelines 2.0 ([WCAG](https://www.w3.org/WAI/WCAG20/quickref/))
## by the Worldwide Web Consortium (W3C)


^ The WCAG was created by the Worldwide Web Consortium (W3C), the governing body of the web, and its current iteration was published in December of 2008. These guidelines are the basis of most web accessibility laws around the world, with some countries even formally including them in their laws.

^ The WCAG contains four principles that encompass its many guidelines for web accessibility, each containing several guidelines.

---

# [fit] Four Principles of the WCAG
## 1. Perceivable

^ available to the senses either through browser or other assistive technologies (screen readers, screen enlargers, etc). The information content and user interface components of the website must be presentable to users in ways they can perceive.

---

# [fit] Four Principles of the WCAG
## 1. Perceivable
## 2. Operable

^ users can interact with all controls and interactive elements using either the mouse, keyboard, or an assistive device

---

# [fit] Four Principles of the WCAG
## 1. Perceivable
## 2. Operable
## 3. Understandable

^ content is clear and limits confusion and ambiguity

---

# [fit] Four Principles of the WCAG
## 1. Perceivable
## 2. Operable
## 3. Understandable
## 4. Robust

^ a wide range of technologies (browsers, assistive tech, operating systems, etc both old and new) can access the content

---

# [fit] WCAG Conformance Levels

- A - must
- AA - should
- AAA - may

^ The WCAG involves three conformance levels (A, AA, and AAA), which increase in strictness and requirements.To meet a conformance, your website must meet the requirements within that level, and those below it.

^ Priority 1: For all users to access the Web content and for Web developers to attain Conformance level “A”, these requirements must be satisfied.

^ Priority 2: These requirements should be satisfied by the Web developers so that no group finds it difficult to access the Web content and so as to attain Conformance level “AA”.

^ Priority 3: These requirements may be satisfied by the Web developers to facilitate access to Web content for some groups and attain Conformance level “AAA”.

---

# [fit] Why might you do an audit?
- You're taking over a site from someone else.
- You want to know how to improve your own site.
- Your client needs to improve their site's accessibility.
- Someone is being sued.

^ do you come up with fixes now, or later?
^ who does an audit?

---

# [fit] How do we do an audit?
## Example Time!

---

# [fit] Guideline [1.4.3](https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-contrast.html) - Contrast (Minimum)
The visual presentation of text and images of text has a contrast ratio of at least 4.5:1, except for the following:
- Large text
- Incidental
- Logotypes

^ What do you think it means? discuss as a group

---

[Hacker News](https://news.ycombinator.com/news)

^ how might we evaluate this site for this guideline? let's try it!
^ webaim color contrast checker

---

# [fit] Guideline [1.1.1](https://www.w3.org/TR/UNDERSTANDING-WCAG20/text-equiv-all.html) - Non-text Content
All non-text content that is presented to the user has a text alternative that serves the equivalent purpose, except for [certain exceptions].

^ What do you think it means? discuss as a group

---

[Chicago Botanic Garden](https://www.chicagobotanic.org/)

^ how might we evaluate this site for this guideline? let's try it!
^ we look at HTML or could use the web developer chrome extension

---

# [fit] Guideline [2.1.1](https://www.w3.org/TR/UNDERSTANDING-WCAG20/keyboard-operation-keyboard-operable.html) - Keyboard
All functionality of the content is operable through a keyboard interface without requiring specific timings for individual keystrokes, except where the underlying function requires input that depends on the path of the user's movement and not just the endpoints.

^ What do you think it means? discuss as a group

---

[18F](https://18f.gsa.gov/)

^ how might we evaluate this site for this guideline? let's try it!
^ example of a tool we might use

---

# [fit] Different ways to organize your audit
- Listed in a document
- An organized spreadsheet
- Something else?

---

# [fit] What do I keep track of?
- Which page you're evaluating
- Which guideline you're using
- Does it fail?
- If it fails, how does it fail?
- Potential notes for future fixes

^ link to example spreadsheet

---

# [fit] Let's do this! Time to try an audit!

- On your own or with a group of 2-3 people
- Pick one of 10 example sites
- Use WCAG 2.0 site and recommended tools
- Pick 4 of the recommended guidelines and audit the site!
- Afterwards, we'll share what we found

---

# [fit] So, what did we find?
- What site did you look at it?
- Which guideline?

---

# [fit] Wrap Up

---

# [fit] Thank You!
