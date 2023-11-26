<h1>Hi, I'm Alphonse! <h2>Cybersecurity Specialist</h2>

<h2>👨‍💻 Projects</h2>

- <b>System Administration</b>
- <b>Cybersecurity</b>


- <b>Programming languages</b>

<b>Python</b>

Algorithm for file updates in Python</b>

Project description</b>

You are a security professional working at a health care company. As part of your job, you're required to regularly update a file that identifies the employees who can access restricted content. The contents of the file are based on who is working with personal patient records. Employees are restricted access based on their IP address. There is an allow list for IP addresses permitted to sign into the restricted subnetwork. There's also a remove list that identifies which employees you must remove from this allow list.
Your task is to create an algorithm that uses Python code to check whether the allow list contains any IP addresses identified on the remove list. If so, you should remove those IP addresses from the file containing the allow list.

Here is how i went throught this scenario : 

 1- Open the file that contains the allow list

The file that i want to open is called "allow_list.txt". i assigned a string containing this file name to the import_file variable. Then, used a with statement to open it. Use the variable file to store the file while you work with it inside the with statement.
 <br/>
 
<img src="https://i.imgur.com/J1PdczB.png" height="80%" width="80%"/>
<br />
<br />

 2- Read the file contents
 
Next, i used the .read() method to convert the contents of the allow list file into a string so that i can read them. Stored this string in a variable called ip_addresses.

<img src="https://i.imgur.com/05WdReK.png" height="80%" width="80%"/>
<br />
<br />

 3- Convert the string into a list
 
In order to remove individual IP addresses from the allow list, the IP addresses need to be in a list format. Therefore, i used the .split() method to convert the ip_addresses string into a list.
 
   <img src="https://i.imgur.com/97us32V.png" height="80%" width="80%"/>
<br />
<br />

4- Remove IP addresses that are on the remove list

In the body of my iterative statement, i added code that will remove all the IP addresses from the allow list that are also on the remove list. First, created a conditional that evaluates if the loop variable element is part of the ip_addresses list. Then, within that conditional, applied the .remove() method to the ip_addresses list and removed the IP addresses identified in the loop variable element. 

<img src="https://i.imgur.com/VdQ067g.png" height="80%" width="80%"/>
<br />
<br />

 5- Update the file with the revised list of IP addresses 
 
Now that i have removed these IP addresses from the ip_address variable, i completed the algorithm by updating the file with this revised list. I first converted the ip_addresses list back into a string using the .join() method, then Applied .join() to the string "\n" in order to separate the elements in the file by placing them on a new line.

<img src="https://i.imgur.com/2SYK4Ng.png" height="80%" width="80%"/>
<br />
<br />

  
<h2>📺 Certifications and trainings</h2>

- [Google Cybersecurity Professionnal Certificate](https://www.credly.com/badges/d47b184a-ccf7-46f9-9ecb-1be9a94bf123/public_url), October 2023, Coursera
- [SOC Analyst Career Path](https://app.letsdefend.io/certificate/show/38e05918-c297-4367-a3d3-cacb00aae89c), September 2023, LetsDefend
- [Junior Cybersecurity Analyst career path](https://www.credly.com/badges/05ad9c12-d4c5-40a8-a03c-6e76d8908d92/public_url), May 2023 to July 2023, CISCO Networking Academy
- Entry-Level Cybersecurity Training, May 2023, Cybrary
- Certified in Cybersecurity (CC), April 2023, ISC2
- Fortinet NSE 1,2,3, April 2023, Fortinet NSE Certification Program
- [Healthcare IT Support](https://coursera.org/verify/specialization/6Z6S3JNHPUX4), March 2023, The Johns Hopkins University
- [Google IT Support Professionnal Certification](https://coursera.org/verify/professional-cert/84HBZTRWKC4A), February 2023, Coursera
- Hazard Recognition and Risks Assessment, November 2022
- [ISO Management System Audit Techniques And Best Practices](https://alison.com/user/learner-verification/26586266/1373), October 2022, Alison
- [Management of development projects](https://courses.edx.org/certificates/c9df3fd6dc7b4392b556e39243155992), September 2022, InerAmérican Bank of Development-EDX
- Lead to Transform Certified, February 2020 to March 2021, International Leadership Foundation
  
<h2>📺 Education</h2>

- Master of Engineering Degree in Industrial Maintenance and Production
 September 2007 to December 2010, National School of Agro-Industrial Science Ngaoundéré, Adamaoua, Cameroon
- Bachelor of Science in Physics
  September 2003 to September 2010, The University of Ngaoundéré Ngaoundéré, Adamaoua, Cameroon
  
<h2> 🤳 Connect with me:</h2>
- [LinkedIn](https://www.linkedin.com/in/alphonse-koumna-75a65738)

