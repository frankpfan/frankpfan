## Hello, GitHub; Hello, World

👋 Hi, I’m @frankpfan, a Chinese student.

👀 I’m interested in maths and programming.

🌱 I’m currently learning at a secondary school, but I am really
interested in linear algebra, calculus, category theory and type theory...\
... though I don't know very much about all the them.
However, I've got my own ideas about the maths world.

⚡ Fun fact: A lot of **'Chinglish'** words and expressions appear in my code...

## My Programming Experience

I currently like to write with Python, but it's not the end.

I've used a few IDE's and editors like Python IDLE, Visual Studio, PyCharm,
Neovim and... sorry, sometimes, when I'm soooo lazy, Windows Notepad,
which has caused much problem. (*sigh.)

## My Maths World: A Glimpse

### 1. About structure

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

### 2. About model

So when we're talking about the group of all integers
( $\mathbb Z$ in set theory),
we're talking about an object in the category $\mathsf{Grp}$,
i.e. $(\mathbb Z, +, (-))$.

But we usually have it in the context of set theory, so we apply a
functor $\mathsf{Grp} \to \mathsf{Grp}_{\mathsf{Set}}$ onto it,
and get the set-representation of it.

And, given a category of all models of something, the initial object
has exactly the same structure as it.

### 3. About identity: structure and relationships

In 1-category theory, two things $a, b \in \mathcal C$ are the same
as long as functors $\mathcal C(-, a) \simeq \mathcal C(-, b)$

We also write $a \simeq b$ in this occasion. That's because,
once two objects in a certain scope has the same relationships
with all others, they look exactly the same in the scope.

For example, two proofs of a proposition is eqaul,
for they does the same thing.
It is just like extensionality. I consider extensionality to be a kind of
'nearsightedness' when we look at things from a higher layer of isomorphism.

### 4. The world itself

In my maths world there is a machine that recognises maths expressions.
You can add some rules for it, such as the basic rules of logic.
The machine can operate on expressions according to the rules.

Then you can put an math object in it as 'theory', and then study it.
You can even make implementations for other theories or objects via
some powerful theories like set theory.

Or, maybe the theory is made of rules, like most type theories,
then what you put in may be a universe like
$\mathsf{Monoid} := (A:\mathcal U)\times(\cdot:A\to A\to A)
\times(\mathrm{assoc}:\prod\limits_{a,b,c:A} abc = a(bc))$.
