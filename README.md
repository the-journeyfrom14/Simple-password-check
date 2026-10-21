# Simple-password-check

#.strip() removes spaces on both ends of input but keeps it in the middle

password = input("Enter new password: ").strip()

while len(password) == 0:
	password = input("Please enter new password: ").strip()


while len(password) < 8:
	print("Password to short")
	password = input("Enter New password: ")
	
print("Password accepted")

#21/10/2026 learnt .strip()
