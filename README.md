# githook for jira

installs a local githook for jira

username in git config must be in shape of surename.lastname
commit message must be in shape of:

```
some text BIO-25 some text

the long message 
will be send to Jira as comment.
```

subject of commit message is parsed for Ticket ID.

set parameters in default/main.yml to your needs.