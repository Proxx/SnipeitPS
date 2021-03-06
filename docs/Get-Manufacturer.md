---
external help file: SnipeItPS-help.xml
Module Name: SnipeItPS
online version: http://go.microsoft.com/fwlink/?LinkId=821589
schema: 2.0.0
---

# Get-Manufacturer

## SYNOPSIS
# Gets a list of Snipe-it Manufacturers

## SYNTAX

```
Get-Manufacturer [[-search] <String>] [-url] <String> [-apiKey] <String>
```

## DESCRIPTION
{{Fill in the Description}}

## EXAMPLES

### -------------------------- EXAMPLE 1 --------------------------
```
Get-Manufacturer -url "https://assets.example.com" -token "token..."
```

### -------------------------- EXAMPLE 2 --------------------------
```
Get-Manufacturer -url "https://assets.example.com" -token "token..." | Where-Object {$_.name -eq "HP" }
```

## PARAMETERS

### -search
{{Fill search Description}}

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -url
URL of Snipeit system, can be set using Set-Info command

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 2
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -apiKey
Users API Key for Snipeit, can be set using Set-Info command

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 3
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

