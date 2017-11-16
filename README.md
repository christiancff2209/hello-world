#Modified by: Christian Caffo
def computeFare(zone, ticketType):
     fare = 0
     if zone <= 2 and ticket == "Adult":
      return "The fare is 23"
     return(fare)
def main():
      z = int(input('Enter the number of zones: '))
      t = input('Enter the ticket type (adult/child): ').lower()
      fare = computeFare(z,t)
      print('The fare is', fare)
 
 #Allow script to be run directly:
 if __name__ == "__main__":
      main()

