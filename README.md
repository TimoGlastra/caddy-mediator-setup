# Mediator Setup

1. Copy `.env.example` to `.env`
2. Modify the values for your setup. Make sure to provide the correct endpoints.
3. Make sure the endpoints redirect to port 2015 on the local machine.
   - .e.g use `ngrok http 2015` to create a tunnel to port 2015.
   - If you use a forwarding service, configure it to point to port 2015.
   - You can also modify the port external port in the docker compose file (e.g. `443:2015` instead of `2015:2015`)
4. `docker-compose up`
5. Copy the invitation and use that in an AFJ mediator with WS support!
