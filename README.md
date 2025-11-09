Tested against:

Show-ADTInstallationWelcome -CloseProcesses $adtSession.AppProcessesToClose -CloseProcessesCountdown 30 -ContinueOnProcessClosure
Show-ADTInstallationWelcome -CloseProcesses $adtSession.AppProcessesToClose -CloseProcessesCountdown 30

Show-ADTInstallationWelcome -CloseProcesses $adtSession.AppProcessesToClose -ForceCloseProcessesCountdown 30 -AllowDefer -DeferTimes 3 -ContinueOnProcessClosure
Show-ADTInstallationWelcome -CloseProcesses $adtSession.AppProcessesToClose -ForceCloseProcessesCountdown 30 -AllowDefer -DeferTimes 3

Show-ADTInstallationWelcome -CloseProcesses $adtSession.AppProcessesToClose -AllowDeferCloseProcesses -DeferTimes 3 -ForceCloseProcessesCountdown 300 -ContinueOnProcessClosure
Show-ADTInstallationWelcome -CloseProcesses $adtSession.AppProcessesToClose -AllowDeferCloseProcesses -DeferTimes 3 -ForceCloseProcessesCountdown 300

Show-ADTInstallationWelcome -CloseProcesses $adtSession.AppProcessesToClose -AllowDeferCloseProcesses -DeferTimes 3 -CloseProcessesCountdown 30 -ContinueOnProcessClosure
Show-ADTInstallationWelcome -CloseProcesses $adtSession.AppProcessesToClose -AllowDeferCloseProcesses -DeferTimes 3 -CloseProcessesCountdown 30

:)
