# CCS-Architecture-Decision-Records
CCS will record here all architecture decision records:
 - that need to be agreed at TDDA 
 - that apply to more than one project
 - where those decisions are _not_ considered sensitive 

Project specific records can be stored in a separate repository. See, for instance, 
[DataSubmissionService-ADRs](https://github.com/Crown-Commercial-Service/DataSubmissionService-ADRs).

Non sensitive records :(which are preferred) are stored in the 
[sinsitive ADR repository](https://github.com/Crown-Commercial-Service/CCS-Architecture-Decision-Records-Sensitive)

## Process

1. All Architecture decision records that are considered sensitive should be mastered here. 
1. records should be marked ADR-XXXX-\<name>
1. Some diagrams are stored in .dot file format - they need to be converted to `jpg` format.

## Structure

```
/doc/adr - adr files
/doc/diagrams - .dot diagram source files
/doc/images - images generated from .dot files for linking into ADRs.
```

### Diagrams

As an experiment we will store some diagrams in [.dot](https://www.graphviz.org/documentation/) language. 
That allows us to change control diagrams. But it adds a generation stage which we can incorporate into our build pipeline.
Until then we can generate the files via command lines or web tools.

