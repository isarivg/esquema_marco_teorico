```mermaid
---
config:
  htmlLabels: false
---
flowchart TD
    subgraph A["Antigüedad clásica y Edad Media"]
        direction LR
        A1["`**Justicia / División de funciones / Orden de la ciudad**
Platón (ca. 380 a. C.)`"]
        A2["`**Justicia distributiva**
Aristóteles (384–322 a. C.)`"]
        A3["`**Bien común**
Tomás de Aquino (1225–1274)`"]

        A1 ~~~ A2 ~~~ A3
    end

    subgraph B["Modernidad e Ilustración"]
        direction LR
        B1["`**Desigualdad natural / Desigualdad social / Propiedad / Herencia**
Thomas Hobbes (1588–1679)`"]
        B3["`**Desigualdad natural / Desigualdad social / Propiedad / Herencia / Poder**
Jean-Jacques Rousseau (1712–1778)`"]

        B1 ~~~ B3
    end

    subgraph C["Sociedad industrial"]
        direction LR
        C1["`**Desigualdad de clases / Medios y modos de producción / Plusvalía**
Karl Marx (1818–1883)`"]
        C2["`**Clase / Estatus / Partido**
Max Weber (1864–1920)`"]

        C1 ~~~ C2
    end

    subgraph D["Desigualdad en el siglo XX"]
        direction LR
        D2["`**Ecología urbana y segregación**
Robert E. Park (1864)`"]
        D3["`**Seguridad social y protección frente a riesgos**
William Beveridge (1879)`"]
        D4["`**Intervención pública, demanda y empleo**
John Maynard Keynes (1883–1946)`"]
        D5["`**Ciudadanía y derechos sociales**
T. H. Marshall (1893)`"]
        D6["`**Estado intervencionista y crisis de legitimación**
Jürgen Habermas (1929)`"]

        D2 ~~~ D3 ~~~ D4 ~~~ D5 ~~~ D6
    end

    subgraph E["Enfoques contemporáneos"]
        direction LR
        E1["`**Desigualdad / Acceso efectivo / Capacidades**
Amartya Sen (1933– )`"]
        E2["`**Desigualdad socioespacial / Derecho a la ciudad**
Henri Lefebvre (1901–1991)`"]
        E3["`**Desigualdad urbana**
David Harvey (1935– )`"]
        E4["`**Desigualdad urbana**
Manuel Castells (1942– )`"]
        E5["`**Justicia espacial / Desigualdad espacial**
Edward W. Soja (1940–2015)`"]

        E1 ~~~ E2 ~~~ E3 ~~~ E4 ~~~ E5
    end

    A --> B --> C --> D --> E
    end

    A --> B --> C --> D --> E
    style D0 fill:none,stroke:none
```
