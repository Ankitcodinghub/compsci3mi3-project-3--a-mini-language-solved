# compsci3mi3-project-3--a-mini-language-solved
**TO GET THIS SOLUTION VISIT:** [COMPSCI3MI3 Project 3 –A Mini Language Solved](https://www.ankitcodinghub.com/product/compsci3mi3-project-3-a-mini-language-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92587&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMPSCI3MI3 Project 3 –A Mini Language Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
1 The Task

Throughout this course, we have been developing language components and type checking rules which evalu- ate the terms of a simple programming language. The time has come to tie it all together, and Build! That! Language!

You are tasked with developing a Haskell program which implements the following language features covered in this course.

• Booleans (As defined in Typed Arithmetic Expression language) • Naturals (As defined in Typed Arithmetic Expression language) • Simply Typed Pure λ-Calculus

• The Unit data type and value

• Let bindings

• The Sequencing Operator • Reference Operations

You will develop a Haskell function, ssos, which implements the semantics of the above language features. You will also develop a function typeCheck, which determines whether or not a term is well typed. You have been provided with data types in the file template.hs. There are likely to be minor variations with the datatypes you used in previous projects. For this project, you will be required to use the data types provided.

The recommended approach to this project is to go through the language constructs in the order provided, testing as you go, and making sure that one language feature works before the next one is attempted. It is highly recommended that you take a backup after completing each language feature, or store your solutions in a (private!) repository. Foir more information on how your project is to be submitted and scored, see §2.

1.1 Test Cases

A file called Test Cases.txt has been provided. This plain-text file contains numerous test cases, with both evaluated results and the found type. Step-by-step evaluations, including intermediate memory states, have been provided.

1.2 eval and run

As with previous projects in this course, you will construct an eval function which repeatedly applies the term you are evaluating to ssos until a normal form is reached (regardless of correctness).

Due to the addition of a typechecker, we can finally verify the correctness of our programs before executing them. You will need to write a function, run, which first typechecks the given term, and only evaluates it if the term typechecks.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
1.3 Booleans (Challenge Rating ⋆ ⋆)

Implementation of Boolean semantics was a large component of Project 1, so our main task with the Booleans in Project 3 will be creating the typechecker. Recall that typechecking is a process that may fail to find a type for a term. While single step semantics, augmented with reflexivity is a total function over terms, typing is a partial function over terms. The way that Haskell handles partial functions is using the Maybe monad.

• You can apply the Maybe monad to a type to indicate that it may or may not exist.

– For example, a value of the type Maybe Bool might be a Boolean, or it might not exist.

• Maybe’s values are either Just x or Nothing, with x being a term of the type within the Maybe.

So, rather than our typechecker directly yielding a type as a value, we want it to return a value wrapped in the Maybe monad. This way, any time our type inference rules fail to determine the type of an expression, we return Nothing. This is reflected in the project template.

</div>
</div>
<div class="layoutArea">
<div class="column">
Page 2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
1.4 Naturals (⋆ ⋆)

You will notice that, in the provided code template, we have amalgamated our former syntactic categories of values and numeric values (and a few more besides!) Before we had a type system, we needed two categories of value to correctly restrict the construction of successor values. With the addition of typechecking, this happily becomes unnecessary. Since the input term to the successor function is required to be typed Nat, we can be confident that a well-typed term does not need to be restricted in this manner at the semantic level.

</div>
</div>
<div class="layoutArea">
<div class="column">
Page 3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
1.5 λ-Calculus (⋆ ⋆ ⋆ ⋆)

Typechecking λ-Calculus requires the introduction of Γ as a parameter of our typechecking function. In the provided template, pairs in the Γ relation are expressed as a list of two element tuples. Naturally, Γ must be passed down through recursive calls to the typechecking function, with modifications any time we are typechecking through a λ abstraction (or let binding).

You will notice that, in the provided template, both variables and abstractions have been included in the set of values, rather than in the set of terms. This is intentional. λ abstractions in particular must be values in order for us to be able to store them in memory.

Finally, on the subject of substitution. The above substitution rules apply for the terms of pure λ- Calculus, but no rules are provided for the other terms. You may assume that substitutions are passed through all other terms with subterms, and that a substitution applied to a non-variable value does nothing. You may assume similar behaviour for relabelling operations.

</div>
</div>
<div class="layoutArea">
<div class="column">
Page 4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
1.6 The Unit Type (⋆)

There’s not much to say about the unit type and value. Most of the work has been provided for you in the code template, and unit has no evaluation rules.

1.7 Let Bindings (⋆ ⋆)

Let bindings in this form are not substantially different from λ abstractions with application, except for the fact that we use a form of type inference to type the variable.

The only tricky part is, in order for type checking to work, let bindings must also contribute a variable- type pair to Γ. As with λ abstraction, typing information for the variable bound by a let binding must also be made available to sub-calls to the typechecking function.

Let bindings are included in this project because we will be using them for a special purpose, when we implement reference operations. Essentially, we will use let bindings to simulate the algebraic variable manipulation used to construct programs in the textbook and lectures.

</div>
</div>
<div class="layoutArea">
<div class="column">
1.8 The Sequencing Operator (⋆ ⋆)

t 1 → t ′1

t 1 ; t 2 → t ′1 ; t 2

unit; t2 → t2

Γ⊢t1 :Unit Γ⊢t2 :T2

Γ ⊢ (t1;t2) : T2

</div>
<div class="column">
(E-Seq) (E-SeqNext) (T-Seq)

</div>
</div>
<div class="layoutArea">
<div class="column">
Page 5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
On it’s own, the sequencing operator should be reasonably straightforward to implement. We have chosen here to model sequencing in the manner of our external language, with sequencing as a full term of the language with its own evaluation and typing rules.

1.9 Reference Operations (⋆ ⋆ ⋆ ⋆ ⋆)

</div>
</div>
<div class="layoutArea">
<div class="column">
Page 6

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
Reference operations are the most difficult portion of this project. The grading scheme has been set such that completing the entire project up to section §1.8 is worth 90% (an A+). A complete and correct sub- mission with a complete and operational implementation of referencing is worth 110% (An A++?) Getting the semantics working is easier than getting the typing operational, but both are challenging.

1.9.1 Semantics (⋆ ⋆ ⋆ ⋆)

Implementing the evaluation rules for referencing has a few tricky parts:

<ul>
<li>For (E-RefV), an unused location must be obtained from the available locations. It doesn’t matter which location is chosen, so long as it is fresh. It is acceptable, if no more locations are available and another is requested, that the program fails with whatever error your implementation would naturally trip. The process greatly resembles selection of a fresh variable name during relabelling.</li>
<li>Note that all evaluation rules must be augmented with a proper handling of μ. Remember, reflexivity rules need to pass on changes that may have been made to μ during the handling of the subterm.</li>
<li>Another place μ will need to be factored in is in your eval function. Under multi-step single step operational semantics, it is correct for the state of μ to be pass from one call to ssos to the next. This is the reason that, in the code template, ssos returns a tuple containing both a term and some μ.
Aside from these points, implementing the referencing evaluation rules should be relatively straightforward. The difficulty of this part is largely the refactoring of ssos to handle μ correctly.
</li>
</ul>
1.9.2 Typing (⋆ ⋆ ⋆ ⋆ ⋆)

An observant student may have noticed that, while the code template contains data structures for Γ and μ, the typing store Σ is noticeably absent. For this project, we will modify our semantics, so as to eliminate the use of Σ.

So far, our implementation has managed to keep typing and evaluation rules completely separate. The population of Σ with location-type pairs is, however, strictly a run-time phenomenon. It is dependent on locations found during memory allocation. In theory, if the new memory location selection mechanism you coded in §1.9.1 was deterministic, and if the typechecker and the single step semantics were persuaded to execute subterms in the same order, a typing traversal would reliably yield the same locations as evaluation traversal in the same order. This is, however, a very bad model of how real memory works, and so we won’t reconstruct Σ during pure typechecking.

To solve this problem, we must first restrict the typing rule for memory allocation so that it is only well typed when it occurs in a let binding. Free occurrences of memory instantiation outside of let bindings will not be considered well typed. Thus, the type of any allocated locations will be added as a

</div>
</div>
<div class="layoutArea">
<div class="column">
Page 7

</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="layoutArea">
<div class="column">
type for the bound variable to Γ. From there, the typing rule for variables will pick the reference type out of Γ later on in the program.

While this approach is somewhat restrictive, it makes the construction of a separate typing store com- pletely unnecessary. Our typing and evaluation rules remain separate and distinct, and nobody has to completely, painfully and laboriously rewrite eval, typeCheck and ssos to account for data sharing be- tween execution and typechecking.

2 Scoring

Scoring will be progressive, based on the number of language features you correctly implement.

</div>
</div>
<div class="layoutArea">
<div class="column">
Feature Set

B 2131515/100

</div>
</div>
<div class="layoutArea">
<div class="column">
Semantics Type Checking Total Cumulative

</div>
<div class="column">
Booleans B

Naturals N λ-Calculus λ Unit Type U

Let bindings L Sequencing S References R

</div>
</div>
<div class="layoutArea">
<div class="column">
B∪N 2 B∪N∪λ 4 B∪N∪λ∪U 3 B∪N∪λ∪U∪L 8 B∪N∪λ∪U∪L∪S 8 B∪N∪λ∪U∪L∪S∪R 8

</div>
<div class="column">
13 15 21 25 2 5

7 15

7 15 12 20

</div>
<div class="column">
30/100 55/100 60/100 75/100 90/100 110 / 100

</div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li>According to the above, the maximum grade available for this project is 110%.</li>
<li>Only the above feature sets are valid feature sets. If a feature is skipped, the project will be graded
with whichever of the above feature sets is the largest subset of the provided features.

– For example, an implementation containing B ∪ N ∪ U will be graded as B ∪ N, because it skipped

λ.
</li>
<li>Full marks will only be available for solutions in which lines of the ssos and typeCheck functions have been commented with the evaluation and typing rule names implemented in that line. For the most part, each typing or evaluation rule only requires one line in either function. Lines which do not correspond to an explicit rule should have a comment indicating the purpose of the line.
– For example, lines giving values reflexivity in ssos should be indicated with a comment.
</li>
<li>Your final submission should be a single Haskell source file, named &lt;Your MacID&gt;.hs. Submission is through the Avenue dropbox.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
Page 8

</div>
</div>
</div>
