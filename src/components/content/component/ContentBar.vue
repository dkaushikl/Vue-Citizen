z`<template>
  <div class="row pr-192">
    <div class="col-md-12 pb-30">
      <p class="profile-title mb-0">
        Tania Sethi
      </p>
    </div>
    <div class="col-md-12 mb-4">
      <div class="profile-box">
        <div class="title-div d-flex align-items-center">
          <p class="mb-0">
            <img
              src="./../../../assets/demographic-icon@2x.png"
              alt="demographic_icon"
              class="demographic_icon"
            />
            <span class="pl-2">
              Demographics
            </span>
          </p>
        </div>
        <div class="content py-3 pl-30">
          <div class="row">
            <div class="col-md-5">
              <div
                class="d-flex align-items-center justify-content-between pb-6"
              >
                <p class="mb-0 profile-lable">Gender</p>
                <p class="mb-0 profile-value">Female</p>
              </div>
              <div
                class="d-flex align-items-center justify-content-between pb-6"
              >
                <p class="mb-0 profile-lable">Born</p>
                <p class="mb-0 profile-value">Feb 19, 1969</p>
              </div>
              <div
                class="d-flex align-items-center justify-content-between pb-6"
              >
                <p class="mb-0 profile-lable">Age</p>
                <p class="mb-0 profile-value">51</p>
              </div>
              <div
                class="d-flex align-items-center justify-content-between pb-6"
              >
                <p class="mb-0 profile-lable">City of residence</p>
                <p class="mb-0 profile-value">Redwood City, CA</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="col-md-12">
      <div class="profile-box mb-60">
        <div class="title-div d-flex align-items-center">
          <p class="mb-0">
            <img
              src="./../../../assets/demographic@2x.png"
              alt="demographic_icon"
              class="demographic_icon"
            />
            <span class="pl-2">
              Major Medical Journeys
            </span>
          </p>
        </div>
        <div class="content">
          <div class="row mx-0">
            <div class="col-md-12 px-0">
              <div role="tablist">
                <b-card no-body class="tablist-card">
                  <b-card-header
                    header-tag="header"
                    class="p-1 border-0"
                    role="tab"
                  >
                    <b-button
                      block
                      v-b-toggle.accordion-1
                      class="expan-button text-align-left"
                    >
                      <img
                        src="./../../../assets/expand@2x.png"
                        alt="expand"
                        class="expand"
                      />
                      Other (xxxx-xxxx)</b-button
                    >
                  </b-card-header>
                  <b-collapse
                    id="accordion-1"
                    visible
                    accordion="my-accordion"
                    role="tabpanel"
                  >
                    <b-card-body class="p-30">
                      <b-card-text
                        >I start opened because <code>visible</code> is
                        <code>true</code></b-card-text
                      >
                      <b-card-text>{{ text }}</b-card-text>
                    </b-card-body>
                  </b-collapse>
                </b-card>

                <b-card no-body class="tablist-card">
                  <b-card-header
                    header-tag="header"
                    class="p-1 border-0"
                    role="tab"
                  >
                    <b-button
                      block
                      v-b-toggle.accordion-2
                      class="expan-button text-align-left"
                    >
                      <img
                        src="./../../../assets/expand@2x.png"
                        alt="expand"
                        class="expand"
                      />
                      Other (xxxx-xxxx)</b-button
                    >
                  </b-card-header>
                  <b-collapse
                    id="accordion-2"
                    accordion="my-accordion"
                    role="tabpanel"
                  >
                    <b-card-body class="p-30">
                      <b-card-text>{{ text }}</b-card-text>
                    </b-card-body>
                  </b-collapse>
                </b-card>

                <b-card no-body class="tablist-card">
                  <b-card-header
                    header-tag="header"
                    class="p-1 border-0"
                    role="tab"
                  >
                    <b-button
                      block
                      v-b-toggle.accordion-3
                      class="expan-button text-align-left"
                    >
                      <img
                        src="./../../../assets/expand@2x.png"
                        alt="expand"
                        class="expand"
                      />
                      Breast Cancer (2015-2017)</b-button
                    >
                  </b-card-header>
                  <b-collapse
                    id="accordion-3"
                    accordion="my-accordion"
                    role="tabpanel"
                  >
                    <b-card-body class=" px-0 pt-30 pb-30">
                      <div>
                        <p class="sub-lable mb-0 pr-30 pl-30">
                          {{
                            `Initial Diagnosis & Tumor Characteristics (April – May 2015)`
                          }}
                        </p>
                        <p class="sub-content mb-0 pl-30 pr-30">
                          In late April 2015, Tania was diagnosed with
                          <span class="underline">
                            ER 50%, PR 50%, HER2 negative invasive ductal
                            carcinoma (IDC)</span
                          >
                          of the <span class="underline"> left breast</span>,
                          confirmed via <span class="underline">biopsy </span>on
                          April 29, 2015. A PET scan on May 11 also indicated
                          metastases to the lymph nodes, liver, spine, (as well
                          as suspicious lung nodules), confirming a diagnosis of
                          Stage IV metastatic breast cancer.
                        </p>
                        <p class="sub-lable mb-0 pr-30 pl-30">
                          Zolaldex-Based Treatment and Disease Control Until
                          First Progression (May 2015 – March 2017)
                        </p>

                        <p class="sub-content mb-0 pl-30 pr-30">
                          TREATMENTS: Tania's first set of treatments were
                          hormonal therapy-based. She was given
                          <span class="text-blue-color">Zoladex</span> from May
                          2015 until Mar 2017. While taking the Zoladex, she
                          also received
                          <span class="text-blue-color">Ibrance</span> and
                          <span class="text-blue-color">Letrozole</span> from
                          May 2015 to Mar 2016. From Aug 2016 to Dec 2016 she
                          also took Xeloda and
                          <span class="text-blue-color"
                            >high dose CBD / THC.</span
                          >
                        </p>
                        <p class="sub-content mb-0 mt-3 pl-30 pr-30">
                          OUTCOMES: She experienced
                          <span
                            class="text-blue-color popup-model-span"
                            v-b-modal.modal-metabolic
                            >Hand Foot Syndrome</span
                          >
                          as a side effect of therapy. After almost two years of
                          disease control, in Feb and Mar 2017
                          <span class="underline"
                            >her disease was found to be progressing</span
                          >
                          and she stopped the Zoladex-based treatment. On May
                          12, 2017, she received her comprehensive lab results.
                        </p>
                        <p class="sub-lable mb-0 pr-30 pl-30">
                          Subsequent Chemotherapy-Based Treatments and Complete
                          Response (March 2017 – June 2017)
                        </p>
                        <p class="sub-content mb-0 pl-30 pr-30">
                          TREATMENTS: After discontinuing Zoladex due to
                          progression, she was started on chemotherapy-based
                          regimens. First, she started
                          <span class="text-blue-color">Doxil</span> on Mar 5,
                          2017, but after her
                          <span class="underline">tumor markers rose</span> this
                          was discontinued Mar 23, 2017. She took IV
                          <span class="text-blue-color">Mistletoe</span> on Mar
                          27, 2017. On Mar 30, 2017 she began
                          <span class="text-blue-color">Taxol</span>, and on May
                          10, 2017 she began intraperitoneal
                          <span class="text-blue-color">Mitoxantrone</span>.
                          From May 16, 2017 to Jun 13, 2017 she was given 3
                          cycles of
                          <span class="text-blue-color">5-FU, Abraxane,</span>
                          <span class="text-blue-color">Faslodex</span>, and
                          <span
                            class="text-blue-color popup-model-span"
                            v-b-modal.modal-labs
                            >Denosumab</span
                          >.
                        </p>
                        <p class="sub-content mb-0 mt-3 pb-0 pl-30 pr-30">
                          OUTCOMES: In late March 2017, Tania was treated by
                          paracentesis and a catheter for
                          <span
                            class="underline"
                            v-b-popover.hover.top="
                              'I am popover directive content!'
                            "
                            title="Popover Title"
                            >ascites due to the spreading cancer.</span
                          >
                          On Jun 30, 2017, a
                          <span class="underline">PET/CT scan</span> showed
                          <span class="underline"
                            >complete resolution of lesions in her left breast,
                            liver, and spine.</span
                          >
                        </p>
                      </div>
                    </b-card-body>
                  </b-collapse>
                </b-card>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="labs-model-content">
      <b-modal id="modal-labs" size="lg" title="LABS" class="labs-model">
        <div class="content pl-60">
          <div class="d-flex align-items-center justify-content-between">
            <p class="mb-0 font-weight-500">
              Cell count and Differential panel - Peritoneal fluid
            </p>
            <p class="mb-0">Jan 09, 2013</p>
          </div>
          <div class="d-flex align-items-center justify-content-between pb-1">
            <p class="mb-0 font-size-13 font-style-italic color-muted">
              Lab panel
            </p>
            <p class="mb-0 font-size-13 font-style-italic color-muted">
              Dr. Jason Prystowsky at Santa Barbara Cottage Hospital
            </p>
          </div>
          <div class="row">
            <div class="col-md-12">
              <table class="table-content">
                <tr>
                  <td>
                    <p class="table-lable mb-0">
                      Mononuclear cells, in Body fluid by Manual count
                    </p>
                  </td>
                  <td>
                    <p class="table-value mb-0">
                      51 /cu mm
                    </p>
                  </td>
                </tr>
                <tr>
                  <td>
                    <p class="table-lable mb-0">
                      Polymorphonuclear cells, in Body fluid
                    </p>
                  </td>
                  <td>
                    <p class="table-value mb-0">
                      3 /cu mm
                    </p>
                  </td>
                </tr>
                <tr>
                  <td>
                    <p class="table-lable mb-0">
                      Blasts, in Body fluid by Manual count
                    </p>
                  </td>
                  <td>
                    <p class="table-value mb-0">
                      0 /cu mm
                    </p>
                  </td>
                </tr>
                <tr>
                  <td>
                    <p class="table-lable mb-0">
                      Eosinophils, in Body fluid by Manual count
                    </p>
                  </td>
                  <td>
                    <p class="table-value mb-0">
                      1 /cu mm
                    </p>
                  </td>
                </tr>
                <tr>
                  <td>
                    <p class="table-lable mb-0">
                      Monocytes, in Body fluid by Manual count
                    </p>
                  </td>
                  <td>
                    <p class="table-value mb-0">
                      14 /cu mm
                    </p>
                  </td>
                </tr>
                <tr>
                  <td>
                    <p class="table-lable mb-0">
                      Lymphocytes, in Body fluid by Manual count
                    </p>
                  </td>
                  <td>
                    <p class="table-value mb-0">
                      37 /cu mm
                    </p>
                  </td>
                </tr>
                <tr>
                  <td>
                    <p class="table-lable mb-0">
                      Neutrophils, in Body fluid by Manual count
                    </p>
                  </td>
                  <td>
                    <p class="table-value mb-0">
                      3 /cu mm
                    </p>
                  </td>
                </tr>
                <tr>
                  <td>
                    <p class="table-lable mb-0">
                      Body Fluid Source
                    </p>
                  </td>
                  <td>
                    <p class="table-value mb-0">
                      Peritoneal
                    </p>
                  </td>
                </tr>
                <tr>
                  <td>
                    <p class="table-lable mb-0">
                      Collection method - Semen
                    </p>
                  </td>
                  <td>
                    <p class="table-value mb-0">
                      Non-viscous
                    </p>
                  </td>
                </tr>
                <tr>
                  <td>
                    <p class="table-lable mb-0">
                      Erythrocytes, in Body fluid by Manual count
                    </p>
                  </td>
                  <td>
                    <p class="table-value mb-0">
                      67 /cu mm
                    </p>
                  </td>
                </tr>
                <tr>
                  <td>
                    <p class="table-lable mb-0">
                      Leukocytes, in Body fluid by Manual count
                    </p>
                  </td>
                  <td>
                    <p class="table-value mb-0">
                      54 /cu mm
                    </p>
                  </td>
                </tr>
                <tr>
                  <td>
                    <p class="table-lable mb-0">
                      Color of Body fluid
                    </p>
                  </td>
                  <td>
                    <p class="table-value mb-0">
                      Yellow
                    </p>
                  </td>
                </tr>
                <tr>
                  <td>
                    <p class="table-lable mb-0">
                      Appearance of Body fluid
                    </p>
                  </td>
                  <td>
                    <p class="table-value mb-0">
                      Clear
                    </p>
                  </td>
                </tr>
              </table>
            </div>
          </div>
        </div>
      </b-modal>
    </div>
    <div class="labs-model-content">
      <b-modal id="modal-metabolic" size="lg" title="LABS" class="labs-model">
        <div class="content pl-60">
          <div class="d-flex align-items-center justify-content-between">
            <p class="mb-0 font-weight-500">
              Comprehensive Metabolic Panel
            </p>
            <p class="mb-0">Jan 09, 2013</p>
          </div>
          <div class="d-flex align-items-center justify-content-between pb-1">
            <p class="mb-0 font-size-13 font-style-italic color-muted">
              Lab panel
            </p>
            <p class="mb-0 font-size-13 font-style-italic color-muted">
              Dr. Jason Prystowsky at Santa Barbara Cottage Hospital
            </p>
          </div>
          <div class="row">
            <div class="col-md-12">
              <table class="table-content width-414">
                <tr>
                  <td>
                    <p class="lable">
                      ALT
                      <span class="sub-text">
                        (U/L)
                      </span>
                    </p>
                  </td>
                  <td></td>
                  <td>
                    <div
                      class="numeric-data d-flex alin-items-center justify-content-between"
                    >
                      <span class="first-number">98</span>
                      <span class="middle-number">104</span>
                      <span class="last-number">108</span>
                    </div>
                  </td>
                  <td></td>
                </tr>
                <tr>
                  <td>
                    <p class="lable">
                      AST
                      <span class="sub-text">
                        (U/L)
                      </span>
                    </p>
                  </td>
                  <td></td>
                  <td>
                    <div
                      class="numeric-data d-flex alin-items-center justify-content-between"
                    >
                      <span class="first-number">17</span>
                      <span class="middle-number">28</span>
                      <span class="last-number">59</span>
                    </div>
                  </td>
                  <td></td>
                </tr>
                <tr>
                  <td>
                    <p class="lable">
                      Albumin
                      <span class="sub-text">
                        (g/dL)
                      </span>
                    </p>
                  </td>
                  <td class="pb-2"><span class="red-number">2.9</span></td>
                  <td>
                    <div
                      class="numeric-data d-flex alin-items-center justify-content-between"
                    >
                      <span class="first-number">3.5</span>
                      <span class="first-number"></span>
                      <span class="middle-number">5</span>
                    </div>
                  </td>
                  <td></td>
                </tr>
                <tr>
                  <td>
                    <p class="lable">
                      Alkaline Phosphatase
                      <span class="sub-text">
                        (U/L)
                      </span>
                    </p>
                  </td>
                  <td></td>
                  <td>
                    <div
                      class="numeric-data d-flex alin-items-center justify-content-between"
                    >
                      <span class="first-number">38</span>
                      <span class="first-number">68</span>
                      <span class="middle-number">126</span>
                    </div>
                  </td>
                  <td></td>
                </tr>
                <tr>
                  <td>
                    <p class="lable">
                      Bilirubin Total
                      <span class="sub-text">
                        (mg/dL)
                      </span>
                    </p>
                  </td>
                  <td></td>
                  <td>
                    <div
                      class="numeric-data d-flex alin-items-center justify-content-between"
                    >
                      <span class="first-number">0.6</span>
                      <span class="first-number">0.2</span>
                      <span class="middle-number">1.6</span>
                    </div>
                  </td>
                  <td></td>
                </tr>
                <tr>
                  <td>
                    <p class="lable">
                      Blood Urea Nitrogen
                      <span class="sub-text">
                        (mg/dL)
                      </span>
                    </p>
                  </td>
                  <td class="pb-2"><span class="red-number">7</span></td>
                  <td>
                    <div
                      class="numeric-data d-flex alin-items-center justify-content-between"
                    >
                      <span class="first-number">9</span>
                      <span class="first-number"></span>
                      <span class="middle-number">20</span>
                    </div>
                  </td>
                  <td></td>
                </tr>
                <tr>
                  <td>
                    <p class="lable">
                      Calcium
                      <span class="sub-text">
                        (mg/dL)
                      </span>
                    </p>
                  </td>
                  <td></td>
                  <td>
                    <div
                      class="numeric-data d-flex alin-items-center justify-content-between"
                    >
                      <span class="first-number">8.4</span>
                      <span class="first-number"></span>
                      <span class="middle-number">10.2</span>
                    </div>
                  </td>
                  <td></td>
                </tr>
                <tr>
                  <td>
                    <p class="lable">
                      Chloride
                      <span class="sub-text">
                        (mmol/L)
                      </span>
                    </p>
                  </td>
                  <td></td>
                  <td>
                    <div
                      class="numeric-data d-flex alin-items-center justify-content-between"
                    >
                      <span class="first-number">98</span>
                      <span class="first-number">104</span>
                      <span class="middle-number">108</span>
                    </div>
                  </td>
                  <td></td>
                </tr>
                <tr>
                  <td>
                    <p class="lable">
                      Carbon Dioxide
                      <span class="sub-text">
                        (mmol/L)
                      </span>
                    </p>
                  </td>
                  <td></td>
                  <td>
                    <div
                      class="numeric-data d-flex alin-items-center justify-content-between"
                    >
                      <span class="first-number">23</span>
                      <span class="first-number">28</span>
                      <span class="middle-number">30</span>
                    </div>
                  </td>
                  <td></td>
                </tr>
                <tr>
                  <td>
                    <p class="lable">
                      Estimated GFR
                      <span class="sub-text">
                        (mL/min/1.73 m2)
                      </span>
                    </p>
                  </td>
                  <td></td>
                  <td>
                    <div
                      class="numeric-data d-flex alin-items-center justify-content-between"
                    >
                      <span class="first-number"></span>
                      <span class="first-number">90</span>
                      <span class="middle-number"></span>
                    </div>
                  </td>
                  <td></td>
                </tr>
                <tr>
                  <td>
                    <p class="lable">
                      Glucose
                      <span class="sub-text">
                        (mg/dL)
                      </span>
                    </p>
                  </td>
                  <td></td>
                  <td>
                    <div
                      class="numeric-data d-flex alin-items-center justify-content-between"
                    >
                      <span class="first-number">74</span>
                      <span class="first-number"></span>
                      <span class="middle-number">106</span>
                    </div>
                  </td>
                  <td class="pb-2 pl-2"><span class="red-number">107</span></td>
                </tr>
                <tr>
                  <td>
                    <p class="lable">
                      Potassium
                      <span class="sub-text">
                        (mmol/L)
                      </span>
                    </p>
                  </td>
                  <td></td>
                  <td>
                    <div
                      class="numeric-data d-flex alin-items-center justify-content-between"
                    >
                      <span class="first-number">35</span>
                      <span class="first-number">4.3</span>
                      <span class="middle-number">5</span>
                    </div>
                  </td>
                  <td></td>
                </tr>
                <tr>
                  <td>
                    <p class="lable">
                      Sodium
                      <span class="sub-text">
                        (mmol/L)
                      </span>
                    </p>
                  </td>
                  <td></td>
                  <td>
                    <div
                      class="numeric-data d-flex alin-items-center justify-content-between"
                    >
                      <span class="first-number">137</span>
                      <span class="first-number">140</span>
                      <span class="middle-number">145</span>
                    </div>
                  </td>
                  <td></td>
                </tr>
                <tr>
                  <td>
                    <p class="lable">
                      Total Protein
                      <span class="sub-text">
                        (g/dL)
                      </span>
                    </p>
                  </td>
                  <td></td>
                  <td>
                    <div
                      class="numeric-data d-flex alin-items-center justify-content-between"
                    >
                      <span class="first-number">6.3</span>
                      <span class="first-number">6.9</span>
                      <span class="middle-number">B.2</span>
                    </div>
                  </td>
                  <td></td>
                </tr>
              </table>
            </div>
          </div>
        </div>
      </b-modal>
    </div>
  </div>
</template>
<script>
export default {
  name: 'ContentBar',
  data () {
    return {
      text: `
          Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry
          richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor
          brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon
          tempor, sunt aliqua put a bird on it squid single-origin coffee nulla
          assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore
          wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher
          vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic
          synth nesciunt you probably haven't heard of them accusamus labore VHS.
        `
    }
  }
}
</script>
<style scoped>
.pr-192 {
  padding-right: 192px;
}
.color-muted {
  color: #8899a6;
}
.font-style-italic {
  font-style: italic;
}
.font-size-16 {
  font-size: 16px;
}
.font-size-12 {
  font-size: 12px;
}
.font-size-13 {
  font-size: 13px;
}
.font-weight-500 {
  font-weight: 500;
}
.width-414 {
  width: 414px;
}
.pb-6 {
  padding-bottom: 6px;
}
.pb-30 {
  padding-bottom: 30px;
}
.pt-30 {
  padding-top: 30px;
}
.pl-30 {
  padding-left: 30px;
}
.pr-30 {
  padding-right: 30px;
}
.pl-60 {
  padding-left: 60px;
}
.p-30 {
  padding: 30px;
}
.mb-60 {
  margin-bottom: 60px;
}

.profile-title {
  font-size: 27px;
  font-weight: 500;
  color: #1565c0;
}
.profile-box {
  height: auto;
  border-radius: 3px;
  box-shadow: 0 2px 6px 0 rgba(0, 0, 0, 0.1);
  border: solid 1px #ebf5ff;
  background-color: #ffffff;
}
.title-div {
  padding-left: 25px;
  height: 40px;
  border-radius: 3px;
  background-color: #daebff;
}
.demographic_icon {
  width: 21px;
  height: 21px;
  object-fit: contain;
}
.profile-lable {
  font-size: 16px;
  font-weight: 300;
  color: #9b9b9b;
}
.profile-value {
  font-size: 16px;
  font-weight: normal;
  color: #4a4a4a;
}
.expan-button,
.expan-button:hover,
.expan-button:active,
.expan-button:focus {
  background-color: #f4f9ff !important;
  border: none !important;
  height: 60px;
  color: #616161 !important;
  box-shadow: none !important;
}
.text-align-left {
  text-align: left;
}
.expand {
  width: 21px;
  height: 21px;
  object-fit: contain;
}
.sub-lable {
  color: #616161;
  font-size: 16px;
  font-weight: 500;
  margin-bottom: 22px;
  background-color: #f5f5f5;
}
.sub-content {
  font-size: 16px;
  line-height: 1.5;
  color: #4a4a4a;
  padding-bottom: 26px;
}
.tablist-card {
  border-top: 0px;
  border-left: 0px;
  border-right: 0px;
  border-bottom: solid 1px #ebebeb;
  border-radius: unset;
  box-shadow: 0 2px 6px 0 rgba(0, 0, 0, 0.1);
}
.underline {
  text-decoration: underline;
  cursor: pointer;
}
.text-blue-color {
  color: #1976d2 !important;
}
.table-content {
  border-top: solid 0.5px #e1e1e1;
}
.table-content .table-lable {
  width: 261px;
  height: 32px;
  font-size: 11px;
  letter-spacing: -0.2px;
  color: #4a4a4a;
  display: flex;
  align-items: center;
}
.table-content .table-value {
  width: 96px;
  height: 32px;
  font-size: 13px;
  font-weight: bold;
  line-height: 1.23;
  text-align: center;
  color: #4a4a4a;
  display: flex;
  align-items: center;
}
.popup-model-span:focus {
  outline-width: 0px;
}
.table-content .lable {
  font-size: 13px;
  color: #333333;
  line-height: 13px;
  /* font-family: Roboto-Regular; */
}
.table-content .lable .sub-text {
  font-size: 9px;
  color: #4a4a4a;
  line-height: 13px;
  /* font-family: Roboto-Light; */
}
.table-content .numeric-data {
  border-bottom: solid 0.5px #e1e1e1;
  padding-bottom: 4px;
}
.table-content .numeric-data .first-number,
.table-content .numeric-data .last-number {
  font-size: 11px;
  line-height: 13px;
  color: #9a9a9a;
}
.table-content .numeric-data .middle-number {
  font-size: 12px;
  line-height: 13px;
  color: #393939;
}
.red-number {
  font-size: 12px;
  line-height: 13px;
  color: #c30016;
}
</style>
