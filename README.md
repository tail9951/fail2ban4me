# fail2ban4me

https://gist.github.com/saniaky/dc75cbf64922e418400b0f54ed5b2c3a

Referring to this article, I've separated the Fail2Ban components to make it easier for myself to clone and run using Docker Compose.

By default, I've only included filtering for Nginx logs.



You can verify whether the IP addresses have been correctly banned in the table by using the following command:
```
sudo iptables -L -n -v
```

20230920

I add slack-notify with webhook accorfing to this article
https://github.com/coleturner/fail2ban-slack-action