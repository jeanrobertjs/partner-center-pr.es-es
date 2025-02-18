---
title: Transición de clientes al plan de Azure | Centro de partners
ms.topic: article
ms.date: 10/15/2019
description: ''
author: LauraBrenner
ms.author: labrenne
Keywords: ''
robots: ''
ms.localizationpriority: high
ms.openlocfilehash: 34895de69eaa1aed16a485ddec032769f8dfc7a3
ms.sourcegitcommit: cd90a59ff0ea81197b603abcb7bf462c4fb1edbe
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 10/09/2019
ms.locfileid: "72171291"
---
# <a name="transition-your-customers-to-azure-plan"></a>Transición de clientes al plan de Azure

Los partners podrán realizar la transición de sus clientes desde recursos de comercialización (GTM) o desde ofertas existentes de Azure en CSP, hacia la nueva experiencia comercial disponible en el programa CSP para Azure. Gracias a ello, los clientes tendrán una forma simplificada de comprar servicios en la nube, ya sea comprando a partners, vendedores de Microsoft o directamente en la web. La capacidad de transición es solo para clientes que hagan la transición a la nueva experiencia comercial y que hayan firmado el Acuerdo de cliente de Microsoft; no se aplica a otras ofertas en CSP como Office 365 o Dynamics 365.

## <a name="transition-existing-csp-offers-to-an-azure-plan"></a>Transición de ofertas de CSP existentes a un plan de Azure

Puedes hacer la transición de un cliente desde sus ofertas existentes de Azure en CSP hacia los servicios de Azure que se incluyen en el plan de Azure, en la nueva experiencia comercial del programa CSP mediante el Centro de partners. Esta transición requiere solo lo siguiente:

- El partner y el cliente final deben tener una relación de vendedor establecida a través del Centro de partners, y el cliente debe haber firmado el Acuerdo de cliente de Microsoft.

### <a name="select-transition-to-azure-plan"></a>Seleccionar la transición al plan de Azure

1. Selecciona el plan de Azure para su cliente.

2. Selecciona la **transición de facturación al plan de Azure**.

![transición](images/azure/transition1.png)

3. Selecciona **Continue** (Continuar)

![transición](images/azure/transition2.png)

Esto te llevará a Azure Portal donde se produce la transición. Tu cliente pasará al plan de Azure sin la necesidad de hacer nada más. 

**El flujo de trabajo de la transición automatiza los pasos de requisitos previos**: 

- Compra de planes de Azure 
- Un plan por cliente en escenarios de CSP directo  
- Un plan por vendedor  

Por ejemplo, un partner compra dos ofertas de Microsoft Azure e incluye dos POR diferentes en la compra. En este caso, el flujo de trabajo de la transición comprará dos planes de Azure (uno por cada vendedor) y asignará las suscripciones de Azure respectivas de los planes de Azure automáticamente.  

**Asignación de la suscripción de Azure al plan de Azure**

Después de comprar los planes de Azure, nuestro sistema asignará las suscripciones de Azure existentes a los planes de Azure. El progreso se puede ver en Azure Portal, así como en el Centro de partners. 

4. Regresa a la página de **suscripciones**  del Centro de partners del cliente para actualizar el límite de presupuesto con su moneda local. 

![Transición](images/azure/transition3.png)

>[!Note]
>El presupuesto que establezcas en el Centro de partners no se transferirá a Azure Portal. Recuerda que también debes establecer el presupuesto y la alerta en Azure Portal.

Cuando pases al plan de Azure, ya no podrás comprar suscripciones de Azure para este cliente. Deberás crear las suscripciones según el plan de Azure en Azure Portal.

### <a name="track-your-transition-details"></a>Seguimiento de los detalles de la transición

Sigue el progreso de la transición en Azure Portal, así como en el Centro de partners.

![Mostrar detalles](images/azure/details1.png)

**Impacto de la facturación en los socios**

Si realizas la transición de un cliente desde una oferta existente de Azure en CSP, se aplicarán los siguientes puntos de facturación:

- Se le cargará en su factura de CSP existente todo el uso hasta el momento de la salida de la suscripción de Azure original en CSP.

- Si tenía derechos de acceso de administrador en la suscripción de CSP existente, continuará teniendo acceso cuando se migre esa suscripción.

Para realizar la transición de los Contratos Enterprise directos a las inscripciones de CSP y de servidor y de nube a los servicios de Azure, consulta [Obtener la propiedad de facturación de las suscripciones de Azure para Microsoft Partner Agreement]().

**Registro de auditoría**:

Para conciliar la facturación, consulta tu historial de suscripciones de "Microsoft Azure" (0145P) en la página de **suscripciones**. 

La suscripción a "Microsoft Azure" (0145P) consta de dos partes:
1. Suscripción comercial 
2. Suscripción de Azure (derecho)

Cuando se completa la transición, la suscripción de Azure se administra en función del nuevo plan de Azure, y la suscripción comercial se suspende para que no se notifique ningún uso adicional.  

>[Nota]: Cuando la suscripción de Microsoft Azure (0145P) se compra en CSP, tanto la suscripción comercial como la de Azure (derecho) tienen el mismo valor. Solo en el caso de realizar cambios o transferencias en la propiedad de facturación difieren los valores. 

**Errores**

No se prevé ningún error durante las transiciones. Si se produce alguno, lo actualizaremos en el flujo de trabajo de la transición. No habrá ninguna interrupción mientras use Azure.  

**Pasos siguientes**

- [Administrar suscripciones y recursos en el plan de Azure](azure-plan-manage.md)

- [Créditos obtenidos del partner: introducción](partner-earned-credit.md)



