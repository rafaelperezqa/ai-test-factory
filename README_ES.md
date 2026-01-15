# 🧠 AI Test Factory  
**Plataforma de generación de Tests y Jira impulsada por IA**

Este repositorio contiene un sistema basado en IA que transforma la creación de tests de una tarea manual en un flujo **automatizado, gobernado y totalmente trazable**.

Combina:
- GitHub Copilot  
- Cline  
- MCPs personalizados  
- APIs de Jira y Xray  
- GitHub Actions  

Para crear **código de test, issues de Jira y artefactos de Xray estandarizados** en minutos en lugar de horas.

---

## 🚀 Qué hace

AI Test Factory permite a un QA crear un test completamente alineado con los estándares simplemente respondiendo a unas pocas preguntas guiadas.

El sistema:
1. Solicita:
   - Carpeta destino  
   - Nombre de la clase  
   - Etiquetas  
   - Jira Test ID (si existe)  
2. Si el test existe en Jira:
   - Lo lee mediante MCP  
   - Extrae pasos, datos y metadatos  
3. Si no existe:
   - Crea el Jira Test  
   - Lo registra en Xray  
   - Aplica estándares y etiquetas  
4. Genera:
   - La clase de test  
   - El método de test  
   - Todas las anotaciones y metadatos requeridos  
5. Mueve el Jira a “In Progress”

Todos los artefactos quedan:
- Estandarizados  
- Trazables  
- Enlazados a Jira y Xray  
- Listos para CI/CD  

---

## 🧬 Por qué esto es importante

En QA corporativo:
- Crear tests es lento  
- Los estándares se degradan  
- La trazabilidad se rompe  
- La automatización se vuelve caótica  

Este sistema lo soluciona porque **es la IA la que impone la arquitectura**.

El QA ya no decide cómo deben ser los tests.  
La plataforma lo hace.

---

## 🏗 Arquitectura

AI Test Factory forma parte de una plataforma de calidad mayor:

- Copilot y Cline son la interfaz de usuario  
- Los MCPs conectan con Jira y Xray  
- GitHub Actions orquesta la generación  
- Los repositorios almacenan el código gobernado  

Todo está conectado mediante APIs y webhooks.

---

## 🎯 Uso real en empresa

Este sistema se usa actualmente en un entorno ecommerce empresarial para:
- Generar nuevos tests automatizados  
- Crear y mantener artefactos Jira/Xray  
- Aplicar estándares globales de QA  
- Reducir drásticamente el tiempo de onboarding  

---

## 🧠 Qué demuestra

Esto no es una demo.  
Es una **plataforma real de QA gobernada por IA en producción**.

Demuestra cómo el Quality Engineering moderno puede ser:
- Automatizado  
- Gobernado  
- Escalable  
- Y nativo de IA  
