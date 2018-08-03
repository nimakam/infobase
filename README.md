# Mindbase
An implementation of the information-base (infobase) concept, similar to a [database](https://en.wikipedia.org/wiki/Database), but more intuitive and flexible for human interaction scenarios. 

# Infobase
Information-base is an organized collection of information, similar to a [database](https://en.wikipedia.org/wiki/Database), that follows intuitive patterns of the mind in terms of its inner workings, as well as its interface with external systems and users. An infobase instance functions in similar ways as a human's understanding and communication functions.Thus, more intuitive applications and user experiences can be built on top of an infobase, and the costs of ramp-up, implementation and support by real people is reduced substancially. Afterall, information systems based on databases and software are implemented and managed by real people, and that makes up a majority of their costs and limitations. There is a significant opportunity in reducing said costs and limitations.

Databases store and index data in document or relational formats, and can be queried using abstract expressions. However they often rely on the application layer to make sense of these data structures, and to map them to separate user interfaces for user interactions and service APIs for system interaction. Infobase instances on the other hand, store, process and "understand" information, following similar patterns as the human mind, and can therefore answer natural language questions.

For example, for a simple personal work item tracking scneario, a database stores task information in relational or document-based format with fixed schema. Developers then build the application layer separately, and translate these schemas to the UI in a way end users would understand. An infobase, on the other hand, would record and index the work items based on discovery, subsequent events affecting information objects over time, similar to how a mind records events related to things. An infobase has enough information about discovery, events and relations between information objects, to "understand" (through learning, supervised or otherwise,) the moving parts of these objects and how they relate to other information objects. As a result, the infobase will be able to present an understandable user interface to users, as well as to systems.

## Example
Let's lay out the above example in more detail. The infobase first learns of "work items", that they have certain properties, and that they should be represented in a certain way to external agents, from a modelling interaction, typically performed by a developer. Subsequent events inform the infobase of new "work item" instances, followed by any changes to the information object. The infobase stores and indexes all discovery and change events, however it also has enough capabilities to provides interaction services for external agents. For example the infobase itself will provide a user interface for humans to read and update "work items", as well as APIs for other digital information systems. A few examples of language-based interactions with an infobase are the following, that are also represented in a user interface:

- Show me the "work item" identified by "name1"
- Show me all "work items" due this week
- Update "work item" identified by "name1" with specific description and "done" status
- Move "work item" identified by "name1" to the top of the list

ToDo - More specific details around following topics:
- Schema development vs Modeling
- Database administration and optimization vs Administration and Learning (Magic)
- Query language vs Mental model, Natural language questions and answers
- UI development process vs System and user interaction models
- General development and maintenance vs More modelling and Learning (Magic)
- So many more ...
