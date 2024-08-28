---
layout: default
---

## Professional Statement

My name is Christian. I am a highly motivated and detail-oriented technical support and cybersecurity professional with a passion for protecting sensitive data and mitigating cyber threats while providing top tier customer support. I am committed to safeguarding company data and maintaining the integrity of digital infrastructures in a forward-thinking organization. I am passionate about staying ahead of the curve in the evolving landscape of cyber threats. I am very eager to bring my knowledge of encryption algorithms and intrusion detection systems to a dynamic cybersecurity team.


# Security Audit for Botium Toys

Conducted a security audit by implementing the NIST CSF, establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. Implemented PCI DSS, GDPR, SOC type 1, and SOC type2 compliances

[Controls and Compliance Checklist](https://github.com/xtiannd/xtiannd.github.io/blob/main/Controls%20and%20compliance%20checklist.pdf)

# NIST Cybersecurity Framework 

Used the NIST CSF to respond to a DDoS attack through a flood of incoming ICMP packets. Implemented a new firewall rule to limit the rate of incoming ICMP packets and an IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics.

[Incident Report Analysis](https://github.com/xtiannd/xtiannd.github.io/blob/main/Incident%20report%20analysis%20.pdf)

# Linux Commands

Used Linux commands to changed multiple permissions to match the level of authorization the organization wanted for files and directories in the projects directory. The first step in this was using ls -la to check the permissions for the directory. This informed my decisions in the following steps. I then used the chmod command multiple times to change the permissions on files and directories.

[File Permissions in Linux](https://github.com/xtiannd/xtiannd.github.io/blob/main/File%20permissions%20in%20Linux%20.pdf)

# SQL

Applied filters to SQL queries to get specific information on login attempts and employee machines. I used two different tables, log_in_attempts and employees. I used the AND, OR, and NOT operators to filter for the specific information needed for each task. I also used LIKE and the percentage sign (%) wildcard to filter for patterns.

[Apply Filters to SQL Queries](https://github.com/xtiannd/xtiannd.github.io/blob/main/Apply%20filters%20to%20SQL%20queries%20.pdf)

# Vulnerable Assessment

Analyzed a vulnerable system for a small business and used NIST SP 800-30 Rev. 1 to guide the risk analysis of the information system, proposed a remediation strategy such as Principle of least privilege, Defense in depth, MFA, AAA framework.

[Vulnerable Assessment Report](https://github.com/xtiannd/xtiannd.github.io/blob/main/Vulnerability%20assessment%20report%20.pdf)

# Incident Documentation 

Documented incidents with an incident handler's journal: Documented a ransomware incident, analyzed a packet capture file using WireShark, used tcpdump to capture and analyze network traffic, Used VirusTotal to investigate a suspicious file hash. 

[Completed Incident Handler's Journal](https://github.com/xtiannd/xtiannd.github.io/blob/main/Completed%20incident%20handler's%20journal%20.pdf)

# PASTA Threat Model Framework

Applied the PASTA threat model framework to launch a sneaker shopping app: Compliance with PCI-DSS, Defined technologies used by the app (API, PKI, SHA-256, SQL), Used data flow diagram to decompose the app, Threat Analysis (Injection and Session hijacking), Vulnerability Analysis (Lack of prepared statements, Broken API token), Used Attack Tree Diagram for Attack Modeling, Risk Analysis and Impact (SHA-256, Incident Response Procedures, Password Policy, Principle of Least Privilege).

[PASTA Worksheet](https://github.com/xtiannd/xtiannd.github.io/blob/main/PASTA%20worksheet%20.pdf)

# Python

Practiced writing Python code: Assign Python Variables, create a conditional statement, create loops, Define and call a function, Create more functions, Work with string values, Develop an algorithm, Use regular expressions to find patterns, Import and parse a text file, Update a File.

[Assign Python Variables](https://github.com/xtiannd/xtiannd.github.io/blob/main/Exemplar_Assign%20Python%20variables.pdf)

[Create A Conditional Statement](https://github.com/xtiannd/xtiannd.github.io/blob/main/LAB_Exemplar_CreateAConditionalStatement.pdf)

[Create Loops](https://github.com/xtiannd/xtiannd.github.io/blob/main/Exemplar_Create%20loops.pdf)

[Define And Call A Function](https://github.com/xtiannd/xtiannd.github.io/blob/main/Exemplar_Define%20and%20call%20a%20function.pdf)

[Create More Functions](https://github.com/xtiannd/xtiannd.github.io/blob/main/Exemplar_Create%20more%20functions.pdf)

[Work With String Values](https://github.com/xtiannd/xtiannd.github.io/blob/main/Exemplar_Work%20with%20strings%20in%20Python.pdf)

[Develop An Algorithm](https://github.com/xtiannd/xtiannd.github.io/blob/main/Exemplar_Develop%20an%20algorithm.pdf)

[Create Another Algorithm](https://github.com/xtiannd/xtiannd.github.io/blob/main/Exemplar_Create%20another%20algorithm.pdf)

[Use Regular Expressions To Find Patters](https://github.com/xtiannd/xtiannd.github.io/blob/main/Exemplar_Use%20regular%20expressions%20to%20find%20patterns.pdf)

[Import And Parse A Text File](https://github.com/xtiannd/xtiannd.github.io/blob/main/Exemplar_Import%20and%20parse%20a%20text%20file.pdf)

[Update A File](https://github.com/xtiannd/xtiannd.github.io/blob/main/Update%20a%20file%20through%20a%20Python%20algorithm.pdf)

[Debug Python Code](https://github.com/xtiannd/xtiannd.github.io/blob/main/Exemplar%20-%20Debug%20Python%20code.pdf)

# Splunk 

Performed a query with Splunk: Upload sample log data, Search through indexed data, evaluate search results, identify different data sources, Locate failed SSH login(s) for the root account.

### Upload Data Into Splunk

1. If you haven't already, download the data file from Step 1:  
tutorialdata.zip
. Click the link then click the download icon. Do not uncompress the file.

1. Navigate to Splunk Home from your Splunk Cloud free trial instance. You might need to log in again using your credentials from Step 3.

1. On the Splunk bar, click Settings. Then click the Add Data icon.

1. Click Upload.

1. Click the Select File button.

1. Upload the tutorialdata.zip file, and click Open.

1. Click the Next button to continue to Input Settings.

1. By the Host section, select Segment in path and enter 1 as the segment number.

1. Click the Review button and review the details of the upload before you submit. The details should be as follows: 

    Input Type: Uploaded File

    File Name: tutorialdata.zip

    Source Type: Automatic

    Host: Source path segment number: 1 

    Index: Default

10. Click Submit. Once Splunk has ingested the data, you will receive confirmation that the file was successfully uploaded.

### Perform A Basic Search

![Image](https://github.com/xtiannd/xtiannd.github.io/blob/main/cc9oz1SmRCK3pfm87DcKZQ_dcda39fb68f147469c41a6b9fcb3cbf1_CS_SRQ-006_homepage-with-labels.png)

1. Navigate to Splunk Home. (To return to Splunk Home, click the Splunk Cloud logo on the Splunk Cloud page.)

1. Click Search & Reporting. You may close any pop ups that appear.

1. In the search bar,  enter your search query:
index=main
This search term specifies the index. An index is a repository for data. Here, the index is a single dataset containing events from an index named main.

1. Select All Time from the time range dropdown to search for all the events across all time.

1. Click the search button. Note that the search button is represented by the magnifying glass icon. Your search should retrieve thousands of events.

![Image](https://github.com/xtiannd/xtiannd.github.io/blob/main/t-w-qDeCQmOMDMXZRUz8Lw_8ceeb7ac61d7471c9ead6a03d17e5cf1_CS_SRQ-006_search.png)

### Evaluate The Fields 

For each event the fields are host, source, and sourcetype. Under SELECTED FIELDS, examine the same fields.

![Image](https://github.com/xtiannd/xtiannd.github.io/blob/main/b-LM5OKBQRecaBKlhE8u4A_10aa13c3ffe64074b8fc019a33cd2cf1_8I5gN09dzpvkvx9AjDfkxZmJ62cOmcJyN4F-fxT0XfU3fHWId7Sf5HLokjN5n8vdQSxBLPvzQmk24uXoj-5T_Egb2EwAgAhY4dpRhRvoUy5D0x7gcfLb7SMpx9aBWso7RW8xG3tl0Jge_VMBuesFp7bPkB3dCqBm1N9Z36HCce21zwEvvdNyxNfg.png)

Examine the field values by clicking on the field under SELECTED FIELDS. You should observe the following:

host: The host field specifies the name of the network host from which the event originated. In this search there are five hosts:

 *  mailsv - Buttercup Games' mail server. Examine events generated from this host.

 *  www1 - This is one of Buttercup Games' web applications.

 *  www2 - This is one of Buttercup Games' web applications.

 *  www3 - This is one of Buttercup Games' web applications.

 *  vendor_sales - Information about Buttercup Games' retail sales.

source: The source field indicates the file name from which the event originates. You should identify eight sources. Notice /mailsv/secure.log, which is a log file that contains information related to authentication and authorization attempts on the mail server.

sourcetype: The sourcetype determines how data is formatted. You should observe three sourcetypes. Examine secure-2.

### Narrow Your Search

Because you've been tasked with exploring any failed SSH logins for the root account on the mail server, you'll need to narrow the search results for events from the mail server.

Under SELECTED FIELDS, click host and click mailsv.

Notice that a new term has been added to the search bar: index=main host=mailsv. The search results have narrowed to over 9000 events that are generated by the mail server.

### Search For A Failed Login For Root

Now that you've narrowed your search results to events generated by the mail server, continue to narrow the search to locate any failed SSH logins for the root account. 

1. Clear the search bar.

1. Enter index=main host=mailsv fail* root into the search bar.
This search expands on the search from the previous task and searches for the keyword fail*. The wildcard tells Splunk to expand the search term to find other terms that contain the word fail such as failure, failed, etc. Lastly, the keyword root searches for any event that contains the term root.

1. Click search.

### Evaluate The Search Results

Your search from the previous task should have retrieved search results for over 300 events. Navigate to other pages of the search results to observe the events not listed on the first page of results.

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

#### Header 4

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Google](https://github.com/xtiannd/xtiannd.github.io/blob/main/Google%20Cybersecurity%20Certificate%20.jpg)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
