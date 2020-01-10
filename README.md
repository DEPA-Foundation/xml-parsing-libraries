As developers might be aware, data flows in the DEPA framework will be encoded in XML according to fixed schemas. [The schemas for each type of financial document can be found here](https://api.rebit.org.in/schema)

In order to make life easier for developers working with the DEPA framework, it would be useful to have open source libraries which can help with parsing this XML into useable and convenient objects or classes.

Ideally, we will write code which accepts an XML string as an input and returns some useable objects as an output. The exact nature of the output can vary according to the language and preference of the author writing the code.

Developers are free to write libraries in any language of their choosing, but it would be useful to have some written out for C#, Java, Python, and Node.js (as these appear to be the most popular languages amongst startups and IT companies).

[Some sample data for an XML string encoding a user's bank account information (according to the 'deposit' FI type) can be found here (in the Request Body in the section 'Adding User Account Transaction')](https://finvu.github.io/sandbox/fip_data_api/)
