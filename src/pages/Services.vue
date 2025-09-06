<script setup>
import HeroWhiteSection from "../components/hero/HeroWhiteSection.vue";
import foodPlate from "../assets/food_plate.webp";
import handIcon from "../assets/hand_icon.png";
import lightIcon from "../assets/light_icon.png";
import zoomIcon from "../assets/zoom_icon.png";
import socialIcon from "../assets/social_icon.png";

import service1 from "../assets/img_services/service_1.webp";
import service2 from "../assets/img_services/service_2.webp";
import service3 from "../assets/img_services/service_3.webp";
import service4 from "../assets/img_services/service_4.webp";
import service5 from "../assets/img_services/service_5.webp";
import service6 from "../assets/img_services/service_6.webp";
import service7 from "../assets/img_services/service_7.webp";
import service8 from "../assets/img_services/service_8.webp";
</script>

<template>
  <!-- uno -->
  <section
    class="relative flex flex-col gap-5 lg:gap-20 items-center justify-center w-full bg-[var(--primary-color)] px-10 sm:px-20 lg:px-50 pt-15"
  >
    <div>
      <span
        class="text-white text-center text-3xl sm:text-3xl lg:text-6xl font-bold"
        >NUESTROS SERVICIOS</span
      >
    </div>

    <div
      class="w-full flex flex-wrap lg:flex-nowrap items-center justify-start gap-10 sm:gap-20 p-10 bg-[#e6e0d3]/30 rounded-3xl"
    >
      <img
        class="w-[300px] sm:w-full sm:max-w-[500px] h-auto rounded-2xl"
        :src="service1"
        alt=""
      />

      <div class="flex flex-col text-black gap-3">
        <span
          class="text-[var(--primary-color)] text-center text-xl md:text-4xl lg:text-4xl uppercase font-extrabold"
          >CONSULTORÍA JURIDICA</span
        >
        <span
          class="text-md md:text-2xl lg:text-1xl font-thin text-left lg:text-justify"
          >Especialistas en consultorías, para regímenes de:</span
        >
        <ul class="list-disc sm:ml-7" type="a">
          <li class="text-sm sm:text-3xl">Servicios públicos</li>
          <li class="text-sm sm:text-3xl">Tránsito, transporte y seguridad vial</li>
          <li class="text-sm sm:text-3xl">Sistema General de Regalías</li>
          <li class="text-sm sm:text-3xl">Catastro Multipropósito</li>
          <li class="text-sm sm:text-3xl">Urbanidad y ordenamiento territorial</li>
          <li class="text-sm sm:text-3xl">Salud y complementarios</li>
          <li class="text-sm sm:text-3xl">Amoblamiento urbano</li>
          <li class="text-sm sm:text-3xl">Planes departamentales de aguas</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- dos -->
  <section
    class="relative flex flex-col gap-5 lg:gap-20 items-center justify-center w-full bg-[white] p-10 sm:p-0 sm:pt-20 sm:px-20 lg:px-50"
  >
    <div class="absolute w-full h-auto top-0 rotate-180">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 197 2011 220"
        style="
          fill: var(--primary-color);
          width: 100%;
          height: 100%;
          display: block;
        "
        preserveAspectRatio="none"
      >
        <g
          transform="rotate(269.3 222.25 222.25) scale(3,-6) translate(-2,-434)"
        >
          <path
            d="M12.84,444.48c0.04,0,0.08,0,0.11,0c0.99,0,1.84-0.73,1.98-1.73L75.98,2.27c0.08-0.57-0.09-1.15-0.47-1.59 C75.13,0.25,74.58,0,74,0H2C1.46,0,0.94,0.22,0.57,0.6S-0.01,1.51,0,2.05l10.96,440.48C10.98,443.57,11.8,444.42,12.84,444.48z"
          />
        </g>
      </svg>
    </div>
    <div
      class="z-10 text-black w-full flex flex-wrap lg:flex-nowrap flex-row-reverse items-center justify-center gap-10 p-10 bg-[#e6e0d3]/30 rounded-3xl"
    >
      <img
        class="w-[300px] sm:w-full sm:max-w-[500px] h-auto rounded-2xl"
        :src="service2"
        alt=""
      />

      <div class="flex text-center items-center flex-col gap-3">
        <span
          class="text-[var(--primary-color)] text-center sm:text-center text-lg md:text-4xl lg:text-4xl uppercase font-bold max-w-[500px]"
          >PLANEACIÓN Y GESTIÓN TERRITORIAL</span
        >
        <span class="text-md sm:text-3xl font-normal text-left sm:text-center"
          >Estructuración y acompañamiento en planes desarrollo y ordenamiento
          de carácter municipal y departamental. Definición de los objetivos
          económicos, sociales, urbanísticos y ambientales de los gobiernos
          locales.</span
        >
      </div>
    </div>
  </section>

  <!-- tres -->
  <section
    class="relative flex flex-col gap-5 lg:gap-20 items-center justify-center w-full bg-white p-10 sm:p-0 sm:px-20 sm:pt-20 lg:px-50 sm:pb-25"
  >
    <div
      class="z-10 text-black w-full flex flex-wrap lg:flex-nowrap items-center justify-center gap-10 p-10 bg-[#e6e0d3]/30 rounded-3xl"
    >
      <img
        class="w-[300px] sm:w-full sm:max-w-[500px] h-auto rounded-2xl"
        :src="service3"
        alt=""
      />

      <div class="flex flex-col gap-3 text-center items-center">
        <span
          class="text-[var(--primary-color)] text-center text-lg md:text-4xl lg:text-4xl uppercase font-bold"
          >Contratación Pública</span
        >
        <span class="text-md sm:text-3xl font-normal text-center"
          >Estructuración del Plan Anual de Adquisición. Acompañamiento en la
          formulación, trámite y adjudicación de procesos de selección:
          Licitación Pública (y de Obra pública), Mínima Cuantía, Selección
          Abreviada, Contratación directa y Concursos de Mérito. Asesoría en las
          etapas precontractual, contractual y poscontractual.</span
        >
      </div>
    </div>
    <div class="absolute w-full h-auto bottom-0">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 197 2011 220"
        style="
          fill: var(--primary-color);
          width: 100%;
          height: 100%;
          display: block;
        "
        preserveAspectRatio="none"
      >
        <g
          transform="scale(-1,1) translate(-2011,0) rotate(269.3 222.25 222.25) scale(3,-6) translate(-2,-434)"
        >
          <path
            d="M12.84,444.48c0.04,0,0.08,0,0.11,0c0.99,0,1.84-0.73,1.98-1.73L75.98,2.27c0.08-0.57-0.09-1.15-0.47-1.59 C75.13,0.25,74.58,0,74,0H2C1.46,0,0.94,0.22,0.57,0.6S-0.01,1.51,0,2.05l10.96,440.48C10.98,443.57,11.8,444.42,12.84,444.48z"
          />
        </g>
      </svg>
    </div>
  </section>

  <!-- cuatro -->
  <section
    class="relative flex flex-col gap-5 lg:gap-20 items-center justify-center w-full bg-[var(--primary-color)] pb-20 pt-10 p-10 sm:p-0 sm:px-20 lg:px-50"
  >
    <div
      class="z-10 text-black w-full flex flex-wrap lg:flex-nowrap md:flex-row-reverse lg:flex-row-reverse items-center justify-center gap-10 p-10 bg-[#e6e0d3]/30 rounded-3xl"
    >
      <img
        class="w-[300px] sm:w-full sm:max-w-[500px] h-auto rounded-2xl"
        :src="service4"
        alt=""
      />

      <div class="flex flex-col gap-3 text-center items-center">
        <span
          class="text-[var(--primary-color)] text-center text-lg md:text-4xl lg:text-4xl uppercase font-bold"
          >Estructuración de proyectos públicos - privados</span
        >
        <span class="text-md sm:text-3xl font-normal text-center"
          >Elaboración de estudios de viabilidad, técnicos, económicos,
          jurídicos, corporativos y financieros para el diseño de proyectos
          público-privados orientados a la prestación de servicios
          públicos.</span
        >
      </div>
    </div>
  </section>

  <!-- cinco -->
  <section
    class="relative flex flex-col gap-5 lg:gap-20 items-center justify-center w-full bg-[var(--primary-color)] p-10 sm:p-0 sm:pt-20 sm:px-20 lg:px-50"
  >
    <div
      class="z-10 text-black w-full flex flex-wrap sm:flex-nowrap items-center justify-between gap-10 p-10 bg-[#e6e0d3]/30 rounded-3xl"
    >
      <img
        class="w-[300px] sm:w-full sm:max-w-[500px] h-auto rounded-2xl"
        :src="service5"
        alt=""
      />

      <div class="flex flex-col gap-3 text-center items-center">
        <span
          class="text-[var(--primary-color)] text-center text-lg md:text-4xl lg:text-4xl uppercase font-bold"
          >Creación y acompañamiento a entidades descentralizadas</span
        >
        <ul class="w-full list-disc sm:ml-25 text-left" type="a">
          <li class="text-sm sm:text-3xl">Sociedades de Economía Mixta</li>
          <li class="text-sm sm:text-3xl">EICE</li>
          <li class="text-sm sm:text-3xl">ESP</li>
          <li class="text-sm sm:text-3xl">Empresas Sociales del Estado</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- seis -->
  <section
    class="relative flex flex-col gap-5 lg:gap-20 items-center justify-center w-full bg-white p-10 sm:p-0 sm:pt-20 sm:px-20 lg:px-50"
  >
    <div
      class="z-10 text-black w-full flex flex-wrap lg:flex-nowrap md:flex-row-reverse lg:flex-row-reverse items-center justify-center gap-10 p-10 bg-[#e6e0d3]/30 rounded-3xl"
    >
      <img
        class="w-[300px] sm:w-full sm:max-w-[500px] h-auto rounded-2xl"
        :src="service6"
        alt=""
      />

      <div class="flex flex-col gap-3 text-center items-center">
        <span
          class="text-[var(--primary-color)] text-center text-lg md:text-4xl lg:text-4xl uppercase font-bold max-w-[600px]"
          >Interventoría y supervisión de contratos estatales</span
        >
        <span class="text-md sm:text-3xl font-normal text-center"
          >Gestión y seguimiento al cumplimiento de las obligaciones legales y
          convencionales de contratos públicos, privados y mixtos.
          Acompañamiento en los procesos contractuales sancionatorios. Apoyo en
          reuniones y comités de las entidades estatales.</span
        >
      </div>
    </div>
    <div class="absolute w-full h-auto top-0 rotate-180">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 197 2011 220"
        style="
          fill: var(--primary-color);
          width: 100%;
          height: 100%;
          display: block;
        "
        preserveAspectRatio="none"
      >
        <g
          transform="rotate(269.3 222.25 222.25) scale(3,-6) translate(-2,-434)"
        >
          <path
            d="M12.84,444.48c0.04,0,0.08,0,0.11,0c0.99,0,1.84-0.73,1.98-1.73L75.98,2.27c0.08-0.57-0.09-1.15-0.47-1.59 C75.13,0.25,74.58,0,74,0H2C1.46,0,0.94,0.22,0.57,0.6S-0.01,1.51,0,2.05l10.96,440.48C10.98,443.57,11.8,444.42,12.84,444.48z"
          />
        </g>
      </svg>
    </div>
  </section>

  <!-- siete -->
  <section
    class="relative flex flex-col gap-5 lg:gap-20 items-center justify-center w-full bg-white p-10 sm:p-0 sm:pt-20 sm:px-20 sm:pb-25 lg:px-50"
  >
    <div
      class="z-10 text-black w-full flex flex-wrap lg:flex-nowrap items-center justify-center gap-10 p-10 bg-[#e6e0d3]/30 rounded-3xl"
    >
      <img
        class="w-[300px] sm:w-full sm:max-w-[500px] h-auto rounded-2xl"
        :src="service7"
        alt=""
      />

      <div class="flex flex-col gap-3 text-center items-center">
        <span
          class="text-[var(--primary-color)] text-center text-lg md:text-4xl lg:text-4xl uppercase font-bold"
          >Finanzas públicas</span
        >
        <span class="text-md sm:text-3xl font-normal text-center"
          >Análisis financieros para el aprovechamiento y buen uso de los
          recursos y presupuesto de las entidades estatales. Estructuración y
          propuesta de herramientas y mecanismos orientados al impulso de las
          economías locales. Apoyo en los proyectos de estatutos tributarios y
          adopción de impuestos, tasas y contribuciones.</span
        >
      </div>
    </div>
    <div class="absolute w-full h-auto bottom-0">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 197 2011 220"
        style="
          fill: var(--primary-color);
          width: 100%;
          height: 100%;
          display: block;
        "
        preserveAspectRatio="none"
      >
        <g
          transform="scale(-1,1) translate(-2011,0) rotate(269.3 222.25 222.25) scale(3,-6) translate(-2,-434)"
        >
          <path
            d="M12.84,444.48c0.04,0,0.08,0,0.11,0c0.99,0,1.84-0.73,1.98-1.73L75.98,2.27c0.08-0.57-0.09-1.15-0.47-1.59 C75.13,0.25,74.58,0,74,0H2C1.46,0,0.94,0.22,0.57,0.6S-0.01,1.51,0,2.05l10.96,440.48C10.98,443.57,11.8,444.42,12.84,444.48z"
          />
        </g>
      </svg>
    </div>
  </section>

  <!-- ocho -->
  <section
    class="relative flex flex-col gap-5 lg:gap-20 items-center justify-center w-full bg-[var(--primary-color)] pb-20 pt-10 p-10 sm:p-0 sm:px-20 lg:px-50"
  >
    <div
      class="z-10 text-black w-full flex flex-wrap lg:flex-nowrap md:flex-row-reverse lg:flex-row-reverse items-center justify-center gap-10 p-10 bg-[#e6e0d3]/30 rounded-3xl"
    >
      <img
        class="w-[300px] sm:w-full sm:max-w-[500px] h-auto rounded-2xl"
        :src="service1"
        alt=""
      />

      <div class="flex flex-col gap-3 text-center items-center sm:mr-20">
        <span
          class="text-[var(--primary-color)] text-center text-lg md:text-4xl lg:text-4xl uppercase font-bold"
          >Defensa judicial y procedimientos sancionatorios</span
        >
        <div class="w-full">
          <ul class="list-disc ml-10 sm:ml-33 text-left" type="a">
            <li class="text-sm sm:text-3xl">Contractuales</li>
            <li class="text-sm sm:text-3xl">Judiciales</li>
            <li class="text-sm sm:text-3xl">Disciplinarios</li>
            <li class="text-sm sm:text-3xl">Fiscales</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <!-- nueve -->
  <section
    class="relative flex flex-col gap-5 lg:gap-20 items-center justify-center w-full bg-[var(--primary-color)] p-10 sm:p-0 sm:pt-20 sm:px-20 lg:px-50"
  >
    <div
      class="z-10 text-black w-full flex flex-wrap lg:flex-nowrap items-center justify-center gap-10 p-10 bg-[#e6e0d3]/30 rounded-3xl"
    >
      <img
        class="w-[300px] sm:w-full sm:max-w-[500px] h-auto rounded-2xl"
        :src="service5"
        alt=""
      />

      <div class="flex flex-col gap-3 text-center items-center">
        <span
          class="text-[var(--primary-color)] text-center text-lg md:text-4xl lg:text-4xl uppercase font-bold"
          >Estructuración de proyectos ambientales y energías limpias</span
        >
        <span class="text-md sm:text-3xl font-normal text-center"
          >Intervención en la formulación y adopción de programas ambientales,
          de recursos y energías renovables, para la implementación de las
          políticas públicas acogidas por nuestro ordenamiento. Apoyo en la
          elaboración de estrategias y mecanismos de protección ambiental.</span
        >
      </div>
    </div>
  </section>

  <!-- diez -->
  <section
    class="relative flex flex-col gap-5 lg:gap-20 items-center justify-center w-full bg-white p-10 sm:p-0 sm:pt-25 sm:px-20 lg:px-50"
  >
    <div
      class="z-10 text-black w-full flex flex-wrap lg:flex-nowrap md:flex-row-reverse lg:flex-row-reverse items-center justify-center gap-10 p-10 bg-[#e6e0d3]/30 rounded-3xl"
    >
      <img
        class="w-[300px] sm:w-full sm:max-w-[500px] h-auto rounded-2xl"
        :src="service6"
        alt=""
      />

      <div class="flex flex-col gap-3 text-center items-center">
        <span
          class="text-[var(--primary-color)] text-center text-lg md:text-4xl lg:text-4xl uppercase font-bold"
          >CATERING PARA EVENTOS</span
        >
        <span class="text-md sm:text-3xl font-normal text-center"
          >Ofrecemos un servicio de catering de alta calidad para eventos
          corporativos, sociales y empresariales, cuidando cada detalle desde la
          selección de ingredientes hasta la presentación final. Diseñamos menús
          adaptados a cada ocasión, garantizando sabor, frescura y
          puntualidad.</span
        >
      </div>
    </div>
    <div class="absolute w-full h-auto top-0 rotate-180">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 197 2011 220"
        style="
          fill: var(--primary-color);
          width: 100%;
          height: 100%;
          display: block;
        "
        preserveAspectRatio="none"
      >
        <g
          transform="rotate(269.3 222.25 222.25) scale(3,-6) translate(-2,-434)"
        >
          <path
            d="M12.84,444.48c0.04,0,0.08,0,0.11,0c0.99,0,1.84-0.73,1.98-1.73L75.98,2.27c0.08-0.57-0.09-1.15-0.47-1.59 C75.13,0.25,74.58,0,74,0H2C1.46,0,0.94,0.22,0.57,0.6S-0.01,1.51,0,2.05l10.96,440.48C10.98,443.57,11.8,444.42,12.84,444.48z"
          />
        </g>
      </svg>
    </div>
  </section>

  <!-- once -->
  <section
    class="relative flex flex-col gap-5 lg:gap-20 items-center justify-center w-full bg-white p-10 sm:p-0 sm:pt-20 sm:px-20 lg:px-50"
  >
    <div
      class="z-10 text-black w-full flex flex-wrap lg:flex-nowrap items-center justify-center gap-10 p-10 bg-[#e6e0d3]/30 rounded-3xl"
    >
      <img
        class="w-[300px] sm:w-full sm:max-w-[500px] h-auto rounded-2xl"
        :src="service7"
        alt=""
      />

      <div class="flex flex-col gap-3 text-center items-center">
        <span
          class="text-[var(--primary-color)] text-center text-lg md:text-4xl lg:text-4xl uppercase font-bold"
          >LOGISTICA DE EVENTOS</span
        >
        <span class="text-md sm:text-3xl font-normal text-center"
          >Planificamos y coordinamos todos los aspectos logísticos de sus
          eventos, asegurando que cada detalle se ejecute a la perfección.
          Gestionamos montaje, decoración, cronogramas, proveedores y personal
          para que su evento sea exitoso y sin contratiempos.</span
        >
      </div>
    </div>
  </section>

  <!-- doce -->
  <HeroWhiteSection>
    <div class="sm:px-20 lg:px-50 lg:pt-20 flex flex-col gap-10 items-center px-10">
      <div
        class="w-full flex flex-wrap lg:flex-nowrap md:flex-row-reverse lg:flex-row-reverse items-center justify-center gap-10 p-10 bg-[#e6e0d3]/30 rounded-3xl text-black"
      >
        <img
          class="w-[300px] sm:w-full sm:max-w-[500px] h-auto rounded-2xl"
          :src="service8"
          alt=""
        />

        <div class="flex flex-col gap-3 text-center items-center">
          <span
            class="text-[var(--primary-color)] text-md text-center md:text-4xl lg:text-4xl uppercase font-bold"
            >TRANSPORTE CORPORATIVO</span
          >
          <span class="text-md sm:text-3xl font-normal text-center"
            >Brindamos soluciones de transporte seguro, cómodo y puntual para
            traslados corporativos, eventos y actividades especiales. Contamos
            con vehículos adecuados, conductores capacitados y planes de
            movilidad adaptados a sus necesidades.</span
          >
        </div>
      </div>

      <div>
        <button
          type="button"
          @click="scrollToContact"
          class="text-white bg-[var(--primary-color)] w-fit font-semibold px-7 py-2 text-lg sm:text-3xl rounded-full hover:text-[#3d7dbd] hover:bg-white"
        >
          Solicitar servicio
        </button>
      </div>
    </div>
  </HeroWhiteSection>
</template>
