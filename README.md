# assignment-3


6946621
CIVIL ENGINEERING 
CE 257 ASSIGNMENT
Question: 
Take it that you visit a car dealership and different varieties of cars are on sale; Generate a code that allows  
A person to input their car brand and they find out whether the car is available or not.(Yes/No)
A person to gain knowledge about the selling price of available cars




#List of available cars and their prices
cars={"McLaren ":308000, "Hennessey Venom F5":450000, "Rimac Nevera":3050000,\
      "Lamborghini aventador ":5036272, "Chevrolet Camaro":553000, "lucran hypersport ":340000,\
      "Cadillac esclade":285000, "Dodge ":400000, "ford  302 Mustang":450000,\
      "Chevrolet Corvette":706282, "Bugatti veron":6004893, "Pagani infinity":1160000,\
       "McLaren P15":95345, "Porsche  Spyder":824636, "Toyota Yaris":639484,\
      "Mercedes  Maybach SV12":625022, "Brabus Amg":790033, "Koenigsegg CCX":585000,\
      "Toyota Camry":490638, "Porsche Carrera GT":490043, "Saleen S7 Twin Turbo":465000,\
      "Ferrari ":448623, "Lamborghini Aventador SVJ":670433, "Brabus Rocket":430000,\
      "McLaren 765LT Spider":675000, "Lexus LFA":375000, "Mercedes-Benz AMG GT Black Series":350000,\
      	"RUF RT12":680000, "Mercedes Benz E class ":245037, "Land cruiser Prado ":250000}
#Get user input for car name
carName= input('Enter car name:')
#Check if car name is in the list of available cars
if carName  in cars:
    print("Yes")
    #if car name is present, get its price
    carPrice = cars[carName]
    print(f"Price of {carName} is ${carPrice}.".format( carName, carPrice))
else:
    #If car name is not available, inform the user
    print(f"{carName} is not available.")
