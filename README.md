#Enter name of student and find mobile number of student.

student = [ {'name' : 'rahul', 'mobile':123456789},
			{'name' : 'shubham', 'mobile':987654321},
			{'name' : 'arpan', 'mobile':435678932},
			{'name' : 'vijay', 'mobile':789654321},
			{'name' : 'suraj', 'mobile':236547891},
			{'name' : 'akshay', 'mobile':398765411},
			{'name' : 'ankit', 'mobile':876654326},
			{'name' : 'kunal', 'mobile':556778832},
		]
    
n = input("Enter a name of student....\n")

for item in student:
	if item['name'] == n:
		print("Mobile=",item['mobile'])
