#include "./common/header.md"

# Remove-VSTeamAccount

## SYNOPSIS
#include "./synopsis/Remove-VSTeamAccount.md"

## SYNTAX

```
Remove-VSTeamAccount [-Force] [-Level <String>]
```

## DESCRIPTION
Clears the environment variables that hold your default project, account and personal access token.
You have to run Add-VSTeamAccount again before calling any other functions.

To remove from the Machine level you must be running PowerShell as administrator.

## EXAMPLES

### -------------------------- EXAMPLE 1 --------------------------
```
PS C:\> Remove-VSTeamAccount
```

This will clear your account name and personal access token.

## PARAMETERS

### -Level
On Windows allows you to clear your account information at the Process, User or
 Machine levels.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

#include "./params/force.md"

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Add-VSTeamAccount](Add-VSTeamAccount.md)