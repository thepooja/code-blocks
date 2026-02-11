## What is Retrofit?

- “Retrofit is a type-safe HTTP client for Android used to consume REST APIs. It converts API responses into Kotlin objects using converters like Gson or Moshi.”

### Why Retrofit?

✔ Simple API calls
✔ Automatic JSON parsing
✔ Works perfectly with Coroutines
✔ Clean & readable code

## What is OkHttp? How is it related to Retrofit?

- “OkHttp is the underlying HTTP client that Retrofit uses to make network calls.”

  Retrofit = Interface + Mapping
  OkHttp = Actual network execution

- OkHttp Interceptors (VERY IMPORTANT)
  Types:

      - Logging Interceptor

      - Authentication Interceptor

      - Network Interceptor
       “We use interceptors to avoid adding headers manually in every API.”

- Interceptor : The Interceptor interface allows developers to intercept and modify network requests and responses. It can be used for tasks such as adding headers, logging, or modifying the request/response before reaching the server or the app.

- Differentiate between Call<T> and Deferred<T> in Retrofit, and when would you prefer to use one over the other?

Explanation: Call<T> is used for synchronous network requests, while Deferred<T> is used for asynchronous requests with Kotlin's coroutines. Use Call<T> for synchronous operations and Deferred<T> for asynchronous tasks.
