---
{"dg-publish":true,"permalink":"/zettelkasten/las-alucinaciones-de-la-ia-pueden-ser-ocasionadas-por-el-ajuste-fino/"}
---

# Las alucinaciones de la IA pueden ser ocasionadas por el ajuste fino

Es posible.

Se entrena una IA LLM en un dataset enorme. Entonces se hace el ajuste fino con un dataset adicional para conseguir mejores resultados en un dominio (nose, servicio al cliente), y ahi se caga.

Las alucinaciones son que de la respuesta incorrecta B a una pregunta que tiene como respuesta correcta A. Esto podria ser un problema de [[Zettelkasten/Sobreajuste vs compresion de IA\|Sobreajuste vs compresion de IA]]. 

Una solucion posible es [[Entrenamiento de IA general por SFT, luego ajuste fino por DPO\|Entrenamiento de IA general por SFT, luego ajuste fino por DPO]].

No tengo actualmente el conocimiento suficiente para entender del todo el paper ni lo que esto significa. #FIXME
## Referencias
[[Zettelkasten/Learning Dynamics of LLM Finetuning\|Learning Dynamics of LLM Finetuning]], pero probablemente muchos otros.