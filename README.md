# console

The web console: the run list, the workflow and its graph, the run inspector, the
sharing panel and a format-preserving YAML editor.

YAML stays the source of truth even when editing happens here. The reverse — a graph
store from which YAML is exported — makes review in a Git repository illusory and lets
the two representations diverge at the first feature with no visual equivalent. The
sharing panel is the one part of the console with no YAML counterpart, by design.

The console validates a workflow before sending it, against the schemas from
[`agentiik/schemas`](https://github.com/agentiik/schemas), and wears the palette and the
icons from [`agentiik/design`](https://github.com/agentiik/design). It releases
independently of the core; compatibility is expressed by the API version alone, which is
why the URL carries `/api/v1`.

Nothing is implemented yet. The console is specified at <https://agentiik.github.io/docs>.

## Licence

AGPL-3.0-or-later, see [LICENSE](LICENSE). This is part of the service, and section 13 is
the point: anyone who modifies it and offers it to users over a network owes those users
the corresponding source. [LICENSING.md](https://github.com/agentiik/.github/blob/main/LICENSING.md) has the reasoning.

## Contributing

[CONTRIBUTING.md](https://github.com/agentiik/.github/blob/main/CONTRIBUTING.md), under the Developer Certificate of Origin 1.1.
