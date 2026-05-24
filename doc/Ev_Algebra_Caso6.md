---
title: "Evaluación de Álgebra: Resolución de Ecuaciones (Caso 6)"
output: html_document
---


# Evaluación de Álgebra: Resolución de Ecuaciones (Caso 6)

<style>
/* Estilos Premium para la Evaluación de Álgebra (Caso 6) - Tema Amatista */
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
  background: linear-gradient(135deg, #8b5cf6 0%, #6d28d9 100%);
  color: white;
  padding: 2.5rem 2rem;
  border-radius: 16px;
  text-align: center;
  margin-bottom: 2rem;
  box-shadow: 0 10px 25px -5px rgba(139, 92, 246, 0.3);
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
  border-left: 5px solid #8b5cf6;
  margin-top: 1rem;
}

.tutorial-question-title {
  font-family: 'Outfit', sans-serif;
  font-size: 1.25rem;
  font-weight: 600;
  color: #1e2638;
  margin-bottom: 1rem;
  line-height: 1.5;
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
  border-color: #8b5cf6 !important;
  background-color: #f5f3ff !important;
  transform: translateX(4px);
}

.answer-option.selected {
  background-color: #ede9fe !important;
  border-color: #8b5cf6 !important;
}

/* Botones */
.btn-primary, .btn-submit, .btn-action {
  background: linear-gradient(135deg, #8b5cf6 0%, #6d28d9 100%) !important;
  border: none !important;
  color: white !important;
  font-weight: 600 !important;
  font-family: 'Outfit', sans-serif !important;
  padding: 0.6rem 1.5rem !important;
  border-radius: 8px !important;
  transition: all 0.2s ease !important;
  box-shadow: 0 4px 12px rgba(139, 92, 246, 0.2) !important;
}

.btn-primary:hover, .btn-submit:hover {
  transform: translateY(-1px) !important;
  box-shadow: 0 6px 16px rgba(139, 92, 246, 0.3) !important;
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

.alert-warning {
  background-color: #fffbeb !important;
  border-color: #f59e0b !important;
  color: #78350f !important;
  border-radius: 8px !important;
}

/* Insignias de Verdadero/Falso */
.badge-true {
  background: #dbeafe;
  color: #1e40af;
  padding: 0.25rem 0.75rem;
  border-radius: 9999px;
  font-size: 0.85rem;
  font-weight: 600;
  display: inline-block;
  margin-bottom: 0.5rem;
}

.badge-false {
  background: #fee2e2;
  color: #991b1b;
  padding: 0.25rem 0.75rem;
  border-radius: 9999px;
  font-size: 0.85rem;
  font-weight: 600;
  display: inline-block;
  margin-bottom: 0.5rem;
}
</style>



## Introducción

Bienvenido a la **Evaluación de Álgebra: Resolución de Ecuaciones (Caso 6)**. Este examen interactivo consta de **35 preguntas** diseñadas para evaluar tu capacidad de resolver analíticamente ecuaciones lineales, fraccionarias, cuadráticas, exponenciales, irracionales y con raíces fraccionarias.

> **Instrucciones:**
> * Resuelve detalladamente cada ecuación en papel antes de responder.
> * ¡Ten cuidado con las raíces extrañas en ecuaciones con radicales! Comprueba siempre tus soluciones.
> * El **51% de las preguntas (18 preguntas)** te pedirá seleccionar las **afirmaciones verdaderas**.
> * El **49% de las preguntas (17 preguntas)** te pedirá seleccionar **únicamente las afirmaciones falsas**.
> * Al final de la prueba, podrás visualizar un reporte detallado con tus respuestas y una recomendación de estudio personalizada.
> * ¡Mucho éxito!

---

## Bloque 1: Preguntas de la 1 a la 12

### Pregunta 1 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513761419845"><div class="learnr-question-text">Resuelve la ecuación lineal: $\frac{2}{3}x+\frac{4}{3}=x -\frac{1}{3}$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513761419845" value="1" data-correct="true" > $x = 5$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513761419845" value="2" data-correct="true" > Al multiplicar ambos lados por $3$, obtenemos la ecuación entera directa $2x + 4 = 3x - 1$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513761419845" value="3" data-correct="true" > El valor $x = 5$ satisface perfectamente la igualdad original dando $14/3$ en ambos lados.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513761419845" value="4" data-correct="false" > $x = -5$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513761419845" value="5" data-correct="false" > $x = 1/3$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513761419845" value="6" data-correct="false" > La ecuación no posee solución en el conjunto de los números reales.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513761419845')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has resuelto la ecuación lineal de manera adecuada.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Elimina los denominadores multiplicando por $3$ y agrupa los términos lineales.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 2 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513761536506"><div class="learnr-question-text">Resuelve la ecuación: $4(1-x)=x-3(x+1)$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513761536506" value="1" data-correct="true" > $x = -7/2$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513761536506" value="2" data-correct="true" > La ecuación se reduce a la identidad lineal simple $x = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513761536506" value="3" data-correct="true" > El conjunto solución incluye a la constante $x = 3.5$ como una raíz de signo negativo.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513761536506" value="4" data-correct="false" > $x = 7/2$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513761536506" value="5" data-correct="false" > Al distribuir los términos obtenemos $4 - 4x = -2x - 3$, que al agrupar da $2x = 7$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513761536506" value="6" data-correct="false" > La solución única es el decimal $3.5$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513761536506')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has identificado todos los distractores incorrectos.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Debes marcar únicamente las afirmaciones falsas sobre la resolución lineal.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 3 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513761711033"><div class="learnr-question-text">Resuelve la ecuación fraccionaria: $\dfrac{4}{r+1}-5=4-\dfrac{3}{r+1}$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513761711033" value="1" data-correct="true" > $r = -2/9$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513761711033" value="2" data-correct="true" > Reagrupando las fracciones en un lado se obtiene $\dfrac{7}{r+1} = 9$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513761711033" value="3" data-correct="true" > El valor $r = -1$ está excluido del dominio por anular el denominador.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513761711033" value="4" data-correct="false" > $r = -9/2$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513761711033" value="5" data-correct="false" > $r = 2/9$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513761711033" value="6" data-correct="false" > $r = 0$</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513761711033')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has resuelto la ecuación fraccionaria lineal de forma correcta.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Junta las expresiones con denominadores comunes en un lado y las constantes en el otro.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 4 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513761802851"><div class="learnr-question-text">Resuelve la ecuación cuadrática: $x(2x-1)=3$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513761802851" value="1" data-correct="true" > La ecuación tiene una única raíz real en $x = 3/2$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513761802851" value="2" data-correct="true" > Las soluciones de la ecuación son $x = -3/2$ y $x = 1$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513761802851" value="3" data-correct="true" > El discriminante de la ecuación cuadrática resultante es negativo.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513761802851" value="4" data-correct="false" > Las soluciones reales son $x = 3/2$ y $x = -1$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513761802851" value="5" data-correct="false" > Al distribuir los términos obtenemos la ecuación cuadrática estándar $2x^2 - x - 3 = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513761802851" value="6" data-correct="false" > La ecuación factorizada es $(2x-3)(x+1) = 0$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513761802851')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has descartado todas las afirmaciones incorrectas.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Debes marcar únicamente las afirmaciones falsas. Recuerda igualar a cero y factorizar como $(2x-3)(x+1) = 0$.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 5 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513761905307"><div class="learnr-question-text">Resuelve la ecuación con exponentes fraccionarios: $0=x^{\frac{1}{4}}-2x^{\frac{1}{2}}+1$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513761905307" value="1" data-correct="true" > $x = 1$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513761905307" value="2" data-correct="true" > Realizando el cambio de variable $y = x^{1/4}$ obtenemos la ecuación cuadrática en términos de $y$: $2y^2 - y - 1 = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513761905307" value="3" data-correct="true" > La raíz $y = -1/2$ se descarta ya que la raíz cuarta de un número real no puede ser negativa, dejando como única solución válida $y = 1 \implies x = 1$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513761905307" value="4" data-correct="false" > $x = 1/16$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513761905307" value="5" data-correct="false" > $x = 0$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513761905307" value="6" data-correct="false" > La ecuación posee dos raíces reales válidas dadas por $x = 1$ y $x = 1/16$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513761905307')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has resuelto la ecuación cuadrática por sustitución correctamente.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Haz un cambio de variable del tipo $y = x^{1/4}$, resuelve la cuadrática para $y$ y descarta las raíces negativas.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 6 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513761999197"><div class="learnr-question-text">Resuelve la ecuación con radicales: $3+\sqrt{3x+1}=x$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513761999197" value="1" data-correct="true" > El conjunto de soluciones reales consta de dos raíces dadas por $x = 1$ y $x = 8$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513761999197" value="2" data-correct="true" > El valor $x = 1$ es una solución válida y real de la ecuación.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513761999197" value="3" data-correct="true" > La ecuación cuadrática resultante al elevar al cuadrado directamente es $x^2 - 6x + 9 = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513761999197" value="4" data-correct="false" > La única solución real y válida es $x = 8$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513761999197" value="5" data-correct="false" > Al elevar al cuadrado la expresión aislada $\sqrt{3x+1} = x-3$ se obtiene la cuadrática $x^2 - 9x + 8 = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513761999197" value="6" data-correct="false" > El valor $x = 1$ es una raíz extraña que se introduce al elevar al cuadrado, ya que $3 + \sqrt{4} = 5 \neq 1$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513761999197')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has identificado el distractor de la raíz extraña.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Debes marcar únicamente las afirmaciones falsas. Recuerda comprobar las soluciones para descartar las raíces extrañas.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 7 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513762081689"><div class="learnr-question-text">Resuelve la ecuación con raíz cúbica: $\sqrt[3]{x^{2}+17}=4$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513762081689" value="1" data-correct="true" > $x = \pm \sqrt{47}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762081689" value="2" data-correct="true" > Elevando al cubo ambos miembros se elimina la raíz cúbica resultando en $x^2 + 17 = 64$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762081689" value="3" data-correct="true" > La ecuación cuadrática resultante tiene como soluciones reales simétricas $x = \sqrt{47}$ y $x = -\sqrt{47}$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762081689" value="4" data-correct="false" > $x = \pm 47$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762081689" value="5" data-correct="false" > $x = \pm 3$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762081689" value="6" data-correct="false" > La ecuación no posee soluciones reales porque el argumento contiene una constante positiva.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513762081689')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Despeje con raíces cúbicas resuelto correctamente.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Eleva ambos lados al cubo para eliminar la raíz cúbica y luego aísla el término cuadrático.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 8 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513762183218"><div class="learnr-question-text">Resuelve la ecuación con múltiples raíces cuadradas: $\sqrt{x+2}-\sqrt{x-3}=\sqrt{x-6}$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513762183218" value="1" data-correct="true" > La ecuación tiene dos soluciones reales válidas dadas por $x = -7/3$ y $x = 7$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762183218" value="2" data-correct="true" > El valor $x = -7/3$ es una raíz completamente válida que satisface la igualdad original.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762183218" value="3" data-correct="true" > El dominio físico de los radicales permite tomar valores reales de $x \ge 3$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762183218" value="4" data-correct="false" > La única solución real y válida es $x = 7$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762183218" value="5" data-correct="false" > La restricción del dominio debido al radical de la derecha exige que $x \ge 6$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762183218" value="6" data-correct="false" > Al elevar al cuadrado consecutivamente se obtiene la ecuación cuadrática $3x^2 - 14x - 49 = 0$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513762183218')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has descartado la raíz fuera del dominio correctamente.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Debes marcar únicamente las afirmaciones falsas. Recuerda que el dominio de $\sqrt{x-6}$ requiere $x \ge 6$, descartando $x = -7/3$.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 9 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513762301154"><div class="learnr-question-text">Resuelve la ecuación con exponente negativo: $x+3-28x^{-1}=0$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513762301154" value="1" data-correct="true" > $x = -7$ y $x = 4$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762301154" value="2" data-correct="true" > Al multiplicar la ecuación por $x$ (con $x \neq 0$) obtenemos la ecuación cuadrática equivalente $x^2 + 3x - 28 = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762301154" value="3" data-correct="true" > La factorización del trinomio resultante es $(x+7)(x-4) = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762301154" value="4" data-correct="false" > $x = 7$ y $x = -4$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762301154" value="5" data-correct="false" > $x = -7$ y $x = -4$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762301154" value="6" data-correct="false" > La única solución real es $x = 4$ ya que los números negativos no son válidos para exponentes negativos.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513762301154')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has resuelto el despeje con potencia negativa de forma correcta.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Reescribe $x^{-1} = 1/x$, multiplica todo por $x$ y resuelve la ecuación cuadrática resultante.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 10 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513762403514"><div class="learnr-question-text">Resuelve la ecuación con radicales racionales: $\dfrac{1}{\sqrt{x}}+\sqrt{x}=\dfrac{5}{\sqrt{x}}-2\sqrt{x}$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513762403514" value="1" data-correct="true" > $x = 3/4$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762403514" value="2" data-correct="true" > El resultado de la ecuación simplificada es la constante entera $x = 3$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762403514" value="3" data-correct="true" > Al multiplicar ambos lados por $\sqrt{x}$ obtenemos la ecuación lineal $3x = 1$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762403514" value="4" data-correct="false" > $x = 4/3$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762403514" value="5" data-correct="false" > Agrupando los términos semejantes se obtiene la igualdad intermedia $3\sqrt{x} = \dfrac{4}{\sqrt{x}}$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762403514" value="6" data-correct="false" > El dominio exige que la variable sea estrictamente positiva ($x > 0$).</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513762403514')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has identificado todos los distractores incorrectos.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Selecciona únicamente las afirmaciones falsas del despeje con radicales racionales.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 11 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513762519569"><div class="learnr-question-text">Resuelve la ecuación fraccionaria compleja: $\dfrac{2}{5}+\dfrac{4}{10x+5}=\dfrac{7}{2x+1}$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513762519569" value="1" data-correct="true" > $x = 29/4$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762519569" value="2" data-correct="true" > Dado que $10x + 5 = 5(2x+1)$, al multiplicar la ecuación por el mínimo común denominador $5(2x+1)$ se obtiene $2(2x+1) + 4 = 35$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762519569" value="3" data-correct="true" > El valor $x = -1/2$ está excluido del dominio de la expresión por anular los denominadores.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762519569" value="4" data-correct="false" > $x = -29/4$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762519569" value="5" data-correct="false" > $x = 4/29$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762519569" value="6" data-correct="false" > La ecuación no posee raíces reales al reducirse a una inconsistencia numérica.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513762519569')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has resuelto la fracción compleja fraccionaria de forma adecuada.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Factoriza el término de la izquierda $10x+5 = 5(2x+1)$ y reduce usando el común denominador.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 12 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513762623279"><div class="learnr-question-text">Resuelve la ecuación por multiplicación cruzada: $\dfrac{3x+1}{6x-2}=\dfrac{2x+5}{4x-13}$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513762623279" value="1" data-correct="true" > $x = 3/61$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762623279" value="2" data-correct="true" > La ecuación cuadrática resultante al expandir los productos cruzados es de segundo grado completo.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762623279" value="3" data-correct="true" > El término independiente final de la ecuación lineal simplificada es positivo.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762623279" value="4" data-correct="false" > $x = -3/61$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762623279" value="5" data-correct="false" > Efectuando el producto cruzado $(3x+1)(4x-13) = (2x+5)(6x-2)$ y simplificando los términos $12x^2$ se reduce a la ecuación lineal $61x = -3$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762623279" value="6" data-correct="false" > Los valores $x = 1/3$ y $x = 13/4$ son restricciones del dominio de la ecuación.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513762623279')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has completado el primer bloque de ecuaciones con éxito.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Debes marcar únicamente las afirmaciones falsas. Recuerda que los términos cuadráticos de $12x^2$ se cancelan directamente.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

---

## Bloque 2: Preguntas de la 13 a la 24

### Pregunta 13 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513762739613"><div class="learnr-question-text">Resuelve la ecuación lineal: $\dfrac{2x-9}{4}=2+\dfrac{x}{12}$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513762739613" value="1" data-correct="true" > $x = 51/5$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762739613" value="2" data-correct="true" > Multiplicar la ecuación por el mínimo común múltiplo $12$ la transforma en la ecuación entera lineal $3(2x-9) = 24 + x$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762739613" value="3" data-correct="true" > El valor decimal de la única solución es exactamente $10.2$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762739613" value="4" data-correct="false" > $x = -51/5$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762739613" value="5" data-correct="false" > $x = 5/51$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762739613" value="6" data-correct="false" > La ecuación posee infinitas soluciones reales.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513762739613')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has resuelto la ecuación lineal de manera adecuada.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Elimina los denominadores multiplicando por 12, distribuye y agrupa la variable lineal.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 14 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513762833287"><div class="learnr-question-text">Resuelve la ecuación con radical: $x=4+\sqrt{4x-19}$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513762833287" value="1" data-correct="true" > El valor $x = 5$ es una raíz extraña de la ecuación cuadrática y debe descartarse.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762833287" value="2" data-correct="true" > La única solución real y válida es $x = 7$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762833287" value="3" data-correct="true" > Al elevar al cuadrado directamente la ecuación sin aislar el radical se obtiene $x^2 = 16 + 4x - 19$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762833287" value="4" data-correct="false" > Ambos valores dadas por la cuadrática, $x = 5$ y $x = 7$, son raíces reales y completamente válidas de la ecuación original.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762833287" value="5" data-correct="false" > Al aislar el radical $x - 4 = \sqrt{4x-19}$ y elevar al cuadrado, se obtiene la cuadrática factorizable $x^2 - 12x + 35 = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762833287" value="6" data-correct="false" > La restricción del dominio requiere que $x \ge 19/4$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513762833287')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has verificado la validez de ambas raíces reales con éxito.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Debes marcar únicamente las afirmaciones falsas. Recuerda comprobar que tanto 5 como 7 satisfacen la igualdad sin inconsistencias.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 15 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513762954415"><div class="learnr-question-text">Resuelve la ecuación con radicales: $\sqrt{7-2x}-\sqrt{5+x}=\sqrt{4+3x}$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513762954415" value="1" data-correct="true" > $x = -1$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762954415" value="2" data-correct="true" > El valor $x = 19/6 \approx 3.17$ es una raíz extraña que surge al elevar al cuadrado, ya que no satisface la igualdad original.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762954415" value="3" data-correct="true" > La ecuación cuadrática obtenida tras elevar consecutivamente al cuadrado es $6x^2 - 13x - 19 = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762954415" value="4" data-correct="false" > $x = 19/6$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762954415" value="5" data-correct="false" > Ambas raíces reales $x = -1$ y $x = 19/6$ son soluciones completamente válidas.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513762954415" value="6" data-correct="false" > La ecuación no posee soluciones reales al estar fuera de todo dominio común.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513762954415')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has descartado la raíz extraña fraccionaria correctamente.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Eleva al cuadrado, agrupa el nuevo radical, eleva nuevamente al cuadrado y comprueba las raíces de la ecuación cuadrática $6x^2-13x-19=0$.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 16 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513763053287"><div class="learnr-question-text">Resuelve la ecuación con doble radical: $\sqrt{2\sqrt{x+1}}=\sqrt{3x-5}$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513763053287" value="1" data-correct="true" > La ecuación tiene como conjunto solución a las raíces $x = 7/9$ y $x = 3$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763053287" value="2" data-correct="true" > El valor $x = 7/9$ es una solución real y válida de la ecuación.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763053287" value="3" data-correct="true" > El dominio exige que la variable tome valores reales de $x \ge -1$ únicamente.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763053287" value="4" data-correct="false" > La única solución real y válida es $x = 3$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763053287" value="5" data-correct="false" > La ecuación cuadrática resultante tras elevar consecutivamente al cuadrado es $9x^2 - 34x + 21 = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763053287" value="6" data-correct="false" > La restricción debido al radical lineal de la derecha exige que $x \ge 5/3$, lo cual excluye de manera lógica al valor $x = 7/9 \approx 0.78$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513763053287')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has identificado el distractor de la raíz extraña cuadrática.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Debes marcar únicamente las afirmaciones falsas. Recuerda que el argumento $3x-5$ debe ser no negativo, descartando $7/9$.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 17 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513763165695"><div class="learnr-question-text">Resuelve la ecuación con raíz anidada: $\sqrt{1+4\sqrt{x}}=\sqrt{x}+1$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513763165695" value="1" data-correct="true" > $x = 0$ y $x = 4$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763165695" value="2" data-correct="true" > Elevando al cuadrado ambos miembros obtenemos la ecuación $1 + 4\sqrt{x} = x + 2\sqrt{x} + 1$, que al simplificarse da $x - 2\sqrt{x} = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763165695" value="3" data-correct="true" > Factorizando como $\sqrt{x}(\sqrt{x}-2) = 0$ obtenemos de forma correcta ambas soluciones válidas.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763165695" value="4" data-correct="false" > La única solución real es $x = 4$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763165695" value="5" data-correct="false" > La única solución real es $x = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763165695" value="6" data-correct="false" > La ecuación no posee soluciones reales debido al radical anidado de la izquierda.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513763165695')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has resuelto la ecuación irracional de dos raíces correctamente.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Eleva al cuadrado, agrupa los términos semejantes y resuelve mediante factorización por factor común $\sqrt{x}$.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 18 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513763285247"><div class="learnr-question-text">Resuelve la ecuación de cuarto grado: $x^{4}-34x^{2}+225=0$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513763285247" value="1" data-correct="true" > La ecuación tiene únicamente dos raíces reales dadas por $x = 3$ y $x = 5$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763285247" value="2" data-correct="true" > La ecuación no es factorizable en el conjunto de los números enteros.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763285247" value="3" data-correct="true" > Las soluciones reales finales de la ecuación son $x = \pm 9$ y $x = \pm 25$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763285247" value="4" data-correct="false" > Las cuatro raíces reales de la ecuación cuadrática por sustitución son $x = \pm 3$ y $x = \pm 5$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763285247" value="5" data-correct="false" > Realizando el cambio de variable $y = x^2$ obtenemos la ecuación cuadrática equivalente $y^2 - 34y + 225 = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763285247" value="6" data-correct="false" > Los factores del trinomio sustituido son $(y-9)(y-25) = 0$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513763285247')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has dominado la ecuación bicuadrática entera.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Debes marcar únicamente las afirmaciones falsas. Recuerda extraer la raíz cuadrada de $y = 9$ y $y = 25$ para hallar las 4 soluciones.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 19 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513763418771"><div class="learnr-question-text">Resuelve la ecuación bicuadrática: $x^{4}-10x^{2}+8=0$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513763418771" value="1" data-correct="true" > $x = \pm \sqrt{5 \pm \sqrt{17}}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763418771" value="2" data-correct="true" > Utilizando la sustitución $y = x^2$, la cuadrática resultante tiene raíces dadas por la fórmula general como $y = 5 \pm \sqrt{17}$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763418771" value="3" data-correct="true" > Dado que $5 - \sqrt{17} \approx 0.88$ es un número real positivo, la ecuación bicuadrática posee cuatro soluciones reales.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763418771" value="4" data-correct="false" > $x = \pm (5 \pm \sqrt{17})$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763418771" value="5" data-correct="false" > $x = \pm \sqrt{10 \pm \sqrt{8}}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763418771" value="6" data-correct="false" > La ecuación no posee raíces reales porque el discriminante de la cuadrática en $y$ es negativo.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513763418771')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has resuelto la ecuación bicuadrática con raíces anidadas correctamente.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Aplica el cambio de variable $y=x^2$, resuelve la ecuación por fórmula cuadrática general y extrae las raíces cuadradas.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 20 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513763504788"><div class="learnr-question-text">Resuelve la ecuación cuadrática básica: $y^{2} - 17y + 16 = 0$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513763504788" value="1" data-correct="true" > Las soluciones reales son $y = -1$ y $y = -16$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763504788" value="2" data-correct="true" > La factorización del trinomio es $(y-8)(y-2) = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763504788" value="3" data-correct="true" > La ecuación no es factorizable en los números reales por tener discriminante negativo.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763504788" value="4" data-correct="false" > Las soluciones de la ecuación son $y = 1$ y $y = 16$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763504788" value="5" data-correct="false" > La factorización del trinomio cuadrático es $(y-16)(y-1) = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763504788" value="6" data-correct="false" > La suma de las raíces es $17$ y su producto es $16$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513763504788')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has descartado todas las afirmaciones incorrectas.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Debes marcar únicamente las afirmaciones falsas del despeje cuadrático simple.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 21 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513763587694"><div class="learnr-question-text">Resuelve la ecuación cuadrática: $2x^{2} + x - 1 = 0$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513763587694" value="1" data-correct="true" > $x = 1/2$ y $x = -1$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763587694" value="2" data-correct="true" > La factorización del trinomio cuadrático mediante aspas da $(2x-1)(x+1) = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763587694" value="3" data-correct="true" > El producto de las dos raíces reales es igual a $-1/2$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763587694" value="4" data-correct="false" > $x = -1/2$ y $x = 1$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763587694" value="5" data-correct="false" > $x = 1/2$ y $x = 1$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763587694" value="6" data-correct="false" > La ecuación posee una única raíz doble en $x = -1$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513763587694')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has resuelto la ecuación cuadrática racional de manera adecuada.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Factoriza el trinomio por aspas como $(2x-1)(x+1)=0$ para aislar los valores.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 22 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513763689449"><div class="learnr-question-text">Resuelve la ecuación cuadrática: $25y^{2} + 15y = -2$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513763689449" value="1" data-correct="true" > Las soluciones reales son $y = 1/5$ y $y = 2/5$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763689449" value="2" data-correct="true" > La factorización del trinomio ordenado es $(5y-1)(5y-2) = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763689449" value="3" data-correct="true" > El discriminante de la ecuación cuadrática resultante es negativo.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763689449" value="4" data-correct="false" > Las soluciones son las constantes fraccionarias negativas $y = -1/5$ y $y = -2/5$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763689449" value="5" data-correct="false" > Al ordenar e igualar a cero se obtiene el trinomio cuadrático completo $25y^2 + 15y + 2 = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763689449" value="6" data-correct="false" > La factorización correcta da $(5y+1)(5y+2) = 0$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513763689449')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has identificado todos los distractores incorrectos.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Debes marcar únicamente las afirmaciones falsas. Recuerda ordenar como $25y^2 + 15y + 2 = 0$ y factorizar.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 23 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513763778320"><div class="learnr-question-text">Resuelve la ecuación cuadrática literal: $2a^{2} = a + 1$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513763778320" value="1" data-correct="true" > $a = 1$ y $a = -1/2$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763778320" value="2" data-correct="true" > La ecuación cuadrática ordenada $2a^2 - a - 1 = 0$ se factoriza como $(2a+1)(a-1) = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763778320" value="3" data-correct="true" > El valor entero $a = 1$ satisface correctamente la igualdad original.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763778320" value="4" data-correct="false" > $a = -1$ y $a = 1/2$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763778320" value="5" data-correct="false" > $a = 1$ y $a = 1/2$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763778320" value="6" data-correct="false" > La ecuación no posee raíces reales debido a la constante.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513763778320')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Despeje cuadrático literal resuelto correctamente.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Ordena e iguala a cero dando $2a^2-a-1=0$, y luego factoriza como $(2a+1)(a-1)=0$.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 24 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513763872001"><div class="learnr-question-text">Resuelve la ecuación cúbica: $x^{3} = 9x$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513763872001" value="1" data-correct="true" > La ecuación cúbica posee únicamente dos soluciones dadas por $x = \pm 3$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763872001" value="2" data-correct="true" > La constante real $x = 0$ no es una raíz válida de la ecuación original al anular las variables.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763872001" value="3" data-correct="true" > Al dividir ambos lados directamente por $x$ se conservan de forma rigurosa todas las raíces.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763872001" value="4" data-correct="false" > Las tres soluciones reales y válidas son $x = 0$ y $x = \pm 3$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763872001" value="5" data-correct="false" > Agrupando e igualando a cero se obtiene $x^3 - 9x = 0$, que se descompone como el producto de factores reales $x(x-3)(x+3) = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763872001" value="6" data-correct="false" > La diferencia de cuadrados resultante tras extraer la variable común $x$ es $x^2 - 9 = 0$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513763872001')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has completado el segundo bloque de ecuaciones con éxito.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Debes marcar únicamente las afirmaciones falsas. Recuerda que dividir por $x$ elimina la raíz $x = 0$, lo cual es incorrecto.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

---

## Bloque 3: Preguntas de la 25 a la 35

### Pregunta 25 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513763969209"><div class="learnr-question-text">Resuelve la ecuación de cuarto grado: $16q^{4} = q^{2}$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513763969209" value="1" data-correct="true" > $q = 0$ y $q = \pm 1/4$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763969209" value="2" data-correct="true" > La ecuación se descompone mediante factorización como $q^2 (16q^2 - 1) = 0$, lo que genera una raíz doble en cero y dos raíces racionales simétricas.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763969209" value="3" data-correct="true" > Las soluciones reales no nulas de la ecuación son las constantes racionales $1/4$ y $-1/4$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763969209" value="4" data-correct="false" > $q = \pm 1/2$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763969209" value="5" data-correct="false" > $q = \pm 4$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513763969209" value="6" data-correct="false" > La ecuación posee cuatro raíces reales distintas dadas por $\pm 1/2$ y $\pm 1/4$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513763969209')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has resuelto la ecuación bicuadrática factorizable correctamente.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Igual a cero dando $16q^4-q^2=0$, extrae el factor común $q^2$ y aplica diferencia de cuadrados.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 26 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513764061549"><div class="learnr-question-text">Resuelve la ecuación de quinto grado: $4w^{5} = 25w^{3}$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513764061549" value="1" data-correct="true" > La ecuación posee únicamente dos raíces dadas por $w = \pm 5/2$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764061549" value="2" data-correct="true" > La constante nula $w = 0$ es una raíz de multiplicidad uno.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764061549" value="3" data-correct="true" > Las soluciones no nulas de la ecuación son $w = \pm 25/4$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764061549" value="4" data-correct="false" > Las soluciones reales son $w = 0$ y $w = \pm 5/2$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764061549" value="5" data-correct="false" > Al igualar a cero y extraer el factor común $w^3$ obtenemos $w^3(4w^2-25) = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764061549" value="6" data-correct="false" > La raíz en cero es de multiplicidad tres ya que el factor común es $w^3$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513764061549')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has detectado todos los distractores incorrectos de grado 5.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Debes marcar únicamente las afirmaciones falsas. Recuerda incluir la raíz $w=0$ con su multiplicidad correcta.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 27 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513764154358"><div class="learnr-question-text">Resuelve la ecuación cuadrática: $3y^{2} - 13y + 4 = 0$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513764154358" value="1" data-correct="true" > $y = 4$ y $y = 1/3$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764154358" value="2" data-correct="true" > La factorización del trinomio mediante aspas se descompone como $(3y-1)(y-4) = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764154358" value="3" data-correct="true" > El producto de las soluciones reales de la ecuación es igual a la constante $4/3$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764154358" value="4" data-correct="false" > $y = -4$ y $y = -1/3$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764154358" value="5" data-correct="false" > $y = 4$ y $y = 3$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764154358" value="6" data-correct="false" > La ecuación no posee soluciones racionales por tener discriminante no cuadrado.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513764154358')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Ecuación cuadrática resuelta de manera adecuada.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Factoriza el trinomio cuadrático como $(3y-1)(y-4)=0$ para aislar las raíces.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 28 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513764248601"><div class="learnr-question-text">Resuelve la ecuación cuadrática: $4x^{2} - 12x + 9 = 0$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513764248601" value="1" data-correct="true" > La ecuación posee dos raíces distintas reales dadas por $x = 3/2$ y $x = -3/2$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764248601" value="2" data-correct="true" > El discriminante de la ecuación cuadrática es estrictamente positivo.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764248601" value="3" data-correct="true" > La ecuación no posee raíces reales por tratarse de una suma cuadrática.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764248601" value="4" data-correct="false" > La ecuación tiene una única raíz real doble en $x = 3/2$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764248601" value="5" data-correct="false" > El trinomio cuadrático es un trinomio cuadrado perfecto de la forma $(2x-3)^2 = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764248601" value="6" data-correct="false" > El discriminante se anula por completo: $D = 144 - 144 = 0$.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513764248601')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has identificado todos los distractores incorrectos de la raíz doble.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Debes marcar únicamente las afirmaciones falsas. Recuerda que es un trinomio cuadrado perfecto y por tanto posee raíz doble.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 29 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513764339613"><div class="learnr-question-text">Resuelve la ecuación cuadrática: $3y^{2} - 7y = -2$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513764339613" value="1" data-correct="true" > $y = 2$ y $y = 1/3$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764339613" value="2" data-correct="true" > Al ordenar e igualar a cero se obtiene el trinomio cuadrático completo $3y^2 - 7y + 2 = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764339613" value="3" data-correct="true" > La factorización por aspas del polinomio resultante da $(3y-1)(y-2) = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764339613" value="4" data-correct="false" > $y = -2$ y $y = -1/3$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764339613" value="5" data-correct="false" > $y = 2$ y $y = 3$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764339613" value="6" data-correct="false" > La ecuación no posee raíces reales al estar el término independiente en el miembro derecho.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513764339613')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Despeje cuadrático resuelto de forma adecuada.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Ordena la ecuación como $3y^2-7y+2=0$ y factoriza como $(3y-1)(y-2)=0$.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 30 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513764438855"><div class="learnr-question-text">Resuelve la ecuación cuadrática: $4a^{2} = -8a - 4$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513764438855" value="1" data-correct="true" > Las soluciones reales son $a = 1$ y $a = -1$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764438855" value="2" data-correct="true" > La ecuación cuadrática resultante tiene raíces complejas conjugadas no reales.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764438855" value="3" data-correct="true" > El discriminante del polinomio final es estrictamente positivo.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764438855" value="4" data-correct="false" > La ecuación posee una única raíz real doble en $a = -1$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764438855" value="5" data-correct="false" > Dividiendo toda la ecuación ordenada $4a^2 + 8a + 4 = 0$ entre $4$ se obtiene la forma simple $(a+1)^2 = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764438855" value="6" data-correct="false" > El discriminante se anula por completo al tratarse de un trinomio cuadrado perfecto.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513764438855')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has detectado todas las justificaciones falsas de la raíz doble.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Debes marcar únicamente las afirmaciones falsas. Recuerda reducir dividiendo por 4 para hallar la raíz doble $-1$.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 31 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513764512046"><div class="learnr-question-text">Resuelve la ecuación cuadrática: $9x^{2} = -30x - 25$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513764512046" value="1" data-correct="true" > $x = -5/3$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764512046" value="2" data-correct="true" > Al ordenar los términos a la izquierda se obtiene el trinomio cuadrado perfecto $9x^2 + 30x + 25 = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764512046" value="3" data-correct="true" > La ecuación posee una única raíz real doble dada por la factorización $(3x+5)^2 = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764512046" value="4" data-correct="false" > $x = 5/3$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764512046" value="5" data-correct="false" > $x = \pm 5/3$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764512046" value="6" data-correct="false" > La ecuación no posee raíces reales por anularse el término cuadrático.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513764512046')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has obtenido la raíz doble fraccionaria correctamente.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Ordena e iguala a cero obteniendo la forma perfecta $(3x+5)^2=0$ para despejar.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 32 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513764596561"><div class="learnr-question-text">Resuelve la ecuación cuadrática: $-10q^{2} = -5q - 2$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513764596561" value="1" data-correct="true" > Las soluciones son racionales y se factorizan como $(5q+2)(2q-1) = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764596561" value="2" data-correct="true" > El discriminante de la ecuación cuadrática ordenada es estrictamente negativo, por lo que no posee raíces reales.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764596561" value="3" data-correct="true" > Las raíces reales son las constantes enteras $q = 2$ y $q = 5$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764596561" value="4" data-correct="false" > Las raíces reales de la ecuación son las constantes irracionales $q = \dfrac{5 \pm \sqrt{105}}{20}$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764596561" value="5" data-correct="false" > Al ordenar e igualar a cero se obtiene la ecuación cuadrática completa $10q^2 - 5q - 2 = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764596561" value="6" data-correct="false" > El discriminante de la cuadrática resultante es $D = 25 - 4(10)(-2) = 105$, lo que confirma la existencia de dos raíces reales distintas.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513764596561')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has analizado el discriminante y las raíces irracionales con éxito.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Debes marcar únicamente las afirmaciones falsas. Recuerda comprobar que el discriminante es positivo ($105$), garantizando raíces reales.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 33 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513764694087"><div class="learnr-question-text">Resuelve la ecuación cuadrática: $-5w^{2} = -2w - 1$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513764694087" value="1" data-correct="true" > $w = \dfrac{1 \pm \sqrt{6}}{5}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764694087" value="2" data-correct="true" > La ecuación cuadrática ordenada e igualada a cero es $5w^2 - 2w - 1 = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764694087" value="3" data-correct="true" > El discriminante de la ecuación resultante es $D = 24$, lo que garantiza que posee dos raíces reales distintas irracionales.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764694087" value="4" data-correct="false" > $w = \dfrac{1 \pm \sqrt{24}}{5}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764694087" value="5" data-correct="false" > $w = \dfrac{2 \pm \sqrt{6}}{5}$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764694087" value="6" data-correct="false" > La ecuación posee soluciones racionales enteras.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513764694087')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has resuelto la ecuación cuadrática irracional de forma correcta.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Ordena la ecuación como $5w^2-2w-1=0$ y aplica la fórmula general simplificando $\sqrt{24} = 2\sqrt{6}$.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 34 (Seleccionar Falsas)

<span class="badge-false">✗ Seleccionar FALSAS</span>

<div class="learnr-question-box" id="q17796513764789581"><div class="learnr-question-text">Resuelve la ecuación con exponentes fraccionarios: $y^{2/3} + 4y^{1/3} - 5 = 0$. Identifica únicamente cuáles de las siguientes afirmaciones son **falsas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513764789581" value="1" data-correct="true" > El conjunto de soluciones reales consta de las raíces $y = -5$ y $y = 1$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764789581" value="2" data-correct="true" > Realizando el cambio de variable $u = y^{1/3}$ obtenemos la ecuación cuadrática $u^2 + 4u + 5 = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764789581" value="3" data-correct="true" > La única solución real válida de la ecuación es $y = 125$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764789581" value="4" data-correct="false" > Las soluciones reales son las constantes enteras $y = -125$ y $y = 1$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764789581" value="5" data-correct="false" > Efectuando la sustitución obtenemos el trinomio cuadrático factorizable $(u+5)(u-1) = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764789581" value="6" data-correct="false" > Elevando al cubo las soluciones del cambio de variable $u = -5 \implies y = -125$ y $u = 1 \implies y = 1$ obtenemos el conjunto final.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513764789581')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has dominado el cambio de variable con potencias racionales.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Debes marcar únicamente las afirmaciones falsas. Recuerda elevar al cubo: $(-5)^3 = -125$ y $1^3 = 1$.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

### Pregunta 35 (Seleccionar Verdaderas)

<span class="badge-true">✓ Seleccionar VERDADERAS</span>

<div class="learnr-question-box" id="q17796513764911049"><div class="learnr-question-text">Resuelve la ecuación con exponente negativo racional: $x^{1/2} + 30x^{-1/2} - 11 = 0$. Identifica cuáles de las siguientes afirmaciones son **verdaderas**:</div><div class="learnr-answers"><div class="learnr-option"><label><input type="checkbox" name="q17796513764911049" value="1" data-correct="true" > $x = 25$ y $x = 36$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764911049" value="2" data-correct="true" > Multiplicando la ecuación por $x^{1/2}$ (con $x > 0$) obtenemos la ecuación lineal cuadrática equivalente en términos de $\sqrt{x}$: $x - 11\sqrt{x} + 30 = 0$.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764911049" value="3" data-correct="true" > Mediante la sustitución $u = \sqrt{x}$, factorizamos el trinomio como $(u-5)(u-6) = 0$ para despejar los valores simétricos cuadrados.</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764911049" value="4" data-correct="false" > $x = 5$ y $x = 6$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764911049" value="5" data-correct="false" > $x = -25$ y $x = -36$</label></div>
<div class="learnr-option"><label><input type="checkbox" name="q17796513764911049" value="6" data-correct="false" > La ecuación no posee soluciones reales debido al exponente racional del denominador.</label></div></div><button type="button" class="learnr-submit-btn" onclick="checkLearnrQuestion('q17796513764911049')">Enviar Respuesta</button><div class="learnr-feedback" style="display:none;"></div><div class="learnr-data-correct" style="display:none;">¡Excelente! Has finalizado toda la evaluación detectando todas las soluciones y planteamientos correctos con éxito.</div><div class="learnr-data-incorrect" style="display:none;">Incorrecto. Multiplica toda la ecuación por $x^{1/2}$ para obtener una forma cuadrática equivalente en términos de $\sqrt{x}$, y eleva al cuadrado.</div><div class="learnr-data-retry" style="display:none;">Intentar de nuevo</div><div class="learnr-data-allowretry" style="display:none;">true</div></div>

---

## Resultados de la Evaluación

Para ver el análisis de tu desempeño en esta prueba, haz clic en el siguiente botón. El sistema evaluará tus respuestas y te proporcionará recomendaciones personalizadas.

<button type="button" class="learnr-submit-btn" style="margin-bottom:1rem;" onclick="showScoreReport('sr17796513765102863', 35, '<strong>¡Espectacular!</strong> Tienes un dominio sobresaliente en la resolución de todo tipo de ecuaciones algebraicas. Comprendes con total claridad la detección de raíces extrañas, cambios de variable exponenciales y descomposiciones de grado superior. ¡Sigue así, has alcanzado la excelencia algebraica!', '<strong>¡Buen intento!</strong> Has aprobado la evaluación, pero aún hay conceptos de raíces extrañas (en ecuaciones irracionales) y multiplicidades que puedes pulir. Te sugerimos repasar la verificación de soluciones en ecuaciones con radicales y potencias racionales. ¡Con un poco más de repaso lograrás la excelencia!', '<strong>Se recomienda más práctica.</strong> Has tenido varias respuestas incorrectas o preguntas sin responder. Te sugerimos repasar a fondo la resolución de ecuaciones cuadráticas básicas por factorización y aspas, y luego avanzar paulatinamente hacia ecuaciones irracionales y bicuadráticas. ¡No te desanimes, con la práctica dominarás las ecuaciones!')">Calcular Mis Resultados</button><div id="sr17796513765102863"></div>
