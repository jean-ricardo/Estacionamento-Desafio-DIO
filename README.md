# DIO - Trilha .NET - Fundamentos
www.dio.me

## Desafio de projeto
Para este desafio, você precisará usar seus conhecimentos adquiridos no módulo de fundamentos, da trilha .NET da DIO.

## Contexto
Building a parking system, designed to manage parked vehicles and carry out operations such as adding, removing, and listing a vehicle. Upon vehicle removal, the total amount to be paid should be displayed.

## Proposta
Create a class named "ParkingLot" with three variables:

initialPrice: Decimal type. It is the fee charged for leaving your vehicle parked.

pricePerHour: Decimal type. It is the hourly rate for the vehicle's parking.

vehicles: A list of strings representing a collection of parked vehicles. It only contains the vehicle's license plate.

The class includes three methods:

AddVehicle: A method responsible for receiving a user-scanned license plate and saving it to the list of vehicles.

VehicleRemover: A method responsible for checking if a specific vehicle is parked. If positive, it will ask for the number of hours the vehicle has been in the parking lot. Afterward, perform the following calculation: initialPrice * pricePerHour, displaying it to the user.

ListVehicles: Lists all vehicles currently in the parking lot. If there are none, display the message "No vehicles parked."

Finally, an interactive menu with the following actions should be implemented:

1.Register vehicle
2.Vehicle remover
3.List vehicles
4.End
