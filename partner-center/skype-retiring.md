---
title: Migrar las suscripciones de plan 1 de Skype Empresarial Online a las versiones más modernas de Office 365 | Centro de partners
ms.topic: article
ms.date: 03/15/2019
Description: Transición de los clientes con la que va a expirar Skype para Business Online Plan 1 de suscripciones a una opción admitida de SKU. Se recomienda mover los clientes para nuevas suscripciones antes de la fecha de finalización de la suscripción anual.
author: LauraBrenner
ms.author: labrenne
keywords: Planes de Skype Empresarial que retiran Skype y Office 365
ms.localizationpriority: medium
ms.custom: seodec18
ms.openlocfilehash: e71e6b05b5ea489b2b6b486f388f5c575dfd02c5
ms.sourcegitcommit: b1ab80345b4e4af649fb8cc51d96d798e0791ade
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 04/23/2019
ms.locfileid: "62133934"
---
# <a name="migrate-skype-for-business-online-plan-1-subscriptions-to-newer-office-365-versions"></a>Migrar las suscripciones de plan 1 de Skype Empresarial Online a las versiones más modernas de Office 365

**Se aplica a**

- Centro de partners

El plan 1 de Skype Empresarial Online se retirará con efectividad desde el 1 de agosto de 2018. Después de esa fecha, los clientes ya no pueden adquirir nuevas suscripciones del plan 1 de Skype Empresarial y las suscripciones existentes no se renovarán automáticamente cuando caduquen, no proporcionando opción de renovación. En la página de detalles de la suscripción, el estado de la suscripción del plan 1 de Skype Empresarial Online ha cambiado a "Expira el [fecha]" desde "Se renueva automáticamente en [fecha]".  

Para garantizar la continuidad para los clientes, debes pasar a los clientes con suscripciones del plan 1 de Skype Empresarial Online a una opción de SKU compatible, enumerada a continuación. Te recomendamos mover los clientes a las nuevas suscripciones antes de la fecha de finalización para evitar interrupciones en el servicio a los clientes. 

>[!NOTE]
>Se retiran tanto el plan 1 de Skype Empresarial Online como los SKU de entidades gubernamentales.

Si usas la API (CREST o Centro de partners), puedes descubrir suscripciones a punto de expirar mediante la evaluación de la fecha de finalización de la suscripción junto con la renovación automática = Propiedad de valor False. Las suscripciones del plan 1 de Skype Empresarial Online estarán establecidas con renovación automática = False el 1 de septiembre de 2018. Puedes mover a los clientes a un plan nuevo en cualquier momento. 

## <a name="skype-for-business-online-plan-1-replacement-plans"></a>Planes de sustitución del plan 1 de Skype Empresarial Online

Con los nuevos planes, los clientes pueden aprovechar las funciones y la funcionalidad más recientes de Office 365. Los detalles de precios se encuentran en la lista de precios y en la matriz de lista de ofertas en el Centro de partners. 

- Opción 1: Office 365 Enterprise F1
- Opción 2: Microsoft 365 Enterprise F1
- Opción 3: Otros planes de Office 365

|**Característica**    |**Opción 1**   |**Opción 2**   |**Opción 3**   |
|:-----------------|:-----------------|:-------------|:------------|
|Obtener todas las funciones incluidas en el plan 1 de Skype Empresarial Online|Sí   |Sí   |Sí   |
|Mensajería instantánea y presencia |Sí   |Sí   |Sí   |
|Audio y vídeo punto a punto a través de IP|Sí   |Sí   |Sí   
|Unirse a reuniones como usuario autenticado| Sí   |Sí   |Sí   |

## <a name="transition-customers-to-new-product-plans"></a>Clientes de transición hacia los nuevos planes de productos

Microsoft ofrece de forma continua nuevos productos y servicios a nuestros partners. En estos casos, podrías tener que actualizar a los clientes con los nuevos servicios o migrar sus suscripciones de SKU que finalmente se apagarán. Migración de los clientes desde SKU retiradas a unas más recientes que requieren los siguiente pasos:

- Comprar la nueva suscripción
- Reasignar licencias de usuario actuales
- Cancelar suscripción antigua

### <a name="migrate-your-customers-to-new-plans"></a>Migrar a los usuarios a nuevos planes

1. Para comprar la nueva suscripción, en la **menú Centro de partners**, seleccione **clientes**, seleccione el cliente que desea mover y, a continuación, seleccione **agregar suscripciones**.

2. Selecciona la suscripción que quieras adquirir del catálogo (en este caso, una de las opciones que se indican más arriba), escribe el número de licencias y, a continuación, **Enviar**. 

El cliente ahora debería tener las suscripciones antiguas y las nuevas, la suscripción del antiguo plan 1 de Skype Empresarial Online y la nueva suscripción de ‘destino’, por ejemplo, Opción 1: Office 365 Enterprise F1.

3. Para volver a asignar las licencias de los usuarios del cliente, desde el **centro de partners** menú, seleccione **clientes**, seleccione el cliente que está moviendo y, a continuación, seleccione **usuarios y licencias** . La página Usuarios y licencias del cliente se abrirá.

4. Para reasignar una licencia de usuario, selecciona el usuario a reasignar y, a continuación, selecciona **Administrar licencias**.

5. En la página **Administrar licencias** desactiva la casilla de la licencia del pan 1 de Skype Empresarial Online y selecciona un nuevo plan de servicios para la suscripción a la que se está moviendo al cliente.

6. Selecciona **Enviar**. Una página de confirmación enumera las nuevas asignaciones de licencias. Sigue este mismo proceso para otros usuarios que necesiten asignaciones de licencias.

Después de mover las licencias de usuario al nuevo servicio, puedes cancelar de forma segura la suscripción retirada al nivel de cliente.

7. Desde el **centro de partners** menú, seleccione **clientes**. Selecciona el cliente cuya suscripción estés cancelando.

8. En la página de detalles de suscripción, establece el estado de la suscripción en **Suspendida**.

9. Selecciona **Enviar**.

Se ha suspendido la suscripción antigua y la nueva suscripción está activa. Se cancelará el aprovisionamiento de la suscripción suspendida automáticamente después de 120 días. El cliente no incurre en costos adicionales para la suscripción antigua.

