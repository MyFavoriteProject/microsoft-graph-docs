---
description: "Automatically generated file. DO NOT MODIFY"
---

```powershell

Import-Module Microsoft.Graph.Calendar

$params = @{
	"@odata.type" = "#Microsoft.OutlookServices.ItemAttachment"
	Name = "name-value"
	Item = @{
		"@odata.type" = "microsoft.graph.message"
	}
}

New-MgUserEventAttachment -UserId $userId -EventId $eventId -BodyParameter $params

```