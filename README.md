# An-algorithm-for-curing-ageing

To solve a problem one must first understand and define it.

So, what is ageing? Ageing is in itself something simple.
Ageing is the processus of accumulating random mutations / defects in our DNA.
Thats it. We could describe it's consequences (symptoms) but they're far too numerous.
Still here's a small list :
Ageing cause your body to degrade, it is such powerful that people are generally able to estimate the age of a person (that is their level of mutations) only from looking at them and with great accuracy. 
Ageing is not only cosmetic, it make you less alive in many ways, the more you age the less you have energy, strength and the more (non linearly) you get diseases.
The worst consequence is that your brain loose neural plasticity, IQ points and fluid intelligence, that is: you loose progressively the ability to learn new things, to think and to update yourself.
It's final consequence, after deeply lowering your quality of life, is death.
This is why fighting ageing in the meaning of fighting loss of quality of life or overall hapiness, must be a consensual and primordial priority of research and funding.

What cause ageing?
Many factors, mainly light which irradiate TODO peau cells, but also free electrons which oxydate your body, and also imperfect copy while cells clone themselves.
This does not aim to be exhaustive.

We can imagine a large variety of solutions for eradicating ageing.
But in fact they all fit in a few set of paradigms.

Let's make a case Disjonction, in increasing order of effectiveness per paradigm:
Finding a solution to each consequences
We can choose to not solve ageing and instead to solve every of it's symptoms individually.
Such an approach will find a specific, different way to solve each age related disease, here's go alzeihmer, cancer, cardiac research [insert more...] 
Such an approach is by many order of magnitudes the less effective in solving ageing, and the less cost effective too.
This is sadly the most popular and funded approach to fighting ageing, by pathetically failing to identify the root cause of all diseases, researchers fight each diseases individually.

Finding a solution to each causes.
We can choose to eliminate all of causes of mutations, therefore eliminating ageing. 
Such an approach is not feasible, and will probably never be. It can still be useful to slightly reduce ageing, by exposing less to light, eating anti oxydants, etc.

Finding a solution that allow DNA to repair or reset to a state before the mutation occurring.
So here we see that we can't just not solve ageing and solve each of it's symptoms, nor can we prevent the causes of mutations.
But what we can, what we must do instead, is to have an ADN that accumulate mutations but FULLY RECOVER from them.
Some facts:
Humans have in average 60000 mutations each day.
DNA has effective DNA repair mechanisms, the ageing of a cell increase dramatically when DNA repair mechanisms become broken by mutations (how ironic)

Two already existing tools :
Vectors: totally safe viruses that can be injected in a body, go through cells and carry a CRISPR/CAS-(pick one) 
CRISPR/CAS9: extremely accurate, cheap and "easy" technology that scale for editing genes. 
Once carried in a cell DNA thanks to a vector, it can remove an interval of DNA, and insert a version of a gene.

It theoretically allow to spread to each DNA of your body, and change any genes you want.
A first low hanging fruit would be to remove every DNA REPAIR genes of each DNA of your body and replace all of them with new, unmutated DNA repair genes.

Such a solution would not totally solve ageing as DNA repair is unperfect, but should have unprecedent results and as a side effects diminishe by an order of magnitude cancer cells. 
Why hasn't this already been done? I'm not aware nor if it has been tried, nor if it is actually researched funded, nor if there is a complete listing of the difficulties of such an implementation. I've read many CRISPR/CAS9 limitations but most of them are patched by recent research.


A second way would be a hard reset of DNA.
That is, we save a copy of your DNA while you're still young, keeping it for you.
Time passe, you age, therefore we replace progressively replace each gene of your DNA of all of your cells, with a copy of the corresponding gene from your saved young DNA.
This effectively hard reset your body to a younger one.
Such a process must be repeated every X years.
For achieving this, we reuse the method of the preceding solution. It simply is a far more massive rewriting of DNA, and add one premise : that is is feasible to preserve a copy of your DNA and that this copy will not mutate.
I preserving a copy of DNA is already possible as many women cryogenize their ovaries for having childs after 40's
This second solution is the first one to completely solve ageing. But still also has the drawback of repeating the operation every X years. 

The last way of solving ageing, is inspired by how NASA make space probes work.
When you think about it, Processors in space are like DNA, they are irradiated by solar rays. 
Those rays defects random transistors. Space probes work thanks to redundancy, they have many processors that performs the same task, and through majority voting, if 3 of 4 cpus have the same output then this output is the choosen one.
This is also how works ECC RAM in datacenters.
To adapt this to DNA, we would need to clone each DNA gene for example 4 times by appending copys at the right of the original gene.
We do not want the gene to be expressed 4 times.. therefore the copys must, through special headers (e.g https://en.wikipedia.org/wiki/Stop_codon) or other techniques be like 98% of the DNA, inactive ( https://en.wikipedia.org/wiki/Non-coding_DNA ).
To assess the viability of having redundant genes, we can see that it already occurs naturally https://en.wikipedia.org/wiki/Genetic_redundancy but in small quantity as, it reduce ageing but redundancy decrease evoltuion, therefore is eliminated by selective pressure.
How to actually go to a specific gene start ? CRISPR already allow to do this.
pasting a gene, allowed too.
I can't find if CRISPR/CAS* already allow copying a gene, but preliminary search queries seems to imply so.
If so, we need to repeat the copying, for each gene of the DNA.
The second step is to update to either the decoder of the DNA or analyses passes like existing DNA repair to implement the following functions, functions which necessitate extremely basic logic such as comparing equality between two amino acids and the ability to retain "in memory" some indexes.
Thoses biological analyzers today go from the start header to the end header of a gene.
here they would go from the first amino acid of a given gene to the first amino acid of the first copy of the given gene. if they're equal go to next first amino acid of the next copy. if not equal rewrite it through majority voting with others amino acid value.
repeat for each amino acid of the gene.
the defectuous parts of the genes copys have effectivelly been rewritten by others most frequent occurence.
therefore the mutations have been reseted.
How can we implement such a basic algorithm in informatic is an open question in biology.
But one interesting thing to observes is that both DNA repair mechanisms and https://en.wikipedia.org/wiki/Messenger_RNA (the decoding protocol) are made of genes TOO! So we could "code" the functions in base 4 in lab and reset Messenger RNA or DNA repair genes, through CRISPR/CAS9.

to study: https://en.wikipedia.org/wiki/Nonsense-mediated_decay
https://en.wikipedia.org/wiki/Leaky_scanning
https://en.wikipedia.org/wiki/MRNA_surveillance
https://en.wikipedia.org/wiki/Central_dogma_of_molecular_biology
