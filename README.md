### Hi there 👋

<!--
**a0v0/a0v0** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->


One formulation of an agile way of building software, often misattributed to Kent
Beck, is:

> [Make it work, make it right, make it fast][wrf]

Where 'work' is making the tests pass, 'right' is refactoring the code, and
'fast' is optimizing the code to make it, for example, run quickly. We can only
'make it fast' once we've made it work and made it right. We were lucky that the
code we were given was already demonstrated to be working, and didn't need to be
refactored. We should never try to 'make it fast' before the other two steps
have been performed because

> [Premature optimization is the root of all evil][popt]
> -- Donald Knuth

[DI]: dependency-injection.md
[wrf]: http://wiki.c2.com/?MakeItWorkMakeItRightMakeItFast
[godoc_race_detector]: https://blog.golang.org/race-detector
[popt]: http://wiki.c2.com/?PrematureOptimization
