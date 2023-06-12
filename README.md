## ansible setup
<code>
    docker-compose up -d
</code>

localhost ~/.ssh/config

<code>
Host localhost
    StrictHostKeyChecking no
    UserKnownHostsFile /dev/null
    Port  2222
</code>

added bind mount for local code setup developement purpose

replace `source: <PATH>` in controller service