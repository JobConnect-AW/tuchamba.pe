## 4.7.2 Class Dictionary

<table>
        <thead>
            <tr>
                <th>Clase</th>
                <th>Descripción</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><strong>Account</strong></td>
                <td>Representa la cuenta base de acceso a la plataforma. Administra la autenticación (email y contraseña), y determina si un usuario está activo o inactivo.</td>
            </tr>
            <tr>
                <td><strong>AccountId</strong></td>
                <td> Identificador único de una cuenta. Asegura la identidad en todo el sistema, conectando múltiples contextos.</td>
            </tr>
            <tr>
                <td><strong>User</strong></td>
                <td>Representa a la identidad pública del usuario dentro de la plataforma. Almacena datos personales, rol, y perfil visible para otros usuarios.</td>
            </tr>
            <tr>
                <td><strong>Customer</strong></td>
                <td>Representa a un usuario con rol de cliente, es decir, aquel que solicita servicios. Incluye fecha de registro para historial.</td>
            </tr>
            <tr>
                <td><strong>Worker</strong></td>
                <td>Representa al usuario que ofrece servicios técnicos o profesionales. Gestiona su experiencia, habilidades, certificaciones, tarifas y disponibilidad.</td>
            </tr>
            <tr>
                <td><strong>Experience</strong></td>
                <td>Representa las experiencias laborales pasadas del trabajador. Aporta credibilidad y trayectoria al perfil del Worker.</td>
            </tr>
            <tr>
                <td><strong>Review</strong></td>
                <td>Representa una evaluación realizada por un usuario hacia otro tras una interacción o servicio completado. Permite generar confianza y reputación en la plataforma.</td>
            </tr>
            <tr>
                <td><strong>ReviewId</strong></td>
                <td>Identificador único que asegura trazabilidad de cada evaluación realizada en la plataforma.</td>
            </tr>
            <tr>
                <td><strong>Proposal</strong></td>
                <td>Representa una propuesta de trabajo que un Worker envía a un Customer. Define los términos del servicio como precio, tiempo estimado y descripción del trabajo.</td>
            </tr>
            <tr>
                <td><strong>SalesOrder_Payment</strong></td>
                <td>Representa la orden de pago relacionada a un servicio aceptado. Gestiona montos, estado del pago y registro de la garantía inicial.</td>
            </tr>
            <tr>
                <td><strong>GuaranteePayment</strong></td>
                <td>Representa una garantía inicial pagada al aceptar una propuesta. Asegura compromiso entre las partes.</td>
            </tr>
            <tr>
                <td><strong>Money</strong></td>
                <td>Representa el dinero (monto y moneda). Centraliza la lógica de operaciones monetarias como suma o resta.</td>
            </tr>
            <tr>
                <td><strong>Chat</strong></td>
                <td>Representa un canal de comunicación entre usuarios (cliente-trabajador). Puede incluir múltiples participantes y mensajes.</td>
            </tr>
            <tr>
                <td><strong>Message</strong></td>
                <td>Representa cada mensaje individual dentro de un chat. Contiene contenido, autor y fecha de envío.</td>
            </tr>
            <tr>
                <td><strong>Ticket</strong></td>
                <td>Representa una queja o disputa surgida durante una orden de servicio. Permite resolver conflictos entre usuarios, ya sea a favor del cliente o trabajador.</td>
            </tr>