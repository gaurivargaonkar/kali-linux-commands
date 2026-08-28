┌──(kali㉿kali)-[/home/kali]
└─PS> echo "Cyber Crime                        
>> Cyber crime encompasses a wide range of illegal activities that exploit computers, networks, and the internet. These crimes include but are not limited to:
>> Malware Attacks: Malicious software that interferes with normal computer operations, damages systems, or gains unauthorized access to data.
>> Denial-of-Service (DoS) and Distributed Denial-of-Service (DDoS) Attacks: Flood a system with excessive traffic to make it unavailable to legitimate users.
>> Phishing Attacks: Fake emails, messages, or websites that impersonate trusted organizations to trick users into revealing sensitive information.
>> Botnets: Networks of infected computers controlled remotely by attackers to carry out large-scale cyberattacks.
>> Online Financial Fraud: Scammers trick users into sharing sensitive information or money transfer details.
>> Digital Arrest/Impersonation Scams: Criminals pose as police or officials to threaten arrest and demand money.
>> Investment/Trading/Crypto Fraud: Fake apps or websites promise high returns on stocks or crypto, leading to financial loss.
>> Phishing & Vishing: Fake emails, SMS, or calls asking for personal information or to click harmful links.
>> Online Job/Part-time Work Scams: Fake offers for work-from-home jobs requiring registration fees or bank details.
>> Sextortion/Blackmail: Threatening to share private photos or videos unless money is paid.
>> Child Pornography/Cyber Bullying/Stalking: Harmful content or harassment online, especially targeting women and children.
>> Malware/Ransomware: Harmful software that steals data or locks devices for ransom.
>> To protect against cyber crime, it is essential to follow cyber safety practices such as using strong, unique passwords, enabling two-factor authentication, and being cautious on social media. If you become a victim, do not panic and act quickly by calling the National Cyber Crime Helpline at 1930." > pract1.txt                      ###Print data to file

┌──(kali㉿kali)-[/home/kali]
└─PS> cat pract1.txt                       ####print file content in terminal
Cyber Crime
Cyber crime encompasses a wide range of illegal activities that exploit computers, networks, and the internet. These crimes include but are not limited to:
Malware Attacks: Malicious software that interferes with normal computer operations, damages systems, or gains unauthorized access to data.
Denial-of-Service (DoS) and Distributed Denial-of-Service (DDoS) Attacks: Flood a system with excessive traffic to make it unavailable to legitimate users.
Phishing Attacks: Fake emails, messages, or websites that impersonate trusted organizations to trick users into revealing sensitive information.
Botnets: Networks of infected computers controlled remotely by attackers to carry out large-scale cyberattacks.
Online Financial Fraud: Scammers trick users into sharing sensitive information or money transfer details.
Digital Arrest/Impersonation Scams: Criminals pose as police or officials to threaten arrest and demand money.
Investment/Trading/Crypto Fraud: Fake apps or websites promise high returns on stocks or crypto, leading to financial loss.
Phishing & Vishing: Fake emails, SMS, or calls asking for personal information or to click harmful links.
Online Job/Part-time Work Scams: Fake offers for work-from-home jobs requiring registration fees or bank details.
Sextortion/Blackmail: Threatening to share private photos or videos unless money is paid.
Child Pornography/Cyber Bullying/Stalking: Harmful content or harassment online, especially targeting women and children.
Malware/Ransomware: Harmful software that steals data or locks devices for ransom.
To protect against cyber crime, it is essential to follow cyber safety practices such as using strong, unique passwords, enabling two-factor authentication, and being cautious on social media. If you become a victim, do not panic and act quickly by calling the National Cyber Crime Helpline at 1930.

┌──(kali㉿kali)-[/home/kali]
└─PS> echo "Cyber Crime                                                                                                                                                                                           
>> About Us
>>          
>> 
>> DCP (Cyber Crime) is overall in-charge of the Cyber Crime Branch. Cyber police stations work under their supervision. The Cyber Police Station started functioning on 09th April, 2009. This branch deals with the investigation of website hacking, cyber stalking, cyber pornography, e-mail, credit card crime, software piracy, online fraud and internet crime. It investigates cases registered specially under Information Technology Act, (amended 2008) along with IPC & other Acts.
>> 
>> Role/ Responsibility of Cyber Police Station :
>> 
>> 1. To provide periodical training to Mumbai Police personnel in Cyber Crime Investigation.
>> 
>> 2. To participate/arrange Cyber Crime Prevention/Awareness programmes in Schools, Colleges and Institutions /Organisations. 
>> 
>> 3. Cyber Police Station also provides technical assistance to investigating Officers of the Local Police Stations, Crime Branch Units and other Branches from Mumbai Police. 
>> 
>> 4. If any adverse remark or malicious comment is found against the State which might result in a Law & Order problem, the Cyber Police Station, Mumbai sends a request to the  Computer Emergency Response Team, India (CERT-IN) through the Nodal Officer (Joint Commissioner of Police, Crime, Mumbai) (under section 69 A IT Act) or sends a request through getting an Order of the concerned Hon. Court to block the electronic transmission of such content; when request made through email is not accepted by the  website Registrar/Service provider.                                                                                     
>>                                                                                                                                                                                                                
>>                                                                                                                                                                                                                
>>                                                                                                                                                                                                                
>> 5. In Child Pornography and Rape, Gang rape cases, Cyber Police Station, Mumbai works as a nodal for Mumbai Police." >> pract1.txt                 ###Add data to file without replacing/deleting file content 

┌──(kali㉿kali)-[/home/kali]
└─PS> head pract1.txt                  ###show first 10 default lines
Cyber Crime
Cyber crime encompasses a wide range of illegal activities that exploit computers, networks, and the internet. These crimes include but are not limited to:
Malware Attacks: Malicious software that interferes with normal computer operations, damages systems, or gains unauthorized access to data.
Denial-of-Service (DoS) and Distributed Denial-of-Service (DDoS) Attacks: Flood a system with excessive traffic to make it unavailable to legitimate users.
Phishing Attacks: Fake emails, messages, or websites that impersonate trusted organizations to trick users into revealing sensitive information.
Botnets: Networks of infected computers controlled remotely by attackers to carry out large-scale cyberattacks.
Online Financial Fraud: Scammers trick users into sharing sensitive information or money transfer details.
Digital Arrest/Impersonation Scams: Criminals pose as police or officials to threaten arrest and demand money.
Investment/Trading/Crypto Fraud: Fake apps or websites promise high returns on stocks or crypto, leading to financial loss.
Phishing & Vishing: Fake emails, SMS, or calls asking for personal information or to click harmful links.

┌──(kali㉿kali)-[/home/kali]
└─PS> head -n7 pract1.txt              ###show first 7 lines         
Cyber Crime
Cyber crime encompasses a wide range of illegal activities that exploit computers, networks, and the internet. These crimes include but are not limited to:
Malware Attacks: Malicious software that interferes with normal computer operations, damages systems, or gains unauthorized access to data.
Denial-of-Service (DoS) and Distributed Denial-of-Service (DDoS) Attacks: Flood a system with excessive traffic to make it unavailable to legitimate users.
Phishing Attacks: Fake emails, messages, or websites that impersonate trusted organizations to trick users into revealing sensitive information.
Botnets: Networks of infected computers controlled remotely by attackers to carry out large-scale cyberattacks.
Online Financial Fraud: Scammers trick users into sharing sensitive information or money transfer details.


┌──(kali㉿kali)-[/home/kali]
└─PS> tail pract1.txt                ####show last 10 default lines

2. To participate/arrange Cyber Crime Prevention/Awareness programmes in Schools, Colleges and Institutions /Organisations. 

3. Cyber Police Station also provides technical assistance to investigating Officers of the Local Police Stations, Crime Branch Units and other Branches from Mumbai Police. 

4. If any adverse remark or malicious comment is found against the State which might result in a Law & Order problem, the Cyber Police Station, Mumbai sends a request to the  Computer Emergency Response Team, India (CERT-IN) through the Nodal Officer (Joint Commissioner of Police, Crime, Mumbai) (under section 69 A IT Act) or sends a request through getting an Order of the concerned Hon. Court to block the electronic transmission of such content; when request made through email is not accepted by the  website Registrar/Service provider. 

 

5. In Child Pornography and Rape, Gang rape cases, Cyber Police Station, Mumbai works as a nodal for Mumbai Police.
                                                                                                                                                                                                                  
┌──(kali㉿kali)-[/home/kali]                                                                                                                                                                                      
└─PS> tail -n5 pract1.txt                ####show last 5 default lines                                                                                                                                            
4. If any adverse remark or malicious comment is found against the State which might result in a Law & Order problem, the Cyber Police Station, Mumbai sends a request to the  Computer Emergency Response Team, India (CERT-IN) through the Nodal Officer (Joint Commissioner of Police, Crime, Mumbai) (under section 69 A IT Act) or sends a request through getting an Order of the concerned Hon. Court to block the electronic transmission of such content; when request made through email is not accepted by the  website Registrar/Service provider.                                                                                        

 

5. In Child Pornography and Rape, Gang rape cases, Cyber Police Station, Mumbai works as a nodal for Mumbai Police.




┌──(kali㉿kali)-[/home/kali]
└─PS> tail -f pract1.txt                 ###live file monitoring                                                                                                                                                  

2. To participate/arrange Cyber Crime Prevention/Awareness programmes in Schools, Colleges and Institutions /Organisations. 

3. Cyber Police Station also provides technical assistance to investigating Officers of the Local Police Stations, Crime Branch Units and other Branches from Mumbai Police. 

4. If any adverse remark or malicious comment is found against the State which might result in a Law & Order problem, the Cyber Police Station, Mumbai sends a request to the  Computer Emergency Response Team, India (CERT-IN) through the Nodal Officer (Joint Commissioner of Police, Crime, Mumbai) (under section 69 A IT Act) or sends a request through getting an Order of the concerned Hon. Court to block the electronic transmission of such content; when request made through email is not accepted by the  website Registrar/Service provider. 

 

5. In Child Pornography and Rape, Gang rape cases, Cyber Police Station, Mumbai works as a nodal for Mumbai Police.
