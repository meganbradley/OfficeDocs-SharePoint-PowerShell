---
external help file: sharepointonline.xml
Module Name: Microsoft.Online.SharePoint.PowerShell
online version: https://learn.microsoft.com/powershell/module/sharepoint-online/set-spoorgnewssite
applicable: SharePoint Online
title: Set-SPOOrgNewsSite
schema: 2.0.0
author: trent-green
ms.author: trgreen
---

# Set-SPOOrgNewsSite

## SYNOPSIS

Marks a site as one of multiple possible tenant's organizational news sites. Requires at least SharePoint administrator permissions.

## SYNTAX

```powershell
Set-SPOOrgNewsSite -OrgNewsSiteUrl <string> [<CommonParameters>]
```

## DESCRIPTION

Use this cmdlet to mark a site as an organizational authoritative news site. Such sites get primary treatment in the SharePoint user interface.

If a site with specified URL doesn't exist, this cmdlet returns a "File not found" error.

## EXAMPLES

### Example 1

```powershell
Set-SPOOrgNewsSite -OrgNewsSiteUrl https://contoso.sharepoint.com/sites/Marketing
```

This example marks <https://contoso.sharepoint.com/sites/Marketing> as an organizational news site.

## PARAMETERS

### -OrgNewsSiteUrl

The URL of a site to be marked as an organizational news site.

```yaml
Type: String
Parameter Sets: (All)
Aliases:
Applicable: SharePoint Online

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters

This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](https://go.microsoft.com/fwlink/p/?LinkID=113216).

## RELATED LINKS

[Remove-SPOOrgNewsSite](Remove-SPOOrgNewsSite.md)

[Get-SPOOrgNewsSite](Get-SPOOrgNewsSite.md)
