@echo off
title  Delete LanSchool - AKA Unlock School Computer
got sta

:sta
cls
echo.
echo WARNING: If you are caught, the developer of this program is NOT responsible for your actions. Whatever you do with this file is at your own
echo fault, and can not blame the creator.
echo.
echo Proceed?
echo.
set /p ulock= y/n: 
if "%ulock%" == %y% goto y
if "%ulock%" == %n% goto n

:y
cls
echo.
del /f C:\LanSchool Files
cls
echo Please Restart your Computer.
:n
cls
exit