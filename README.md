# kydera-codeplug
Kydera CDR-300UV codeplug manipulations (c) 2020, EU1ADI

Download / upload codeplug from/to Kydera CDR-300UV / Retevis RT73

Exprot/Import codeplug to/from CSV file

- Zone: add, remove, change
- Channel: add, remove, rename, change rx, tx, power, contact, rx list, scanl list, and order in zone
- Contact: add, remove, change
- ScanList: add, remove, change
- RxList: add, remove, change

## Usage

`kydera.exe -help`

`kydera.exe -read -codeplug file.bin` - Download code plug from radio to file

`kydera.exe -export -codeplug file.bin -csv file.csv` - Export from binary codeplug to CSV file

At this point you can edit CSV file. DON'T change hexadecimal data in channels.

`kydera.exe -import -codeplug file.bin -csv file.csv` - Export from CSV file to binary codeplug

`kydera.exe -write -codeplug file.bin` - Upload code plug to radio from file

## Download

`kydera.zip` - compiled x64 version

`kydera.x86.zip` - compiled x86 version
