To enable loading the profile from this repo...

First, run this to enable script execution:

    Set-ExecutionPolicy Bypass -Scope CurrentUser

Open your powershell profile, creating its directory if needed:

    mkdir -Force (ls $profile).Directory.FullName
    EDIT $profile

And add this line to the file and save:

    . ~/psprofile/profile.ps1