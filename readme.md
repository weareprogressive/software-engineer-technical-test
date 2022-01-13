# Software Engineer Technical Test

This technical test is designed to give us an understanding of how you identify, prioritise, and solve problems, as well as your ability to understand specifications, best practices, and technical requirements which may be in addition to the original specification.

## Specification / Requirements

1. Create an API endpoint which proxies requests to [getaddress.io](https://getaddress.io)
1. Responses should return to the user
1. Your API endpoint will not require authentication
1. You may use vanilla PHP (version ≥ 7.4) or Laravel/Lumen (any currently supported version)
1. Your code must be delivered via GitHub repository which is either public or to which `@johnothecoder` has been given access
1. If any installation instructions are required, they should be delivered via the repository's `readme.md` file

# Considerations

We will be looking for the following;

1. Adherence to international coding standards and best practices
1. Testing / Testability
1. Usage of the SOLID principles
1. Exception and error handling
1. Git usage and commits

# API Endpoint Information

GetAddress is an API which provided postcode lookup queries for UK addresses. You can find more information at [getaddress.io](https://getaddress.io) - you can [sign up for your free API key here](https://getaddress.io/Plan/Free)

The only endpoint which needs to be handled currently is `[GET] /find/{postcode}`