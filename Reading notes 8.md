Reading 08: https://www.howtogeek.com/370022/windows-registry-demystified-what-you-can-do-with-it/
   
   Vocabulary:
        BSoD: Blue screen of death that will contain memory addressing and stop code
        
   Reading: 
   
        -Windows registry is a collection of several databases containing system registry settings found at C:\Windows\System32\Config\ in Win7/Win10
   
         -consists of groups of keys and values called hives
   
        -developers can decide how and if they want to use the registry
   
         -some actions can only be done in registry; useful to look up "registry hacks" for these
   
        -best practice to backup registry before making changes
   
         - can edit registry through program regeit.exe
         
         - can download asnd run .reg files that contains reg changes; useful for complex "registry hacks"
   
    Lecture Notes: 
        Event Viewer: Success Audit is successful security attempt (like login) while Failure Audit is denied/failed security attempt (like a failed login)
        Windows Registry: A local database for storing critical configurations for the PC that windows references for many aspects of OS behavior. 
          Can find profiles for each user or configurations for installed apps
          The registry contains registry "values" which are instructions, located with registry "keys"
          "Keys" are folders thast contain more data
          "hives" large sections that contain many other things
          
          Script notes: @echo off turns off "flash"
          Save notepad script as .bat file (batch). Right+click on file and run as admin
          Task Scheduler: Can create tasks, such as running one on login
        
    The registry is something I always had questions about but never really understood. Changing settings in the lab and reading about it really hasd "demystified" it to an extent and I'm sure I'll use this knowledge in the future
