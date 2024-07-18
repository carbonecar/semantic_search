## Resumen
Existen tres enfoques
 * usar el modelo de elastic ELSER
 * importar modelos y usarlos dentro del elastic
 * Usar modelos externos por fuera del elastic



 ### usando modelos Externos por fuera del elastic

En este ejemplo se muestra como al crear un indice con el campo del tipo embedding (un array de dimension n) e indicarle que este mismo esta indexado
Se pude: 
 * crear un embedding del documento (los campos que se deseen)
 * agregarlo al documento
 * obtener una query semantica en términos de una oración 
 * calcular el embedding de esa query (con el mismo modelo que se calculo el embedding anterior)
 * realizar una consulta a elasticsearch para que busque eficientemente entre todos los embedings calculados y este nuevo que le pasamos

https://medium.com/@teeppiphat/install-elasticsearch-docker-on-macos-m1-7dfbb8876b99

https://www.youtube.com/watch?v=KSwPR9eig7w

Enrolment token: eyJ2ZXIiOiI4LjMuMSIsImFkciI6WyIxNzIuMTguMC4yOjkyMDAiXSwiZmdyIjoiNmVmMzlhOWQwZGI2NmFlMmU4ZDgyYWM2ZjkzYjJjNGU5ZDY2OGEwYmQzMjE5ZjlmNTI4MmVmYzdkM2Y5MDEyMCIsImtleSI6InVrRHZycEFCTnJPTUJ2LTAySG9DOlJHSExqaFg4U1RtVlV1MUJNZ1h0d1EifQ==

kmZd*ryHh-rkjiAu2Txw


### TODO: 
 * create a docker-compose with elasticsearch and kibana
 * create a dev-container for it


 ### Models:
 https://sbert.net/docs/sentence_transformer/pretrained_models.html

