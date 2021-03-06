---
description: 
manager: carmonm
ms.topic: article
author: jpjofre
ms.prod: powershell
keywords: "powershell,командлет"
ms.date: 2016-12-12
title: "Запуск 32-разрядной версии Windows PowerShell"
ms.technology: powershell
ms.assetid: 12b31890-2609-4a76-8c24-0ebe78084f50
ms.openlocfilehash: 691818e242600234564479aa97255567760139e0
ms.sourcegitcommit: 8acbf9827ad8f4ef9753f826ecaff58495ca51b0
translationtype: HT
---
# <a name="starting-the-32-bit-version-of-windows-powershell"></a>Запуск 32-разрядной версии Windows PowerShell
При установке Windows PowerShell на 64-разрядном компьютере в дополнение к 64-разрядной версии устанавливается **Windows PowerShell (x86)** — 32-разрядная версия Windows PowerShell. При открытии Windows PowerShell по умолчанию запускается 64-разрядная версия.

Однако в некоторых случаях нужно запустить **Windows PowerShell (x86)**, например при использовании модуля, которому требуется 32-разрядная версия, или при удаленном подключении к 32-разрядному компьютеру.

Для запуска 32-разрядной версии Windows PowerShell воспользуйтесь любой из следующих процедур.

#### <a name="in-windows-server-2012-r2"></a>Windows Server® 2012 R2

-   На экране **Пуск** щелкните **Windows PowerShell (x86)**. Щелкните плитку **Windows PowerShell x86**.

-   Выберите пункт **Windows PowerShell (x86)** в меню **Сервис** **диспетчера сервера**.

-   На рабочем столе переместите курсор в правый верхний угол, щелкните элемент **Поиск**, введите **PowerShell x86** и выберите **Windows PowerShell (x86)**.

-   В командной строке введите следующее: `%SystemRoot%\SysWOW64\WindowsPowerShell\v1.0\powershell.exe`

#### <a name="in-windows-server-2012"></a>Windows Server® 2012

-   На экране **Пуск** введите **PowerShell** и выберите **Windows PowerShell (x86)**.

-   Выберите пункт **Windows PowerShell (x86)** в меню **Сервис** **диспетчера сервера**.

-   На рабочем столе переместите курсор в правый верхний угол, щелкните элемент **Поиск**, введите **PowerShell** и выберите **Windows PowerShell (x86)**.

-   В командной строке введите следующее: `%SystemRoot%\SysWOW64\WindowsPowerShell\v1.0\powershell.exe`

#### <a name="in-windows-81"></a>Windows® 8.1

-   На экране **Пуск** щелкните **Windows PowerShell (x86)**. Щелкните плитку **Windows PowerShell x86**.

-   Если вы используете [средства удаленного администрирования сервера](http://go.microsoft.com/fwlink/?LinkID=304145) для Windows 8.1, можно также открыть Windows PowerShell x86 из меню **Сервис** диспетчера сервера. Выберите **Windows PowerShell (x86)**.

-   На рабочем столе переместите курсор в правый верхний угол, щелкните элемент **Поиск**, введите **PowerShell x86** и выберите **Windows PowerShell (x86)**.
   
-   В командной строке введите следующее: `%SystemRoot%\SysWOW64\WindowsPowerShell\v1.0\powershell.exe`

#### <a name="in-windows-8"></a>Windows® 8

-   На экране **Пуск** переместите курсор в правый верхний угол, щелкните **Параметры**, **Плитки**, а затем переместите ползунок **Показать средства администрирования** в значение "Да". Введите **PowerShell** и выберите **Windows PowerShell (x86)**.

-   Если вы используете [средства удаленного администрирования сервера](http://www.microsoft.com/download/details.aspx?id=28972) для Windows 8, можно также открыть Windows PowerShell x86 из меню **Сервис** диспетчера сервера. Выберите **Windows PowerShell (x86)**.

-   На экране **Пуск** или рабочем столе введите **PowerShell (x86)** и выберите **Windows PowerShell (x86)**.

-   В командной строке введите следующее: `%SystemRoot%\SysWOW64\WindowsPowerShell\v1.0\powershell.exe`

