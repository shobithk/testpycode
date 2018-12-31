
print ("User Database\n")
print ("\n")
print ("Add Entry -1\nDelete Entry -2\nDisplay DB -3\nExit -4\n")

ui =input("Enter any of below options - ")
if ui.strip()=='1':
	ui_name=input("Enter Name")
	ui_dob=input("Enter DOB")
	ui_gender=input("Enter Gender")
	with open('database.csv',mode='a') as db_open:
		db_open.write(ui_name +','+ ui_dob+','+ui_gender + '\n')
		db_open.close()
