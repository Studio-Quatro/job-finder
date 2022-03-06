# 2. First approach

[Back to home](../README.md) | [3 - Case diagrams](.)

## Tech stack

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

- Project manager.
- UI designer.
- SRE specialist.
- Sr. Frontend Developer.
- Sr. Backend Developer.

## Time estimation for deploy a MVP

- First six weeks cicle: BASIC and functional MVP
- Two weeks cool down: Internal meetings to review the product.

- Second six weeks cicle: COMPLETE MVP, fix bugs.
- Two weeks cool down:

- Third six weeks cicle: Adding features
- Two weeks cool down: Review next steps...

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
