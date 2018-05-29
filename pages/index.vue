<template>
  <section>

    <section>
      <div class="row">
        <div class="col-md-7">
          <p>Planning Green Futures Ltd is a multi-disciplinary consultancy offering a wide range of skills and services in environmental assessment, natural resources planning , and social and community welfare enhancement. The company was established in August 2012 and is affiliated to pgf Consulting based in Bristol in the United Kingdom. It is managed by Ranita Adama Sandi-Koroma, a Postgraduate of the University of Sierra Leone (Fourah Bay) with wide experience in social and environmental impact assessment, fisheries, land use and community and gender issues.</p>
          <p>Planning Green Futures Ltd’s International Director is Peter Jon Nelson, who is also the Principal of pgf Consulting and is an international planner and environmental scientist. Peter has worked extensively in West Africa since 2002.</p>
          <p>Planning Green Futures Ltd is a new style of planning practice, since its main objective is to build environmental capacity in Sierra Leone. Its primary role is to assist Government Ministries and Agencies, District Councils, Civil Society and International Partners to introduce state of the art policies, plans and programmes for improving livelihoods and reducing poverty . All projects are designed to ensure environmental enhancement, sustainable use of natural resources and self-help within local communities.</p>
          <p>While the primary focus lies in providing services to the public sector, pgf Ltd also supports investors and development companies that have adopted a positive commitment towards sustainable development.</p>
          <p>Pgf Ltd guards its objectivity and independence carefully. It will only take on assignments that are in the National Interest of countries in which it works.</p>
        </div>
        <div class="col-md-5">
          <p>Current and Recent Projects:</p>
          <ul class="spaced">
            <li><span>Designing a Climate Change adaptation programme for rural water and sanitation improvements in five districts for the African Development Bank and Ministries of Water Resources, Health and Sanitation;</span></li>
            <li><span>Undertaking the design and environmental assessment of a new waste recycling and composting site for Bo City Council (promoted by Welthungerhilfe, the Council and UK Aid);</span></li>
            <li><span>Developing the National Ecotourism Policy for the National Tourist Board and Ministry of Tourism and Cultural Affairs;</span></li>
            <li><span>Assessing the development of an new fibreoptics internet networkfor Airtel;</span></li>
            <li><span>Conducting a Gender Assessment on Sierra Leone National Policies, Acts and Laws for World Vision;</span></li>
            <li><span>Collaborating with "IslandAid", a volunteer organisation of national communities, to develop livelihood programmes for islands affected by poverty, lack of resources, isolation and sea level rise.</span></li>
          </ul>
        </div>
      </div>
    </section>

    <section class="services">
      <h2>Services</h2>
      <div class="row">
        <div class="col-md-6">
          <ul class="spaced">
            <li><span>Preparation of field surveys</span></li>
            <li><span>Production of plans and reports</span></li>
            <li><span>Facilitation of workshops and com- munity meetings</span></li>
          </ul>
        </div>
        <div class="col-md-6">
          <ul class="spaced">
            <li><span>Representing clients’ views at stakehold- er meetings</span></li>
            <li><span>Project design and management Feasibility Studies</span></li>
            <li><span>Research studies, SEAs, EIAs & ESIAs</span></li>
          </ul>
        </div>
      </div>
    </section>

    <section class="projects">
      <h2>Projects</h2>
      <div class="cards">
        <a href="/rural-water-supply">Building Climate Change Resilience and Adaptation into the Rural Water Supply and Sanitation Programme in Sierra Leone</a>
        <a href="/national-ecotourism-policy">Preparation of a National Ecotourism Policy and Action Plan</a>
        <a href="/bo-city-council-waste-recycling">Environmental and Social Impact Assessment of the Mile 5 Waste Recycling and Disposal Site for Bo City Council</a>
        <a href="/fibre-optic-broadband-network">Environmental and Social Impact Assessment of the Fibre-optic Broadband Network for Freetown and the Western Peninsula</a>
        <a href="/sea-for-oil">Rich Future or Resource Curse? SEA for Oil</a>
        <a href="/needs-assessment-for-epa">Needs Assessment for the Environment Protection Agency-SL</a>
        <a href="/fisheries-sesa-in-ghana">Fisheries SESA in Ghana</a>
        <a href="/shire-river-basin-in-malawi">The Shire River Basin, Malawi</a>
        <a href="/land-use-planning-tana-delta-in-kenya">Land Use Planning and SEA for the Tana Delta in Kenya</a>
        <a href="/regulations-for-mining-in-sierra-leone">Environmental and Social Regulations for Mining in Sierra Leone</a>
      </div>
    </section>

    <section>
      <h2>Team</h2>

      <ul class="people">
        <li>
          <h4>Peter Nelson</h4>
          <img src="~/assets/images/peter.png" alt="Peter Nelson">
          <p>In addition to leading the Sierra Leone Oil and Gas SEA, Peter Nelson is currently advising the Government of Kenya and Nature Kenya on the preparation of a Land Use Plan for the Tana Delta and a Strategic Assessment of water use and pastoral farming in the Tana River Basin.</p>
          <p>He is also a member of the Expert Review Panel advising on development of the water resources of the Abbey / Blue Nile in Ethiopia.</p>
        </li>
        <li>
          <h4>Ranita Koroma</h4>
          <img src="~/assets/images/ranita.png" alt="Ranita Koroma">
          <p>Ranita Koroma is currently undertaking the socioeconomic assessment on behalf of a consortium for a Palm Oil Development in Pujehun District, Sierra Leone.</p>
          <p>Ranita is also assisting the SEA of potential Oil and Gas development in Sierra Leone, including field research on the impacts of the Jubilee Field in Ghana.</p>
        </li>
      </ul>
    </section>

    <section>
      <h2>Contact</h2>
      <p>Tel: +232 (0)78 585 5727</p>
      <p>Email: <a href="mailto:planninggreenfutures@gmail.com">planninggreenfutures@gmail.com</a></p>
    </section>
  </section>
</template>

<script>

export default {
  head: {
    title: "Planning Green Futures - Sierra Leone"
  }
}

</script>

<style lang="scss">
  @import '@/assets/stylesheets/main.scss';

  ul.people {
    margin: 0;
    padding: 0;
    li {
      list-style: none;
      margin: 0;
      padding: 1rem;
    }
    img {
      border-radius: 50%;
      float: left;
      height: 100px;
      margin: 0 1rem 1rem 0;
      width: 100px;
    }
  }
</style>
