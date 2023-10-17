{% assign branchPrefix = branchName | slice: 0, 2 %}
{% assign branchTitle = branchName | remove:'-' | slice: 2, branchName.size %}

## [{{branchPrefix}}] {{branchTitle | replace:'-',' '}}

**Description**

Provide a brief description of the changes made in this PR.
