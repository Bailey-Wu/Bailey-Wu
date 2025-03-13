## Some of my favorite AHK Scripts
Resources: https://www.autohotkey.com/docs/v2/

---
~~~
# Sleep Mode (Ctrl + Windows Key + y)

^#y::
DllCall("PowrProf\SetSuspendState", "int", 0, "int", 1, "int", 0)

# Source: https://www.reddit.com/r/AutoHotkey/comments/28kc6j/how_to_put_windows_to_sleep_using_autohotkey/>
~~~
--------------------------------------------------------------------------------------------
~~~
# Script to switch to Microsoft Outlook when the middle mouse button is clicked
; MButton refers to the middle mouse button

MButton::
    ; Check if the Outlook window exists
    IfWinExist, ahk_class rctrl_renwnd32 ; 
    {
        ; Activate the Outlook window
        WinActivate
    }
    else
    {
        ; Display a message if Outlook is not running
        MsgBox, Outlook window not found!
    }
return
~~~
--------------------------------------------------------------------------------------------
~~~
# Manually Submitting Timecard (Ctrl + Win + t)

^#t::
{
Run, "https://company-timecard-website" ;
Sleep 3000
Send, {Tab}
Send, {Tab}
Send, {Tab}
Send, {Tab}
Send, {Down}
Send, {Enter}

Sleep 2000
Send, 8
Send, {Tab}
Send, {Tab}
Send, {Down}
Send, {Enter}
}
Return 
~~~
--------------------------------------------------------------------------------------------
~~~
# Passwords to Corporate Websites
# Script to store passwords for various corporate websites with different password requirements

~~~
--------------------------------------------------------------------------------------------
~~~
# Generic Functions
# Run Calculator
Run calc.exe 

# Prompt Message Box
MsgBox "You pressed AltGr+m."

~~~
--------------------------------------------------------------------------------------------
~~~
