# Mediator Setup

1. Copy `.env.example` to `.env`
2. Modify the values for your setup. Make sure to provide the correct endpoints.
3. Make sure the endpoints redirect to port 9000 (ws) and 9001 (http) on the local machine.
   - .e.g use `ngrok http 9001` to create a tunnel to port 9001.
   - If you use a forwarding service, configure it to point to port 9000 and 9001 respectively.
4. `docker-compose up`
5. Copy the invitation and use that in an AFJ agent with WS support!
