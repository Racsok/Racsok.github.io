<section id="sobre-mi" class="mb-8">
    <h2 class="text-2xl font-semibold mb-4">Sobre Mí</h2>
        <p>
            Soy estudiante de Ingeniería de Sistemas en la Universidad Distrital Francisco José de Caldas, 
            con una profundización en análisis de datos. A lo largo de mi formación, he adquirido 
            conocimientos sólidos en lenguajes de programación como Python, Java y JavaScript.
        </p>
       <span class="ocultar hidden">
            <p>
                Además, tengo experiencia en la creación y manejo de scripts de automatización utilizando Bash
                y Python, lo que me permite optimizar procesos y aportar soluciones eficientes en diversos
                entornos.
            </p>
            <p>    
                Cuento con habilidades blandas esenciales como el trabajo en equipo y el uso de metodologías 
                de trabajo estructuradas. También manejo herramientas como Excel, lo que complementa mis 
                competencias técnicas para abordar proyectos de manera integral.
            </p>
            <p>    
                Estoy motivado por aprender y seguir creciendo profesionalmente en el campo de la tecnología
            </p> 
       </span>  
       <input type="checkbox" name="btn-leer" id="btn-leer" class="appearance-none hidden">
       <label for="btn-leer" class="p-4 cursor-pointer block w-max bg-slate-50 rounded-2xl"></label>
</section>

<style>
    label{
        border-bottom: 1px solid #3e3e3e;
    }
    label::before{
        content: "Leer más";
    }

    #btn-leer:checked ~ label::before {
        content: "Ocultar";
    }

    .ocultar:has(~ #btn-leer:checked){
        display: block;
    }
</style>