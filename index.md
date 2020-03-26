---
title: Welcome
---

{% assign d = site.data.SessionInformation.NextSessionDate | date: "%-d" %}

# What is St. Ives Tabletop?

We are starting a fortnightly tabletop group for the area around St. Ives, Cambridgeshire.

We aim to cover:
* Tabletop RPGs (we have a good amount of experience running); and
* Board games (we have hundreds between us!).

# Next session

In light of the government’s recent recommendations around COVID-19 (aka coronavirus), we have decided to have a hiatus for St Ives Tabletop until further notice.
We are keen to restart the club as and when the advice changes and will keep you updated via our various [communication channels](/Contact.html).

For those who would like to continue during this break to play either board games or role-playing games, we are organising some virtual sessions in place of the regular Wednesday fortnightly sessions (e.g. using [Tabletop Simulator](https://www.tabletopsimulator.com) or various websites for board games, [Roll20](https://roll20.net) for tabletop RPGs, with [Discord][Discord] as voice/video chat).
If you are interested in joining, please join our [Discord][Discord] server and please let us know so we can organise.

The next virtual session will be:  
*{%- case d %}
	{%- when "1" or "21" or "31" %}{{ d }}st
	{%- when "2" or "22" %}{{ d }}nd
	{%- when "3" or "23" %}{{ d }}rd
	{%- else %}{{ d }}th
{%- endcase %} {{ site.data.SessionInformation.NextSessionDate | date: "%B %Y" }} @ {{ site.data.SessionInformation.SessionStart | date: "%l:%M%P" }} until {{ site.data.SessionInformation.SessionEnd | date: "%l:%M%P"}}*

See the [calendar](/Calendar.html) for the following sessions (which will be virtual until further notice).

![Poster](/images/{{ site.data.SessionInformation.NextSessionDate | date: "%Y_%m_%d"}}_Poster.png "Next Session: {% case d %}
	{%- when "1" or "21" or "31" %}{{ d }}st
	{%- when "2" or "22" %}{{ d }}nd
	{%- when "3" or "23" %}{{ d }}rd
	{%- else %}{{ d }}th
{%- endcase %} {{ site.data.SessionInformation.NextSessionDate | date: "%B %Y" }}"){:class="img_poster"}

[Discord]: https://discord.gg/bScV82f
