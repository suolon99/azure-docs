---
author: cynthn
ms.service: virtual-machines
ms.topic: include
ms.date: 10/26/2018
ms.author: cynthn
---
The following table lists the possible upload and capture combinations of Linux generalized and specialized OS images. The combinations that will process without any errors are indicated by a Y, and those that will throw errors are indicated by an N. The causes and resolutions for the different errors you will run into are given below the table.

| OS | Upload spec. | Upload gen. | Capture spec. | Capture gen. |
| --- | --- | --- | --- | --- |
| Linux gen. |N<sup>1</sup> |Y |N<sup>3</sup> |Y |
| Linux spec. |Y |N<sup>2</sup> |Y |N<sup>4</sup> |

