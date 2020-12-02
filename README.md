# dotnethelloworldconsole


## install dot net 

https://dotnet.microsoft.com/download

dot net ( recommended )

https://docs.microsoft.com/en-us/dotnet/core/install/linux

I use Mint Linux but this is not specifically mentioned so use ubuntu LTS ( see  https://docs.microsoft.com/en-us/dotnet/core/install/linux-ubuntu#2004- ) copy paste and run the cmds to :

add the Microsoft package signing key to your list of trusted keys and add the package repository.
install the DSK

confirm installation. run cmd : dotnet --version
output to console for e.g. 5.0.100

## options 
1. clone repo into a dir
2. run cmd : dotnet new console --output dotnethelloworldconsole ( see https://docs.microsoft.com/en-us/dotnet/core/get-started )

## how to run the console app

run cmd cd dotnethelloworldconsole 
run cmd : dotnet run ( note this generates /bin /obj )

output to console for e.g. 
Hello KLOWN World!
3



