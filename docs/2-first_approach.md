# 2. First approach

[Back to home](../README.md) | [3 - Case diagrams](.)

## Our metodology

We develop software solutions with agile metodology. First, we need to define scope and requirements of the project and then we can proceed to development planning.

Usually, we develop in six weeks cicles and, then, we take two weeks to analyze the job done and refine the next development cycle.

For us, is fundamental have a MVP (minimum viable product) delivered even from the first development cycle. For you, that means a first version of your product totally functional with his fundamental features ready to use (IN SIX WEEKS).

Working in this way, after each delivery, we have two weeks to analyze the product with you and your users and planning posible pivots. In our experience, it's very frecuent that users don't use some very complex features and, in the other hand, are loving other thing that we considered a "secondary thing". Fortunately, we don't need wait a year or six months to take other path or maybe give more protagonism to that secondary thing that was awesome for your users.

## Tech stack

For this specific problem, we propose to use the following technology stack.

![Tech stack](figures/stack.png)

## Preliminar models

This is a simplified version of full class diagram. Methods, attributes and encapsulated objects are not shown here.

![Simplified diagram](figures/models.svg)

### Relations

- A company has many jobs.
- A job belongs to a company.
- A job has many candidates (trough applications).
- Each application has one hiring process (and employeer could set that from templates).
- An employeer has many companies.
- Every candidate has a *path* (built from skills, experience, education and certifications).
- Every job has *requirements* (built from skills, experience, education and certifications).

## Preliminar views

A first fast estimation is that is necessary build a CRUD for 12 resources. So, we need, at least, 48 views.

## Team

We suggest a team composed by:

- [Project manager (part-time)](https://www.linkedin.com/in/david-cejas/).
- UI designer.
- SRE specialist.
- [Sr. Frontend Developer](https://www.linkedin.com/in/ignacio-agust%C3%ADn-grassini-75113b150/).
- [Sr. Backend Developer](https://www.linkedin.com/in/juanmamaffei/).
- [Sr. QA/QC Engineer (part-time)](https://www.linkedin.com/in/valeriagrassini).

## Time estimation for deploy a MVP

- First six weeks cicle: BASIC and functional MVP
- Two weeks cool down: Internal meetings to review the product.

- Second six weeks cicle: COMPLETE MVP, fix bugs.
- Two weeks cool down:

- Third six weeks cicle: Adding features
- Two weeks cool down: Review next steps (scalability and new features)...

*Total duration:* 24 weeks (6 months) with a total functional first product since second month.

- Development: 2100 hours. U$ 52500

- Other:
  - Legal (privacy, terms and conditions contracts).
  - ElasticSearch license.
  - Domains, SSL.
  - Server infraestructure leasing (API, databases, web frontend, notifications).
  - Manual QA/QC engineer (contractor).

[//]: # (TASKS)
[//]: # (Review entire logic. BE+FE - 20)
[//]: # (Design API. BE - 100)
[//]: # (Write stories. PM - 15)
[//]: # (Sketch UI. UI - 100)
[//]: # (Create components. FE - 100)
[//]: # (Mounting infraestructure. SRE - 100)
[//]: # (First deploy. SRE - 100)
[//]: # (565 hours)

[//]: # (Nacho: 500 horas, Tano: 500 horas, Juanma: 500 horas)
