# Setting up Spring Security JWT

Step 1: We need /authenticate API endpoint <br/>
a. Accepts user ID and password
b. Returns JWT as a response

Step 2: Intercept all incoming requests
a. Extract JWT from header (RequestHeader("Authorization"))
b. Validate and set in execution context

