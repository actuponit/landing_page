<template>
  <div class="min-h-screen bg-[#f8f8f8]">
    <div class="h-[calc(100vh+6rem)] w-full">
      <TopBar />
      <SmallScreenBar />
      <div class="flex items-center font-extrabold justify-center gap-20 w-full min-h-screen bg-cover bg-no-repeat" style="background-image: url('/landing_picture.jpg');">
        <div class="w-full flex bg-yellow-300/20 backdrop-brightness-75 min-h-screen items-center">
          <div class="flex flex-col items-start justify-center gap-5 text-white w-full h-full px-10 2xl:px-28">
            <p class="text-xl md:text-2xl xl:text-3xl md:leading-[45px] max-w-4xl 2xl:max-w-2xl font-extrabold relative z-20 mt-10 md:mt-24 xl:mt-10">
              BRIDGES is a five-year programme (2019-2024) working to support and create jobs and micro, small and medium enterprises by unlocking the job-creation potential of industrial parks and other big enterprises in Ethiopia
            </p>
            <a href="http://partner.bridges-fc.com/" target="_blank" class="flex items-center justify-center bg-primary px-16 py-4 rounded-full text-xl font-semibold group mt-10">
              Login
              <Icon name="mdi:arrow-right" size="20" class="h-6 w-6 ml-5 group-hover:translate-x-2 duration-150"/>
            </a>
          </div>
          <div class="hidden lg:flex w-full px-20">
            <img src="/main-banner.41709a16.svg" alt="" class="right-20">
          </div>
        </div>
      </div>
    </div>
    <div class="w-full h-auto bg-primary-light pt-24" id="about">
      <div class="flex flex-col-reverse lg:flex-row text-xs md:text-lg items-center w-full h-full gap-20 px-10 md:px-24 py-8 text-gray-1">
        <div class="w-full">
          <span class="bg-primary text-white rounded-full px-2 py-1 text-xs">About</span>
          <h1 class="text-xl md:text-[40px] font-semibold py-5 md:py-10"> About the Project </h1>
          <p class="md:py-5 leading-7 md:leading-9"> 
            With Ethiopias labour force increasing by two million each year, BRIDGES aims to contribute toward efforts to create productive and decent jobs for the young population by direct job creation and by supporting employment opportunities in micro, small and medium enterprises (MSMEs). BRIDGES is currently managing 23 interventions organized under four focus areas or ‘Bridges,’ tackling constraints that hinder youth employment by partnering with over 70 private and public actors. BRIDGES capitalizes on and scales up First Consult’s previous achievements and learnings in the industrial sector, in addition to venturing into new sectors and approaches, to meet its target of supporting 600,000 jobs and 15,000 MSMEs.
          </p>
        </div>
        <div class="w-full h-3/5 mt-5 flex items-end">
          <div class="w-full h-64 flex flex-col lg:flex-row justify-center gap-10 lg:gap-0 items-center xl:border-l-2 xl:border-[#ECC791] px-10 md:px-20">
            <div class="w-full h-auto">
              <img src="/FC_logo.7f7d6352.svg" alt="fclogo" class="h-20 pr-0 lg:pr-10 grayscale hover:grayscale-0 mx-auto">
            </div>
            <div class="w-full h-auto">
              <img src="/mastercard_dark.9a9795c5.svg" alt="fclogo" class="h-32 pr-0 lg:pr-10 grayscale hover:grayscale-0 mx-auto">
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="flex flex-col w-full mt-10 px-5">
      <div class="bg-primary text-white rounded-full px-2 py-1 text-xs self-center my-10">4 Bridges</div>
      <h1 class="text-xl md:text-[40px] font-semibold py-2 text-gray-1 text-center">The Bridges Programme</h1>
      <p class="text-sm text-center mt-7 mx-auto max-w-[90ch] font-normal text-gray-1 leading-5">
        The BRIDGES Programme has four focus areas or “bridges,” each one connecting target participants to further opportunities.
      </p>
      <div class="grid sm:grid-cols-1 md:grid-cols-2 w-full gap-x-10 lg:gap-x-14 xl:gap-x-32 gap-y-10 px-7 sm:px-16 md:px-20 lg:px-32 xl:px-36 mt-10">
        <Service 
          title="Enterprise Development Bridge" 
          description="The Enterprise Development Bridge (EDB) works to identify unemployed young people and provide them with demand-based life skills, employability and entrepreneurial skills training and Business Development Services (BDS) to enable them to establish their own micro and small enterprises (MSEs). EDB provides profession-specific technical trainings, soft skills and linkage with financial services."
          image="/enterprise_development.png"
        />
        <Service 
          title="Employment Linkage Bridge" 
          description="The Enterprise Development Bridge (EDB) works to identify unemployed young people and provide them with demand-based life skills, employability and entrepreneurial skills training and Business Development Services (BDS) to enable them to establish their own micro and small enterprises (MSEs). EDB provides profession-specific technical trainings, soft skills and linkage with financial services."
          image="/employement_linkage.jpg"
        />
        <Service 
          title="Access to Finance" 
          description="Micro, small and medium enterprises’ (MSME) poor access to finance is often stated as one of the key challenges hindering firm growth. MSMEs are credit-constrained and have a huge financing gap that is not met by Ethiopian financial institutions. Further, the financial sector eco-system remains underdeveloped and requires technical and financial capacity building to increase access to finance to."
          image="/accessToFinance.png"
        />
        <Service 
          title="Enterprise Competitiveness Bridge" 
          description="Ethiopia has been successfully attracting foreign direct investments (FDI) currently standing at over USD4 billion per year. These large foreign investments have an import dependency rate of over 80%, offering market opportunities for local enterprises supply to this demand. However, local enterprises do not adequately work to seize this market opportunity as they face many challenges related to."
          image="/competitive.png"
        />
      </div>
    </div>
    <div class="pt-24 w-full">
      <div class="flex flex-col py-5 md:py-10 gap-5 justify-center items-center">
        <div class="bg-primary text-white rounded-full px-2 py-1 text-xs self-center my-10">Partners</div>
        <h1 class="text-xl md:text-[40px] font-semibold py-2"> Implementing Partners </h1>
        <p class="text-sm md:text-base px-5 md:px-0 font-normal text-center leading-8"> Below are our gevernments stakeholders and implementing partners. </p>
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 justify-items-center items-center gap-20 pt-20 w-full mb-20 px-10 md:px-40">
          <img src="https://www.bridges-fc.com/assets/mls.a98784b1.svg" class="h-10 lg:h-16 grayscale hover:grayscale-0" />
          <img src="https://www.bridges-fc.com/assets/moi_logo.5e495217.svg" class="h-10 lg:h-16 grayscale hover:grayscale-0" />
          <img src="https://www.bridges-fc.com/assets/IPDC%20COLOR.da4ae0b6.svg" class="h-10 lg:h-16 grayscale hover:grayscale-0" />
          <img src="https://www.bridges-fc.com/assets/EIC.8f6d138f.svg" class="h-10 lg:h-16 grayscale hover:grayscale-0" />
        </div>
      </div>
    </div>
    <div class="flex flex-col py-10 gap-5 justify-center items-center pt-24">
        <div class="bg-primary text-white rounded-full px-2 py-1 text-xs self-center my-10">Services</div>
        <h1 class="text-xl md:text-[40px] font-semibold py-2">Services Offered</h1>
        <p class="text-sm md:text-base px-5 md:px-0 font-normal text-center leading-8">This platform is built to provide a multi-tier reporting and data tracking for the bridges programme.</p>
    </div>
    <div class="flex justify-center items-center">
      <div class="grid py-14 pb-40 justify-items-end gap-20 grid-cols-1 lg:grid-cols-2 xl:grid-cols-3">
        <Offer 
          title="Partner"
          description="Partners of the Bridges programme shall use this login to report on their respective impact."
          icon="lucide:handshake"
        />
        <Offer 
          title="Management"
          description="The MEL Management team the Bridges programme to use this login to manage and approve reported impacts."
          icon="mynaui:users-group"
        />
        <Offer 
          title="Adminstrator"
          description="Administrations of the Bridges programme shall use this login to configure the report tool."
          icon="lucide:user-cog"
        />
      </div>
    </div>
    <Footer />
  </div>
</template>
