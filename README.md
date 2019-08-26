# Network-PrinterMigration
Powershell script to migrate between network printers on the same print-server.
$OLDPrinter = $Args[0]
$NEWPrinter = $Args[1]
$printserver = $Args[2]

Example:
migrate.ps1 oldprintername newprintername printservername
