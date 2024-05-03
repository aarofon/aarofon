- 👋 Hi, I’m @aarofon
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
aarofon/aarofon is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
graph LR;
    A((Consulta del Cliente)) -- Sí --> B((Atención por parte del Vendedor));
    A -- No --> X((Fin del Proceso));
    B -- Sí --> C((Generación de Certificado de Pandero));
    C -- Sí --> D((Pago de Cuota de Inscripción));
    D -- Sí --> E((Sorteo Mensual Realizado));
    E -- No --> X;
    E -- Sí --> F((Selección de Ganador));
    F -- Sí --> G((Cliente Ganador));
    F -- No --> X;
    G -- Sí --> H((Pago de Cuota de Adjudicación));
    G -- No --> X;
    H --> I((Entrega del Auto));
    
