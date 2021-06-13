# GOLDMAN-SACHS---CRACK-LEAKED-PASSWORD-DATABASE
# Password Controls and Security Policies
# Overview
As a governance analyst, it is part of your duties to assess the level of protection offered by implemented controls and minimize the probability of a successful breach. You often need to know the techniques used by hackers to circumvent implemented controls and propose uplifts to increase the overall level of security in an organization. Gaining valid credentials gives the attackers access to the organization’s IT system, thus circumventing most of the perimeter controls in place.
# Project Objective
What type of hashing algorithm was used to protect passwords?
What level of protection does the mechanism offer for passwords?
What controls could be implemented to make cracking much harder for the hacker in the event of a password database leaking again?
Here is a sample data file containing hashes dumped together:

https://github.com/ne3lakolkar/Goldman-Sachs-Crack-Leaked-Passsword-Database/blob/main/passwd_dump.txt

After overall analysis, it was determined that the organization uses an outdated password hashing algorithm (MD5) which offers very little protection in the event of a password database leaking. It was also set on that the current password policy is not line up with industry best practices allowing users to have short passwords (6 characters) and reuse usernames as part of passwords.

As a result of the analysis the following uplifts are proposed to increase the overall level of password protection:

●	There are currently three hashing algorithms that are safe to use: 1.PBKDF2 2. Bcrypt 3. scrypt. Passwords should be hashed with either PBKDF2, bcrypt, or scrypt these will greatly increase the time needed to crack individual passwords, Currently, the most vetted hashing algorithm providing most security is bcrypt.

●	Commonly used modern hashing algorithms include Message Digest (MDx) algorithms, such as MD5, and Secure Hash Algorithms (SHA), such as SHA-1 and the SHA-2 family that includes the widely used SHA-256 algorithm. 

●	Using salting to prevent usage of rainbow table attacks to speed up cracking

●	The key aspects of a strong password are length (the longer the better); a mix of letters (upper and lower case), numbers, and symbols this will increase the computational effort required to crack the password and will give additional time to change all passwords in the event of the password database being leaked.

●	Prevent passwords that have no ties to your username or a password of all digits or all the same letter or reuse usernames as part of passwords such a password combination is easy to check without gaining access to the password database itself.

●	The secret to designing a hard-to-crack password that’s unique and easy to remember is to focus on making it memorable and making it hard to guess. Having a password policy is required, long passwords with a number of special characters results in users writing passwords down or constantly resetting them. The best way to create a strong and user-friendly password is by using passphrases (e.g.PasswordforaFacebookaccount). The best way to create such passwords is to blend a couple of totally random words. It’s also directed to use some special characters and numbers as easy-to-remember substitutions to expand the keyspace(Pwrd4Acct-Fb).

●	System and network administrators must create policies and procedures for site security, including password administration. Users must be made aware of these policies on creating a safe and easy password because when users use weak passwords, you make it easier and faster for hackers to succeed. This is a risk to both user accounts and administrative accounts.

# Project Report and Observations
Completing this task assigned by Goldman Sachs, MD5 and SHA were the two algorithms that I came across. After examining the passwords and their respective security algorithms used, I jot down my observations into this report.

●	Guide users on the benefits of password managers, a password manager is a book of your passwords, locked by a master key that only you know. If you’ve chosen a strong and unique, but easy-to-remember master password, you’ve established a near-perfect way to protect the rest of your personal passwords from improper access.

# Project Report
<div class="highlight">
    <pre>
        <code>
Dear Sir/Ma’am

I tried to crack all the leaked hashes, I found several threats in your password policy and this email concludes all the findings and pieces of suggestion to improve your password policy.
Secure Hash Algorithm (SHA) and Message Digest (MD5) are the standard cryptographic hash functions to provide data security for authentication.

All the passwords which hold were using MD5 which is a hash algorithm that is weak and is prone to collisions. It was very simple to crack with Hashcat.com and rockyou.txt wordlist via terminal and web browsers. 
I would suggest that you use a very strong password encryption mechanism to create hashes for the password based on SHA.
After cracking the passwords, we find the following things about the organization’s password policy:

●	Minimum length for a password is set to 6.
●	There is no specific requirement for password creation. Users can use any combinations of characters, numbers, as well as upper- and lower-case letters.

I would like to change several new things in the password policy and I can say I would recommend these for your organization:
●	Set Minimum Password Length like 8 characters is a starting point, a minimum character length of 14 characters becomes a better standard.
●	Utilize Passphrases, these can be used with a 15-character minimum length that is easier to remember and type, but harder to gain access to.
●	Make sure they do not reference the legal name, username, date of birth, or any other personal information while creating a password.
●	Robust passwords also utilize combinations of special characters, numbers, as well as upper- and lower-case letters.
●	Don’t reuse your passwords.
●	Set Minimum and Maximum Password Age Limits, Setting a maximum password age limit also helps with network security.
●	Usually, this is set anywhere from 90 days for passwords to 180 days for passphrases.
●	Instruct your users to follow these policies regularly to keep their passwords safe and secure.

Thanking you, 
Name: Keerthi Chukka
B.Tech Information Technology
</code>
    </pre>
</div>

# Observations:
<div class="highlight">
    <pre>
        <code>
        
Security Algorithms used: 
experthead:e10adc3949ba59abbe56e057f20f883e – MD5
interestec:25f9e794323b453885f5181f1b624d0b – MD5
ortspoon:d8578edf8458ce06fbc5bb76a58c5ca4 –MD5
reallychel:5f4dcc3b5aa765d61d8327deb882cf99 –MD5
simmson56:96e79218965eb72c92a549dd5a330112 – MD5
bookma:25d55ad283aa400af464c76d713c07ad – MD5 
popularkiya7:e99a18c428cb38d5f260853678922e03 – MD5
eatingcake1994:fcea920f7412b5da7be0cf42b8c93759 – MD5 
heroanhart:7c6a180b36896a0a8c02787eeafb0e4c – MD5
edi_tesla89:6c569aabbf7775ef8fc570e228c16b98 – MD5
liveltekah:3f230640b78d7e71ac5514e57935eb69 – MD5
blikimore:917eb5e9d6d6bca820922a0c6f7cc28b – MD5
johnwick007:f6a0cb102c62879d397b12b62c092c06 – MD5
flamesbria2001:9b3b269ad0a208090309f091b3aba9db – MD5
oranolio:16ced47d3fc931483e24933665cded6d - MD5
spuffyffet:1f5c5683982d7c3814d4d9e6d749b21e - MD5
moodie:8d763385e0476ae208f21bc63956f748 - MD5
nabox:defebde7b6ab6f24d5824682a16c3ae4 - MD5
bandalls:bdda5f03128bcbdfa78d8934529048cf - MD5

Cracked Passwords:

Reallychel:5f4dcc3b5aa765d61d8327deb882cf99 = password
bookma: 25d55ad283aa400af464c76d713c07ad = 12345678
popularkiya7: e99a18c428cb38d5f260853678922e03 = abc123
Ortspoon: d8578edf8458ce06fbc5bb76a58c5ca4 = qwerty
experthead: e10adc3949ba59abbe56e057f20f883e = 123456
heroanhart:7c6a180b36896a0a8c02787eeafb0e4c - password1
edi_tesla89:6c569aabbf7775ef8fc570e228c16b98 - password!
liveltekah:3f230640b78d7e71ac5514e57935eb69 - qazxsw
blikimore:917eb5e9d6d6bca820922a0c6f7cc28b - Pa$$word1
johnwick007:f6a0cb102c62879d397b12b62c092c06 - bluered

</code>
    </pre>
</div>

# Resources

https://arstechnica.com/information-technology/2013/05/how-crackers-make-minced-meat-out-of-your-passwords/
https://howsecureismypassword.net/
https://en.wikipedia.org/wiki/Password_cracking#Software
https://en.wikipedia.org/wiki/Salt_(cryptography)
https://hashcat.com
https://dzone.com/articles/crack-hashed-passwords-with-hashcat

  
     






