# L O C A L 

### How is it used?

1. Why would a developer use local storage for a web application?
    * The main transport layer of the internet, HTTP, is *stateless*. So when the application is used and then closed, it's state is reset the next time you open it. If you close an application on your desktop and re-open it, the most recent state is restored. This is why as a developer, we have to store the state of our interface somewhere, IE local storage.

2. What information should not be stored in local storage?
    * PII or anything that can be used to access your accounts, financial or otherwise. THe reason for ths is that it's far too easy for hackers or scammers to access local storage via cookies. The cookies act as a "trap-door" to your information. 

3. Local storage can store what type of data? How would you convert it to that type before storing?
    * Local storage only accepts data as strings in different keys. The workaround to this is parsing that data input as a JSON object using JSON.stringify()