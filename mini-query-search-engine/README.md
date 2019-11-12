# Instruction on the use of query_search_mapreducer
1. Check the availability of document files in the "datafiles" folder.
2. Check the availability of the query file and stopwords file in the project directory. Both of them should be in .txt format.
3. In the terminal, redirect to the current project directory.
4. Enter the command: python query_search_mapreducer.py query.txt no_of_docs_required.
5. Take note that 3 arguments are to be provided in terminal: name of script file, name of the query file, no of relevant documents required. Required no of relevant documents should not exceed the amount of documents in the "datafiles" folder.