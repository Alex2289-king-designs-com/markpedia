```{=mediawiki}
{{short description|Common response to a recurring problem that is usually ineffective or counterproductive}}
```
An **anti-pattern** is a common response to a recurring problem that is
usually ineffective and risks being highly counterproductive.[^1][^2]
The term, coined in 1995 by [Andrew
Koenig](Andrew_Koenig_(programmer) "wikilink"),[^3] was inspired by a
book, *[Design Patterns](Design_Patterns_(book) "wikilink")*, which
highlights a number of [design patterns](design_pattern "wikilink") in
[software development](software_development "wikilink") that its authors
considered to be highly reliable and effective.

The term was popularized three years later by the book
*[AntiPatterns](AntiPatterns "wikilink")*, which extended its use beyond
the field of software design to refer informally to any commonly
reinvented but bad solution to a problem. Examples include [analysis
paralysis](analysis_paralysis "wikilink"), [cargo cult
programming](cargo_cult_programming "wikilink"), [death
march](death_march_(software_development) "wikilink"),
[groupthink](groupthink "wikilink") and [vendor
lock-in](vendor_lock-in "wikilink").

Definition
----------

According to the authors of *Design Patterns*, there must be at least
two key elements present to formally distinguish an actual anti-pattern
from a simple bad habit, bad practice, or bad idea:

1.  A commonly used process, structure, or pattern of action that
    despite initially appearing to be an appropriate and effective
    response to a problem, has more bad consequences than good ones.
2.  Another solution exists that is documented, repeatable, and proven
    to be effective.

Examples
--------

### Social and business operations {#social_and_business_operations}

#### Organizational

-   [Analysis paralysis](Analysis_paralysis "wikilink"): A project
    stalled in the analysis phase, unable to achieve support for any of
    the potential plans of approach
-   [Bicycle shed](Parkinson's_law_of_triviality "wikilink"): Giving
    disproportionate weight to trivial issues
-   [Bleeding edge](Bleeding_edge "wikilink"): Operating with
    cutting-edge technologies that are still untested or unstable
    leading to cost overruns, under-performance or delayed delivery
-   [Bystander apathy](Bystander_apathy "wikilink"): The phenomenon in
    which people are less likely to or do not offer help to a person in
    need when others are present
-   [Cash cow](Cash_cow "wikilink"): A profitable legacy product that
    often leads to complacency about new products
-   [Design by committee](Design_by_committee "wikilink"): The result of
    having many contributors to a design, but no unifying vision
-   [Escalation of commitment](Escalation_of_commitment "wikilink"):
    Failing to revoke a decision when it proves wrong
-   [Groupthink](Groupthink "wikilink"): A collective state where group
    members begin to (often unknowingly) think alike and reject
    differing viewpoints
-   [Management by objectives](Management_by_objectives "wikilink"):
    Management by numbers, focus exclusively on quantitative management
    criteria, when these are non-essential or cost too much to acquire
-   [Micromanagement](Micromanagement "wikilink"): Ineffectiveness from
    excessive observation, supervision, or other hands-on involvement
    from management
-   [Moral hazard](Moral_hazard "wikilink"): Insulating a decision-maker
    from the consequences of their decision
-   [Mushroom management](Mushroom_management "wikilink"): Keeping
    employees \"in the dark and fed manure\" (also \"left to stew and
    finally canned\")
-   [Peter principle](Peter_principle "wikilink"): Continually promoting
    otherwise well-performing employees up to their level of
    incompetence, where they remain indefinitely[^4]
-   [Seagull management](Seagull_manager "wikilink"): Management in
    which managers only interact with employees when a problem arises,
    when they \"fly in, make a lot of noise, dump on everyone, do not
    solve the problem, then fly out\"
-   [Stovepipe or Silos](Stovepipe_(organisation) "wikilink"): An
    organizational structure of isolated or semi-isolated teams, in
    which too many communications take place up and down the hierarchy,
    rather than directly with other teams across the organization
-   [Typecasting](Typecasting_(acting) "wikilink"): Locking successful
    employees into overly safe, narrowly defined, predictable roles
    based on their past successes rather than their potential
-   [Vendor lock-in](Vendor_lock-in "wikilink"): Making a system
    excessively dependent on an externally supplied component

#### Project management {#project_management}

-   [Cart before the horse](Cart_before_the_horse "wikilink"): Focusing
    too many resources on a stage of a project out of its sequence
-   [Death march](Death_march_(software_development) "wikilink"): A
    project whose staff, while expecting it to fail, are compelled to
    continue, often with much overwork, by management which is in
    denial[^5]
-   [Ninety-ninety rule](Ninety-ninety_rule "wikilink"): Tendency to
    underestimate the amount of time to complete a project when it is
    \"nearly done\"
-   [Overengineering](Overengineering "wikilink"): Spending resources
    making a project more robust and complex than is needed
-   [Scope creep](Scope_creep "wikilink"): Uncontrolled changes or
    continuous growth in a project\'s scope, or adding new features to
    the project after the original requirements have been drafted and
    accepted (also known as requirement creep and [feature
    creep](feature_creep "wikilink"))
-   [Smoke and mirrors](Smoke_and_mirrors "wikilink"): Demonstrating
    unimplemented functions as if they were already implemented
-   [Brooks\'s law](Brooks's_law "wikilink"): Adding more resources to a
    project to increase velocity, when the project is already slowed
    down by coordination overhead.

### Software engineering {#software_engineering}

#### Software design {#software_design}

<span id="General design anti-patterns"></span>

-   [Abstraction inversion](Abstraction_inversion "wikilink"): Not
    exposing implemented functionality required by callers of a
    function/method/constructor, so that the calling code awkwardly
    re-implements the same functionality in terms of those calls
-   [Ambiguous viewpoint](Ambiguous_viewpoint "wikilink"): Presenting a
    model (usually [Object-oriented analysis and
    design](Object-oriented_analysis_and_design "wikilink") (OOAD))
    without specifying its viewpoint
-   [Big ball of mud](Big_ball_of_mud "wikilink"): A system with no
    recognizable structure
-   [Database-as-IPC](Database-as-IPC "wikilink"): Using a database as
    the message queue for routine [interprocess
    communication](Inter-process_communication "wikilink") where a much
    more lightweight mechanism would be suitable
-   [Gold plating](Gold_plating_(analogy) "wikilink"): Continuing to
    work on a task or project well past the point at which extra effort
    is not adding value
-   [Inner-platform effect](Inner-platform_effect "wikilink"): A system
    so customizable as to become a poor replica of the software
    development platform
-   [Input kludge](Input_kludge "wikilink"): Failing to specify and
    implement the handling of possibly invalid input
-   [Interface bloat](Interface_bloat "wikilink"): Making an interface
    so powerful that it is extremely difficult to implement
-   [Magic pushbutton](Magic_pushbutton "wikilink"): A form with no
    dynamic validation or input assistance, such as dropdowns
-   [Race hazard](Race_hazard "wikilink"): Failing to see the
    consequences of events that can sometimes interfere with each other
-   [Stovepipe system](Stovepipe_system "wikilink"): A barely
    maintainable assemblage of ill-related components

#### Object-oriented programming {#object_oriented_programming}

-   [Anemic domain model](Anemic_domain_model "wikilink"): The use of
    the [domain model](domain_model "wikilink") without any [business
    logic](business_logic "wikilink"). The domain model\'s objects
    cannot guarantee their correctness at any moment, because their
    validation and mutation logic is placed somewhere outside (most
    likely in multiple places). Martin Fowler considers this to be an
    anti-pattern, but some disagree that it is always an
    anti-pattern.[^6]
-   [Call super](Call_super "wikilink"): Requiring subclasses to call a
    superclass\'s overridden method
-   [Circle-ellipse problem](Circle-ellipse_problem "wikilink"):
    [Subtyping](Subtype "wikilink") variable-types on the basis of
    value-subtypes
-   [Circular dependency](Circular_dependency "wikilink"): Introducing
    unnecessary direct or indirect mutual dependencies between objects
    or software modules
-   [Constant interface](Constant_interface "wikilink"): Using
    interfaces to define constants
-   [God object](God_object "wikilink"): Concentrating too many
    functions in a single part of the design (class)
-   [Object cesspool](Object_cesspool "wikilink"): Reusing objects whose
    state does not conform to the (possibly implicit) contract for
    re-use
-   [Object orgy](Object_orgy "wikilink"): Failing to properly
    encapsulate objects permitting unrestricted access to their
    internals
-   [Poltergeists](Poltergeist_(computer_science) "wikilink"): Objects
    whose sole purpose is to pass information to another object
-   [Sequential coupling](Sequential_coupling "wikilink"): A class that
    requires its methods to be called in a particular order
-   [Yo-yo problem](Yo-yo_problem "wikilink"): A structure (e.g., of
    inheritance) that is hard to understand due to excessive
    fragmentation

#### Programming

-   [Accidental complexity](Accidental_complexity "wikilink"):
    Programming tasks which could be eliminated with better tools (as
    opposed to essential complexity inherent in the problem being
    solved)
-   [Action at a
    distance](Action_at_a_distance_(computer_science) "wikilink"):
    Unexpected interaction between widely separated parts of a system
-   [Boat anchor](Boat_anchor_(computer_science) "wikilink"): Retaining
    a part of a system that no longer has any use
-   [Busy waiting](Busy_waiting "wikilink"): Consuming
    [CPU](CPU "wikilink") while waiting for something to happen, usually
    by repeated checking instead of messaging
-   [Caching failure](Caching_failure "wikilink"): Forgetting to clear a
    cache that holds a negative result (error) after the error condition
    has been corrected
-   [Cargo cult programming](Cargo_cult_programming "wikilink"): Using
    patterns and methods without understanding why
-   [Coding by exception](Coding_by_exception "wikilink"): Adding new
    code to handle each special case as it is recognized
-   [Design pattern](Design_pattern "wikilink"): The use of patterns has
    itself been called an anti-pattern, a sign that a system is not
    employing enough
    [abstraction](Abstraction_principle_(computer_programming) "wikilink")[^7]
-   [Error hiding](Error_hiding "wikilink"): Catching an error message
    before it can be shown to the user and either showing nothing or
    showing a meaningless message. This anti-pattern is also named
    *Diaper Pattern*. Also can refer to erasing the [Stack
    trace](Stack_trace "wikilink") during exception handling, which can
    hamper debugging.
-   [Hard code](Hard_code "wikilink"): Embedding assumptions about the
    environment of a system in its implementation
-   [Lasagna code](Spaghetti_code#Lasagna_code "wikilink"): Programs
    whose structure consists of too many layers of inheritance
-   [Lava flow](Lava_flow_(programming) "wikilink"): Retaining
    undesirable (redundant or low-quality) code because removing it is
    too expensive or has unpredictable consequences[^8][^9]
-   [Loop-switch sequence](Loop-switch_sequence "wikilink"): Encoding a
    set of sequential steps using a switch within a loop statement
-   [Magic
    numbers](Magic_number_(programming)#Unnamed_numerical_constants "wikilink"):
    Including unexplained numbers in algorithms
-   [Magic
    strings](Magic_string_(programming)#Magic_strings_in_code "wikilink"):
    Implementing presumably unlikely input scenarios, such as
    comparisons with very specific strings, to mask functionality.
-   [Repeating yourself](Don't_Repeat_Yourself "wikilink"): Writing code
    which contains repetitive patterns and substrings over again; avoid
    with [once and only once](once_and_only_once "wikilink")
    (abstraction principle)
-   [Shooting the messenger](Shooting_the_messenger "wikilink"):
    Throwing exceptions from the scope of a plugin or subscriber in
    response to legitimate input, especially when this causes the outer
    scope to fail.
-   [Shotgun surgery](Shotgun_surgery "wikilink"): Developer adds
    features to an application codebase which span a multiplicity of
    implementors or implementations in a single change
-   [Soft code](Softcoding "wikilink"): Storing business logic in
    configuration files rather than source code[^10]
-   [Spaghetti code](Spaghetti_code "wikilink"): Programs whose
    structure is barely comprehensible, especially because of misuse of
    code structures

#### Methodological

-   [Copy and paste programming](Copy_and_paste_programming "wikilink"):
    Copying (and modifying) existing code rather than creating generic
    solutions
-   [Every Fool Their Own Tool](Every_Fool_His_Own_Tool "wikilink"):
    Failing to use proper software development principles when creating
    tools to facilitate the software development process
    itself.[^11]`{{Original research inline|date=March 2018}}`{=mediawiki}
-   [Golden hammer](Golden_hammer "wikilink"): Assuming that a favorite
    solution is universally applicable (See: [Silver
    bullet](Silver_bullet "wikilink"))
-   [Improbability factor](Improbability_factor "wikilink"): Assuming
    that it is improbable that a known error will occur
-   [Invented here](Invented_here "wikilink"): The tendency towards
    dismissing any innovation or less than trivial solution originating
    from inside the organization, usually because of lack of confidence
    in the staff
-   [Not Invented Here](Not_Invented_Here#In_computing "wikilink") (NIH)
    syndrome: The tendency towards *[reinventing the
    wheel](reinventing_the_wheel "wikilink")* (failing to adopt an
    existing, adequate solution)
-   [Premature
    optimization](Optimization_(computer_science)#When_to_optimize "wikilink"):
    Coding early-on for perceived efficiency, sacrificing good design,
    maintainability, and sometimes even real-world efficiency
-   [Programming by permutation](Programming_by_permutation "wikilink")
    (or \"programming by accident\", or \"programming by coincidence\"):
    Trying to approach a solution by successively modifying the code to
    see if it works
-   [Reinventing the square
    wheel](Reinventing_the_square_wheel "wikilink"): Failing to adopt an
    existing solution and instead adopting a custom solution which
    performs much worse than the existing one
-   [Silver bullet](No_Silver_Bullet "wikilink"): Assuming that a
    favorite technical solution can solve a larger process or problem
-   [Tester Driven Development](Tester_Driven_Development "wikilink"):
    Software projects in which new requirements are specified in bug
    reports

#### Configuration management {#configuration_management}

-   [Dependency hell](Dependency_hell "wikilink"): Problems with
    versions of required products
-   [DLL hell](DLL_hell "wikilink"): Inadequate management of
    [dynamic-link libraries](dynamic-link_libraries "wikilink") (DLLs),
    specifically on [Microsoft Windows](Microsoft_Windows "wikilink")
-   [Extension conflict](Extension_conflict "wikilink"): Problems with
    different extensions to [classic Mac OS](classic_Mac_OS "wikilink")
    attempting to patch the same parts of the operating system
-   [JAR hell](JAR_hell "wikilink"): Overutilization of multiple
    [JAR](JAR_(file_format) "wikilink") files, usually causing
    versioning and location problems because of misunderstanding of the
    [Java class loading](Java_Classloader "wikilink") model

See also {#see_also}
--------

-   [Code smell](Code_smell "wikilink") -- symptom of unsound
    programming
-   [Design smell](Design_smell "wikilink")
-   [List of software development
    philosophies](List_of_software_development_philosophies "wikilink")
    -- approaches, styles, maxims and philosophies for software
    development
-   [Software Peter principle](Software_Peter_principle "wikilink")
-   [Capability Immaturity
    Model](Capability_Immaturity_Model "wikilink")
-   [ISO 29110](ISO_29110 "wikilink"): Software Life Cycle Profiles and
    Guidelines for Very Small Entities (VSEs)
-   *[The Innovator\'s Dilemma](The_Innovator's_Dilemma "wikilink")*

References
----------

```{=mediawiki}
{{reflist|30em}}
```
Further reading {#further_reading}
---------------

1.  ```{=mediawiki}
    {{cite book |last1=Laplante |first1=Phillip A. |last2=Neill |first2=Colin J. |year=2005 |title=Antipatterns: Identification, Refactoring and Management |publisher=Auerbach Publications |isbn=0-8493-2994-9}}
    ```
2.  ```{=mediawiki}
    {{cite book |last1=Brown |first1=William J. |last2=Malveau |first2=Raphael C. |last3=McCormick |first3=Hays W. |last4=Thomas |first4=Scott W. |editor-last=Hudson |editor-first=Theresa Hudson |title=Anti-Patterns in Project Management |publisher=[[John Wiley & Sons]] |year=2000 |isbn=0-471-36366-9}}
    ```

External links {#external_links}
--------------

```{=mediawiki}
{{Commonscat|Anti-patterns}}
```
-   [Anti-pattern](http://c2.com/cgi/wiki?AntiPattern) at
    [WikiWikiWeb](WikiWikiWeb "wikilink")
-   [Anti-patterns catalog](http://c2.com/cgi/wiki?AntiPatternsCatalog)
-   [AntiPatterns.com](http://www.antipatterns.com) Web site for the
    [AntiPatterns](AntiPatterns "wikilink") book
-   [Patterns of Toxic
    Behavior](http://www.personal.psu.edu/cjn6/Personal/Antipatterns-%20Patterns%20of%20Toxic%20Behavior.htm)
-   [C Pointer
    Antipattern](https://docs.google.com/document/d/160BsSq4J46Ds3KZVnX2zMnxc_oZMk-nrnI9srrdk6Ro/pub)
-   [Email Anti-Patterns](https://leanpub.com/email-antipatterns/) book
-   [Patterns of Social
    Domination](http://publicsphereproject.org/anti-patterns/)

[ ](Category:Anti-patterns "wikilink") [Category:Software
architecture](Category:Software_architecture "wikilink")
[Category:Design](Category:Design "wikilink") [Category:Industrial and
organizational
psychology](Category:Industrial_and_organizational_psychology "wikilink")
[Category:Organizational
behavior](Category:Organizational_behavior "wikilink")
[Category:Anti-social
behaviour](Category:Anti-social_behaviour "wikilink")
[Category:Workplace](Category:Workplace "wikilink")

[^1]: `{{Cite book
     | author=Budgen, D.
     | title=Software design
     | year=2003
     | publisher=Addison-Wesley
     | location=Harlow, Eng.
     | isbn=0-201-72219-4
     | page=225
     | url=https://books.google.com/books?id=bnY3vb606bAC&pg=PA225&dq=%22anti-pattern%22+date:1990-2003
    }}`{=mediawiki} \"As described in Long (2001), design anti-patterns
    are \'obvious, but wrong, solutions to recurring problems\'.\"

[^2]: `{{Cite book
     | author= [[Scott W. Ambler]]
     | title=Process patterns: building large-scale systems using object technology
     | year=1998
     | publisher=Cambridge University Press
     | location=Cambridge, UK
     | isbn=0-521-64568-9
     | page=4
     | url=https://books.google.com/books?id=qJJk2yEeoZoC&pg=PA4&dq=%22anti-pattern%22+date:1990-2001
    }}`{=mediawiki} \"\...common approaches to solving recurring
    problems that prove to be ineffective. These approaches are called
    antipatterns.\"

[^3]: `{{cite journal|title=Patterns and Antipatterns|journal=Journal of Object-Oriented Programming|date=March–April 1995|first=Andrew|last=Koenig|volume=8 |issue=1|pages=46–48|id= |url=|format= }}`{=mediawiki};
    was later re-printed in the: `{{Cite book
     | author=Rising, Linda
     | title=The patterns handbook: techniques, strategies, and applications
     | year=1998
     | publisher=Cambridge University Press
     | location=Cambridge, U.K.
     | isbn=0-521-64818-1
     | page=387
     | url=https://books.google.com/books?id=HBAuixGMYWEC&pg=PT1&dq=0-521-64818-1
    }}`{=mediawiki} \"An antipattern is just like a pattern, except that
    instead of a solution it gives something that looks superficially
    like a solution, but isn\'t one.\"

[^4]: Peter, Lawrence J. (1969), *The Peter Principle: Why Things Always
    Go Wrong*; 1969 Buccaneer Books,
    `{{ISBN|9781568491615}}`{=mediawiki}

[^5]: Yourdon, Edward (1997), *Death March*;
    `{{ISBN|978-0137483105}}`{=mediawiki}

[^6]: `{{Cite web|url = https://blog.inf.ed.ac.uk/sapm/2014/02/04/the-anaemic-domain-model-is-no-anti-pattern-its-a-solid-design/|title = The Anaemic Domain Model is no Anti-Pattern, it’s a SOLID design|date = 4 February 2014|accessdate = 3 January 2015|website = SAPM: Course blog|publisher = |last = |first = }}`{=mediawiki}

[^7]: `{{cite web|url=http://www.paulgraham.com/icad.html|title=Revenge of the Nerds|quote=In the OO world you hear a good deal about "patterns". I wonder if these patterns are not sometimes evidence of case (c), the human compiler, at work. When I see patterns in my programs, I consider it a sign of trouble. The shape of a program should reflect only the problem it needs to solve. Any other regularity in the code is a sign, to me at least, that I'm using abstractions that aren't powerful enough— often that I'm generating by hand the expansions of some macro that I need to write.}}`{=mediawiki}

[^8]: [Lava Flow](http://www.antipatterns.com/lavaflow.htm) at
    antipatterns.com

[^9]: `{{cite web |url=http://www.icmgworld.com/corp/news/Articles/RS/jan_0202.asp |title=Undocumented 'lava flow' antipatterns complicate process |publisher=Icmgworld.com |date=14 January 2002 |accessdate=3 May 2010 |archive-url=https://web.archive.org/web/20110311103207/http://www.icmgworld.com/corp/news/Articles/RS/jan_0202.asp |archive-date=11 March 2011 |dead-url=yes }}`{=mediawiki}

[^10]: `{{cite web |last=Papadimoulis |first=Alex |url=http://thedailywtf.com/Articles/Soft_Coding.aspx |title=Soft Coding |publisher=thedailywtf.com |date=10 April 2007 |accessdate=27 June 2011}}`{=mediawiki}

[^11]: `{{cite web|url=https://www.linkedin.com/pulse/every-fool-his-own-tool-marcel-heemskerk-msc-scea|title=Every Fool His Own Tool|author=|date=23 January 2017|website=linkedin.com}}`{=mediawiki}
