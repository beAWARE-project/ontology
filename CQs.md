# Competency Questions

This is a list of all the Competency Questions (CQs) that the ontology should be able to respond to.

CQ# | Competency Question | SPARQL
--- | ------------------- | ------
CQ1-1 | Which natural disasters may lead to natural disaster [X]? | `SELECT ?disaster ?location`<br/>`WHERE {`<br/>&nbsp;&nbsp;&nbsp;&nbsp;`?disaster rdf:type ba:NaturalDisaster .`<br/>&nbsp;&nbsp;&nbsp;&nbsp;`?location rdf:type ba:Location .`<br/>&nbsp;&nbsp;&nbsp;&nbsp;`?disaster ba:hasDisasterLocation ?location .`<br/>`}`
CQ2-1 | Which natural disasters may lead to natural disaster [X]? | `if (isAwesome){  return true}`

