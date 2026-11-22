---
layout: default
title: Our coaching
---

# 🇨🇭 Team {{ site.team }}: coaching Switzerland

We are the coaches of the Swiss national team. To prepare our players, we studied thousands of past Wikispeedia games with one question in mind: **what decides whether a player reaches the target article?**

<div class="team-grid">
{% for member in site.data.team %}
  <div class="member"><strong>{{ member.name }}</strong><span>{{ member.role }}</span></div>
{% endfor %}
</div>

## Our advice in short

<div class="callout" markdown="1">
- **TODO: Advice 1** (from part 1, strategy)
- **TODO: Advice 2** (from part 1, training)
- **TODO: Message to the organizing committee** (from part 2)
</div>

---

## Part 1: What players can control

### The question

Some Wikipedia articles are **hubs**: they are linked to and from a huge number of other pages (think *United States* or *Europe*). Does passing through a hub increase a player's chances of finishing the game?

### How we tested it

TODO: describe how hubs are defined (e.g. number of incoming/outgoing links) and how you compare games that go through a hub with games that do not.

### What we found

TODO: main result.

{% include figure.html caption="TODO: Success rate of games that go through a hub vs. games that do not." %}

### What it means for our team

TODO: which strategies to teach, and how much training the team needs.

---

## Part 2: What players cannot control

### The question

Not all games are equal: some start–target pairs may be much harder than others. Which features of a game make it hard, and do they predict failure?

### Our difficulty criteria

TODO: list the criteria, for example:

- Shortest-path distance between start and target
- How well connected the target article is
- TODO: other criteria

### What we found

TODO: main result.

{% include figure.html caption="TODO: Failure rate as a function of each difficulty criterion." %}

### Our message to the organizing committee

TODO: if some games are far harder, explain how the committee could use these criteria to build the five difficulty levels, so that every competitor plays games of the same level.

---

## Conclusion

TODO: wrap-up.
