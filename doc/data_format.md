# OIA Data Format 

* The data is serialized in jasonline format, with each line a sample. 

* Each sample has three fields: "meta", "words", and "oia".

    * The "meta" field contains the data source and the Uniform Resource Identifier(URI)

    * The "words" field contains the words in the sentence.

    * The "oia" field contains two list: "nodes" and "edges".
        - each node in "nodes" has two fields
            - the 'spans' field contains the context in the node, which could be
                - pre-defined predicate/function
                - the list of placeholders, additional (be) words, or start-end index pairs
            - 'type' field is the fine-grained node type
        - each edge in "edges" has three fields
            - start node index of the edge
            - end node index of the edge
            - the label of the edge
