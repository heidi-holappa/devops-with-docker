## Summary

I copied the barely working application and just for my own convenience made a little change to the docker-compose.yml (moved it into a subdirectory). I first ran the application and studied it. After that, I restarted it with the following command

```
docker compose up -d --scale compute=5
```

Then I decided that I want to see the logs, so I used the spell
```
docker compose logs -f
```

Then I went into the app, tested my solution and got a green light! 
