# Footprinting through search engines

Attackers use search engines to **extract information about atarget**. **Search engine caches** and **Internet archives** may also provide sensitive information that has been removed from the World Wide Web (WWW)

- Search for the target company's external URL in a search engine such as Google, Bing, etc.
- Restricted URLs **provide an insight** into different departments and business units in an organization.


## Monitoring target using Alerts

Alerts are the **content monitoring services** that provide **up-to-date information** based on your preference usually via email or SMS in an automated manner

1. [Google Alerts](http://www.google.com/alerts)
2. [Yahoo! Alerts](http://alerts.yahoo.com)
3. [Twitter Alerts](https://twitter.com/alerts)
4. [Giga Alert](http://www.gigaalert.com/)


## Social Networking Sites/People Search Services

Social networking sites are the great source of personal and organiztional information

Information about an individual can be found at various **people search websites**

The people search returns the following **information about a person or organization**:
- Residential addresses and email addresses.
- Contact numbers and date of birth (may be a try for password hacking)
- Photos and social networking profiles
- Blog URLs
- Satellite pictures of private residences
- Upcoming projects and operating environment

People Search Online Serivces:
- [AnyWho](http://www.anywho.com)
- [US Search](http://www.ussearch.com)
- [Intelius](http://www.intelius.com)
- [411](http://www.411.com)
- [People Finders](http://www.peoplefinders.com)
- [Veromi](http://www.veromi.net)
- [Private eye](http://www.privateeye.com)
- [People Search Now](http://www.peoplesearchnow.com)
- [Public Background checks](http://www.publicbackgroundchecks.com)

# Footprinting using Advanced Google Hacking Techniques

- **Query string:** Google hacking refers to **creating complex search queries** in order to extract sensitive or hidden information
- **Vulnerable targets:** it helps attackers to **find vulnerable targets**
- **Google Operators:** it uses advanced Google search operators to **locate specific strings of text** within the search results

Google supports several advanced operators that help in **modifying the search**
- `[cache:]` displays **the web pages** stored in Google cache
- `[link:]` lists web pages that have **links to the specified web page**
- `[related:]` lists web pastes that are **similar** to a specified web page
- `[info:]` presents some **information** that Google has about a particular web page
- `[site:]` restrictes the results to those websites in the given **domain**
- `[allintitle:]` restricts the results to those websites with all of the search **keywords in the title**
- `[intitle:]` restricts the results to **documents** containing the serach keyword **in the title**
- `[allinurl:]` restricts the results to those with all of the search keywords in the URL
- `[inurl:]` restricts the results to **documents** containing the search keyword **in the URL**

## References

- Google Hacking Database (GHDB) [https://www.exploit-db.com/google-hacking-database/](https://www.exploit-db.com/google-hacking-database/)
- Google Dorks

# Footprinting through Social Networking Sites

Attackers use social engineering trick to gather sensitive information from social networking websites suc as **Facebook**, **MySpace**, **LinkedIn**, **Twitter**, **Pinterest**, **Google+**, etc.

Attackers create a **fake profile** on social networking sites and then use the false identity to lure the employees to give up their sensitive information

Employees may **post personal information** such as date of birth, educational and employment backgrounds, spouses names, etc. and information about their company such as potential clients and business partners, trade secrets of business, websites, company's upcoming news, mergers, acquisitions, etc.

Attackers collect information about the employee's interests by **tracking their groups** and then trick the employee to reveal more information

## Information Available on Social Networking Sites

| What attacker gets               |     | What users do                | What organizations do              |     | What attacker gets              |
|----------------------------------|-----|------------------------------|------------------------------------|-----|---------------------------------|
| Contact info, location, etc.     | <-- | Maintain profile             | User surveys                       | --> | Business strategies             |
| Friends list, friends info, etc. | <-- | Connect to friends, chatting | Promote products                   | --> | Product profile                 |
| Identity of family member        | <-- | Share photos and videos      | User support                       | --> | Social Engineering              |
| Interests                        | <-- | Play games, join groups      | Recruitment                        | --> | Platform/technology information |
| Activities                       | <-- | Create events                | Background check to hire employees | --> | Type of Business                |

# Website Footprinting

Website footprinting refers to **monitoring and analyzing the target organization's website** for information.

Browsing the target website may provide:
- Software used and its version
- Operating system used
- Sub-directories and parameters
- Filename, path, database field name, or query
- Scripting platfrom
- Contact details and CMS details

Use **Burp Suite**, **Zaproxy**, **Paros Proxy**, **Website Informer**, **Firebug**, etc. to view headers that 

Eximining HTML source provide:
- Comments in the source code
- Contact details of web developer or admin
- File system structure
- Script type

Examining cookies may provide:
- Software in use and its behavior
- Scripting platforms used

## Web spiders

Web spiders perform automated searches on the target website and collect specified information such as **employee names**, **email addresses**, etc.

Attackers use the collected information to perform further **footprinting** and **social engineering attacks**

## **Mirroring** entire website:

Mirroriing an entire website onto the local system enables an attacker to browse website offline; it also assists in finding **directory structure** and other valuable information from the mirrored copy without multiple requests to web server.

Web mirroring tools allow you to **download a website to a local directory**, building recurisvely all directories, HTML, images, flash, videos, and other files from the server to you computer.

Some website mirroring tools:
- [BlackWidow](http://softbytelabs.com)
- [NCollector Studio](http://www.calluna-software.com)
- [Website ripper copier](http://www.tensons.com)
- [Teleport pro](http://www.tenmax.com)
- [Portable Offline Browser](http://www.metaproducts.com)
- [PageNest](http://www.pagenest.com)
- [Offline Explorer Enterprise](http://www.metaproducts.com)
- [GNU Wget](http://www.gnu.org)
- [Hooeey Webprint](http://www.hooeeywebprint.com)

Web updates monitoring tools:
- [Change detaction](http://www.changedetection.com)
- [Follow That Page](http://www.followthatpage.com)
- [Page2RSS](http://page2rss.com)
- [Watch that page](http://www.watchthatpage.com)
- [Check 4 Change](https://addons.mozilla.org)
- [OnWebChange](http://onwebchange.com)
- [Infominder](http://www.infominder.com)
- [Tracked Content](http://trackedcontent.com)
- [Web Snitcher](http://websnitcher.com)
- [Update scanner](https://addons.mozilla.org)


# Email Footprinting

Collecting information from **email header**:
- The address from which the message was sent
- Sender's IP Address
- Sender's mail server
- Date and time received by the originator's email server
- Authentication system used by sender's mail server
- Date and time of message sent
- Sender's fullname

Email tracking tools:
- [eMailTrackerPro](http://www.emailtrackerpro.com)
- [PoliteMail](http://www.politemail.com)
- [Email Lookup - Free Email tracker](http://www.ipaddresslocation.org)
- [Yesware](http://www.yesware.com)
- [ContactMonkey](http://contactmonkey.com)
- [Read Notify](http://www.readnotify.com)
- [DidTheyReadIt](http://www.didtheyreadit.com)
- [TraceEmail](http://whatismyipaddress.com)
- [Zendio](http://www.zendio.com)
- [PointOfMail](http://www.pointofmail.com)
- [WhoReadMe](http://whoreadme.com)
- [Get Notify](http://www.getnotify.com)
- [G-Lock Analytics](http://glockanalytics.com)

# Competitive Intelligence

Competitive intelligence gathering is the process of **identifying**, **gathering**, **analyzing**, **verifying**, and using information about your competitors from resources suc as the Internet

Competitive intelligence is **non-interfering** and **subtle of nature**

Sources of Competitive Intelligence:
1. Company websites and employments ads
2. Search engines, Internet, and online DB.
3. Press releases and annual reports
4. Trade journals, conferences, and newspaper
5. Patent and trademarks
6. Social engineering employees
7. Product catalogues and retail outlets
8. Analyst and regulatory reports
9. Customer and vendor interviews
10. Agents, distributors, and supplies

## Monitoring website traffic of target company

Attacker uses website traffic monitoring tools such as **web-stat**, **Alexa**, **Monitis**, etc. to collect the information about the target company

Traffic monitoring helps to collect information about the **target's customer base** which helps attackers to disguise as a customer and launch social engineering attacks on the target.

## Tracking Online Reputation of the target

Online Reputation Management (ORM) is a process of **monitoring a company's reputation on Internet** and taking certains measures to minimize the negative search results/reviews thereby improve its brand reputation.

An attacker uses ORM tracking tools to:
- Track **company's online reputation**
- Collect company's **search engine ranking** information
- Obtain **email notifications** when a company is mentioned online
- Track **conversations**
- Obtain **social news** about the target organization

# WHOIS Footprinting

WHOIS database are maintained by **Regional Internet Registries** and contain the **personal information of domain owners**.

WHOIS query returns:
- Domain name details
- Contact details of domain owner
- Domain name servers
- NetRange
- When a domain has been created
- Expiry records
- Records last updated

Information obtained from WHOIS database assists an attacker to:
- Gather personal information that assisists to perform social engineering

# DNS Footprinting

Attacker can gather DNS information to **determine key hosts in the network** and can perform social engineering attacks

DNS records provide important information about location and type of servers

| Record type | Description                                      |
|-------------|--------------------------------------------------|
| A           | Points to a host's IP Address                    |
| MX          | Points to domain's mail server                   |
| NS          | Points to host's name server                     |
| CNAME       | Canonical naming allows aliases to a host        |
| SDA         | Indicate authority for domain                    |
| SRV         | Service records                                  |
| PTR         | Maps IP Address to a hostname                    |
| RP          | Responsible person                               |
| HINFO       | Host information record includes CPU type and OS |
| TXT         | Unstructured text records                        |

Locate the **Network range**:
- Network range information assists attackers to create a **map of target network**
- Find the **range of IP addresses** using **ARIN whois database search** tool
- You can find the range of IP addresses and the subnet mask used by the target orgranization from **Regional Internet Registry (RIR)**

Traceroute programs work on the concept of **ICMP protocol** and **use the TTL field in the header of ICMP packets** to discover the routers on the path to a target host.
- Attackers conduct traceroute to extract information about: **network topology**, **trusted routers**, and **firewall locations**
- By putting this information together, attackers can draw the **network diagram**

Traceroute tools:
- Path Analyzer Pro
- VisualRoute

# Network Footprinting

# Footprinting through Social Engineering