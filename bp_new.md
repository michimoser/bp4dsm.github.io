| ID | Name | Description | Phase |
|----|------|-------------|-------|
|2|Define domain scope| Define the appropriate domain scope of your solution. The scope of a DSM solution should be closely alined with business needs.|Analysis|
|3|Identify DSL usage| The early identification of language usage will have strong influence on language concepts. Precisely identify and describe usage of a domain specific language. Usages of a DSL in real world production scenarios are an important source of knowledge to support decisions in language design and implementation. |Analysis|
|135|Use end-user personas| The specification of needs of end-users in form of personas helps to reduce the distance to potential end-users. The use of personas are  a good mean to keep focused on the professional requirements and tasks of end-users not only during analysis phase but throughout the whole dsm project.|Analysis|
|134|Perform expert review| Ask usability experts for advice and apply heuristic review evaluation. In a heuristic evaluation, usability experts review interaction with the language and tooling and compare it to accepted usability principles.|Analysis|
|79|Do not overestimate domain experts| Do not expect the domain experts to know what the computer can (should) do for them; do not expect them to understand what it cannot possibly do for them! DSL designers need to aquire domain expertise by themself.|Analysis|
|4|Understand present solution| Understand the design of the present solution. This will allow to focus on the needed scope of a language and helps to mitigate the risk to over-design languages.|Analysis|
|6|Balance genericity and specialization| Find the right balance between genericity and specialization. Developers often create a language that is too generic. A generic language design and language concepts may facilitate reusability of a language and make it more robust to changing requirements. However, beware of reusing general purpose modeling languages. Adaptations for your special case will be necessary and your end-users must deal with complex language designs.|Design|
|5|Reuse language definitions| If suitable language exists try to reuse the language, do not reinvent the wheel! Sometimes existing language definitions can also be a good starting point. Most of the time is better to take what is already their than creating one from scratch.|Design|
|7|Adopt existing domain notations| A crucial step during requirement analysis is to learn how domain experts articulate and present problem and solution domain. Adopt existing notations (e.g. from domain experts, software, documentation). Inventing a new concrete syntax will raise the threshold for domain experts to pick up your language.|Design|
|9|Support model reuse on language level| Provide mechanisms that support reuse of models on language level. References between models, modularization or library concepts are a good starting point.|Design|
|8|Design must have purpose| All features of a language should support a purpose. The purpose of the language must be closely aligned with business needs.|Design|
|16|Design for language evolution| It is thus essential to allow extending the language at any time. Compilation to a target language like Java from a DSL and to generate end-user support for Utilize tool support to facilitate model evolution. Define what a “compatible” model change is and ensure all dependent designs follow this same model. Evolution. Need for language evolution. Minimize DSL changes which break existing models. Proactively manage language evolution. Do not postpone addition and extension of language concepts.|Design|
|10|Carefully choose form of notation| Often the choice for a certain type of notation (e.g. textual, graphical, tabular) is predetermined by experiences and expectations of different stakeholders. E.g. software engineers may favor a textual notation, or engineers in industrial automation expect graphical notations to create models. These decisions are often biased and should be questioned.|Design|
|13|Avoid redundancy| Avoid redundancy on a conceptual level. Redundancy is a constant source of problem. Having several concepts at hand gives users the possibility to create different models to describe the same fact.|Design|
|15|Viewpoint orientation| Identify different viewpoints on a software system. This may influence hwo you modularize a DSL. Different concerns of stakeholders can be separated by using a viewpoint oriented approach. Moreover, the identified viewpoints can help to structure implementation. See <a href=#49>viewpoint aware processing</a>.|Design|
|28|Provide Integrability| Ensure that the DSL and associated tooling can be integrated with existing frameworks and languages. Choose integrability over extensibility. If possible, it is best to provide integration mechanisms on model level (e.g. base integration on metamodel).|Design|
|14|Make elements distinquishable| In graphical languages different elements should exhibit enough syntactic differences. There are more possibilities than changing the color of elements (e.g. shape, behavior, docking).|Design|
|22|Consistent style everywhere| Be consistent on language elements. In graphical languages a consistent use of color, icons, shapes, or connectability has a huge impact on usability of a language.|Design|
|18|Limit nr. of language elements| Languages with hundreds of different language elements are hard to read, comprehend and to use. Try to avoid this by creating new sub-languages providing functionality via library mechanisms.|Design|
|171|Support variability on language level| Drive your language design by focusing on variabilities. Provide mechanisms which handle variability on language level. Rather that having separate elements for representing variants, core language concepts should be designed to handle variabilities.|Design|
|11|Reuse type systems| Designing a type system can be hard. Therefore, if possible reuse existing type system semantic. This not only eases language design but to assure comprehensibility and avoid errors. An unconventional type system may be hard to adpot for users which have been exposed to conventional type system in other languages.|Design|
|12|Keep it simple| Keep a language simple. A language should be as simple as possible in order to express the concepts of interest and to support its users and stakeholders in their preferred ways of working. So again, keep it simple!|Design|
|73|Effective process for DSML definition| Use well established practices to provide an effective DSML definition process. |Design|
|30|Care for quality| Care for quality on all levels. Quality of the provided language, DSML tool support and the target systems which built using your DSM solution.|Design|
|136|Perform usability evaluations| Usability evaluations provide valuable feedback for the design of both the notation as well as the tool interaction. Usability evaluations during early project phases provide have a strong influence on the design of a language. Use techniques like paper prototypes to perform evaluations if no runnable software is available.|Design|
|172|Create guidelines for language definition| Guidelines are important and help new project members to adopt a proven development process. Guideline may support a wide range of development activities from naming and styling of elements, over application of best practice, to documentation issues.|Design|
|173|Define language rules| Define language usage rules and communicate these rules to your users. Provide automatic consistency checks for rules, constraints.|Design|
|165|Derive concepts from physical structure| Derive language concepts and presentation from the physical structures of the real world objects the represent.|Design|
|166|Derive concepts from Look&Feel| Derive language concepts and presentation from the look and feel of real world systems.|Design|
|199|First things first: The language| The language is the most important part of a DSM solution. So do it first.|Design|
|168|Derive concepts from domain expert concepts| Derive the concepts of a language from the concepts domain experts using your solutions share.|Design|
|169|Derive concepts from expected output| Analyse and structure the expected output of your DSML solution. Discussing expected output with domain experts will highlight concepts needed on language level.|Design|
|170|Reuse existing computational model| Reuse existing computational models.|Design|
|21|Balance compactness and understandability| Finding a good balance between compactness and understandability is an important property of a language. Comprehensibility may be provided by precise naming and representations. However, restrain the language of being to verbose.|Design|
|23|Interface concept| DSLs should provide an interface concept similar to interfaces as known from programming languages.|Design|
|124|Precise high-level abstraction| Use precise, high-level abstractions in the metamodel.|Design|
|125|Detect recurring patterns in design| Watch out for recurring patterns when performing modeling. These may indicate that the metamodel needs to be modified.|Design|
|17|Compose existing languages| The development of a language and associated tooling is labor-intensive. Often languages exist which match certain requirements in your language. Composing your language by embedding existing languages can reduce the effort for language creation. OCL is a good example to that, it can be embedded in other languages to define constraints on elements.|Design|
|126|Provide sufficient level of detail| The concepts of a language should allow for modeling at alevel of detail that is sufficient for all foreseeable applications. To cover further possible applications, it should provide extension mechanisms. This last statement relates to <a href=#49>Design for language evolution</a>.|Design|
|127|Multiple levels of abstractions| A modeling language should provide concepts that allow for clearly distinguishing different levels of abstraction within a model. Mixing different levels of abstraction within a model compromises on model interpretation.|Design|
|128|Clear language to target mapping| There should be a clear mapping of the language concepts to the concepts of relevant target representations. It should be understandable and traceable how language concepts transform into target representations.|Design|
|25|Turn API into DSL| Turn an existing API into a DSL. If necessary, add a user-friendly notation to an existing API. This practice somehow contradicts with <a href=#49>a library is not a language</a>.|Design|
|26|Strive for 80% solution| Providing a 100% solution will often increase complexity of a language and introduce complicated language concepts. Strive for a 80% solution, which will gives end-users of the language enough time to manually solve the remaining 20%.|Design|
|29|Care for longevity| The DSL should be used and useful for a non-trivial period of time in order to ensure tool support, and to make it possible to quantify to the DSL. |Design|
|31|Care for scalabiltiy| Your DSL might be used to create large scale description. Make sure that your solution scales to real world requirements. Modularization and <a href=9>library</a> concepts may be used to control size of single models.|Design|
|32|Care for usability| Space economy, accessibility, understandability -  are all characteristics that are desirable, and which may be partly covered by the core requirements.<a href=9> Perform usability evaluations</a> of language and tooling with end-users to assert usability.|Design|
|34|Beware of misplaced emphasis| Too strong emphasis on a particular domain concept may drive language design in an unwanted direction.|Design|
|33|A library is not the language| Do not overemphasize the target framework of a component library. This will drag abstraction level down and hinder retargeting. This often happens when domain frameworks and libraries are sources for language concepts. Make the problem domain itself the source! Conflicts with <a href=25>Turn API into language</a>.|Design|
|175|Filter details from notational elements| In graphical languages make use of filters to hide details from language elements. Show properties in separate property views.|Design|
|177|Use colors| Make use of colors to improve readability. For example colors can be used to emphasis different states or usages of a language element and highlight differences between different language elements.|Design|
|178|Use transparency containments| Use transparency to highlight containment relationships between language elements in graphical languages.|Design|
|179|Derive notation from corporate identity| Descriptions of corporate identity may hold important design guidelines for a language (e.g. usage of colors, fonts).|Design|
|180|Ask graphic designers for help| DSML development teams often comprise software engineers, language engineers, test experts, and domain experts. Infrequently these team members also have expertise in graphic design. Use professional services of graphic designers to polish your language and tooling. This can make a significant difference to your solution and improve adoption by end-users.|Design|
|19|Use descriptive notations| Descriptive notations support learnability and comprehensibility. Make use of descriptive notations to lower the threshold for end-users to adopt a language.|Design|
|20|Usage of syntactic sugar| The usage of syntactic sugar is important and can help to improve readability and domain specifity of a language. However, beware to distract end-user by overuse of syntactic sugar.|Design|
|24|Transform visual to text| Consider the transformation of of existing visual notations to textual notations. This may improve composition and compactness of models.|Design|
|27|Use mixture of language notations| Sometimes it is not only one kind of notation that is needed to express domain expertise. Consider using a mix of language notations to facilitate different requirements (e.g. a graphical notation for element composition and a textual notation for constraint definition).|Design|
|35|Importance of meta-tooling| The benefits of using language workbenches to create a DSL is reported by many. Effective meta-tools lead to faster, better and cheaper DSML development.|Implementation|
|36|Importance of DSL-tooling| Usage of a DSL must be supported by effective tool support. Any language, no matter how good, benefits from strong tool support. Good tool support facilitates understandability, learnability, readability, writeability and maintainability of dsm models.|Implementation|
|186|Use generators of varying granularity| Provide generators of varying granularity. Generators may be provided for each modeling language, file type, or object type.|Implementation|
|72|Incremental development| Benefits of incremental development are in particular important for the development of domain-specific solutions. Incrementally  expand the feature set of a DSML solution allows to integrate feedback from domain experts and adapt design decisions at an early stage of product development. |Implementation|
|37|Partition your meta-model| Structure the overall meta-model into different model units. This eases language implementation and supports modularization of language models.|Implementation|
|45|Don't modify generated code| A general advice from generative development approaches (e.g. model-driven software development), which is true for domain-specific modeling as well. Do not modify generated code. If manual adaptation is required, provide designs and architectures that support integration of generated and manually created code.|Implementation|
|51|Simplify generators by M2M transformations| An general observation in DSM and model-driven approaches is, that generators tend to become complicated. Try to simplify generation by preprocessing input models. Use model-2-model transformations to provide generators with models which are easier to process.|Implementation|
|59|Use source-source transformation| Source-to-source transformation can be used to ease the burden of DSL implementation. When the DSL cannot be designed as a language extension, specialisation, or using the piggyback pattern, it is often possible to leverage the facilities provided by existing language tools using a source-to-source transformation technique. The tools available for the existing language are then used to host ± compile or interpret the code generated by the transformation.  process.|Implementation|
|58|Restrict host language by specialization| If parts of an existing language should be reused, try to restrict the host language by specialization to  targeted at the problem domain. |Implementation|
|61|DSL preprocessing| A pattern which can be used in piggyback. A language preprocessor filters elements and passes relevant elements to the existing host language.|Implementation|
|62|System front-end DSL for configuration| description|Implementation|
|63|Pipeline DSL processors| Each DSL handles its own language elements and passes the rest down to the others. Solves Problem of DSL composition. Supports best practice <a href=12>Keep it simple</a>.|Implementation|
|204|Provide metamodel| Use a metamodel for language design. A metamodel can leverage language development and improve language provide means for systematic language evolution.|Implementation|
|131|Use constraint language in Meta-modeling| The concepts of a metamodeling language should be supplemented by a language for specifying constraints on language elements. This facilitates efficient constraint definition and later verification by software components.|Implementation|
|198|Create proof of concepts to show benefits| Moving an organization from traditional software development towards model-based approaches takes time. To show benefits of DSM and to dismantle prejudices it is a good approach to build a short proof of concept project. Goal is to build a small but still significant part of the DSM solution. |Implementation|
|200|Follow in-house standards| The DSM solution should follow/respect in-house standards.|Implementation|
|55|Documentation needed| Communicate to users how the DSL and generators work. Documentation targets are language structure and syntax, how to use the editors and the generators, how and where to write manual code and how to integrate it.|Implementation|
|78|Plan DSL usage reviews| Similar to usability evaluations usage reviews provided valuable feedback from your users. Plan these usage reviews in advance and stick to your plan.|Implementation|
|65|Identify DSL usage process| description|Implementation|
|195|Move duplicated code to domain framework| Duplicated code hints functionality that should be moved to domain frameworks.|Implementation|
|196|Provide good API for generated code| The generated code needs to interact with a domain framework. These interactions are created by your generators. The better the API of a domain framework the easier for generators to generate respective code.|Implementation|
|43|Domain specific frameworks| Code generation is good, but make use of a rich domain-specific framework. Try to move duplicated code to domain frameworks. Relates to <a href="">Hide complexity in domain framework </a> and <a href="">Move duplicated code to domain framework </a>.|Implementation|
|64|Hide complexity in domain framework| Try to hide complexity in domain frameworks. This makes development of code generators more efficient and improves readability of the generated code.|Implementation|
|176|Provide user modes| Provide different user modes according to the experience of users. Modes may adapt tooling support and provide hints to novice users. Moreover, modes could be used to filter language concepts according to tasks users need to transform. |Implementation|
|38|Define usage convention| Not everything has to be enforced by language design. Try to define language usage conventions. This may produce simpler language designs and facilitate flexible language usage.|Implementation|
|41|Teamwork support| Just like any other software development approach, DSM must care for teamwork support. Models written in a DSL must be versioned, tagged and evolved in a team setting. DSL tooling must facilitate team support.|Implementation|
|44|Check constraints first| description|Implementation|
|68|Avoid debugging at source-code-level| description|Implementation|
|111|Target-Specific Generator Classes| description|Implementation|
|183|Turn DSM models into documentation| description|Implementation|
|184|Integrate handwritten code on file level| description|Implementation|
|185|Use autobuild for DSM models| description|Implementation|
|189|Parallel generators per prog. langugage| description|Implementation|
|191|One version for all| description|Implementation|
|193|Do not build generator to soon| description|Implementation|
|114|Generate all documents| description|Implementation|
|122|Stabilize design quickly| description|Implementation|
|119|Modularize transformations| description|Implementation|
|120|Consistent input to transformations| description|Implementation|
|42|Interpretation vs. code generation| description|Implementation|
|46|Control manually written code| description|Implementation|
|47|Care about generated code| description|Implementation|
|48|Make code true to the model| description|Implementation|
|49|Viewpoint aware processing| description|Implementation|
|50|Care about templates| description|Implementation|
|56|Effective Generators| description|Implementation|
|66|Avoid semiautomatic transformation| description|Implementation|
|82|Mapping grammars to recursive-descent reco| description|Implementation|
|90|Normalized Heterogeneous AST| description|Implementation|
|91|Irregular Heterogeneous AST| description|Implementation|
|92|Embedded Heterogeneous Tree Walker| description|Implementation|
|93|External Tree Visitor| description|Implementation|
|94|Tree Grammar| description|Implementation|
|95|Tree Pattern Matcher| description|Implementation|
|96|Symbol Table for Monolithic Scope| description|Implementation|
|97|Symbol Table for Nested Scopes| description|Implementation|
|98|Symbol Table for Data Aggregates| description|Implementation|
|99|Symbol Table for Classes| description|Implementation|
|83|LL(1) Recursive-Descent Lexer| description|Implementation|
|100|Computing Static Expression Types| description|Implementation|
|101|Automatic Type Promotion| description|Implementation|
|102|Enforcing Static Type Safety| description|Implementation|
|103|Enforcing Polymorphic Type Safety| description|Implementation|
|104|Syntax-Directed Interpreter| description|Implementation|
|105|Tree-Based Interpreter| description|Implementation|
|106|Bytecode Assembler| description|Implementation|
|107|Stack-Based Bytecode Interpreter| description|Implementation|
|108|Register-Based Bytecode Interpreter| description|Implementation|
|109|Syntax-Directed Translator| description|Implementation|
|84|LL(1) Recursive-Descent Parser| description|Implementation|
|110|Rule-Based Translator| description|Implementation|
|85|Backtracking Parser| description|Implementation|
|86|Memoizing Parser| description|Implementation|
|87|Predicated Parser| description|Implementation|
|88|Parse Tree| description|Implementation|
|89|Homogeneous AST| description|Implementation|
|205|Reuse mechanisms in metamodel| description|Implementation|
|206|Model sharing and splitting mechanisms| description|Implementation|
|207|Version your models| description|Implementation|
|112|Use DSL to enforce standards| description|Implementation|
|39|Syntax alignment of concepts| description|Implementation|
|145|Semantic Model| description|Implementation|
|154|Regex Table Lexer| description|Implementation|
|155|Recursive Descent Parser| description|Implementation|
|156|Parser Combinator| description|Implementation|
|157|Parser Generator| description|Implementation|
|158|Tree Construction| description|Implementation|
|159|Parser Embedded Translation| description|Implementation|
|160|Parser Embedded Interpretation| description|Implementation|
|161|Foreign Code| description|Implementation|
|162|Alternative Tokenization| description|Implementation|
|163|Nested operator expression| description|Implementation|
|146|Symbol Table| description|Implementation|
|164|Newline Separators| description|Implementation|
|147|Context Variable| description|Implementation|
|148|Construction Builder| description|Implementation|
|149|Macro: Transform input text| description|Implementation|
|150|Notification for meta-model| description|Implementation|
|151|Delimiter-Directed Translation| description|Implementation|
|152|Syntax-Directed Translation| description|Implementation|
|153|Formally define the syntax of your languag| description|Implementation|
|141|Atomic concept pattern| description|Implementation|
|142|Entitype pattern| description|Implementation|
|143|Deep configuration pattern| description|Implementation|
|144|Concept tailoring pattern| description|Implementation|
|52|Allow for adaptation| description|Implementation|
|53|Create annotation models| description|Implementation|
|54|Test your DSL| description|Implementation|
|57|Base implementation on usage| description|Implementation|
|60|Data-structure representation| description|Implementation|
|67|Avoid enforcing validation rules| description|Implementation|
|81|Separate language model from validation| description|Implementation|
|81|Separate language model from validation| description|Implementation|
|40|Syntax agnostic layouts| description|Implementation|
|132|Instance representation for meta-models| description|Implementation|
|130|Common graphical notation for meta-tooling| description|Implementation|
|74|Provide training| Even if a DSL uses domain concepts and is intuitive to use, users must be trained. It is a worst practice in DSM to not train end-users in using a DSL and the provided DSL tooling during introductory phases of a project.|Maint.|
|77|Understand and deal with your weaknesses| A general advice which is even more true for DSL development; Analyse the problems and errors you encounter and make a plan to deal with those problems.|Maint.|
|80|Users do not overlook your mistakes| Do not expect users to settle with weak and confusing designs. Especially, if promise is given that it will be "cleaned up in the final version". Provide a process that assures that shortcomings are resolved.|Maint.|
|182|Use tooling for model evolution| description|Maint.|
|201|Plan for evolution| description|Maint.|
|123|Expect redesign and plan| Take major redesign of a language into account and plan for it. Leave explicit time slots in project schedules for redesign of languages, generators and generated code.|Maint.|
|71|Domain engineering team| Constitute a team of domain engineers, domain experts, domain developers and language engineers. A good mix of expertise, e.g. from language engineering, domain engineering, domain knowledge, software engineering, or usability engineering leads to a specialized and dedicated team.|Plan|
|75|Iterative development| The creation of languages is no waterfall process. Viewing the initial language version as unalterable is a bad habit. Iterative development with short iterations, clearly defined milestones, accessible deliverables, and frequent feedback from different stakeholders are a means to improve DMS development.|Plan|
|197|DSM requires organization| description|Plan|
|76|Treat DSM as product development| Organize teams for DSM development as a product teams and domain user teams. The product teams develope languages, frameworks, and tooling. Domain teams apply the DSM solutions. Try to have short feedback loops from domain team to product teams. Even exchange people (i.e. domain experts) between teams from time to time.|Plan|
|69|Acquire language development expertise| Development of a DSL is a complex task and requires skilled experts in language engineering. For in-house DSML development consider hiring experts.|Plan|
|70|Fit technology transfer to business model| Assure that the required technology transfer of a DSM solution into cooperation infrastructure fits the cooperations business model. Minor problems during technology transfer in introductory phases can jeopardize overall acceptance of the DSM solution.|Plan|
|138|Define cost-benefit of generator testing| Different testing strategies for generators may substantially vary in effort. Make sure to provide test strategies which provide a good cost-benefit ratio. Try to use different testing strategies depending on your testing goals.|Test|
|139|Use fuzzy testing| Apply fuzzy testing of models. Fuzzy testing proved to be a very effective means to synthesize valid models and to discover robustness defects. Approximately 10% of the randomly generated models reveal a defect of some kind.|Test|
|140|Measure test coverage| Measure test coverage for your DSM solution. As in general software development projects test coverage directs test development and reveals yet uncovered parts.|Test|
|137|Create DSLs for testing DSLs| Create DSLs which are specifically designed for DSL testing. Effective ways for testing different language definition aspects (e.g. type system, checking rules) help to increase testing efficiency.|Test|
