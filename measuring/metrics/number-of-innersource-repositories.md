[⬑ back to the overall graph](../use_gqm.md)

# **Metric:** Number of InnerSource repositories

As projects adopt InnerSource, there are signs of such adoption on the corresponding source code repositories.
Examples are the presences of a `CONTRIBUTING.md` file, a "How to Contribute" section on the `README.md` file or repository topics in GitHub such as `innersource`.

One challenge with this metric, is defining an InnerSource repository, as there is no clear cut definition.
Some companies may have strict requirements that define an InnerSource repository, while others may adopt a _self-declaration_.

Another challenge is that companies that use (entirely or partially) the concept of a monorepo may need to find a different unit of measure to observe, as a single repository may be used for many projects or software packages.

**Synopsis**: Number of source code repositories that adopt InnerSource 

**Unit of Measurement**: Number of repositories 

**Interpretation**: Comparing an absolute number to a range does not make sense in this context. Comparing percentages does make sense, but there's no strong base for comparison.

e.g. 10% of repositories are InnerSource

It's more interesting to observe this metric's trend over time.  

**Measuring**

Examples:
- Measure the number of GitHub repositories tagged with the `innersource` topic.
- Measure the number of repositories that are above a given threshold using an automated maturity score calculation

## Related InnerSource Patterns
- [InnerSource Portal](https://patterns.innersourcecommons.org/p/innersource-portal) - typically shows the number of InnerSource projects
- [Repository Activity Score](https://patterns.innersourcecommons.org/p/repository-activity-score) - defines a score for ranking active projects, usable as a criteria to identify InnerSource repositories
- [Standard Base Documentation](https://patterns.innersourcecommons.org/p/base-documentation) - describe common files used to document different aspects of InnerSource projects
- [Maturity Model](https://patterns.innersourcecommons.org/p/maturity-model) - defines levels of maturity for InnerSource projects and can help classify a repository as InnerSource.
