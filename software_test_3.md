# software pricing

-   theoretically, it is simply the cost of development + profit
-   in practise, broader organizational, economic, political and bussinuess
    considerations are taken into account

### factors

1. market opportunity
    - quote lower price to enter new segment
    - accept low profit on one project make greater
      profit later
2. cost estimate uncertainity
    - pricing contingency
3. contract terms
    - ownership of source code
4. requirement volatility
    - price lower intially
    - charge higher for changes
5. financial health
    - better to make low profit than to got out of bussinuess
    - cash flow important in difficult economy

# version management

1. version and release identification
    - version tags
    - consistent naming
    - attributes with versions (mobile, smallscreen etc.)
2. storage management
    - efficient storage of changes
3. change history recording
4. independent development
    - keeps track of components
    - changes made to components by different developers don't interfere
5. project support
    - development of several projects which share components
    - check-in/out all files associated with projects at once

# config management

concerned with policies, process and tools for managing software systems

1. change management
    - track software change requests
    - decide when change should be implemneted
2. version management
    - keep track of multiple versions
    - components from different developers don't interfere
3. system builing
4. release managemen

# system building

-   create complete executable by compiling, linking the system components,
    external libs, config files, build tools and version management tools.
-   tools must communicate as build process involves checking out source code from vcs

### features

1. build script generation
    - should also support manual creation
2. version management system integration
    - checkout required version from vcs
3. minimal recompilation
4. executable creation
    - compiled object files
5. testing automation
6. error reporting
7. documentation generation

# release planning

### factors

1. technical quality
    - serious fault
    - OTA patches
2. platform change
    - new release on OS change
3. competition
    - new features to retain market shared
4. marketing requirements
    - commitment to make release on time
5. lehman's 5th Law
    - adding new functionality results in bugs
    - if system released with lot of new functionality,
      then it will be followed with releases that focus on repairs
      and performance
6. customer change proposal

# inspection checklist

### Types of faults

1. data
    - variable initialization
    - constants
    - array bounds
    - string delimiter
    - buffer overflow
2. control
    - are if-else condition correct?
    - infinite loops
    - brackets around compound statements
    - switch-case exhaustiveness
    - switch-case break statements
3. I/O
    - are all i/p variables used?
    - are all output variables assigned?
    - unexpected inputs
4. interface
    - number, order and data type of parameters
    - shared memory structure
5. storage management
    - internal links to other objects should be correctly re-assigned
    - dynamic memory allocation pitfalls
6. exception management

# prototypes

### process

1. establish objectives > prototype plan
2. define functionality > outline definition
3. develop > executable prototype
4. evaluate > evaluation report

### benifits

1. citation and validation of system requirements
2. explore solutions

### meant to be thrown away

because proto generally:

1. don't meet non-functional requirements (performance, security etc.)
2. undocumented
3. degraded system structure
4. low quality standard

# extreme programming

1. incremental planning
    - story cards or developmental tasks
    - choose cards based on time availability.
2. small releases
    - minimal functionality that produce bussinuess value
3. simple design
    - enough to meet requirements
4. write tests before implementation
5. pair programing
6. collective ownership
7. continuous integration..
    - integrate code into system frequently
8. sustainable pace
    - no large overtime

# SCRUM

1. structures development in cycles of work called "sprints"
2. doesn't prescribe test-first development and pair programming

### phases

1. outline planning
2. sprint cycles
    - assess
    - select
    - review
    - develop
3. project closure
    - docs
    - user manuals
    - lessons learned

### key characteristics

1. fix-length, 2-4 week sprints
2. product backlog (list of work)
3. selection of features to be developed during sprints
4. work presented to stakeholders

### advantages

1. effective use of time and money
2. project divided into easily managable sprints
3. developments are coded and tested during sprint review
4. works well for fast-moving projects
5. team gets clear visibility through SCRUM meetings
6. scrum is agile -- adopts feedback from customers and stakeholders
7. short sprints make change feedback easy
8. individual effort of each team member visible

# agile

### principles

1. customer involvement
2. incremental delivery
3. people, not process
    - recognize technical skills of all team members
    - allow team members to develop their own ways of working
4. embrace change
5. maintain simplicity

### perspective on scaling agile methods

1. scaling up
    - for large software system, that can't be developed by small team
2. scaling out
    - introduction into large organization

### for large systems engineering

1. inexpeienced project managers may be reluctant
2. bureaucratic nature incompatible with agile
    - QC checks and standards are integrated into tools and are mandatory
3. only works best in teams with high skill level.
    - organizations have mixed skills
    - low skill level member may not be effective in agile
4. cultural resistance
    - especially in organization where conventional processes are used
