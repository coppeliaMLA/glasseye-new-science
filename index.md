---
# Glasseye course page. Layout and styling: _layouts/glasseye_course.html
layout: glasseye_course
permalink: /
image: /assets/images/glasseye/telescope-16-9.jpg
# Which side the hero text sits on, on wide screens (left or right); pick the side away from the image's subject
hero_text_side: left

# Search engines and link previews
description: "The New Science: a three-session Glasseye course on doing data science, statistics, and machine learning well now that AI has changed the environment, the tools, and the skills."

# Hero (top of page)
# Tip: wrap any value containing ": " in double quotes, or the page won't build.
eyebrow: A Glasseye course
title: The New Science
dek: "Agents have changed the work of data scientists – there's no going back. Used correctly they free you up for the proper work of a scientist: testing theories, building tools, and, above all, solving problems. Learn how to make agents work with you to produce robust, effective data science."
button_text: Sign up now
# Sign-up form: the ID from your Tally form's share link (tally.so/r/<ID>).
# Leave empty and the buttons do nothing.
tally_form_id: kb95N1

# Syllabus. Each session's `content` is Markdown:
#   - plain bullet lists, with nested items indented two spaces
#   - "#### Heading" for a group heading inside a session
syllabus_heading: The syllabus
sessions:
  - number: I
    title: The new environment
    kicker: Session one
    content: |
      In which we explore in detail:

      - What has changed for data science as a result of generative AI
      - Why we must adapt to these changes
      - And how we should adapt

      The "how" question is of particular importance. Here we dissect:

      - What data-science teams are getting wrong in their current approach to the use of agents and generative AI
      - How to stay in control, maintain integrity, and continue to learn when working with agents

      Finally we will look at strategies for succeeding in a tech environment that is rapidly evolving. 

  - number: II
    title: The new tools
    kicker: Session two
    content: |
      In which we introduce you to:

      - The new tools and concepts – not just coding agents, but skills, MCPs, connectors, plugins, hooks and harnesses, evals, guardrails, and the use of multiple agents
      - Old tools to be used in new, very different ways: CLIs, linters, validators, unit tests, notebooks, config files, repositories, versioning software, graphs, and knowledge bases

  - number: III
    title: The new skills
    kicker: Session three
    content: |
      This is where it all comes together as we learn how to effectively deploy the new tools in the new environment.

      This means:

      - Going back to the fundamentals of science – coding agents give fresh relevance to:
        - Preparatory analysis, including mathematical modelling, ontology specification, and concept clarification
        - The scientific process of conjecture and refutation, with the agent as critic/adversary
        - The need for clear and precise prose, at the right level of detail, when writing prompts and instructing agents
        - Managing teams, human and virtual, in disciplined pursuit of a research goal
        - Quality control through guardrails, testing, and the management of uncertainty
      - And rethinking existing disciplines: statistical modelling, machine learning, and causal analysis

      Finally we present a fully worked example of a data-science project using the tools and skills.

# "Why Glasseye" section (after the syllabus). `why` is Markdown.
why_heading: Why do this with Glasseye?
why: |
  The course is run by [Simon Raper](https://www.linkedin.com/in/simonrapercoppelia), a veteran data scientist with 25 years of experience of problem solving in data science, statistics, and machine learning. He has trained and mentored hundreds of data scientists, including at Google, *The Economist*, and ITV.

  Simon is also a rabid early adopter of new technology and has been adapting his methods since the early days of generative AI. He has both the old knowledge and the new techniques.

  The [Glasseye newsletter](https://www.glasseye.ink), written by Simon, fiercely promotes good practice, in a world dominated by hype, and explores the implications of the AI revolution for that practice.

# Closing band (bottom of page): heading, then the package label with the sign-up button
cta_heading: Join The New Science
package_heading: The course package
package:
  - Three 90-minute online workshops
  - A 30-minute one-to-one technical development session with Simon
  - A one-year subscription to the paid tier of Glasseye
---

Almost everyone is saying the same thing... 

The first 80% of an agent-run data-science project is magical; the final 20% a nightmare of unpicking errors and sifting through reams of unverified output. 

The problem is not with the tool, but with how it is used. Agents used with self-discipline, the correct level of oversight, and an understanding of what they should and shouldn't do are phenomenally effective.

In other words, it's all in the *how*. This course will introduce you to the [**new environment**](#the-new-environment), familiarise you with the [**new tools**](#the-new-tools), and teach you the [**new skills**](#the-new-skills). You will leave with an understanding of what it means to be a data scientist in the post-GenAI world.
