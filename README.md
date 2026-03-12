# 🧠 Thinking Skills for Claude Code

20 human thinking frameworks as Claude Code custom commands.

## Install

Copy `.claude/commands/` into your project root:

```bash
cp -r .claude/ /path/to/your-project/
```

Then in Claude Code, use `/command-name` to invoke any thinking skill.

## Skills

| Command | Thinking Framework | What It Does |
|---------|-------------------|--------------|
| `/critical-thinking` | 批判性思维 | Question assumptions, evaluate evidence, detect biases |
| `/first-principles` | 第一性原理 | Strip away assumptions, rebuild from ground truth |
| `/systems-thinking` | 系统思维 | Causal loops, emergence, feedback, holistic view |
| `/design-thinking` | 设计思维 | Empathize → Define → Ideate → Prototype → Test |
| `/lateral-thinking` | 横向思维 | Break out of conventional paths, find creative solutions |
| `/six-thinking-hats` | 六顶思考帽 | White/Red/Black/Yellow/Green/Blue perspectives |
| `/socratic-method` | 苏格拉底式提问 | Progressive questioning to reveal deep logic |
| `/bayesian-thinking` | 贝叶斯思维 | Prior → Evidence → Update beliefs |
| `/second-order-thinking` | 二阶思维 | "And then what?" — chain reactions & long-term consequences |
| `/inversion-thinking` | 逆向思维 | Flip it: how would this fail? |
| `/dialectical-thinking` | 辩证思维 | Thesis → Antithesis → Synthesis |
| `/abductive-reasoning` | 溯因推理 | Infer the best explanation from observations |
| `/mental-models` | 心智模型 | Munger-style multi-disciplinary cross-validation |
| `/red-team` | 红队思维 | Adversarially attack your own plan |
| `/steelman` | 钢人论证 | Strengthen the opposing argument, then address it |
| `/probabilistic-thinking` | 概率思维 | Decision-making under uncertainty |
| `/analogical-reasoning` | 类比推理 | Map from known domains to unknown ones |
| `/counterfactual-thinking` | 反事实思维 | "What if it had been different?" |
| `/opportunity-cost` | 机会成本思维 | The true cost is the best alternative forgone |
| `/premortem` | 事前验尸 | Assume failure, work backwards to find causes |

## Usage Example

```
> /critical-thinking Should we switch from REST to GraphQL for our API?
> /red-team Our plan to launch in 3 markets simultaneously
> /premortem The new pricing model we're about to ship
```

## License

MIT — use however you want.
