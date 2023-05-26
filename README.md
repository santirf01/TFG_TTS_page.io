
<head><meta name="viewport" content="width=device-width, initial-scale=1"><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    
    <title>One-Shot Voice Conversion with Weight Adaptive Instance Normalization</title>
    <link href="./WINVC-css/bootstrap.min.css" rel="stylesheet">
  <style type="text/css"></style></head>
  
<header id ="top" class="header">
<div class="jumbotron jumbotrocolor text-center">
 <div class="container">
  <hl>
   TFG Coqui_TTS: Explorando la efectividad de la síntesis de voz
   <br>
   mediante técnicas de aprendizaje profundo(VITS).
   <hl>
   <p class="lead">
     </p>
    <p class="lead">
     </p>
    </div>
  </div>
</header>
	 


	  

# TFG : 

## Original

 <audio controls>
  <source src="https://drive.google.com/uc?export=download&id=14g2DpUARA_zWYDTacr26yfn_-f8zVhrB" type="audio/wav">
  Tu navegador no soporta la reproducción de audio.
</audio>

## Resultados

***
<table>
  <tr>
    <th>Frase</th>
    <th>Step 1000</th>
    <th>Step 5000</th>
    <th>Step 10000</th>
    <th>Step 25000</th>
    <th>Step 50000</th>
    <th>Final</th>
  </tr>
  <tr>
    <td class="text-cell">
     "Me tomo mucho tiempos desarrollar una voz, ahora que la tengo no me callaré."
    </td>
    <td>
      <audio class="audio-button" controls>
        <source src="https://drive.google.com/uc?export=download&id=1qpmh4_Z-OT95QhOSk_VjweMlAvWf20lk" type="audio/wav">
        Tu navegador no soporta la reproducción del audio 0 en el step 1000.
      </audio>
    </td>
    <td>
      <audio class="audio-button" controls>
        <source src="https://drive.google.com/uc?export=download&id=1BHzXReSXkiLcCeYIuo361ZvlHUvF5Adq" type="audio/wav">
        Tu navegador no soporta la reproducción de audio 0 en el step 5000.
      </audio>
    </td>
   <td>
      <audio class="audio-button" controls>
        <source src="https://drive.google.com/uc?export=download&id=1rhWhAt9yThWcgsihMdSfCZ2jLfRrHW3W" type="audio/wav">
        Tu navegador no soporta la reproducción de audio 0 en el step 10000.
      </audio>
    </td>
    <td>
      <audio class="audio-button" controls>
        <source src="https://drive.google.com/uc?export=download&id=1bEpMfu-3Us3Rq6KcNrijDBMV9D1IJ5ia" type="audio/wav">
        Tu navegador no soporta la reproducción de audio 0 en el step 25000.
      </audio>
    </td>
    <td>
      <audio class="audio-button" controls>
        <source src="https://drive.google.com/uc?export=download&id=1IB3ul9HwJn949xCvUdiKo-X00AeB7XlU" type="audio/wav">
        Tu navegador no soporta la reproducción de audio 0 en el step 50000.
      </audio>
    </td>
   <td>
      <audio class="audio-button" controls>
        <source src="https://drive.google.com/uc?export=download&id=1E9QxN6-K3CcU9zcOFEn5EhxisNglPC46" type="audio/wav">
        Tu navegador no soporta la reproducción de audio 0 en el step final.
      </audio>
    </td>
   
  </tr>
 
 <tr>
    <td class="text-cell">
     "Sé una voz no un eco."
    </td>
    <td>
      <audio class="audio-button" controls>
        <source src="https://drive.google.com/uc?export=download&id=1IIU5LOqPRnvKQLacnGqIgVMV3VEpqfe9" type="audio/wav">
        Tu navegador no soporta la reproducción del audio 1 en el step 1000.
      </audio>
    </td>
    <td>
      <audio class="audio-button" controls>
        <source src="https://drive.google.com/uc?export=download&id=1nlt5zcEad8s--9ZupogV5OM-crW-cVjU" type="audio/wav">
        Tu navegador no soporta la reproducción de audio 1 en el step 5000.
      </audio>
    </td>
   <td>
      <audio class="audio-button" controls>
        <source src="https://drive.google.com/uc?export=download&id=1WDIBTlBnXtjksMfMI-D5Sb9vMuXjYZNh" type="audio/wav">
        Tu navegador no soporta la reproducción de audio 1 en el step 10000.
      </audio>
    </td>
    <td>
      <audio class="audio-button" controls>
        <source src="https://drive.google.com/uc?export=download&id=1nHglyMNlA0igRNCKx5oCaXRO7D0sWzEV" type="audio/wav">
        Tu navegador no soporta la reproducción de audio 1 en el step 25000.
      </audio>
    </td>
    <td class="text-cell">
      <audio class="audio-button" controls>
        <source src="https://drive.google.com/uc?export=download&id=1WNwJQk4nqICFV-RRCWc2F6jwpG4M_O4E" type="audio/wav">
        Tu navegador no soporta la reproducción de audio 1 en el step 50000.
      </audio>
    </td>
   <td>
      <audio class="audio-button" controls>
        <source src="https://drive.google.com/uc?export=download&id=175nkAuTpSyVw_O6kF-8rW_3vbEEer78I" type="audio/wav">
        Tu navegador no soporta la reproducción de audio 1 en el step final.
      </audio>
    </td>
   
  </tr>
  <tr>
    <td class="text-cell">
     "Lo siento mundo lamentablemente no puedo hacer eso."
    </td>
    <td>
      <audio class="audio-button" controls>
        <source src="https://drive.google.com/uc?export=download&id=10ZLvnLeBQNsb04AQcSp9_bHw8pXIHN7h" type="audio/wav">
        Tu navegador no soporta la reproducción del audio 2 en el step 1000.
      </audio>
    </td>
    <td>
      <audio class="audio-button" controls>
        <source src="https://drive.google.com/uc?export=download&id=1rLvg_XxOY58kHiqpdXZSL4NqXEP_q6d4" type="audio/wav">
        Tu navegador no soporta la reproducción de audio 2 en el step 5000.
      </audio>
    </td>
   <td>
      <audio class="audio-button" controls>
        <source src="https://drive.google.com/uc?export=download&id=109TxN0fM1JNEyhJvSg7O7G5lcXXjLYGg" type="audio/wav">
        Tu navegador no soporta la reproducción de audio 2 en el step 10000.
      </audio>
    </td>
    <td>
      <audio class="audio-button" controls>
        <source src="https://drive.google.com/uc?export=download&id=1er_Cerkm8lxvgPoyA6vf-gLLpIYCuUmR" type="audio/wav">
        Tu navegador no soporta la reproducción de audio 2 en el step 25000.
      </audio>
    </td>
    <td>
      <audio class="audio-button" controls>
        <source src="https://drive.google.com/uc?export=download&id=120kanoJ4bIh1vx7mO3At0VqsIB8aVzWu" type="audio/wav">
        Tu navegador no soporta la reproducción de audio 2 en el step 50000.
      </audio>
    </td>
   <td>
      <audio class="audio-button" controls>
        <source src="https://drive.google.com/uc?export=download&id=1agHDiQzKj0ejTBawWC-56iLYfIOGo3WE" type="audio/wav">
        Tu navegador no soporta la reproducción de audio 2 en el step final.
      </audio>
    </td>
   
  </tr>
  <tr>
    <td class="text-cell">
     "Espero que esta vez se realice de manera correcta la prueba de un solo orador"
    </td>
    <td>
      <audio class="audio-button" controls>
        <source src="https://drive.google.com/uc?export=download&id=1BILZH0EHW19H049twvCV2QItElrc6Br2" type="audio/wav">
        Tu navegador no soporta la reproducción del audio 3 en el step 1000.
      </audio>
    </td>
    <td>
      <audio class="audio-button" controls>
        <source src="https://drive.google.com/uc?export=download&id=1OrQyt144mNxMgFOQ_niTkJJWcU45T1QA" type="audio/wav">
        Tu navegador no soporta la reproducción de audio 3 en el step 5000.
      </audio>
    </td>
   <td>
      <audio class="audio-button" controls>
        <source src="https://drive.google.com/uc?export=download&id=1g2f8_xeRWcgh9uE9tlMJ-RW0bP6p1gNJ" type="audio/wav">
        Tu navegador no soporta la reproducción de audio 3 en el step 10000.
      </audio>
    </td>
    <td>
      <audio class="audio-button" controls>
        <source src="https://drive.google.com/uc?export=download&id=1E16QylEQpXtklwd95OF6geYvJwbJixIU" type="audio/wav">
        Tu navegador no soporta la reproducción de audio 3 en el step 25000.
      </audio>
    </td>
    <td>
      <audio class="audio-button" controls>
        <source src="https://drive.google.com/uc?export=download&id=1Y1TuJpN1q51xtjpKJLa8RS_2lN0dmX4A" type="audio/wav">
        Tu navegador no soporta la reproducción de audio 3 en el step 50000.
      </audio>
    </td>
   <td>
      <audio class="audio-button" controls>
        <source src="https://drive.google.com/uc?export=download&id=1XqaKRoM-vXYIqTzdS4fozEU_SLbOSBMq" type="audio/wav">
        Tu navegador no soporta la reproducción de audio 3 en el step final.
      </audio>
    </td>
  </tr>
  <tr>
    <td class="text-cell">
     "Esta prueba está realizada a 21 de Marzo de 2023"
    </td>
    <td>
      <audio class="audio-button" controls>
        <source src="https://drive.google.com/uc?export=download&id=1evBcDVv-FF_3y80Sn2VHugsLTQHUssB7" type="audio/wav">
        Tu navegador no soporta la reproducción del audio 4 en el step 1000.
      </audio>
    </td>
    <td>
      <audio class="audio-button" controls>
        <source src="https://drive.google.com/uc?export=download&id=1p-lC8I4Cd044RV7jzCa9cq7bDfwZhizJ" type="audio/wav">
        Tu navegador no soporta la reproducción de audio 4 en el step 5000.
      </audio>
    </td>
   <td>
      <audio class="audio-button" controls>
        <source src="https://drive.google.com/uc?export=download&id=1RnVm-mmuvmdVpAPMC0NftOev8UIw3alT" type="audio/wav">
        Tu navegador no soporta la reproducción de audio 4 en el step 10000.
      </audio>
    </td>
    <td>
      <audio class="audio-button" controls>
        <source src="https://drive.google.com/uc?export=download&id=18sX_OFpaY4JrvFFzUeCSxUynXIANETtK" type="audio/wav">
        Tu navegador no soporta la reproducción de audio 4 en el step 25000.
      </audio>
    </td>
    <td>
      <audio class="audio-button" controls>
        <source src="https://drive.google.com/uc?export=download&id=1kSzGL3gg48mg4B5Fdu5OzpZNUn-PLXDX" type="audio/wav">
        Tu navegador no soporta la reproducción de audio 4 en el step 50000.
      </audio>
    </td>
   <td>
      <audio class="audio-button" controls>
        <source src="https://drive.google.com/uc?export=download&id=1fhbi7Tc6vIUMK-5pI_60n3s10cPTbTSP" type="audio/wav">
        Tu navegador no soporta la reproducción de audio 4 en el step final.
      </audio>
    </td>  
  </tr>
</table>


