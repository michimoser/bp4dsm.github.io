ID-2
##Define domain scope 
Define the appropriate domain scope of your solution. The scope of a DSM solution should be closley alined with business needs.
ID-3
##Identify DSL usage 
The early identification of language usage will have strong influence on language concepts. Precisly identify and describe usage of a domain specific language. Usages of a DSL in real world production scenarios are an important source of knowledge to support decisions in language design and implementation. 
ID-135
##Use end-user personas  
The specification of needs of end-users in form of personas helps to reduce the distance to potential end-users. The use of personas are 
a good mean to keep focused on the professional requirements and tasks of end-users not only during analysis phase but throughout the whole dsm project.
ID-134
##Perform expert review 
Ask usability experts for advice and apply heuristic review evaluation. In a heuristic evaluation, usability experts review interaction with the language and tooling and compare it to accepted usability principles.
ID-79
##Do not overestimate domain experts 
Do not expect the domain experts to know what the computer can (should) do for them; do not expect them to understand what it cannot possibly do for them! DSL designers need to aquire domain expertise by themselve.
ID-4
##Understand present solution 
Understand the design of the present solution. This will allow to focus on the needed scope of a language and helps to mitigate the risk to over-design languages.
ID-6
##Balance genericity and specialization 
Find the right balance between genericity and specialization. Developers often create a language that is too generic. A generic language
design and language concepts may facilitate reusability of a language and make it more robust to changing requirements. However, beware of reusing general purpose modeling languages. Adaptations for your special case will be necessary and your end-users must deal with complex language designs.
ID-5
##Reuse language definitions 
If suitable language exists try to reuse the language, do not reinvent the wheel! Sometimes existing language definitions can also be a goood starting point. Most of the time is better to take what is already their than creating one from scratch.
ID-7
##Adopt existing domain notations 
An curical step during requirment analysis is to learn how domain experts articulate and present problem and solution domain. Adopt exisiting notations (e.g. from domain experts, software, documentation). Inventing a new concrete syntax will raise the threshold for domain experts to pick up your language.
ID-9
##Support model reuse on language level 
Provide mechanisms that support reuse of models on language level. References between models, modularization or library concepts are a good starting point.
ID-8
##Design must have purpose 
All features of a language should support a purpose. The purpose of the language must be closely aligned with buisness needs.
ID-16
##Design for language evolution 
It is thus essential to allow extending the language at any time. Compilation to a target language like Java from a DSL and to generate end-user support for Utilize tool support to facilitate model evolution. Define what a “compatible” model change is and ensure all dependent designs follow this same model. Evolution. Need for language evolution. Minimize DSL changes which break existing models. Proactively manage language evolution. Do not postpone addition and extension of language concepts.
ID-10
##Carefully choose form of notation 
Often the choice for a certain type of notation (e.g. textual, graphical, tabular) is pretermined by experiences and expectations of different stackholders. E.g. software engineers may favor a textual notation, or engineers in industrial automation expect graphical notations to create models. These decisions are often biased and should be questioned.
ID-13
##Avoid redundancy 
Avoid redundancy on a conceptual level. Redundancy is a constant source of problem. Having several concepts at hand gives users the possibility to create different models to describe the same fact.
ID-15
##Viewpoint orientation 
Identify different viewpoints on a software system. This may influence hwo you modularize a DSL. Different concerns of stakeholders can be seperated by using a viewpoint oriented approach. Moreover, the identified viewpoints can help to structure implementation. See <a href=#49>viewpoint aware processing</a>.

ID-28
##Provide Integrability 
Ensure that the DSL and associated tooling can be integrated with existing frameworks and languages. Choose integrability over extensibility. If possible, it is best to provide integration mechanisms on model level (e.g. base integration on metamodel).

ID-14
##Make elements distinquishable  
In graphical languages different elements should exhibit enough syntactic differences. There are more possibilities than changing the color of elements (e.g. shape, behavior, docking).
ID-22
##Consistent style everywhere 
Be consitent on language elements. In graphical languages a consitent use of color, icons, shapes, or connectability has a huge impact on usability of a language.
ID-18
##Limit nr. of language elements 
Languages with hundreds of different language elements are hard to read, comprehend and to use. Try to avoid this by creating new sub-languages providing functionality via library mechanisms.
ID-171
##Support variability on language level 
Drive your language design by focusing on variabilities. Provide mechanisms which handle variability on language level. Rather that having seperate elements for representing variants, core language concepts should be designed to handle variabilities.
ID-11
##Reuse type systems 
Designing a type system can be hard. Therefore, if possible reuse existing type system semantic. This not only eases language design but to asure comprehensibility and avoid errors. An unconventional type system may be hard to adpot for users which have been exposed to conventional type system in other languages.
ID-12
##Keep it simple 
Keep a language simple. A language should be as simple as possible in order to express the concepts of interest and to support its users and stakeholders in their preferred ways of working. So again, keep it simple!
ID-73
##Effective process for DSML definition 
Use well established practices to provide an effective DSML definition process. 
ID-30
##Care for quality 
Care for quality on all levels. Quality of the provided language, DSML tool support and the target systems which built using your DSM solution.
ID-136
##Perform usability evaluations 
Usability evaluations provide valuable feedback for the design of both the notation as well as the tool interaction. Usability evaluations during early project phases provide have a strong influence on the design of a language. Use techniques like paper prototypes to perform evaluations if no runnable software is availabel.
ID-172
##Create guidelines for language definition 
Guidlines are important and help new project members to adopt a proofen development process. Guideline may support a wide range of development activities from naming and styling of elements, over application of best practice, to documentation issues.
ID-173
##Define language rules 
Define language usage rules and commuicate thes rules to your users. Provide automatic consistency checks for rules, constraints.

ID-165
##Derive concepts from physical sturcture 
Derive language concepts and presentation from the physical structures of the real world objects the represent.

ID-166
##Derive concepts from Look&Feel 
Derive language concepts and presentation from the look and feel of real world systems.

ID-199
##First things first: The language 
The language is the most important part of a DSM solution. So do it first.

ID-168
##Derive concepts from domain expert concepts 
Derive the concepts of a language from the concepts domain experts using your solutions share.

ID-169
##Derive concepts from expected output 
Analyse and structure the expected output of your DSML solution. Discussing expected output with domain experts will highlight concepts needed on language level.
ID-170
##Reuse existing computational model 
Reuse existing computational models.
ID-21
##Balance compactness and understandability 
Finding a good balance between compactness and understandability is an important property of a language. Comprehensibility may be provided by precise nameing and representations. However, restrain the language of being to verbose.
ID-23
##Interface concept 
DSLs should provide an interface concept similar to interfaces as known from programming languages.
ID-124
##Precise high-level abstraction 
Use precise, high-level abstractions in the metamodel.
ID-125
##Detect recurring patterns in design 
Watch out for recurring patterns when performing modeling. These may indicate that the metamodel needs to be modified.
ID-17
##Compose existing languages 
The development of a language and associated tooling is labor-intensive. Often languages exist which match certain requirements in your language. Composing your language by embedding existing languages can reduce the effort for language creation. OCL is a good example to that, it can be embedded in other languages to define constraints on elements.
ID-126
##Provide sufficient level of detail 
The concepts of a language should allow for modeling at alevel of detail that is sufficient for all foreseeable applications. To cover further possible applications, it should provide extension mechanisms. This last statement relates to <a href=#49>Design for language evolution</a>.
ID-127
##Multiple levels of abstractions 
A modeling language should provide concepts that allow for clearly distinguishing different levels of abstraction within a model. Mixing different levels of abstraction within a model compromises on model interpretation.
ID-128
##Clear language to target mapping 
There should be a clear mapping of the language concepts to the concepts of relevant target representations. It should be understandable and traceable how language concepts transform into target representations.
ID-25
##Turn API into DSL 
Turn an exisiting API into a DSL. If necessary, add a user-friendly notation to an exisiting API. This practice somehow contradicts with <a href=#49>a library is not a language</a>.

ID-26
##Strive for 80% solution 
Providing a 100% solution will often increase complexity of a language and introduce complicated language concepts. Strive for a 80% solution, which will gives end-users of the language enough time to manually solve the remaining 20%.
ID-29
##Care for longevity 
The DSL should be used and useful for a non-trivial period of time in order to ensure tool support, and to make it possible to quantify to the DSL. 
ID-31
##Care for scalabiltiy 
Your DSL might be used to create large scale description. Make sure that your solution scales to real world requirements. Modularization and <a href=9>library</a> concepts may be used to control size of single models.
ID-32
##Care for usability 
Space economy, accessibility, understandability -  are all characteristics that are desirable, and which may be partly covered by the core requirements.<a href=9> Perform usability evaluations</a> of language and tooling with end-users to assert usability.
ID-34
##Beware of misplaced emphasis 
Too strong emphasis on a particular domain concept may drive language design in an unwanted direction.
ID-33
##A library is not the language 
Do not overemphasize the target framework of a component library. This will drag abstraction level down and hinder retargeting. This often happens when domain frameworks and libraries are sources for language concepts. Make the problem domain itself the source! Conflicts with <a href=25>Turn API into language</a>.
ID-175
##Filter details from notational elements 
In graphical languages make use of filters to hide details from language elements. Show properties in separate property views.
ID-177
##Use colors 
Make use of colors to improve readability. For example colors can be used to emphasis different states or usages of a language element and highlight differences between different language elements.
ID-178
##Use transparency containments 
Use transparency to highlight containment relationships between language elements in graphical languages.
ID-179
##Derive notation from corporate identity 
Descriptions of corporate identity may hold important design guidelines for a language (e.g. usage of colors, fonts).
ID-180
##Ask graphic designers for help 
DSML development teams often comprise software engineers, language engineers, test experts, and domain experts. Infrequently these team members also have expertise in graphic design. Use professional services of graphic designers to polish your language and tooling. This can make a significant difference to your solution and improve adoption by end-users.
ID-19
##Use descriptive notations 
Descriptive notations support learnability and comprehensibility. Make use of descriptive notations to lower the threshold for end-users to adopt a language.
ID-20
##Usage of syntactic sugar 
The usage of syntactic sugar is important and can help to improve readability and domain specifity of a language. However, beware to distract end-user by overuse of syntactic sugar.
ID-24
##Transform visual to text 
Consider the transformation of of existing visual notations to textual noations. This may improve composition and compactness of models.
ID-27
##Use mixtuer of language notations 
Sometimes it is not only one kind of notation that is needed to express domain expertise. Consider using a mix of language notations to facilitate different requirements (e.g. a graphical notation for element composition and a textual notation for constraint definition).
ID-35
##Importance of meta-tooling 
The benefits of using language workbenches to create a DSL is reported by many. Effective meta-tools lead to faster, better and cheaper DSML development.
ID-36
##Importance of DSL-tooling 
Usage of a DSL must be supported by effictive tool support. Any language, no matter how good, benefits from strong tool support. Good tool support facilitates understandability, learnability, readability, writeability and maintainability of dsm models.
ID-186
##Use generators of varing granularity 
Provide generators of varying granularity. Generators may be provided for each modeling language, file type, or object type.
ID-72
##Incremental development 
Benefits of incremental development are in particular important for the development of domain-specific solutions. Incrementially expand the feature set of a DSML solution allows to integrate feedback from domain experts and adapt design decisions at an early stage of product development. 
ID-37
##Partition your meta-model 
Structure the overall meta-model into different model units. This eases language implementation and supports modularization of language models.
ID-45
##Don't modify generated code 
A general adivce from generative development approaches (e.g. model-driven software development), which is true for domain-specific modeling as well. Do not modify generated code. If manual adaptation is required, provide designs and architectures that support integration of generated and manually created code.
ID-51
##Simplify generators 
description
ID-59
##Use source-source transformation 
description
ID-58
##Restrict host language by specialization 
description
ID-61
##DSL preprocessing  
description
ID-62
##System front-end DSL for configuration 
description
ID-63
##Pipeline DSL processors 
description
ID-204
##Provide meta-metamodel 
description
ID-131
##Use constraint language in Meta-modeling 
description
ID-198
##Create proof of concepts to show benefits 
description
ID-200
##Follow inhouse standards 
description
ID-55
##Document your code 
description
ID-78
##Plan DSL usage reviews 
description
ID-65
##Identify DSL usage process 
description
ID-195
##Move duplicated code to domain framework 
description
ID-196
##Provide good API for generated code 
description
ID-43
##Domain specific frameworks 
description
ID-64
##Hide complexity in domain framework 
description
ID-176
##Provide user modes  
description
ID-38
##Identify usage convention 
description
ID-41
##Teamwork support 
description
ID-44
##Check constraints first 
description
ID-68
##Avoid debugging at source-code-level 
description
ID-111
##Target-Specific Generator Classes 
description
ID-183
##Turn DSM models into documenation 
description
ID-184
##Integrate handwritten code on file level 
description
ID-185
##Use autobuild for DSM models 
description
ID-189
##Parallel generators per prog. langugage 
description
ID-191
##One version for all 
description
ID-193
##Do not build generator to soon 
description
ID-114
##Generate all documents 
description
ID-122
##Stabilize design quickly 
description
ID-119
##Modularize transformations 
description
ID-120
##Consistent input to transformations 
description
ID-42
##Interpretation vs. code generation 
description
ID-46
##Control manually written code 
description
ID-47
##Care about generated code 
description
ID-48
##Make code true to the model 
description
ID-49
##Viewpoint aware processing 
description
ID-50
##Care about templates 
description
ID-56
##Effective Generators 
description
ID-66
##Avoid semiautomatic transformation 
description
ID-82
##Mapping grammars to recursive-descent reco 
description
ID-90
##Normalized Heterogeneous AST 
description
ID-91
##Irregular Heterogeneous AST 
description
ID-92
##Embedded Heterogeneous Tree Walker 
description
ID-93
##External Tree Visitor 
description
ID-94
##Tree Grammar 
description
ID-95
##Tree Pattern Matcher 
description
ID-96
##Symbol Table for Monolithic Scope 
description
ID-97
##Symbol Table for Nested Scopes 
description
ID-98
##Symbol Table for Data Aggregates 
description
ID-99
##Symbol Table for Classes 
description
ID-83
##LL(1) Recursive-Descent Lexer 
description
ID-100
##Computing Static Expression Types 
description
ID-101
##Automatic Type Promotion 
description
ID-102
##Enforcing Static Type Safety 
description
ID-103
##Enforcing Polymorphic Type Safety 
description
ID-104
##Syntax-Directed Interpreter 
description
ID-105
##Tree-Based Interpreter 
description
ID-106
##Bytecode Assembler 
description
ID-107
##Stack-Based Bytecode Interpreter 
description
ID-108
##Register-Based Bytecode Interpreter 
description
ID-109
##Syntax-Directed Translator 
description
ID-84
##LL(1) Recursive-Descent Parser 
description
ID-110
##Rule-Based Translator 
description
ID-85
##Backtracking Parser 
description
ID-86
##Memoizing Parser 
description
ID-87
##Predicated Parser 
description
ID-88
##Parse Tree 
description
ID-89
##Homogeneous AST 
description
ID-205
##Reuse mechanisms in metamodel 
description
ID-206
##Model sharing and splitting mechanisms 
description
ID-207
##Version your models 
description
ID-112
##Use DSL to enforce standards 
description
ID-39
##Syntax alignment of concepts 
description
ID-145
##Sematic Model 
description
ID-154
##Regex Table Lexer 
description
ID-155
##Recursive Descent Parser 
description
ID-156
##Parser Combinator 
description
ID-157
##Parser Generator 
description
ID-158
##Tree Construction 
description
ID-159
##Parser Embedded Translation 
description
ID-160
##Parser Embedded Interpretation 
description
ID-161
##Foreign Code 
description
ID-162
##Alternative Tokenization 
description
ID-163
##Nested operator expression 
description
ID-146
##Symbol Table 
description
ID-164
##Newline Separators 
description
ID-147
##Context Variable 
description
ID-148
##Construction Builder 
description
ID-149
##Macro: Transform input text 
description
ID-150
##Notification for meta-model 
description
ID-151
##Delimiter-Directed Translation 
description
ID-152
##Syntax-Directed Translation 
description
ID-153
##Formally define the syntax of your languag 
description
ID-141
##Atomic concept pattern 
description
ID-142
##Entitype pattern 
description
ID-143
##Deep configuration pattern 
description
ID-144
##Concept tailoring pattern 
description
ID-52
##Allow for adaptation 
description
ID-53
##Create annotation models 
description
ID-54
##Test your DSL 
description
ID-57
##Base implementation on usage 
description
ID-60
##Data-structure representation 
description
ID-67
##Avoid enforcing validation rules 
description
ID-81
##Separate language model from validation 
description
ID-81
##Piggyback 
description
ID-40
##Syntax agnostic layouts  
description
ID-132
##Instance representation for meta-models 
description
ID-130
##Common graphical notation for meta-tooling 
description
ID-74
##Provide training 
description
ID-77
##Understand and deal with your weaknesses  
description
ID-80
##Users do not overlook your mistakes 
description
ID-182
##Use tooling for model evolution 
description
ID-201
##Plan for evolution 
description
ID-123
##Expect redesign and plan 
description
ID-71
##Domain engineering team 
Consitute a team of domain engineers, domain experts, domain developers and language engineers. A good mix of expertise, e.g. from language engineering, domain engineering, domain knowledge, software engineering, or usability engineering leads to a specialized and dedicated team.
ID-75
##Iterative development 
description
ID-197
##DSM requires organization 
description
ID-76
##Treat DSM as product development 
description
ID-69
##Aquire language development expertise 
description
ID-70
##Fit technology transfer to business model 
description
ID-138
##Define cost-benefit of generator testing 
description
ID-139
##Use fuzzy testing 
Apply fuzzy testing to models. Approximately 10% of the randomly generated models reveal a defect of some kind.
ID-140
##Measure test coverage 
Measure test coverage for your solution.
ID-137
##Create DSLs for testing DSLs 
description
