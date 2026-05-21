Caro Francesco,

globalmente sono molto soddisfatto dal Suo lavoro e ho pochissimi commenti.

Scrivo in inglese perché il testo è in inglese.

> [x] Intro, par, 1: Historically...No. Historically, local class field theory was first DEDUCED from global class field theory by Hasse, who later find a way to go in the other direction. But there was no cohomology at the time. Cohomology in local class field theory was introduced by Tate and Nakayama. The first proof of the duality theorem USED class field theory. Serre and Tate later remarked that Grothendieck's concept of the dualizing module can be used to give an independent proof and that's what you have written up here.

> [x] p.4, top: an abelian category _which_ has enough projectives and injectives (not in particular).

> [x] p.4, 1.1.4: Hom(A,B), not Hom(A,G)

> [x] p.9, proof of 1.2.10. This is very complicated. The statement is a trivial consequence of Shapiro that you'll discuss later.
^ Okay, I reordered the section about functoriality so that I could still use dimension shifting to show that conjugation induces the identity in cohomology (although this too could be done using universality).

> [~] p.12, proof of 1.3.6: I have always found that this delta-functor bla bla is not necessary to obtain the basic results in group cohomology. See how I do it in my homological algebra notes.
^ As far as I understand, the proof in the notes doesn't work for profinite groups because Z[G] is not a discrete G-module, and I do need Shapiro for profinite groups. The proof I included also works for profinite groups, provided one checks that the co-induced functor is still right exact (which I've now explained in Remark 2.3.9).

> [x] p. 22, 2.4.6; H^2(G, Z/pZ). Also, maybe it would be relevant to include a complete proof as this will be crucial later for determining the cohomological dimension of F_p.
^ I added a section about the cohomology of cyclic groups, and adapted the proof using the functoriality via inflation maps present in your book.

> [x] p. 27, 2.5.9: In the second example you are also using passage to a p-Sylow. It is also possible to prove the third example easily using the periodicity of the cohomology of the group Z/2Z = Gal(C|R).
^ Corrected and added the proof of the third example.

> [x] p. 27, 2.5.11 cd_p, not cd.

> [x] p.30, 3.1.4: the _additive_ group of A is a profinite abelian group.

> [x] p. 31, 3.1.7: In the first example you are giving the finite unramified extensions of \kappa((t)). In the second it would be easier to consider the totally ramified extensions \kappa((\root n\of t)) of the same field.

> [x] p. 31, 3.1.8: In the whole theorem you have to fix an algebraic closure of K and the fields L and K_nr are subfields of the fixed alg.closure.

> [~] p. 32: in Thm 3.2.1 you have to assume\kappa is finite. However, in the discussion after it it is enough that \kappa is perfect.
^ In Serre the hypothesis are slightly more general, but might as well state it in the appropriate context since I don't prove it. In the below paragraph, after a few general facts which holds in any complete discretely valued field I need the finiteness of \kappa to show that U_K has a splitting and that U_K is profinite; I now made this clearer and expanded on a few points.

> [x] p. 32, 3.2.2: residue field \kappa

> [x] p. 32, bottom: were p-adic fields defined somewhere?

> [x] p. 35, 3.4.1: cd_l, not cd

> [x] p. 36, 3.5.1: write isomorphisms, not equalities.

> [x] p. 36, 3.5.2: In char p the other statements of 3.5.1 are also problematic because then cd_p is 1 and \mu_p is not a Galois module.
^ right, \mu_p=1; I've clarified the statement.

> [~] p. 39: You will need the notion of Pontryagin duality only for finite abelian groups where it is easy. The rest is superfluous.
^ I use it in the profinite case for the first isomorphism in in the chain of isomorphisms above Remark 4.4.1; I can prove that (\Gamma^ab)^\* is isomorphic to the dual of the completion of K^\times without it, but I would still need to dualize in order to get the original statement. In Harari the isomorphism is proved by using the compatibility of the cup-product with the reciprocity map, which would require Tate-Nakayama.

> [x] p. 40, 4.2.2: no, (4.2) is not representable on Mod_G^f because I is not an object of it. It is only ind-representable, or representable by an object of the ind-category.

> [x] p. 42: the word arbitrariety does not exist.

> [~] p. 42, 4.2.8: this is a perfect pairing of FINITE groups.
^ I extend the duality theorem to torsion modules by passing to the limit in 4.2.6, which is needed for $A=I$ in 4.2.9.

> [x] p. 45, 4.3: duality for finite modules, not groups.

> [~] p. 45, 4.3.2: the last isomorphism is by 3.5.1.
^ Thanks, I forgot to motivate it. However, the duality isomorphism only says that $i=<id_I,->$ (which I use to apply 4.2.9) is an homomorphism into \Q/\Z, and although the computation I=\mu ultimately uses the local invariant through 3.5.1 I don't see how it relates directly to $i$. However, to show that $i$ is an isomorphism I can perhaps see it as the colimit of $<id_{\mu_n},->$ and notice that id\_{\mu_n} must go to an element of order n in H^2(\Gamma,\mu_n)^\*.

> [x] p. 46: this is the only proof you have messed up. After (4.8), the map is H^1(K,M) -> H^1(K,B). Then you are using that the direct limit (for n=1) is 0 and that M is finite to find B containing M such that H^1(K,M) -> H^1(K,B) is the zero map. It is not necessarily true that H^1(K,B) itself is 0.

> [x] p. 47, bottom diagram: explain the commutativity. It follows from the compatibility of the Brauer group isomorphism with corestriction. Once you have this, you can easily fill in the missing details in the proof of 4.4.4.
^ I couldn't figure out how to prove the commutativity. Can we discuss it in person Monday or Tuesday, so we can also talk about the presentation? The deadline for sending the final version of the thesis is Tuesday.

Biblio: Gille-Szamuely

---

Buona serata,
T. Sz.
