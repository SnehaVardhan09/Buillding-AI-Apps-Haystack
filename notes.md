https://github.com/deepset-ai/haystack/tree/main
1.**Introduction**

* Framework vs entire app from scratch. From scratch gives you great learning experience and full control over every step, Using Framework makes our job done faster and gives you abstractions that make your code more maintainable and readable.
* Few difficulties in GenAI tech - Integrate APIs from different providers of LMS, better databases,  stiching them together to make the workflow, framework allows us to focus more on developing your apps at a higher level of abstraction

* Common Interface and a simple abstraction
* Based on two main elements *Components* & *Pipelines*


2. Haystack Building Blocks:

* Combining Components into full pipelines
* Components - Building Blocks
             - Perform tasks such as preprocessing, retrieving, or summarizing text
             - Generators / Embedders / Retrievers / Converters / Rankers / Routers / Preprocessing 
             - Can create our own components

* Pipelines Powerful components + easy way to put them together

2. **Haystack Building Blocks**
* About Components - How to run them individually
                   - How to combine them into full pipelines

* How to build pipelines - Document search pipelines 
`indexing pipeline` , `document search pipeline`



ERRORs:
1. Failed to import transformers.modeling_tf_utils because of the following error (look up to see its traceback): No module named 'tensorflow'
   uninstalled and installed tensorflow
