# HTTPtoHTTPS-Windows-IIS
Http to Https rule for Windows Servers

Pattern ```(.*) ```

| Input  	|Type   	|Pattern   	|  
|---	    |---	    |---	    	|
|{HTTPS}   	    |  Matches the Pattern 	   	|^OFF$   	   	  |

Action type: ```Redirect```
Redirect URL: ```https://example.org/{R:1}```
Redirect type: ```Permanent (301)```
