[<img src="assets/images/su-logo.png" alt="Skills Union Logo" height="80px" />](https://www.skillsunion.com/)

# API's & Postman: Study

Use [DuckDuckGo](https://duckduckgo.com/) or your preferred search engine along with the provided resources to research and answer the [questions below](#questions).

## Required Reading

- [What is HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP)
- [HTTP Messages - Request & Response](https://developer.mozilla.org/en-US/docs/Web/HTTP/Messages)
- [HTTP Verbs](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods)

## Optional Reading

- [What is Internet?](https://youtu.be/Dxcc6ycZ73M)
- [HTTP Response Status](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status)

## Questions

1. Describe how HTTP works?

   ```
   HTTP does not keep any state during requests. It works by a "client-server model", whereby a client opens a connection, makes a request, there is a waiting period and the response is received. 
   ```

2. What are the required information for a HTTP Request ot be sent?

   ```
   Examples:
   1. URL - the address of the information to be requested
   2. // it requires a action to be performed indicated by a verb, method or noun associated with HTTP e.g. Post
   3. // The authority component of a URL, consisting of the domain name and may include the port which is the optional part
   4. // "The HTTP version, which defines the structure of the remaining message, acting as an indicator of the expected version to use for the response" MDN 2021
   ```

3. Describe the expected actions to be performed by the following HTTP Verbs:

   ```
   POST: // Data is send back "posted" to the server, examples where this happens includes when a temporary document is send back.
   GET: // In the reverse to post, GET retrieves a resource
   PUT: // As there is overwriting involved, put is similar to post in that it will send data to a server to create or to update a resource.The difference is calling the same PUT request many times will always produce the same outcome. (W3 Schools 2021). Whereas for calling for POST request repeatedly will creating the same resource multiple times.
   DELETE: // Will action a delete on the resource that is specified.
   ```

---

## Create a Postman Account

Create an account at https://www.postman.com/ (skip team creation step)

---

### Response Guidelines

Please follow these guidelines as you answers these questions:

- Cite any relevant sources consulted during your research
- Do not reply using direct quotes from the source material
- Provide an answer using your own words and voice

Resource used W3 Schools reference https://www.w3schools.com/tags/ref_httpmethods.asp
2021
