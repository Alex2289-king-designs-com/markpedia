# Anti-pattern

An **anti-pattern** is a common response to a recurring problem that is
usually ineffective and risks being highly counterproductive.
The term, coined in 1995 by [Andrew
Koenig](Andrew_Koenig_(programmer).md), was inspired by a
book, [Design Patterns](Design_Patterns_(book).md), which
highlights a number of [design patterns](design_pattern.md) in
[software development](software_development.md) that its authors
considered to be highly reliable and effective.

The term was popularized three years later by the book
[AntiPatterns](AntiPatterns.md), which extended its use beyond
the field of software design to refer informally to any commonly
reinvented but bad solution to a problem. Examples include [analysis
paralysis](Analysis_paralysis.md), [cargo cult
programming](Cargo_cult_programming.md), [death
march](Death_march_(software_development).md),
[groupthink](Groupthink.md) and [vendor
lock-in](Vendor_lock-in.md).

## Definition

According to the authors of *Design Patterns*, there must be at least
two key elements present to formally distinguish an actual anti-pattern
from a simple bad habit, bad practice, or bad idea:

1.  A commonly used process, structure, or pattern of action that
    despite initially appearing to be an appropriate and effective
    response to a problem, has more bad consequences than good ones.
2.  Another solution exists that is documented, repeatable, and proven
    to be effective.

## Examples

#### Organizational

-   [Analysis paralysis](Analysis_paralysis.md): A project
    stalled in the analysis phase, unable to achieve support for any of
    the potential plans of approach
-   [Bicycle shed](Parkinson's_law_of_triviality.md): Giving
    disproportionate weight to trivial issues
-   [Bleeding edge](Bleeding_edge.md): Operating with
    cutting-edge technologies that are still untested or unstable
    leading to cost overruns, under-performance or delayed delivery
-   [Bystander apathy](Bystander_apathy.md): The phenomenon in
    which people are less likely to or do not offer help to a person in
    need when others are present
-   [Cash cow](Cash_cow.md): A profitable legacy product that
    often leads to complacency about new products
-   [Design by committee](Design_by_committee.md): The result of
    having many contributors to a design, but no unifying vision
-   [Escalation of commitment](Escalation_of_commitment.md):
    Failing to revoke a decision when it proves wrong
-   [Groupthink](Groupthink.md): A collective state where group
    members begin to (often unknowingly) think alike and reject
    differing viewpoints
-   [Management by objectives](Management_by_objectives.md):
    Management by numbers, focus exclusively on quantitative management
    criteria, when these are non-essential or cost too much to acquire
-   [Micromanagement](Micromanagement.md): Ineffectiveness from
    excessive observation, supervision, or other hands-on involvement
    from management
-   [Moral hazard](Moral_hazard.md): Insulating a decision-maker
    from the consequences of their decision
-   [Mushroom management](Mushroom_management.md): Keeping
    employees \"in the dark and fed manure\" (also \"left to stew and
    finally canned\")
-   [Peter principle](Peter_principle.md): Continually promoting
    otherwise well-performing employees up to their level of
    incompetence, where they remain indefinitely
-   [Seagull management](Seagull_manager.md): Management in
    which managers only interact with employees when a problem arises,
    when they \"fly in, make a lot of noise, dump on everyone, do not
    solve the problem, then fly out\"
-   [Stovepipe or Silos](Stovepipe_(organisation).md): An
    organizational structure of isolated or semi-isolated teams, in
    which too many communications take place up and down the hierarchy,
    rather than directly with other teams across the organization
-   [Typecasting](Typecasting_(acting).md): Locking successful
    employees into overly safe, narrowly defined, predictable roles
    based on their past successes rather than their potential
-   [Vendor lock-in](Vendor_lock-in.md): Making a system
    excessively dependent on an externally supplied component

#### Project management

-   [Cart before the horse](Cart_before_the_horse.md): Focusing
    too many resources on a stage of a project out of its sequence
-   [Death march](Death_march_(software_development).md): A
    project whose staff, while expecting it to fail, are compelled to
    continue, often with much overwork, by management which is in
    denial
-   [Ninety-ninety rule](Ninety-ninety_rule.md): Tendency to
    underestimate the amount of time to complete a project when it is
    \"nearly done\"
-   [Overengineering](Overengineering.md): Spending resources
    making a project more robust and complex than is needed
-   [Scope creep](Scope_creep.md): Uncontrolled changes or
    continuous growth in a project\'s scope, or adding new features to
    the project after the original requirements have been drafted and
    accepted (also known as requirement creep and [feature
    creep](Feature_creep.md))
-   [Smoke and mirrors](Smoke_and_mirrors.md): Demonstrating
    unimplemented functions as if they were already implemented
-   [Brooks\'s law](Brooks's_law.md): Adding more resources to a
    project to increase velocity, when the project is already slowed
    down by coordination overhead.

### Software engineering

#### Software design

-   [Abstraction inversion](Abstraction_inversion.md): Not
    exposing implemented functionality required by callers of a
    function/method/constructor, so that the calling code awkwardly
    re-implements the same functionality in terms of those calls
-   [Ambiguous viewpoint](Ambiguous_viewpoint.md): Presenting a
    model (usually [Object-oriented analysis and
    design](Object-oriented_analysis_and_design.md) (OOAD))
    without specifying its viewpoint
-   [Big ball of mud](Big_ball_of_mud.md): A system with no
    recognizable structure
-   [Database-as-IPC](Database-as-IPC.md): Using a database as
    the message queue for routine [interprocess
    communication](Inter-process_communication.md) where a much
    more lightweight mechanism would be suitable
-   [Gold plating](Gold_plating_(analogy).md): Continuing to
    work on a task or project well past the point at which extra effort
    is not adding value
-   [Inner-platform effect](Inner-platform_effect.md): A system
    so customizable as to become a poor replica of the software
    development platform
-   [Input kludge](Input_kludge.md): Failing to specify and
    implement the handling of possibly invalid input
-   [Interface bloat](Interface_bloat.md): Making an interface
    so powerful that it is extremely difficult to implement
-   [Magic pushbutton](Magic_pushbutton.md): A form with no
    dynamic validation or input assistance, such as dropdowns
-   [Race hazard](Race_hazard.md): Failing to see the
    consequences of events that can sometimes interfere with each other
-   [Stovepipe system](Stovepipe_system.md): A barely
    maintainable assemblage of ill-related components

#### Object-oriented programming

-   [Anemic domain model](Anemic_domain_model.md): The use of
    the [domain model](Domain_model.md) without any [business
    logic](Business_logic.md). The domain model\'s objects
    cannot guarantee their correctness at any moment, because their
    validation and mutation logic is placed somewhere outside (most
    likely in multiple places). Martin Fowler considers this to be an
    anti-pattern, but some disagree that it is always an
    anti-pattern.
-   [Call super](Call_super.md): Requiring subclasses to call a
    superclass\'s overridden method
-   [Circle-ellipse problem](Circle-ellipse_problem.md):
    [Subtyping](Subtype.md) variable-types on the basis of
    value-subtypes
-   [Circular dependency](Circular_dependency.md): Introducing
    unnecessary direct or indirect mutual dependencies between objects
    or software modules
-   [Constant interface](Constant_interface.md): Using
    interfaces to define constants
-   [God object](God_object.md): Concentrating too many
    functions in a single part of the design (class)
-   [Object cesspool](Object_cesspool.md): Reusing objects whose
    state does not conform to the (possibly implicit) contract for
    re-use
-   [Object orgy](Object_orgy.md): Failing to properly
    encapsulate objects permitting unrestricted access to their
    internals
-   [Poltergeists](Poltergeist_(computer_science).md): Objects
    whose sole purpose is to pass information to another object
-   [Sequential coupling](Sequential_coupling.md): A class that
    requires its methods to be called in a particular order
-   [Yo-yo problem](Yo-yo_problem.md): A structure (e.g., of
    inheritance) that is hard to understand due to excessive
    fragmentation

#### Programming

-   [Accidental complexity](Accidental_complexity.md):
    Programming tasks which could be eliminated with better tools (as
    opposed to essential complexity inherent in the problem being
    solved)
-   [Action at a
    distance](Action_at_a_distance_(computer_science).md"):
    Unexpected interaction between widely separated parts of a system
-   [Boat anchor](Boat_anchor_(computer_science).md): Retaining
    a part of a system that no longer has any use
-   [Busy waiting](Busy_waiting.md): Consuming
    [CPU](CPU.md) while waiting for something to happen, usually
    by repeated checking instead of messaging
-   [Caching failure](Caching_failure.md): Forgetting to clear a
    cache that holds a negative result (error) after the error condition
    has been corrected
-   [Cargo cult programming](Cargo_cult_programming.md): Using
    patterns and methods without understanding why
-   [Coding by exception](Coding_by_exception.md): Adding new
    code to handle each special case as it is recognized
-   [Design pattern](Design_pattern.md): The use of patterns has
    itself been called an anti-pattern, a sign that a system is not
    employing enough
    [abstraction](Abstraction_principle_(computer_programming).md)
-   [Error hiding](Error_hiding.md): Catching an error message
    before it can be shown to the user and either showing nothing or
    showing a meaningless message. This anti-pattern is also named
    *Diaper Pattern*. Also can refer to erasing the [Stack
    trace](Stack_trace.md) during exception handling, which can
    hamper debugging.
-   [Hard code](Hard_code.md): Embedding assumptions about the
    environment of a system in its implementation
-   [Lasagna code](Spaghetti_code#Lasagna_code.md): Programs
    whose structure consists of too many layers of inheritance
-   [Lava flow](Lava_flow_(programming).md): Retaining
    undesirable (redundant or low-quality) code because removing it is
    too expensive or has unpredictable consequences
-   [Loop-switch sequence](Loop-switch_sequence.md): Encoding a
    set of sequential steps using a switch within a loop statement
-   [Magic
    numbers](Magic_number_(programming)#Unnamed_numerical_constants.md"):
    Including unexplained numbers in algorithms
-   [Magic
    strings](Magic_string_(programming)#Magic_strings_in_code.md"):
    Implementing presumably unlikely input scenarios, such as
    comparisons with very specific strings, to mask functionality.
-   [Repeating yourself](Don't_Repeat_Yourself.md): Writing code
    which contains repetitive patterns and substrings over again; avoid
    with [once and only once](Once_and_only_once.md)
    (abstraction principle)
-   [Shooting the messenger](Shooting_the_messenger.md):
    Throwing exceptions from the scope of a plugin or subscriber in
    response to legitimate input, especially when this causes the outer
    scope to fail.
-   [Shotgun surgery](Shotgun_surgery.md): Developer adds
    features to an application codebase which span a multiplicity of
    implementors or implementations in a single change
-   [Soft code](Softcoding.md): Storing business logic in
    configuration files rather than source code
-   [Spaghetti code](Spaghetti_code.md): Programs whose
    structure is barely comprehensible, especially because of misuse of
    code structures

#### Methodological

-   [Copy and paste programming](Copy_and_paste_programming.md):
    Copying (and modifying) existing code rather than creating generic
    solutions
-   [Every Fool Their Own Tool](Every_Fool_His_Own_Tool.md):
    Failing to use proper software development principles when creating
    tools to facilitate the software development process
    itself.
-   [Golden hammer](Golden_hammer.md): Assuming that a favorite
    solution is universally applicable (See: [Silver
    bullet](Silver_bullet.md))
-   [Improbability factor](Improbability_factor.md): Assuming
    that it is improbable that a known error will occur
-   [Invented here](Invented_here.md): The tendency towards
    dismissing any innovation or less than trivial solution originating
    from inside the organization, usually because of lack of confidence
    in the staff
-   [Not Invented Here](Not_Invented_Here#In_computing.md) (NIH)
    syndrome: The tendency towards [reinventing the
    wheel](Reinventing_the_wheel.md) (failing to adopt an
    existing, adequate solution)
-   [Premature
    optimization](Optimization_(computer_science)#When_to_optimize.md):
    Coding early-on for perceived efficiency, sacrificing good design,
    maintainability, and sometimes even real-world efficiency
-   [Programming by permutation](Programming_by_permutation.md)
    (or \"programming by accident\", or \"programming by coincidence\"):
    Trying to approach a solution by successively modifying the code to
    see if it works
-   [Reinventing the square
    wheel](Reinventing_the_square_wheel.md): Failing to adopt an
    existing solution and instead adopting a custom solution which
    performs much worse than the existing one
-   [Silver bullet](No_Silver_Bullet.md): Assuming that a
    favorite technical solution can solve a larger process or problem
-   [Tester Driven Development](Tester_Driven_Development.md):
    Software projects in which new requirements are specified in bug
    reports

#### Configuration management

-   [Dependency hell](Dependency_hell.md): Problems with
    versions of required products
-   [DLL hell](DLL_hell.md): Inadequate management of
    [dynamic-link libraries](Dynamic-link_libraries.md) (DLLs),
    specifically on [Microsoft Windows](Microsoft_Windows.md)
-   [Extension conflict](Extension_conflict.md): Problems with
    different extensions to [classic Mac OS](Classic_Mac_OS.md)
    attempting to patch the same parts of the operating system
-   [JAR hell](JAR_hell.md): Overutilization of multiple
    [JAR](JAR_(file_format).md) files, usually causing
    versioning and location problems because of misunderstanding of the
    [Java class loading](Java_Classloader.md) model

## See also

-   [Code smell](Code_smell.md) -- symptom of unsound
    programming
-   [Design smell](Design_smell.md)
-   [List of software development
    philosophies](List_of_software_development_philosophies.md)
    -- approaches, styles, maxims and philosophies for software
    development
-   [Software Peter principle](Software_Peter_principle.md)
-   [Capability Immaturity
    Model](Capability_Immaturity_Model.md)
-   [ISO 29110](ISO_29110.md): Software Life Cycle Profiles and
    Guidelines for Very Small Entities (VSEs)
-   [The Innovator\'s Dilemma](The_Innovator's_Dilemma.md)

# External links

-   [Anti-pattern](http://c2.com/cgi/wiki?AntiPattern) at
    [WikiWikiWeb](WikiWikiWeb.md)
-   [Anti-patterns catalog](http://c2.com/cgi/wiki?AntiPatternsCatalog)
-   [AntiPatterns.com](http://www.antipatterns.com) Web site for the
    [AntiPatterns](AntiPatterns.md) book
-   [Patterns of Toxic
    Behavior](http://www.personal.psu.edu/cjn6/Personal/Antipatterns-%20Patterns%20of%20Toxic%20Behavior.htm)
-   [C Pointer
    Antipattern](https://docs.google.com/document/d/160BsSq4J46Ds3KZVnX2zMnxc_oZMk-nrnI9srrdk6Ro/pub)
-   [Email Anti-Patterns](https://leanpub.com/email-antipatterns/) book
-   [Patterns of Social
    Domination](http://publicsphereproject.org/anti-patterns/)
