# Markov Chains
## Transient and Recurrent Properties

Independent study on the topic of Markov Chains and their applications alongside Professor Hyunchul Park of the SUNY New Paltz Math Department. I presented the research at the 2019 Spring Symposium hosted by SUNY New Paltz. Please refer to the pdf to see the full presentation, including the mathematical proofs alongside the graphs from the Juypter Notebook.

## Abstract

Stochastic processes are often used in various fields within mathematics and probability theory.
In particular, Markov chains are powerful tools due to their *memorylessness.*
This property allows one to predict the future based soley on the present state.
Through this condition, it is possible to determine if a state is recurrent or transient in a given state-space; either the chain return to the state *ad infinitum* or the chain will never return to the state afer finitely many steps.

Not only will we provide a formal written proof utilizing the Markov property, we have also developed Python simulations to illustrate recurrence and transience in real-life scenarios.
These examples are symmetric random walks on d-dimenstional integer lattices.

This simulation helps us to classify recurrence further into either a null recurrence, the expected number os steps to return to where the chain started is infinite, or a positive recurrence, the expected number is finite.
We show by an example that in the null recurrence case, the chain returns to the starting point but the number can very very large.