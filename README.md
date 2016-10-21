# Spam Reporter    
A BASH script to aid in reporting spamming activity to the proper abuse contacts.    
    
## Install    
$ git clone https://github.com/ProbieK/spamreporter.git    
$ cd spamreporter    
$ sudo chmod +x ./spamreporter    
$ ./spamreporter    
    
## Usage    
1. Import the email addresses you'd like to report for abuse.   
  a. Option 1) will present you with a prompt where you can provide a new line delineated list of email addresses. The path can either be absolute or relative to the ./spamreporter/ directory.    
  b. Option 2) will present you with a prompt where you can type in a single email address and hit [ENTER]    
2. After you import the bad emails, select option 3) to query whois and extract all of the Abuse, Admin, and Tech email addresses listed in the whois directory.    
3. Select option 4) to set the "From" address as it will appear to the receiver of the abuse report.    
4. Select option 5) to review all of your imported data to make sure everything is working and set so far.    
5. Option 6) through 8) are predefined templates of the body of your abuse report. You can edit these to suite your needs.    
6. Option 9) will prompt you to type in your own custom email abuse report. If you use this script for actually sending the abuse report, you will probably use this option 90% of the time.    
7. Option 10) will clean the tmp files and exit the script cleanly.    
    
## How You Can Help    
1. Find bugs and report them. Submit a pull request if you can!    
2. Edit or add email templates to make them more useful... and submit a pull request!    
3. Find better ways of doing things... and submit a pull request!   
4. Be nice and play nice. This is only the second remotely useful script I've ever written.   

## Road Map    
1. Split out the Abuse, Admin, and Tech addresses in the whois lookup so that they can be used independently depending on the selected template.   
2. Have the Template emails open in an editor (similar to Custom option) so that they can be edited easily before sending.    
3. Clean and comment the code better.    
