# Setting up Spring Security JWT

Step 1: We need /authenticate API endpoint <br/>
a. Accepts user ID and password <br/>
b. Returns JWT as a response <br/>

Step 2: Intercept all incoming requests <br/>
a. Extract JWT from header (RequestHeader("Authorization")) <br/>
b. Validate and set in execution context <br/>

