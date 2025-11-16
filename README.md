# Actividad-Grupo-11
## Análisis de expresión de RNA-seq
Para la realización de la actividad nuestro grupo ha decidido simular un análisis de expresión 
de RNA-seq. Para ello, se utilizarán los datos generados y analizados en el estudio:

Téllez-Robledo B, Manzano C, Saez A, Navarro-Neila S, Silva-Navas J, de Lorenzo L,
González-García MP, Toribio R, Hunt AG, Baigorri R, Casimiro I, Brady SM, Castellano
MM, Del Pozo JC. The polyadenylation factor FIP1 is important for plant development
and root responses to abiotic stresses. Plant J. 2019 Sep;99(6):1203-1219. doi:
10.1111/tpj.14416. Epub 2019 Jun 26. PMID: 31111599.

Los datos del estudio están disponibles en la base de datos Gene Expression Omnibus
(GEO), que recopila datos de transcriptómica, con el número de acceso: GSE127972.

El objetivo de este estudio es ver la importancia de la poliadenilación en el desarrollo 
de la planta mediante un análisis de expresión génica diferencial entre el control de 
*Arabidopsis thaliana* y las plántulas mutantes fip1-2 cultivadas en medio normal. 
Por ello, en este estudio vamos a disponer de 4 muestras a analizar: 2 réplicas del control
y 2 réplicas del mutante fip1-2.

Para ello hemos creado en nuestro directorio el espacio de trabajo para la realización de dicho
experimento.

## Preparación del espacio de trabajo 
### Carpeta Genome 
Para la realización del análisis que hemos elegido se usa la planta *Arabidopsis Thaliana* como organismo modelo. Por ello, en esta carpeta se encontraría el fichero FASTA con el genoma completo de dicha planta. Dicho fichero FASTA con el genoma nos lo podemos descargar de la base de datos plants.ensembl.org

### Carpeta Samples
Esta carpeta contiene los datos crudos de secuenciación obtenidos mediante RNA-Seq. Incluye 4 archivos FASTQ, correspondientes a:
- 2 réplicas biológicas de la condición control.
- 2 réplicas biológicas de la muestra mutante para FIP1.
Estos archivos se utilizan como punto de partida para los posteriores análisis (control de calidad, preprocesamiento, mapeo, análisis de expresión diferencial, etc).
