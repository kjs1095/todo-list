# Pull Request Template


## Reviewer

@mentions of the person or the team responsible for reviewing proposed changes.


## Type of Change

Please delete options that are not relevant.<br/>
You can create a new option if none of the below are applicable.

- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ] Code refactoring (improve readability and reduce complexity without affecting the external behavior)
- [ ] Document update (changes on nonfunctional files)
- [ ] This change requires a documentation update


## Description

For issue fix: please add a summary of the change, which issue is fixed, and a reference to the related issue.<br/>
For feature addition: please add a summary of the feature and its functionality.<br/>
For documentation changes: please add a summary of the change.<br/>
List of dependencies that may be required for this change.<br/>

- [ ] Fixes # (issue)
- [ ] Features # (function)
- [ ] Dependencies # (list)
- [ ] Reference # (issue)
- [ ] [Optional] Relevant motivation and context

**Example**<br/>

- [x] **Fix (issue #2266)**<br/>

**Subject:**<br/>
Routing path metadata loading crash issue<br/>
**Summary:**<br/>
Calling the routing path metadata loader API may cause the system to crash if the parquet file does not exist in the path or a wrong path is given.<br/>
Adding an exception handler to the loader API to resolve this issue.<br/>
**Reference:**<br/>
Issues _*#2266*_, _*#978*_, _*#8740*_


## Tests

Please describe the tests that you ran to verify your changes.<br/> 
Instructions for reproducing your results.<br/>
List any relevant details for your test configuration.

- Test X
    - Details ...
- Test Y
    - Details ...

**Unit Test Report**:

+ Normal case
+ Corner case
+ Failed case


## Checklist:

- [ ] Code follows the style guidelines
- [ ] Performed a self-review of the code
- [ ] Included comments in the code, particularly in the hard-to-understand areas
- [ ] Made corresponding changes to the documentation
- [ ] New changes generate no new warnings
- [ ] Added tests that prove the fix is effective or the new feature works
- [ ] Any dependent changes have been merged and published in downstream modules


## Impacted Areas in the Project:

Please list components that this PR will affect.

- Component A
- Component B


## Deploy Notes

Notes regarding deployment of the contained body of work.<br/>
These should note any database migrations, etc.


