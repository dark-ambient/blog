---
tags:
  - management
  - "#risks"
draft:
---
Alright, let's define the risk as a term:
**Risk** - positive or negative event, which can happen or not happen.

As the following techniques applied to risks overall, it means they applied both to positive and negative events that can happen or not.
It's fine to keep different registries for positive and negative though.

#### Algorithm

```mermaid 
flowchart TD
	IR(identify risks)
	QA(quantitative analysis)
	QuA(qualitative analysis)
	P(Reaction plan)
	C(Control)
	IR-->QA & QuA -->P-->C
```


That will help to fill the following table (an example of short business travel that includes flying by plane)

| Risk                                                               | Probability                                                                                                           | Impact | Importance |
| ------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------- | ------ | ---------- |
| Being late to an important meeting due to a flight being cancelled | ~[1%](https://www.nerdwallet.com/article/travel/avoid-airline-cancellations?t#why-are-so-many-flights-being-canceled) | High   | High       |

#### Reaction plan

| Risk name                                                          | Plan A                                                                                        | Plab B                                                                                                     | Trigger                                                                      | Owner    |
| ------------------------------------------------------------------ | --------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------- | -------- |
| Being late to an important meeting due to a flight being cancelled | Buy an insurance; get an earlier flight; study other options if not flights (train, car, bus) | Utilize the options given the information about the flights; notify partners if you are late than expected | An announcement by the airline, a digital comm you received from the company | yourself |
|                                                                    |                                                                                               |                                                                                                            |                                                                              |          |
Plan A - **before the risk occurs**, our actions to avoid the negative risk or mimize it's potential impact; in case of positive - actions to improve the probability of the risk to happen. The Plan B is immediately being executed after the identification.

Plan B - our actions in case the risk occurred.

A trigger of a risk - a fact (symptom), i.e. answers the question "how to understand the risk got occurred?".

An owner of a risk - a person, who noticed the trigger and understands that the time for the Plan B has come.

```mermaid
flowchart TB
A(Plan A)
B(Plan B)
R(Risk)
T(Trigger)

S(success)
F(failure)

A-->R-->T-.->|owner acts|B-->S
T-.->|owner doesn't act|F
```


There are various strategies for the Plan A: avoid, mitigate, transfer, accept a risk.


---
[[Disclaimer|Disclaimer]]
