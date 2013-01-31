Databasedotcom Console creates an executable called 'dbdc' that whips up an interactive ruby console that is connected to your Salesforce instance.  

If you're tired of using Excel formulas, CSV files or other arduous tools to work with Salesforce data, this is the gem for you.  

The console is Just Plain Ruby(TM) so you can use any ruby methods you want to process your salesforce data.  You can of course require other ruby libraries as well.

Install (supports Ruby 1.8.7 and up):
```
gem install databasedotcom_console
```

Just open a bash shell and run 'dbdc' and you'll be prompted for credentials.  Alternatively you can pass your creds as parameters:
```bash
>> dbdc -u <username> -h <host> -p <password>
```

You can also execute a prewritten script:
```bash
>> dbdc exec /path/to/my/file
```

For more information about the API available for querying and editing your data, check out https://github.com/heroku/databasedotcom
If you're new to Ruby, I suggest spending 20 minutes at www.tryruby.org.  It could add years to your life.
