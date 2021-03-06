# <a name="uninstallation-instructions"></a>Инструкции по удалению

## <a name="using-command-prompt"></a>Использование командной строки
1.  Откройте окно **Командная строка**.
2.  Запустите [Windows Update Standalone Launcher](https://support.microsoft.com/en-us/kb/934307) (Автономное средство запуска Центра обновления Windows), как показано ниже:

В Windows Server 2012 R2 и Windows 8.1:
```powershell
wusa /uninstall /kb:3134758
```
В Windows Server 2012:
```powershell
wusa /uninstall /kb:3134759
```
В Windows Server 2008 R2 с пакетом обновления 1 (SP1) и Windows 7 с пакетом обновления 1 (SP1):
```powershell
wusa /uninstall /kb:3134760
```

## <a name="using-control-panel"></a>Использование панели управления
1.  Откройте **Панель управления**.
2.  Откройте **Программы** и выберите **Удаление программы**.
3.  Щелкните **Просмотр установленных обновлений**.
4.  Выберите **Windows Management Framework 5.0** в списке установленных обновлений. Это соответствует *KB3134758*, *KB3134759* или *KB3134760*. Щелкните **Удалить**.
