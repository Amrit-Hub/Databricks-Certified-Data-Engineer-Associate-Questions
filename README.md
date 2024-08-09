# Databricks Certified Data Engineer Associate Questions v2 & v3

## Suggestions

- [Practice from these notebooks throroughly](/files/data-engineering-with-databricksv314.dbc) and below pdf
  * [de-mod-0-get-started-with-pyspark-programming](/files/de-mod-0-get-started-with-pyspark-programming.pdf)
  * [de-mod-1-get-started-with-databricks-data-science-and-engineering-workspace](/files/de-mod-1-get-started-with-databricks-data-science-and-engineering-workspace.pdf)
  * [de-mod-2-transform-data-with-spark](/files/de-mod-2-transform-data-with-spark.pdf)
  * [de-mod-3-manage-data-with-delta-lake](/files/de-mod-3-manage-data-with-delta-lake.pdf)
  * [de-mod-4-build-data-pipelines-with-delta-live-tables](/files/de-mod-4-build-data-pipelines-with-delta-live-tables.pdf)
  * [de-mod-5-deploy-workloads-with-databricks-workflows](/files/de-mod-5-deploy-workloads-with-databricks-workflows.pdf)
  * [Udemy Practice](https://www.udemy.com/course/practice-exams-databricks-certified-data-engineer-associate/)[You can try this. Use Udemy for Bussiness for free]
  * [Udemy Practice](https://www.udemy.com/course/databricks-certified-data-engineer-associate-practice-tests/)[You can try this. Use Udemy for Bussiness for free]
- Practice [&#34;PracticeExam&#34;](/files/PracticeExam-DataEngineerAssociate.pdf) questions available in this repo.
- Every options in [&#34;PracticeExam&#34;](/files/PracticeExam-DataEngineerAssociate.pdf) question becomes a question in actual exam.
- Read [Databricks Certified Associate Data Engineer Exam](/files/DatabricksCertifiedAssociateDataEngineerExam.pdf) thoroughly.
- Read [Manage data with delta lake](/files/de-mod-3-manage-data-with-delta-lake.pdf)
- Read [Build pipeline with DLT](/files/de-mod-4-build-data-pipelines-with-delta-live-tables.pdf)

Repo [link](https://github.com/Amrit-Hub/Databricks-Certified-Data-Engineer-Associate-Questions)

## Topics

1. What could cause data to be unavailable in Delta Lake, and how do commands like `VACUUM`, `MERGE`, or `OPTIMIZE` play a role?
2. How does Delta Lake become a single source of truth in a data architecture?
3. Does a Delta table contain single or multiple files for history, metadata, and data?
4. What are the advantages of using Delta Lake over a traditional data lake?
5. In Databricks architecture, which part does the web application belong to, and why? Control plane
6. What operations need to be performed outside a repository (e.g., pull, push, commit, clone)?
7. How does branching provide an advantage of using a repository over notebook versioning?
8. What makes Delta Lake ACID compliant?
9. How can you avoid duplicates during data processing  in Delta Lake? using the `MERGE` command
10. When to use the `INSERT OVERWRITE` command in Delta Lake?
11. How does Z-Ordering improve query performance in Delta Lake?
12. Why might the `COPY INTO` command not work in a specific code scenario? [reference](https://docs.databricks.com/sql/language-manual/delta-copy-into.html)
13. What is the difference between using `EXCEPT` or `DROP` on violation in Databricks Delta Live Tables (DLT)? [reference](https://docs.databricks.com/workflows/delta-live-tables/delta-live-tables-expectations.html)
14. When should you use the "Grant All" privileges in Unity Catalog?
15. When to use the "Grant Usage" privilege in Unity Catalog?
16. What are the advantages of using array functions in Spark?
17. How do you interpret `processingTime = "5 seconds"` in a Databricks streaming context?
18. Refer practice exam Question 36, particularly in a continuous production environment?
19. Which physical object should you create for 10 tables so that other teams can use them efficiently?
20. Delete metadata but retain the files in Delta Lake? when using an external table
21. When to use "Streaming Live" in a Databricks (refer to practice exam)?
22. How would you use the `COMMENT` statement to mark a table containing PII data in Databricks? Create table `<tbl>` comment "Contains PII"
23. How do you describe a database like `customer360` to retrieve its path in Databricks?
24. What is the advantage of using a gold table over a silver table in Delta Lake?
25. How do bronze tables differ from raw tables in Delta Lake?
26. Refer practice exam Question 31, particularly focusing on the transition from silver to bronze code?
27. How can you create a dependent task in a Delta Live Tables (DLT) pipeline?
28. What techniques can be used to speed up query execution in Databricks?
29. How can you prevent a particular block of code from running on Sundays?
30. Where can you view Data Quality metrics in a Delta Live Tables (DLT) pipeline?
31. How can you execute a Delta Live Tables (DLT) pipeline?
32. How can you save costs by using a serverless endpoint or by controlling DBU in a SQL warehouse?
33. How should you address a manager's concerns about over-costing after a project release, and what strategies can be used to save costs?
34. Refer practice exam Question 40
35. How does adding an auto-stop feature in a SQL endpoint reduce cluster costs?
36. Refer practice exam Question 1?
37. Refer practice exam Question 3?
38. What are the differences between using `spark.table("mytable")`, `spark.delta.table("mytable")`, and `spark.sql("mytable")` in PySpark?
39. What is the JDBC driver name for SQLite?
40. How would you create an `all_transaction` table from `march_transaction` and `april_transaction` tables without duplicates - using join, merge, or union?
41. Refer practice exam Question 27?
42. Refer practice exam Question 33?
43. How can you check the failed status of a task in a Delta Live Tables (DLT) pipeline?
44. For practice exam Question 42, when should you use a webhook or an email alert?
45. How can using cluster pools speed up query execution in Databricks?

## Lessons Learned

No matter what, please attempt the practice exam thoroughly. The answers in each question becomes another question. You will have ample amount of time during assessment.
