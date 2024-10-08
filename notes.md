# Polling

1. don't use `setInterval` - as API request might take more time than an interval
2. use `setTimeout` with recursion
3. use `requestAnimationFrame` for polling to avoid making requests when the window is out of focus
