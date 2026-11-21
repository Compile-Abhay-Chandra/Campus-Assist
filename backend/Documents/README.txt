NORTHBRIDGE UNIVERSITY — RAG DEMO KNOWLEDGE BASE V3

Contents
--------
01_IT_Services_Handbook_v3.pdf
02_HR_Employee_Services_Handbook_v3.pdf
03_Student_Fees_Finance_Handbook_v3.pdf
04_Campus_Facilities_Handbook_v3.pdf
00_ROUTING_AND_EVALUATION_CATALOG.txt
router_test_cases.csv

Recommended metadata
--------------------
domain
document_id
document_type
section
effective_date
source_filename

Recommended chunking
--------------------
450–750 tokens per chunk
60–120 token overlap
Keep section heading and document ID in metadata.

Recommended retrieval output
-----------------------------
source document ID
section title
retrieved chunk
similarity/relevance score

Recommended evaluation metrics
------------------------------
Routing accuracy
Retrieval hit@k
Source/citation accuracy
Grounded answer accuracy
Clarification accuracy
Human-handoff accuracy
False-routing rate
End-to-end resolution rate
