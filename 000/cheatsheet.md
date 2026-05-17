𝒩 = the network
cᵢ = individual neuron
Pr = predicate expression
Nᵢ(t) = "neuron i fired at time t"
S = time shift, S(P)(t) = P(t-1)
Principia dot groups:
- Group I: dots flanking connectives — marks scope
  p . ≡ . q    means    p ⟺ q

- Group II: dots after quantifiers — marks how far quantifier reaches
  (Ex) . P(x)         means    ∃x(P(x))
  (Ex) : P(x) . Q(x)  means    ∃x(P(x) ∧ Q(x))  — colon has wider scope

- Group III: dot between two formulas — means AND
  P(x) . Q(x)    means    P(x) ∧ Q(x)

- More dots = wider scope
  single dot .   binds tightest
  colon :        binds looser
  double colon :: binds loosest
N₁...Nₚ = input neurons
Nₚ₊₁...Nₙ = internal neurons
Inhibition is absolute veto