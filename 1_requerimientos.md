# Definicion de Requerimientos

El **problema** que se plantea segun el enunciado del proyecto es una organizacion que se dedica a ofrecer el _servicio de lavanderia_ con varios tipos de lavado, los cuales se describen a continuacion:

- Lavado a mano
- Lavado con la lavadora

por lo que desde las perspectiva de la organizacion se necesita saber lo siguiente:

1. Verificar si el cliente ya esta registrado o no:

   - Si esta registrado sigue el proceso normal
   - Sino esta registrado se le solicitaran los siguientes datos:
     - Apellido
     - Nombre
     - Domicilio (Calle, numero, apartamento y piso)
     - Barrio y telefono

2. Determinar el tipo de servicio a aplicar sobre las prendas del cliente:

   - Se genera un pedido con los siguientes datos:
     - Numero de pedido
     - Fecha de pedido
     - Los tipos de prenda
     - Tipo de servicio para cada prenda
     - Cantidad de prenda
     - Fecha pautada de devolucion
     * Precio unitario
     * Precio total

      Precios en general segun el servicio contratado por cliente, para su posterior facturacion:

      | Tipo de Servicio | Blusa | Acolchado |
      | ---------------- | ----- | --------- |
      | Lavado a Seco    | Q150  | Q380      |
      | Maquina Lavador  | Q110  | Q300      |

3. Se lavan las prendas segun el pedido del cliente

   - Una ves listas se ubican para su retiro

4. Cliente llega a retirar prendas

   - Se verifica que este listo el pedido
   - Se emite un ticket y se cobra el servicio
     - Este ticket se emite segun reglamentacion vigentes de la SAT, y solo se acepta pago de contado

5. Retiro de prendas

   - Cliente tiene 90 dias a partir de la fecha pactada para retirar sus prendas
     - Pasado ese plazo sino las retira la empresa de lavendaria puede disponer de ellas.

6. Compra de insumos

   - Semanalmente se compran insumos y productos para el lavado correcto de prendas.

7. Reportes
   - Mensualmente se genera un reporte con los tipos de servicios de lavado mas solicitado.

[![gracias.png](https://i.postimg.cc/zGcw6gQV/gracias.png)](https://postimg.cc/rD5ttKMk)
