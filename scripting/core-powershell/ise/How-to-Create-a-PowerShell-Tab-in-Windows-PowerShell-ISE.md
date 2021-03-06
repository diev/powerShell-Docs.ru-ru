---
description: 
manager: carmonm
ms.topic: article
author: jpjofre
ms.prod: powershell
keywords: "powershell,командлет"
ms.date: 2016-12-12
title: "Создание вкладки PowerShell в интегрированной среде сценариев Windows PowerShell"
ms.technology: powershell
ms.assetid: c10c18c7-9ece-4fd0-83dc-a19c53d4fd83
ms.openlocfilehash: 1c57e557e2fefbdf67b6a3c71721cd2a916a0ec5
ms.sourcegitcommit: 8acbf9827ad8f4ef9753f826ecaff58495ca51b0
translationtype: HT
---
# <a name="how-to-create-a-powershell-tab-in-windows-powershell-ise"></a>Создание вкладки PowerShell в интегрированной среде сценариев Windows PowerShell
Вкладки в интегрированной среде скриптов Windows PowerShell® позволяют одновременно создавать и использовать несколько сред выполнения внутри одного приложения. Каждая вкладка PowerShell соответствует отдельной среде выполнения или отдельному сеансу.

> [!NOTE]
> Переменные, функции и псевдонимы, созданные на одной вкладке, на другую не переносятся. Это разные сеансы Windows PowerShell.

Выполните следующие действия, чтобы открыть или закрыть вкладку в Windows PowerShell. Чтобы переименовать вкладку, задайте свойство [DisplayName](The-PowerShellTab-Object.md#Displayname) для объекта сценария на вкладке Windows PowerShell.

## <a name="to-create-and-use-a-new-powershell-tab"></a>Создание и использование вкладки PowerShell
В меню **Файл** щелкните элемент **Создать вкладку PowerShell**. Новая вкладка PowerShell всегда открывается в виде активного окна. Вкладки PowerShell нумеруются последовательно в порядке их открытия. Каждая вкладка связана с собственным окном консоли Windows PowerShell. Одновременно можно открыть до 32 вкладок PowerShell со своим сеансом (в интегрированной среде сценариев Windows PowerShell 2.0 это ограничение равно 8).

Обратите внимание, что нажатие значка **Создать** или **Открыть** не приводит к созданию вкладки с отдельным сеансом.  Эти кнопки открывают новый или существующий файл сценария на активной вкладке с сеансом. Для каждой вкладки и сеанса можно открыть несколько файлов сценариев. Вкладки сценариев для сеанса отображаются под вкладками сеанса, только когда соответствующий сеанс активен.

Чтобы сделать вкладку PowerShell активной, щелкните ее. Чтобы выбрать одну из всех открытых вкладок PowerShell, щелкните ее в меню **Вид**.

## <a name="to-create-and-use-a-new-remote-powershell-tab"></a>Создание и использование вкладки удаленного использования PowerShell
В меню **Файл** щелкните **Создание вкладки удаленного использования PowerShell** для создания сеанса на удаленном компьютере. Отображается диалоговое окно, предлагающее ввести сведения для установки удаленного подключения. Удаленная вкладка PowerShell работает так же, как и локальная, только команды и сценарии выполняются на удаленном компьютере.

## <a name="to-close-a-powershell-tab"></a>Закрытие вкладки PowerShell
Чтобы закрыть вкладку, можно использовать любой из следующих способов:

-   Щелкните вкладку, которую требуется закрыть.

-   В меню **Файл** щелкните **Закрыть вкладку PowerShell** или нажмите кнопку "Закрыть" (**X**) на активной вкладке для ее закрытия.

Если на закрываемой вкладке PowerShell имеются несохраненные файлы, вам будет предложено сохранить их или отменить изменения. Дополнительные сведения о сохранении сценария см. в статье [Сохранение скрипта](https://technet.microsoft.com/library/162f594d-efd3-4234-9960-45e56e6eadc8).

## <a name="see-also"></a>См. также
- [Использование интегрированной среды сценариев Windows PowerShell](Using-the-Windows-PowerShell-ISE.md)
- [Использование области консоли в интегрированной среде сценариев Windows PowerShell](How-to-Use-the-Console-Pane-in-the-Windows-PowerShell-ISE.md)

