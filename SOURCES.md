# Sources

Domains the scheduled publisher searches and credits. One row per domain. Which posts credit which domain lives in `post-sources.tsv`; counts here are derived from it.

Status: `seed` = starting list; `found` = discovered by a run or test; `trusted` = a found source promoted after confirming ideas in 2+ posts, or after appearing with 2+ distinct seed/trusted sources in published posts. Aggregators and SEO summaries are never listed, only the original pages they point to.

| domain | status | note |
|---|---|---|
| addyosmani.com | found | long-running agent practices (credited in leave-a-handoff-for-the-next-session) |
| agentpatterns.ai | found | silent partial success in tool chains (credited in treat-empty-tool-results-as-suspect); hypothesis-driven debugging (credited in instrument-before-you-patch) |
| ai.meta.com | found | Meta AI blog, Agents Rule of Two (credited in drop-one-of-three-risky-powers) |
| anthropic.com | seed | engineering blog, docs, research |
| arize.com | found | agent evals and error analysis (credited in read-the-traces-before-fixing) |
| arxiv.org | seed | papers with practical takeaways |
| claude.dev | found | Anthropic model and effort guidance (credited in run-low-then-escalate-failures) |
| code.claude.com | trusted | Claude Code docs, best-practices page (Anthropic) |
| cognition.com | found | multi-agent context sharing (subagents test, no post yet) |
| cursor.com | found | Cursor blog, Debug Mode (credited in instrument-before-you-patch) |
| deepmind.google | seed | |
| developer.chrome.com | found | Chrome team, DevTools MCP launch post (credited in instrument-before-you-patch) |
| engineering.atspotify.com | found | Spotify Engineering, background coding agent verification and judge (credited in keep-the-diff-inside-the-request) |
| eugeneyan.com | seed | |
| felixrieseberg.com | trusted | credited in 6 posts |
| hackernoon.com | found | practitioner article on agents under partial outage (credited in treat-empty-tool-results-as-suspect); individual articles only, the domain does not vouch for a source |
| hamel.dev | seed | |
| impatientprogramming.org | trusted | |
| kentbeck.com | found | Tidy First? newsletter |
| labs.scale.com | found | LHAW underspecification study (credited in ask-or-assume) |
| langchain.com | found | subagent context modes; offloading large tool results (credited in keep-big-tool-outputs-out-of-context) |
| latent.space | seed | |
| lilianweng.github.io | seed | |
| manus.im | found | Manus team blog on context engineering (credited in keep-big-tool-outputs-out-of-context) |
| neurips.cc | found | NeurIPS 2026 workshop paper on silent tool failure (credited in treat-empty-tool-results-as-suspect) |
| openai.com | seed | blog, cookbook, docs |
| simonwillison.net | seed | credited in 4 posts |
| rajiv.com | found | personal blog, browser verification by agents (credited in use-the-thing-before-you-call-it-done); individual article only |
| thoughtworks.com | found | Technology Radar entries (credited in drop-one-of-three-risky-powers) |
| tianpan.co | found | personal blog, agent scope creep (credited in keep-the-diff-inside-the-request); individual article only |
| strongdm.ai | found | gene transfusion technique page |
| x.com | found | posts by individuals (e.g. Matt Pocock); the domain alone does not vouch for a source |
| xyproblem.info | found | the XY problem |
