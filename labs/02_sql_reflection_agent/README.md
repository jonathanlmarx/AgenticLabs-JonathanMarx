# 🧪 Lab 2 – Agentic SQL Generation with Reflection

This lab demonstrates an agentic SQL workflow that improves natural-language-to-SQL generation using reflection grounded in real execution results.

## Workflow Overview (V1 → V2)

1. Generate an initial SQL query (V1) from a natural-language question
2. Execute V1 against a SQLite database
3. Reflect on the actual query output (external feedback)
4. Identify semantic issues (e.g., sign errors)
5. Refine the SQL (V2) and re-execute to confirm correctness

## Key Insight

SQL that looks correct can still be semantically wrong.  
Execution-aware reflection enables agents to self-correct.

## Files

- `M2_SQL_Reflection_Workflow.ipynb` – full notebook workflow
- `products.db` – SQLite database (generated in notebook)
- `utils.py` – helper utilities

## Skills Demonstrated

- Agentic workflow design
- Reflection + external feedback
- Natural language → SQL generation
- Execution-grounded validation
