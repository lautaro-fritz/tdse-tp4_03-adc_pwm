### Comentarios de la entrega  
Dentro de la función de actualización del valor del PWM, se realizó una modificación para que se calcule un nuevo valor en cada iteración, según el valor leído del ADC.  
  
Se modifica el valor del _duty cycle_ según la siguiente fórmula:
<tt>pwm_active = adc_value * PERIOD / MAX_ADC</tt>
