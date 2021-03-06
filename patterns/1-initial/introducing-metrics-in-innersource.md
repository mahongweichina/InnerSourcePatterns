## Title

Introducing Metrics in InnerSource

## Patlet

Involve all stakeholders in designing and interpreting metrics to measure the current status in terms of _health_ and performance of the InnerSource initiative.

## Context

An organization that is planning to apply or is in the early stages of applying InnerSource would like to measure the 'health' and performance of the initiative i.e. Is there an increase in cross-divisional and cross-location collaboration?

This pattern applies very widely from IS initiatives in their infancy stages to small or large scale IS initiatives that are already mature in their initial process and steps.

## Problem

This organization may already have qualitative feedback from the involved teams, but desire more objective information focused
on development activities.

The organization does not really know where to start measuring things or what are the key parameters to measure.

Changes in the top level initiatives may affect the InnerSource program as they rely on the good will of some executive from the organization.

You may have a problem justifying the InnerSource effort when there is a change in business priorities or business leadership. Then you need something concrete to justify the program. A future problem you're guarding against.

If there's a change in the C-level, metrics might be helpful to convince them that InnerSource is useful.

## Forces

People do not like to be tracked or measured.

There is no canonical monitoring infrastructure for the software development process. Furthermore, such infrastructure is hard to build
or to get funding for.

There is not a culture of software development metrics.

Metrics can be misunderstood especially if people have not received any training on the same.

Organizations collect vanity of any other type of metrics that do not track business objectives' success or failure over time.

Metrics tend to become goals, will subsequently be gamed and thus meaningless.

There is potential conflict in reconciling metrics on team effectiveness or productivity if teams within the organization have different versions of them.

Some organizations in some countries may face extra complexity when introducing metrics as the countries may not allow tracking individuals.

There might be a learning curve in the discussion about metrics. And perhaps the tools do not support the IS metrics we're looking for .

## Solution

Bring developers, middle managers and C-level to have a discussion about metrics. And consider other roles out of the usual development process such as Human Resources, legal departments, product management, and others.

Let developers and middle managers know that these metrics or KPIs are not focused on tracking their personal performance, but to compare if the initiative is currently working as expected.

Consider a third party that is seen as a neutral player to produce such metrics.

Have specific training on the topic of metrics and good practices to use them. An example is to have a methodology to follow metrics such as the Goal-Question-Metric approach or the Objectives-KeyResults one. On the other hand, try to reflect the short-term and medium-term goals in the metrics to be used.

Metrics when published or discussed should be done so in the aggregate without refering to specific people.

Produce a characterization of metrics as this might be helpful for others to understand and follow.

* Nearly always InnerSource is not a goal in-and-of itself but a proposal of how to improve some larger problem that the company is having. One class of metrics is around that larger goal (e.g. quality, interrupt-driven work, duplicated code, etc.) and reflects the company's progress towards it.
* Another class of metrics is around how much InnerSourcing is happening. A raw definition of InnerSource based on code submissions to a repository not owned by the submitter's team could be measurable in a few ways.
* A third class of metrics are KPIs that we believe will improve the raw amount of InnerSourcing happening (e.g. mean-time-to-review, automated test runs on PRs, etc.).

Note: The aforementioned metrics are some common examples. They aren't a one-size-fits-all. We expect the business goals of the organization to drive the metric selection process.

## Resulting Context

The organization builds a monitoring and reporting infrastructure for the metrics that flow directly from its business goals.

Those metrics will provide visibility into the current situation of the project to the C-level executives. By comparing the metric measurements before applying inner source and to the metric measurements after applying the inner source initiative, it is possible to guage the effectiveness of the inner source initiave.

Continued monitoring of these metrics will help middle management and developers understand how the initiative evolves and will help them with their daily work.

## Known Instances

## State

Initial

## Authors

- Daniel Izquierdo
- Tim Yao
- Clint
- Russ Rutledge
- Tom

## Acknowledgement

- Georg
- Bob
