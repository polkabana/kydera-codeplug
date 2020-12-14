# kydera-codeplug
Kydera CDR-300UV codeplug manipulations (c) 2020, EU1ADI

Download / upload codeplug from/to Kydera CDR-300UV / Retevis RT73

Exprot/Import codeplug to/from CSV file

But now you can only some manipulations (like change order or name) with zones and channels order. Main reason for this program - change channels order in codeplug. Native CPS_DRS can't allow this, only add or del zones and channels.

## Usage

`kydera.exe -help`

`kydera.exe -read -codeplug file.bin` - Download code plug from radio to file

`kydera.exe -export -codeplug file.bin -csv file.csv` - Export from binary codeplug to CSV file

At this point you can edit CSV file: rename zone; change channels order, name. You can't change total count of zones and channels. May be this will be fixed later. DON'T change hexadecimal data.

`kydera.exe -import -codeplug file.bin -csv file.csv` - Export from CSV file to binary codeplug

`kydera.exe -write -codeplug file.bin` - Upload code plug to radio from file

## Download

`kydera.zip` - compiled x64 version

`kydera.x86.zip` - compiled x86 version
