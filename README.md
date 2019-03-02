# i.FLATION texts

In this repo, all text files for the [i.FLATION](https://inflation.pdg-obersulm.de) project are stored. The [main repo](https://github.com/pdg-obersulm/i.FLATION) crawls these files to display them to the user.

## Folder Structure

```
- /
  - scenario1/
    - _description.md
    - _judgement.md		// optional
    - agent1.md
    - agent2.md

  - scenario2/
    - _description.md
    - agent1.md
    - agent2.md

  - config.json
```

## Configuration

```js
{
	"scenarios": [{
		"name": "ScenarioA",
		"icon": "mdi-...",
		"default": true, // only one with this key set to true allowed
		"slug": "scenarioa" // optional, default is name in lowercase
	}, ...],
	"agents": [{
		"name": "AgentA",
		"slug": "agentb" // optional, default is name in lowercase
	}, "AgentB", "AgentC", ...] // shorthand version possible
}
```

## License

The CC-BY-SA-4.0 applies to these texts. Note that the source code and the videos do apply to different licenses.

[![CC-BY-SA-4.0](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](LICENSE.md)
