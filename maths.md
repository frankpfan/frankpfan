# My Maths World: A Glimpse

## 1. About structure

Every maths object has its own structure,
and has relationships with other objects.

A set of axioms denfines a structure. It is a gate that
only some objects could enter.
Only those with the structure of monoid can enter the door of monoids.\
Similarly, only those things that together looks like all sets can enter
the door of set theory, and they must enter together
to represent the whole theory.

Then it is called a 'monoid'.
Then they, the collection of things, is called a 'set theory';
more precisely, they are called a model of the theory --- but
that's the same thing to me.

## 2. About model

So when we're talking about the group of all integers
( $\mathbb Z$ in set theory),
we're talking about an object in the category $\mathsf{Grp}$,
i.e. $(\mathbb Z, +, (-))$.

But we usually have it in the context of set theory, so we apply a
functor $\mathsf{Grp} \to \mathsf{Grp}_{\mathsf{Set}}$ onto it,
and get the set-representation of it.

And, given a category of all models (or instances) of something, the initial object
has exactly the same structure as the thing.

## 3. About identity: inner structure and relationships

In 1-category theory, two things $a, b \in \mathcal C$ are the same
as long as functors $\mathcal C(-, a) \simeq \mathcal C(-, b)$

We also write $a \simeq b$ in this occasion. That's because,
once two objects in a certain scope has the same relationships
with all others, they look exactly the same in the scope.

For example, two proofs of a proposition is eqaul,
for they does the same thing.
It is just like extensionality. I consider extensionality to be a kind of
'nearsightedness' when we look at things from a higher layer of isomorphism.

## 4. The world itself

In my maths world there is a machine that recognises maths expressions.
You can add some rules for it, such as the basic rules of logic.
The machine can operate on expressions according to the rules.

Then you can put an math object into it as 'theory', and then study it.
You can even make implementations for other theories or objects via
some powerful theories like set theory.

Or, maybe the theory itself is made of rules, like most type theories,
then what you put in may be a universe like
$\mathsf{Monoid} := \sum\limits_{A:\mathcal U} (\cdot:A\to A\to A)
\times(\mathrm{assoc}:\prod\limits_{a,b,c:A} (a\cdot b)\cdot c = a\cdot(b\cdot c))$.

--- Structure gets known from the relationship, so does identity.\
Same as this, How I relate to everything else tells who I am.
