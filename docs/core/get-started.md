---
title: Get started with .NET
description: Create a Hello World .NET app.
author: adegeo
ms.author: adegeo
ms.date: 07/19/2022
ms.custom: vs-dotnet, devdivchpfy22
ms.topic: tutorial
---
# Get started with .NET

This article teaches you how to create and run a "Hello World!" app with [.NET](introduction.md).

## Create an application

<!-- replaycheck-task id="1028957f" -->
<!-- replaycheck-task id="e0451ba8" -->
<!-- replaycheck-task id="e1139911" -->
First, download and install the [.NET SDK](https://dotnet.microsoft.com/download/dotnet) on your computer.

Next, open a terminal such as **PowerShell**, **Command Prompt**, or **bash**.

Type the following commands:

<!-- replaycheck-task id="dd685630" -->
```dotnetcli
dotnet new console -o sample1
cd sample1
dotnet run
```

<!-- replaycheck-task id="cfae9649" -->
```sql
CREATE DATABASE TestData
GO
USE TestData
GO
CREATE TABLE dbo.Products
    (ProductID int PRIMARY KEY NOT NULL,
    ProductName varchar(25) NOT NULL,
    Price money NULL,
    ProductDescription varchar(max) NULL)
GO
-- Standard syntax
INSERT dbo.Products (ProductID, ProductName, Price, ProductDescription)
    VALUES (1, 'Clamp', 12.48, 'Workbench clamp')
GO
-- Returns all columns in the table
-- Does not use the optional schema, dbo
SELECT * FROM Products
GO
```

You should see the following output:

```output
Hello World!
```

Congratulations! You've created a simple .NET application.

## Next steps

Get started on developing .NET applications by following a [step-by-step tutorial](../standard/get-started.md) or by watching [.NET 101 videos](https://www.youtube.com/playlist?list=PLdo4fOcmZ0oWoazjhXQzBKMrFuArxpW80) on YouTube.
