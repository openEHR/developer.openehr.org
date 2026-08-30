# Conformance

Conformance guidance is being developed for the openEHR Developer Guide.

For now, see the [Tooling](../tooling/index.md) section and the [openEHR specifications](https://specifications.openehr.org/).

## Testing conformance today

The openEHR Conformance (CNF) component defines the concepts — a conformance
statement, a test schedule, profiles — and its Platform Conformance Test
Schedule (last content amendment March 2022) describes which behaviours a
platform product should be tested for. The CNF component has not published a
stable release, and its assessment layer was not written.

[Veredictum](https://veredictum.eu) is an independent, community-driven
conformance instrument built on those concepts. It executes a machine-readable
catalogue of 1143 test cases, each citing the released specification section
it enforces, against a running CDR over its REST API (ITS-REST 1.1.0,
AQL 1.1), records every exchange, and computes verdicts as pure functions over
the record, so a report is reproducible by anyone from the same inputs. Runs
can be sealed with a digest manifest and detached signature. It is pre-1.0 and
is not an openEHR Foundation product; the released openEHR specifications are
its only test authority, and where they are silent it records the gap in a
public ambiguity register and reports it to the SEC rather than deciding
privately.

- Documentation: <https://veredictum.eu/docs/>
- Source and catalogue: <https://github.com/rubentalstra/Veredictum>
- Published on crates.io as `veredictum`
