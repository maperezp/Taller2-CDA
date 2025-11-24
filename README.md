# **Taller 2 - Servicios inmobiliarios**

### **Integrantes:**
- María Alejandra Pérez Petro - 201923972
- Daniel Esteban Aguilera Figueroa - 202010592 


## **Instrucciones de ejecución**

Clone el repositorio:
``` bash
git clone https://github.com/maperezp/Taller2-CDA.git
```

Ubíquese en el directorio de trabajo:
```bash
cd Taller2-CDA
```

Instale las dependencias:
```bash
pip install -r requirements.txt
```

Ejecute el notebook [Taller2.ipynb](./Taller2.ipynb) en orden.


## **Documentación**
El informe ejecutivo se encuentra en el archivo [InformeEjecutivo.pdf](./docs/InformeEjecutivo.pdf).

## **Insights/ Estrategias recomendadas**
Con base en los hallazgos del análisis y el desempeño del modelo, se proponen las siguientes estrategias para maximizar el valor generado por HabitAlpes.

* **Priorizar despliegue del modelo en apartamentos de precio medio**, donde el error es bajo y el volumen es mayor, para maximizar ahorro de tiempo y retorno.
* **Adoptar un flujo híbrido modelo–perito**: automatizar decisiones en casos de alta confianza y enviar a revisión manual los de baja confianza o en segmentos extremos.
* **Establecer revisión obligatoria del perito en apartamentos baratos**, debido al MAPE extremadamente alto y al riesgo de sobreprecio.
* **Definir alertas automáticas para subestimaciones en apartamentos caros**, enviando estos casos a avalúo experto antes de publicar precios.
* **Concentrar campañas comerciales y de captación en unidades de estrato medio–alto, áreas amplias y antigüedad moderada**, donde el modelo es más preciso y el margen potencial es mayor.
* **Integrar explicaciones SHAP en la interfaz interna**, para que los peritos comprendan por qué el modelo sugiere cierto precio y puedan corregir sesgos.
* **Explorar nuevas líneas de negocio ligadas a inmuebles antiguos**, como servicios de remodelación, aprovechando que la antigüedad es un factor clave en la caída de precio.
