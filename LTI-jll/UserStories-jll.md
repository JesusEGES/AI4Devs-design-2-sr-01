# Historias de Usuario

## Historia de Usuario 1: Publicar vacantes en LinkedIn

**T�tulo:** Como Responsable de RRHH, quiero publicar vacantes directamente en LinkedIn para atraer candidatos de manera eficiente.

**Descripci�n:** Esta funcionalidad permitir� a los responsables de RRHH publicar vacantes en LinkedIn desde el sistema LTI, sincronizando autom�ticamente los datos de la oferta laboral.

**Criterios de Aceptaci�n:**
- Dado que el Responsable de RRHH tiene una vacante creada en el sistema,
  - Cuando selecciona la opci�n de publicar en LinkedIn,
  - Entonces la vacante se publica correctamente en LinkedIn con todos los datos sincronizados.
- Dado que la publicaci�n en LinkedIn requiere autenticaci�n,
  - Cuando el Responsable de RRHH no ha iniciado sesi�n en LinkedIn,
  - Entonces el sistema solicita autenticarse antes de publicar.

**Equipo:** Backend, Integraci�n API

**Notas adicionales:**
- La integraci�n debe usar la API oficial de LinkedIn.
- Se debe registrar un log de auditor�a para cumplir con el RGPD.

**Estimaci�n:** 16 horas.

## Historia de Usuario 2: Evaluar candidatos con IA

**T�tulo:** Como Reclutador, quiero que el sistema punt�e autom�ticamente a los candidatos para priorizar a los m�s prometedores.

**Descripci�n:** Esta funcionalidad permitir� al reclutador recibir una puntuaci�n autom�tica basada en el an�lisis de los CVs y los requisitos de la vacante, utilizando el motor de IA del sistema.

**Criterios de Aceptaci�n:**
- Dado que el Reclutador ha recibido aplicaciones para una vacante,
  - Cuando accede a la lista de candidatos,
  - Entonces cada candidato tiene una puntuaci�n visible basada en el an�lisis del motor de IA.
- Dado que el motor de IA utiliza criterios configurables,
  - Cuando el Reclutador ajusta los criterios de evaluaci�n,
  - Entonces las puntuaciones se recalculan autom�ticamente.

**Equipo:** Backend, IA

**Notas adicionales:**
- El motor de IA debe ser explicable y cumplir con el RGPD.
- Se debe registrar un log de auditor�a para cada c�lculo de puntuaci�n.

**Estimaci�n:** 20 horas.

## Historia de Usuario 3: Feedback automatizado para candidatos no seleccionados

**T�tulo:** Como Responsable de RRHH, quiero enviar feedback automatizado a los candidatos no seleccionados para cerrar procesos de manera eficiente y profesional.

**Descripci�n:** Esta funcionalidad permitir� al Responsable de RRHH generar y enviar autom�ticamente mensajes personalizados a los candidatos no seleccionados al cerrar una vacante.

**Criterios de Aceptaci�n:**
- Dado que el Responsable de RRHH ha cerrado una vacante,
  - Cuando selecciona la opci�n de enviar feedback automatizado,
  - Entonces los candidatos no seleccionados reciben un mensaje personalizado.
- Dado que el feedback debe ser claro y profesional,
  - Cuando el sistema genera el mensaje,
  - Entonces incluye detalles b�sicos como el nombre del candidato y el puesto aplicado.

**Equipo:** Backend, Notificaciones

**Notas adicionales:**
- El sistema debe permitir personalizar plantillas de mensajes.
- Se debe registrar un log de auditor�a para cada mensaje enviado, cumpliendo con el RGPD.

**Estimaci�n:** 12 horas.

## Historia de Usuario 4: Interfaz para publicar vacantes en LinkedIn

**T�tulo:** Como Responsable de RRHH, quiero una interfaz intuitiva para publicar vacantes en LinkedIn para facilitar el proceso de publicaci�n.

**Descripci�n:** Esta funcionalidad permitir� al Responsable de RRHH utilizar una interfaz gr�fica para seleccionar y publicar vacantes en LinkedIn, mostrando opciones claras y pasos guiados.

**Criterios de Aceptaci�n:**
- Dado que el Responsable de RRHH accede al sistema,
  - Cuando selecciona una vacante para publicar,
  - Entonces se muestra una interfaz con opciones para configurar y confirmar la publicaci�n en LinkedIn.
- Dado que la publicaci�n requiere autenticaci�n,
  - Cuando el Responsable de RRHH no est� autenticado en LinkedIn,
  - Entonces la interfaz muestra un mensaje y un bot�n para iniciar sesi�n.

**Equipo:** Frontend, UX/UI

**Notas adicionales:**
- La interfaz debe incluir validaciones visuales para campos obligatorios.
- Debe mostrar un mensaje de �xito o error tras intentar publicar.

**Estimaci�n:** 14 horas.

## Historia de Usuario 5: Interfaz para evaluar candidatos con IA

**T�tulo:** Como Reclutador, quiero una interfaz que muestre las puntuaciones de los candidatos para facilitar la priorizaci�n.

**Descripci�n:** Esta funcionalidad permitir� al Reclutador visualizar las puntuaciones generadas por el motor de IA en una interfaz clara y ordenada, con opciones para ajustar los criterios de evaluaci�n.

**Criterios de Aceptaci�n:**
- Dado que el Reclutador accede a la lista de candidatos,
  - Cuando visualiza la lista,
  - Entonces cada candidato tiene su puntuaci�n claramente visible.
- Dado que los criterios de evaluaci�n son configurables,
  - Cuando el Reclutador ajusta los criterios desde la interfaz,
  - Entonces las puntuaciones se actualizan en tiempo real.

**Equipo:** Frontend, UX/UI

**Notas adicionales:**
- La interfaz debe permitir ordenar y filtrar candidatos por puntuaci�n.
- Debe incluir una explicaci�n breve de c�mo se calculan las puntuaciones.

**Estimaci�n:** 18 horas.

## Historia de Usuario 6: Interfaz para enviar feedback automatizado

**T�tulo:** Como Responsable de RRHH, quiero una interfaz para personalizar y enviar feedback automatizado a los candidatos no seleccionados.

**Descripci�n:** Esta funcionalidad permitir� al Responsable de RRHH utilizar una interfaz gr�fica para personalizar plantillas de mensajes y enviar feedback automatizado a los candidatos no seleccionados.

**Criterios de Aceptaci�n:**
- Dado que el Responsable de RRHH ha cerrado una vacante,
  - Cuando accede a la opci�n de feedback automatizado,
  - Entonces se muestra una interfaz con opciones para personalizar y enviar mensajes.
- Dado que los mensajes deben ser claros y profesionales,
  - Cuando el Responsable de RRHH selecciona una plantilla,
  - Entonces el sistema muestra una vista previa del mensaje.

**Equipo:** Frontend, UX/UI

**Notas adicionales:**
- La interfaz debe incluir un editor de texto para personalizar plantillas.
- Debe mostrar un resumen de los candidatos que recibir�n el feedback.

**Estimaci�n:** 16 horas.
