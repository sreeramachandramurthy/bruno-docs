# Bru Markup Language

Bru is a simple markup language that utilizes plain text files to document and organize information for your API requests.

The api requests in your collections are stored as plain text files using this language.

This allows you to save your API collections in a folder within your code repository, and use your preferred version control system to manage and share them with your team. Collaboration on your API collections can be done through pull requests, as the human-readable file format makes it easy for developers to understand the changes made to the API collection.

Below is a sample of a Bru file for a `GET` request with some query params

![bru lang sample](assets/images/github-collection.png)

You can checkout the sample repository which contains GitHub rest API collection [here](https://github.com/usebruno/github-rest-api-collection)

If you are wondering why had to design a DSL instead of just using JSON/YAML, you can checkout this [github discussion](https://github.com/usebruno/bruno/discussions/360)
