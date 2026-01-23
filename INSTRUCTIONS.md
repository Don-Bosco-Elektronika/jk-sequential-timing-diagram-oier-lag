# 🛠️ Cronograma de Circuitos Secuenciales / Zirkuitu Sekuentzialen Kronograma / Sequential Circuit Timing Diagram

| **Alumnos** | **Curso** | **Módulo** |
|-------------|-----------|------------|
| 2ME         | 1º        | EEM (Equipos Microprogramables) |

---

## 📌 Ejercicio / Ariketa / Exercice

**ariketa (EU): (zenbakia idatzi)**  
| Nombre                     | Número de Chip | Símbolo         | Descripción del Funcionamiento                                                                 |
|---------------------------|------------------|------------------|---------------------------------------------------------------------------------|
| JK flanco descendente | 7476        | <img width="159" height="154" alt="image" src="https://github.com/user-attachments/assets/7d57e11b-7901-48b4-9bff-14f64fa70b1a" /> | Flip-Flop zaharra da. Erlojuaren seinalea "1"etik "0"ra jaisten denean (bajada) aldatzen du egoera. | 

**Ariketa (EU): (ZENBAKIA IDATZI)**  
| Izena                     | Txip Zenbakia | Sinboloa         | Funtzionamendu Describapena                                                                |
|---------------------------|------------------|------------------|---------------------------------------------------------------------------------|
| JK flanco ascendente | 4027         | <img width="150" height="132" alt="image" src="https://github.com/user-attachments/assets/98ed9b8f-552e-4075-8af6-6cd41bcd32e7" />| Hau ere JK da, baina honek erlojua igotzean (subida) egiten du aldaketa. |  





## Tabla de la verdad

| Entrada A | Entrada B | Entrada C | Salida    | Salida |
|-----------|-----------|-----------|-----------|--------|
| 0         | 0         | 0         | ░0░       | ░0░    |
| 0         | 0         | 1         | ░1░       | ░1░    |
| 1         | 1         | 0         | ░1░       | ░1░    |
| 1         | 1         | 1         | ░0░       | ░0░    |

---

## 🔲 Circuitos a Simular / Simulatzeko Zirkuituak / Circuits to Simulate

*(<img width="631" height="443" alt="image" src="https://github.com/user-attachments/assets/91cb6a52-930a-4192-9c5a-83a5a110a6fb" />
)*
(<img width="538" height="383" alt="image" src="https://github.com/user-attachments/assets/79d3095f-9e5c-42cd-8cc6-13ba49c63751" />
)

## 🔲 Resultado del Cronograma / Kronogramaren Emaitza / Timing Diagram Result
Circuito A

*(<img width="581" height="362" alt="image" src="https://github.com/user-attachments/assets/e9265323-4ad8-4e48-a95e-8c5a53c4ba63" />
)*

Circuito B

*(<img width="574" height="357" alt="image" src="https://github.com/user-attachments/assets/e56e732c-0ad6-4b58-afe2-18eccfdd2dbc" />
)*




## 🔲 Código del Cronograma / Kronogramaren Kodea / Timing Diagram Code
Circuito A

*({signal: [

  {name: 'clk', wave: 'N................'},
  
  {name: 'J', wave: '0101..0101.0..1.0'},
  
  {name: 'K', wave: '1...0..1.0..1..01'},
  
  {},
  
  {name: 'Q', wave: '0.101...0.1..0.1.'},
  
  {name: '-Q', wave: '1.010...1.0..1.0.'}
  
]}
)*

Circuito B

*({signal: [

  {name: 'clk', wave: 'N................'},
  
  {name: 'J', wave: '0101..0101.0..1.0'},
  
  {name: 'K', wave: '1...0..1.0..1..01'},
  
  {},
  
  {name: 'Q', wave: '0.101...0.1..0.1.'},
  
  {name: '-Q', wave: '1.010...1.0..1.0.'}
  
]}


)*




## 📤 Entrega / Igo / Upload  

➡️ **Instrucciones:**  

- **ES:** Sube los siguientes archivos. Todos los archivos subidos han de tener tu nombre.  
  - Una foto del símbolo.  
  - El archivo en Proteus y una captura de imagen de cada circuito en Proteus.  
  - Capturas de cada resultado del Wavedrom (solo el gráfico).  
  - **ATENCIÓN:** El código del cronograma TIENE que ser código, no una imagen.

- **EU:** Igo hurrengo fitxategiak. Igotako fitxategi guztiek zure izena eduki behar dute.  
  - Sinboloaren argazki bat.  
  - Proteus fitxategia eta zirkuitu bakoitzaren irudia (captura) Proteusen.  
  - Wavedrom bakoitzaren emaitzaren kaptura (grafikoa bakarrik).  
  - **KONTUZ:** Kronogramaren kodea kodea izan behar da, ez irudi bat.

- **EN:** Upload the following files. All uploaded files must include your name.  
  - A photo of the symbol.  
  - The Proteus file and an image capture of each circuit in Proteus.  
  - Uno capture of each Wavedrom result (graph only).  
  - **ATTENTION:** The schedule code MUST be real code, not an image.



