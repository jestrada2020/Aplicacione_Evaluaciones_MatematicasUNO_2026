---
title: "Simulacro de Evaluación Uno (Respaldo)"
output: html_document
---


# Simulacro de Evaluación Uno (Respaldo)

<style>
/* Estilos Premium para la Evaluación de Respaldo */
@import url('https://fonts.googleapis.com/css2?family=Outfit:wght@400;600;700;800&family=Inter:wght@400;500;600&display=swap');

body {
  font-family: 'Inter', sans-serif;
  background: #f7f9fc;
  color: #2e384d;
}

h1, h2, h3, h4, .tutorial-title {
  font-family: 'Outfit', sans-serif;
  font-weight: 700;
  color: #1e2638;
}

.tutorial-title {
  background: linear-gradient(135deg, #0284c7 0%, #0369a1 100%);
  color: white;
  padding: 2.5rem 2rem;
  border-radius: 16px;
  text-align: center;
  margin-bottom: 2rem;
  box-shadow: 0 10px 25px -5px rgba(2, 132, 199, 0.3);
  font-size: 2.5rem;
  text-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.section.level2 {
  background: white;
  border-radius: 16px;
  padding: 2rem;
  margin-bottom: 2rem;
  box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05), 0 2px 4px -1px rgba(0, 0, 0, 0.03);
  border: 1px solid #eef2f6;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.section.level2:hover {
  transform: translateY(-2px);
  box-shadow: 0 12px 20px -8px rgba(0, 0, 0, 0.08);
}

/* Estilo para las preguntas de learnr */
.tutorial-question {
  background-color: #fafbfc;
  border-radius: 12px;
  padding: 1.5rem;
  border-left: 5px solid #0284c7;
  margin-top: 1rem;
}

.tutorial-question-title {
  font-family: 'Outfit', sans-serif;
  font-size: 1.2rem;
  font-weight: 600;
  color: #1e2638;
  margin-bottom: 1rem;
}

/* Opciones de respuesta */
.answer-option {
  background: white !important;
  border: 1.5px solid #e2e8f0 !important;
  border-radius: 8px !important;
  padding: 0.75rem 1rem !important;
  margin-bottom: 0.5rem !important;
  transition: all 0.2s ease !important;
  cursor: pointer;
}

.answer-option:hover {
  border-color: #0284c7 !important;
  background-color: #f0f9ff !important;
  transform: translateX(4px);
}

.answer-option.selected {
  background-color: #e0f2fe !important;
  border-color: #0284c7 !important;
}

/* Botones */
.btn-primary, .btn-submit, .btn-action {
  background: linear-gradient(135deg, #0284c7 0%, #0369a1 100%) !important;
  border: none !important;
  color: white !important;
  font-weight: 600 !important;
  font-family: 'Outfit', sans-serif !important;
  padding: 0.6rem 1.5rem !important;
  border-radius: 8px !important;
  transition: all 0.2s ease !important;
  box-shadow: 0 4px 12px rgba(2, 132, 199, 0.2) !important;
}

.btn-primary:hover, .btn-submit:hover {
  transform: translateY(-1px) !important;
  box-shadow: 0 6px 16px rgba(2, 132, 199, 0.3) !important;
  opacity: 0.95;
}

/* Alertas de retroalimentación */
.alert-success {
  background-color: #ecfdf5 !important;
  border-color: #10b981 !important;
  color: #065f46 !important;
  border-radius: 8px !important;
}

.alert-danger {
  background-color: #fef2f2 !important;
  border-color: #ef4444 !important;
  color: #991b1b !important;
  border-radius: 8px !important;
}
</style>



## Introducción

Bienvenido al **Simulacro de Evaluación Uno**. Esta prueba consta de **12 preguntas interactivas** sobre ecuaciones cuadráticas, geometría analítica (parábolas y rectas) y potenciación.

> **Instrucciones:**
> * Utiliza las aplicaciones Shiny de soporte integradas para analizar de manera visual cada una de las ecuaciones y curvas.
> * Selecciona únicamente las afirmaciones que consideres correctas para cada caso.
> * Al final de la prueba, podrás visualizar un reporte detallado con tus respuestas correctas, incorrectas y una recomendación de estudio personalizada.
> * ¡Mucho éxito!

---

## Bloque 1: Ecuaciones Cuadráticas

<iframe src="https://procesouces2020.shinyapps.io/FormulaEstudianteV2/?showcase=0" width="672" height="1000px" data-external="1"></iframe>

### Pregunta 1

<div class="learnr-question-box" id="q17796552933625306"><div class="learnr-question-text">Use la aplicación Shiny (fórmula del estudiante). Seleccione sólo las afirmaciones verdaderas sobre la ecuación: $$\ 2x^{2}+ x-1=0$$</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796552933625306" value="1" data-correct="true" > El Discriminante es un real positivo </label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552933625306" value="2" data-correct="false" > Tiene ambas raíces en el lado negativo de los reales</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552933625306" value="3" data-correct="true" > Una raíz de la ecuación $2x^{2}+ x-1=0$ es $x=-1$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552933625306" value="4" data-correct="true" > Una raíz de la ecuación $2x^{2}+ x-1=0$ es $x=0.5$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552933625306" value="5" data-correct="true" > El vértice de la parábola $y=2x^{2}+ x-1$ está bajo el eje $X$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552933625306" value="6" data-correct="false" > Las raices son de un polinómio de cuarto grado</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552933625306" value="7" data-correct="false" > El Discriminante es un real negativo</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552933625306" value="8" data-correct="false" > Ambas raices de la ecuación $2x^{2}+ x-1=0$ son complejas</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796552933625306')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">Correcto!</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto</div><div class="learnr-data-retry" style="display:none;">Intentelo nuevamente</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 2

<div class="learnr-question-box" id="q17796552933739430"><div class="learnr-question-text">Use la aplicación Shiny (fórmula del estudiante). Seleccione sólo las afirmaciones verdaderas sobre la ecuación: $$\ 2x^{2}= x+1$$</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796552933739430" value="1" data-correct="true" > El Discriminante es un real positivo </label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552933739430" value="2" data-correct="false" > Tiene ambas raíces en el lado negativo de los reales</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552933739430" value="3" data-correct="true" > Una raíz de la ecuación $2x^{2}= x+1$ es $x = 1$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552933739430" value="4" data-correct="true" > Una raíz de la ecuación $2x^{2}= x+1$ es $x=-0.5$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552933739430" value="5" data-correct="true" > El vértice de la parábola $y=2x^{2}- x-1$ está bajo el eje $X$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552933739430" value="6" data-correct="false" > Las raices son de un polinómio de cuarto grado</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552933739430" value="7" data-correct="false" > El Discriminante es un real negativo</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552933739430" value="8" data-correct="true" > Ambas raices de la ecuación $2x^{2}= x+1$ son números reales y no enteras</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796552933739430')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">Correcto!</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto</div><div class="learnr-data-retry" style="display:none;">Intentelo nuevamente</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 3

<div class="learnr-question-box" id="q17796552933847458"><div class="learnr-question-text">Use la aplicación Shiny (fórmula del estudiante). Seleccione sólo las afirmaciones verdaderas sobre la ecuación: $$\ 16x^{2}= 1$$</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796552933847458" value="1" data-correct="true" > El Discriminante es un real positivo </label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552933847458" value="2" data-correct="false" > Tiene ambas raíces en el lado negativo de los reales</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552933847458" value="3" data-correct="true" > Una raíz de la ecuación $16x^{2}= 1$ es $x=0.25$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552933847458" value="4" data-correct="true" > Una raíz de la ecuación $16x^{2}= 1$ es $x=-0.25$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552933847458" value="5" data-correct="true" > El vértice de la parábola $y=16x^{2}-1$ está bajo el eje $X$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552933847458" value="6" data-correct="false" > Las raices son de un polinómio de cuarto grado</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552933847458" value="7" data-correct="false" > El Discriminante es un real negativo</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552933847458" value="8" data-correct="false" > Ambas raices de la ecuación $16x^{2}= 1$ son complejas</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796552933847458')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">Correcto!</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto</div><div class="learnr-data-retry" style="display:none;">Intentelo nuevamente</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 4

<div class="learnr-question-box" id="q17796552933949822"><div class="learnr-question-text">Use la aplicación Shiny (fórmula del estudiante). Seleccione sólo las afirmaciones verdaderas sobre la ecuación: $$\ -(16x^{2}+1)= 8x$$</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796552933949822" value="1" data-correct="false" > El Discriminante es un real positivo </label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552933949822" value="2" data-correct="true" > Tiene ambas raíces en el lado negativo de los reales</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552933949822" value="3" data-correct="false" > Una raíz de la ecuación $-(16x^{2}+1)= 8x$ es $x=0.25$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552933949822" value="4" data-correct="true" > Una raíz de la ecuación $-(16x^{2}+1)= 8x$ es $x=-0.25$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552933949822" value="5" data-correct="true" > El vértice de la parábola $y=-16x^{2}-8x-1$ está en el eje $X$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552933949822" value="6" data-correct="false" > Las raices son de un polinómio de cuarto grado</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552933949822" value="7" data-correct="false" > El Discriminante es un real negativo</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552933949822" value="8" data-correct="false" > Ambas raices de la ecuación $-(16x^{2}+1)= 8x$ son complejas</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796552933949822')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">Correcto!</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto</div><div class="learnr-data-retry" style="display:none;">Intentelo nuevamente</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

---

## Bloque 2: Parábolas y Rectas

<iframe src="https://procesouces2020.shinyapps.io/ParabolaV2/?showcase=0" width="672" height="1150px" data-external="1"></iframe>

### Pregunta 5

<div class="learnr-question-box" id="q17796552934193950"><div class="learnr-question-text">Use la aplicación Shiny (Parábola y Recta).  Seleccione sólo las afirmaciones verdaderas sobre la función: $$\ (x+5)^{2}= -4(y+1)$$</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796552934193950" value="1" data-correct="false" > La parábola es concava hacia arriba</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934193950" value="2" data-correct="true" > La parábola es concava hacia abajo</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934193950" value="3" data-correct="true" > La parábola tiene vértice por debajo del eje $X$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934193950" value="4" data-correct="false" > La parábola tiene vértice por arriba del eje $X$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934193950" value="5" data-correct="true" > Todas las raíces son complejas en la parábola $(x+5)^{2}= -4(y+1)$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934193950" value="6" data-correct="false" > Todas las raíces son reales en la parábola $(x+5)^{2}= -4(y+1)$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934193950" value="7" data-correct="false" > La parábola tiene como Discriminante $D=1.75$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934193950" value="8" data-correct="false" > Una raìz positiva de la parábola es $x \cong 0.64575$</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796552934193950')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">Correcto!</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto</div><div class="learnr-data-retry" style="display:none;">Intentelo nuevamente</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 6

<div class="learnr-question-box" id="q17796552934286465"><div class="learnr-question-text">Use la aplicación Shiny (Parábola y Recta).  Seleccione sólo las afirmaciones verdaderas sobre la función: $$\ x^{2}+6x+y+11=0$$</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796552934286465" value="1" data-correct="false" > La parábola es concava hacia arriba</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934286465" value="2" data-correct="true" > La parábola es concava hacia abajo</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934286465" value="3" data-correct="true" > La parábola tiene vértice por debajo del eje $X$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934286465" value="4" data-correct="false" > La parábola tiene vértice por arriba del eje $X$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934286465" value="5" data-correct="true" > Todas las raíces son complejas en la parábola $x^{2}+6x+y+11=0$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934286465" value="6" data-correct="false" > Todas las raíces son reales en la parábola $x^{2}+6x+y+11=0$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934286465" value="7" data-correct="true" > La parábola es tiene como Discriminante $D=-8$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934286465" value="8" data-correct="false" > Una raìz positiva de la parábola es $x \cong 0.15$</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796552934286465')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">Correcto!</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto</div><div class="learnr-data-retry" style="display:none;">Intentelo nuevamente</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 7

<div class="learnr-question-box" id="q17796552934361761"><div class="learnr-question-text">Use la aplicación Shiny (Parábola y Recta).  Seleccione sólo las afirmaciones verdaderas sobre la función: $$\ -2x^{2}+12x-8y-18=0$$</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796552934361761" value="1" data-correct="false" > La parábola es concava hacia arriba</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934361761" value="2" data-correct="true" > La parábola es concava hacia abajo</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934361761" value="3" data-correct="false" > La parábola tiene vértice por debajo del eje $X$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934361761" value="4" data-correct="true" > La parábola tiene vértice en el eje $X$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934361761" value="5" data-correct="false" > Todas las raíces son complejas en la parábola $-2x^{2}+12x-8y-18=0$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934361761" value="6" data-correct="true" > Todas las raíces son reales en la parábola $-2x^{2}+12x-8y-18=0$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934361761" value="7" data-correct="true" > La parábola es tiene como Discriminante $D=0</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934361761" value="8" data-correct="false" > Una raìz positiva de la parábola es $x \cong 0.215$</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796552934361761')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">Correcto!</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto</div><div class="learnr-data-retry" style="display:none;">Intentelo nuevamente</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 8

<div class="learnr-question-box" id="q17796552934455934"><div class="learnr-question-text">Use la aplicación Shiny (Parábola y Recta).  Seleccione sólo las afirmaciones verdaderas sobre la función: $$\ 4x^{2}-2y=0$$</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796552934455934" value="1" data-correct="true" > La parábola es concava hacia arriba</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934455934" value="2" data-correct="false" > La parábola es concava hacia abajo</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934455934" value="3" data-correct="false" > La parábola tiene vértice por debajo del eje $X$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934455934" value="4" data-correct="false" > La parábola tiene vértice por arriba del eje $X$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934455934" value="5" data-correct="false" > Todas las raíces son complejas en la parábola $4x^{2}-2y=0$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934455934" value="6" data-correct="true" > Todas las raíces son reales en la parábola $4x^{2}-2y=0$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934455934" value="7" data-correct="false" > La parábola es tiene como Discriminante $D=1.125$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934455934" value="8" data-correct="true" > Una raìz positiva de la parábola es $x =0$</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796552934455934')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">Correcto!</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto</div><div class="learnr-data-retry" style="display:none;">Intentelo nuevamente</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 9

<div class="learnr-question-box" id="q17796552934543430"><div class="learnr-question-text">Use la aplicación Shiny (Parábola y Recta).  Seleccione sólo las afirmaciones verdaderas sobre la función: $$\ 3x-4y+12=0$$</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796552934543430" value="1" data-correct="true" > La recta $3x-4y+12$ esta entre el $I$ y $III$ cuadrante</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934543430" value="2" data-correct="false" > La recta esta entre el $II$ y $IV$ cuadrante</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934543430" value="3" data-correct="false" > La recta corta al eje $X$ en $x=2$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934543430" value="4" data-correct="true" > La recta corta al eje $X$ en $x=-4$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934543430" value="5" data-correct="false" > La recta corta al eje $Y$ en $y=2$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934543430" value="6" data-correct="true" > La recta corta al eje $Y$ en $y=3$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934543430" value="7" data-correct="true" > La recta corta a ambos ejes coordenados en puntos diferentes del origen</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934543430" value="8" data-correct="true" > La recta es inclinada ya que el corte con el eje $Y$ es diferente de cero</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934543430" value="9" data-correct="false" > La recta tiene pendiente $m<0$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934543430" value="10" data-correct="true" > La recta pasa por el punto $P$ de coordenadas $P(0,3)$</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796552934543430')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">Correcto!</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto</div><div class="learnr-data-retry" style="display:none;">Intentelo nuevamente</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 10

<div class="learnr-question-box" id="q17796552934644341"><div class="learnr-question-text">Use la aplicación Shiny (Parábola y Recta).  Seleccione sólo las afirmaciones verdaderas sobre la función: $$\frac{1}{2}x-3y=3$$</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796552934644341" value="1" data-correct="true" > La recta esta entre el $I$ y $III$ cuadrante</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934644341" value="2" data-correct="false" > La recta esta entre el $II$ y $IV$ cuadrante</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934644341" value="3" data-correct="true" > La recta corta al eje $X$ en $x=6$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934644341" value="4" data-correct="false" > La recta corta al eje $X$ en $x=-4$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934644341" value="5" data-correct="false" > La recta corta al eje $Y$ en $y=2$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934644341" value="6" data-correct="true" > La recta corta al eje $Y$ en $y=-1$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934644341" value="7" data-correct="true" > La recta corta a ambos ejes coordenados en puntos diferentes del origen</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934644341" value="8" data-correct="true" > La recta es inclinada ya que el corte con el eje $Y$ es diferente de cero</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934644341" value="9" data-correct="false" > La recta tiene pendiente $m<0$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934644341" value="10" data-correct="true" > La recta pasa por el punto $P$ de coordenadas $P(0,-1)$</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796552934644341')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">Correcto!</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto</div><div class="learnr-data-retry" style="display:none;">Intentelo nuevamente</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 11

<div class="learnr-question-box" id="q17796552934733266"><div class="learnr-question-text">Use la aplicación Shiny (Parábola y Recta).  Seleccione sólo las afirmaciones verdaderas sobre la función: $$3x+5y+4=0$$</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796552934733266" value="1" data-correct="false" > La recta $3x+5y+4=0$ esta entre el $I$ y $III$ cuadrante</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934733266" value="2" data-correct="true" > La recta esta entre el $II$ y $IV$ cuadrante</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934733266" value="3" data-correct="false" > La recta corta al eje $X$ en $x=6$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934733266" value="4" data-correct="true" > La recta corta al eje $X$ en $x=\frac{-4}{3}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934733266" value="5" data-correct="false" > La recta corta al eje $Y$ en $y=2$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934733266" value="6" data-correct="true" > La recta corta al eje $Y$ en $y=\frac{-4}{5}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934733266" value="7" data-correct="true" > La recta corta a ambos ejes coordenados en puntos diferentes del origen</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934733266" value="8" data-correct="true" > La recta es inclinada ya que el corte con el eje $Y$ es diferente de cero</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934733266" value="9" data-correct="false" > La recta tiene pendiente $m>0$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934733266" value="10" data-correct="true" > La recta pasa por el punto $P$ de coordenadas $P(2,-2)$</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796552934733266')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">Correcto!</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto</div><div class="learnr-data-retry" style="display:none;">Intentelo nuevamente</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 12

<div class="learnr-question-box" id="q17796552934821267"><div class="learnr-question-text">Seleccione todas las afirmaciones verdaderas sobre la expresión matemática: $$3^2 \cdot 3$$</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796552934821267" value="1" data-correct="true" > Es equivalente a $3^3$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934821267" value="2" data-correct="true" > Su valor simplificado es igual a 27</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934821267" value="3" data-correct="true" > Es equivalente a la operación $9 \cdot 3$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934821267" value="4" data-correct="true" > Representa una multiplicación de potencias con la misma base</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934821267" value="5" data-correct="false" > Su valor simplificado es igual a 9</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934821267" value="6" data-correct="false" > Es equivalente a $3^6$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796552934821267" value="7" data-correct="false" > Su valor simplificado es igual a 18</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796552934821267')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">Correcto!</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto</div><div class="learnr-data-retry" style="display:none;">Inténtelo nuevamente</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

---

## Resultados de la Evaluación

Para ver el análisis de tu desempeño en esta prueba, haz clic en el siguiente botón. El sistema evaluará tus respuestas y te proporcionará recomendaciones personalizadas.

<button type="button" class="learnr-submit-btn" style="margin-bottom:1rem;" onclick="showScoreReport('sr17796552935031208', 12, '<strong>¡Espectacular!</strong> Tienes un dominio sobresaliente de las ecuaciones cuadráticas, parábolas y análisis de rectas. Has alcanzado un nivel excelente de razonamiento geométrico y algebraico. ¡Sigue así!', '<strong>¡Buen intento!</strong> Has aprobado el simulacro, pero aún hay conceptos de geometría analítica que puedes pulir. Te sugerimos repasar el cálculo del vértice de una parábola y la identificación exacta de cortes y pendientes en rectas. ¡Con un poco más de práctica lograrás el dominio completo!', '<strong>Se recomienda más práctica.</strong> Has tenido varias respuestas incorrectas o dudas en los temas. Te sugerimos usar las aplicaciones interactivas de Shiny incluidas de manera detenida para comprender la relación exacta entre las ecuaciones y sus gráficas (vértices, raíces e inclinaciones) antes de volver a intentarlo. ¡No te desanimimes, la práctica hace al maestro!')">Calcular Mis Resultados</button><div id="sr17796552935031208"></div>
