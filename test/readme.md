# Manually running validation

Manual execution of validation does like this:

Commit updates to dev branch then run:

```powershell
.\validate.ps1
```

If you want to keep the resources created during the validation to inspect them of troubleshoot issues run the validation with the following command:

```powershell
.\validate.ps1 -doNotCleanup
```

Departments must replace the principleId with a validate userid or groupid.  At this point there is no way to pull this from ARM.