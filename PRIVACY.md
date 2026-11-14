# Privacy Policy — cvagent

*Effective date: 14 November 2026 · [Español más abajo](#política-de-privacidad--cvagent)*

**cvagent** is a personal, single-user application written and operated by its owner, Juan Carlos Contreras Gastélum
([github.com/jccontrerasg08-cpu](https://github.com/jccontrerasg08-cpu)). It is not offered to the public: the only person
whose Google account it connects to is its owner. Its source code lives in a private repository.

## What it does
cvagent helps its owner with his own job search. It looks for job opportunities in his Gmail inbox (recruiter emails,
job-board alerts and notification emails), tailors his CV to each one using only facts from his own CV, and prepares a
reply as a Gmail draft. Sending an email automatically is switched off by default.

## Google user data it accesses, and why
It requests two Gmail permissions and nothing else:

| Permission | Why |
|---|---|
| `gmail.readonly` | to read messages that look like job opportunities, so the CV can be tailored to them |
| `gmail.compose` | to create drafts (and, only if the owner turns it on, to send an email with his CV) |

## What is stored, where, and for how long
- **In a private GitHub repository owned by the owner:** for each opportunity, the sender's address, a title and company
  taken from the subject, and a short excerpt (at most 1,500 characters) of the message; the name and address of people
  who wrote to him and identified themselves by name; and the CVs produced. Messages that are not job opportunities are
  not stored, only their message identifier so they are not read again.
- **As an encrypted GitHub Actions secret:** the OAuth credentials needed to reach the owner's own mailbox.
- Data is kept until the owner deletes it. The application includes a command to erase a person from its records on
  request, and the owner can revoke its access at any time at <https://myaccount.google.com/permissions>.

## How it is processed and shared
- Processing runs on GitHub Actions runners operated by GitHub, so the data passes through GitHub's infrastructure
  under GitHub's terms. It is not sent to any other service.
- Google user data is **not** sold, shared with or transferred to third parties, **not** used for advertising, and **not**
  used to develop, improve or train artificial-intelligence or machine-learning models. No person other than the owner
  reads it.

## Limited Use
cvagent's use and transfer of information received from Google APIs adheres to the
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the
Limited Use requirements.

## People who write to the owner
Recruiters and other senders appear in the records only because they wrote to the owner. Their data is used only to avoid
contacting the same person twice and to keep track of applications. Anyone can ask for it to be erased by contacting the
owner through his GitHub profile.

## Changes and contact
Changes to this policy will be published on this page with a new effective date.
Contact: [github.com/jccontrerasg08-cpu](https://github.com/jccontrerasg08-cpu).

---

# Política de privacidad — cvagent

*Fecha de entrada en vigor: 14 de noviembre de 2026*

**cvagent** es una aplicación personal, de un solo usuario, escrita y operada por su dueño, Juan Carlos Contreras Gastélum
([github.com/jccontrerasg08-cpu](https://github.com/jccontrerasg08-cpu)). No se ofrece al público: la única cuenta de Google
a la que se conecta es la de su dueño. Su código vive en un repositorio privado.

## Qué hace
cvagent ayuda a su dueño con su propia búsqueda de empleo. Busca oportunidades en su bandeja de Gmail (correos de
reclutadores, alertas de bolsas de trabajo y notificaciones), adapta su CV a cada una usando solo datos de su propio CV y
prepara una respuesta como borrador de Gmail. El envío automático de correos está apagado por defecto.

## Datos de Google a los que accede, y para qué
Solicita dos permisos de Gmail y ninguno más:

| Permiso | Para qué |
|---|---|
| `gmail.readonly` | leer los mensajes que parecen oportunidades de empleo, para adaptar el CV |
| `gmail.compose` | crear borradores (y, solo si el dueño lo activa, enviar un correo con su CV) |

## Qué se guarda, dónde y por cuánto tiempo
- **En un repositorio privado de GitHub del dueño:** por cada oportunidad, la dirección del remitente, un título y empresa
  tomados del asunto y un extracto corto (máximo 1,500 caracteres) del mensaje; el nombre y la dirección de quienes le
  escribieron y se identificaron con su nombre; y los CV generados. Los mensajes que no son oportunidades no se guardan,
  solo su identificador para no volver a leerlos.
- **Como secreto cifrado de GitHub Actions:** las credenciales OAuth necesarias para llegar al correo del propio dueño.
- Los datos se conservan hasta que el dueño los borre. La aplicación incluye un comando para borrar a una persona de sus
  registros cuando lo pida, y el dueño puede revocar su acceso en cualquier momento en
  <https://myaccount.google.com/permissions>.

## Cómo se procesan y se comparten
- El procesamiento corre en ejecutores de GitHub Actions operados por GitHub, por lo que los datos pasan por su
  infraestructura bajo sus términos. No se envían a ningún otro servicio.
- Los datos de usuario de Google **no** se venden, no se comparten ni se transfieren a terceros, **no** se usan para
  publicidad y **no** se usan para desarrollar, mejorar ni entrenar modelos de inteligencia artificial o aprendizaje
  automático. Nadie más que el dueño los lee.

## Uso limitado
El uso y la transferencia que cvagent hace de la información recibida de las API de Google cumple la
[Política de datos de usuario de los servicios de API de Google](https://developers.google.com/terms/api-services-user-data-policy),
incluidos los requisitos de uso limitado.

## Personas que escriben al dueño
Los reclutadores y otros remitentes aparecen en los registros solo porque escribieron al dueño. Sus datos se usan únicamente
para no contactar dos veces a la misma persona y para dar seguimiento a las postulaciones. Cualquiera puede pedir que se
borren escribiendo al dueño por su perfil de GitHub.

## Cambios y contacto
Los cambios a esta política se publicarán en esta página con una nueva fecha.
Contacto: [github.com/jccontrerasg08-cpu](https://github.com/jccontrerasg08-cpu).
