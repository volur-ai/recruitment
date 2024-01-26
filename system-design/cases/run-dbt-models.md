# Running dbt models in production

At Völur, we utilize [dbt](https://www.getdbt.com/) to perform data
transformations and to manage models in our data warehouse efficiently. This
ensures our data warehouse remains structured and that the resulting data is
accessible to stakeholders including Data Analysts, Data Scientists, BI tools,
ML Pipelines, etc.

In this exercise, you are tasked with designing a solution for executing an
arbitrary dbt model in a production environment, hosted on a prominent Cloud
Provider.

## Starting point

The following prerequisites are provided:

- A GitHub repository containing dbt models,
- Availability of GitHub Actions for workflow automation,
- Existing mechanisms for deploying resources to a selected Cloud Provider.

> [!NOTE]
> You are feel free to make any additional assumptions you need to complete the
> task.

> [!TIP]
> While we mostly use Azure at Völur, you are not restricted to it. Feel
> free to select any Cloud Provider that you believe would best suit the
> solution or you feel most comfortable with.

## Task

We're looking for a solution that facilitates the scheduled execution of a dbt
model. We expect you to present

- a conceptual architecture for the proposed solution,
- a CI/CD process for deploying dbt models into production,
- the necessary infrastructure components required for running dbt models in
  production,
- error handling strategies, including notification mechanisms for error
  occurrences,
- an observability approach to monitor and log the system's performance and
  health,
- security measures and best practices to keep the deployed models and
  data safe.

Please provide an overview that highlights the following aspects of your
solution:

- Advantages: What are the benefits of your design?
- Potential Pitfalls: Where could the design potentially fail or fall short?
- Risks: What risks should be taken into consideration?
- Future Plans: Outline any opportunities for future improvements or expansion.

## Deliverables

> [!TIP]
> Note that we are looking for a high-level design, not a complete
> implementation.

You may present your solution in a format of your choosing—this can be a
written document, a flow diagram, a slide presentation, or any other medium
that effectively conveys your thought process.

The priority is for you to be able to **articulate the reasoning** behind your
conceptual solution.
