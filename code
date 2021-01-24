from replit import clear

print(logo)
#HINT: You can call clear() to clear the output in the console.

name = input("What is your name?: ")
bid = int(input("What's your bid?: "))
another_bidder = input("Are there any other bidders? Type 'yes' or 'no'.\n")

auction = {}
auction[name] = bid

while another_bidder == 'yes':
  clear()
  name = input("What is your name?: ")
  bid = int(input("What's your bid?: "))
  another_bidder = input("Are there any other bidders? Type 'yes' or 'no'.\n")
  auction[name] = bid


max_bid = 0
for name in auction:
  if max_bid < auction[name]:
    max_bid = auction[name]
print(f"The winner is {name} with a bid of {auction[name]}")
