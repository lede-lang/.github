# Lede

Lede (Line-Encoded Document Engine) is a line-oriented page format that AI models write instead of HTML. A compiler turns it into one
self-contained page with charts, diagrams, light and dark themes and a phone layout, and no JavaScript. The model writes between a
fifth and a seventh of the tokens it would write as HTML.

It is an early 0.x release: cheaper and safer than HTML, and not yet as good as the best HTML. There is a lot of room to improve it.

- **Site, reference, examples and a playground:** [ledelang.dev](https://ledelang.dev)
- **Code, specification and skill:** [lede-lang/lede](https://github.com/lede-lang/lede)
- **Add the skill to your agent:** `npx skills add lede-lang/lede`, or in Claude Code `/plugin marketplace add lede-lang/lede`
- **Compile pages:** `npm install -g @lede-lang/cli`, then `lede build page.lede -o page.html`
- **Report a problem or a page Lede can't draw:** [open an issue](https://github.com/lede-lang/lede/issues)

Made by [Andrew Chemis](https://andrewchemis.dev).
