---
layout: default
---

## Sync For Science

### Who is S4S?

S4S is a collaboration among researchers (Harvard Medical School Department of
Biomedical Informatics), electronic health record vendors (Allscripts,
athenahealth, Cerner, drchrono, Epic, McKesson), and the United States federal
government (Office of the National Coordinator for Health IT, Office of Science
and Technology Policy, and National Institutes of Health).

### Who benefits from S4S?

#### Research Participants

An easier way of contributing to scientific progress and sharing medical
records with researchers that doesn’t require faxed forms, delays, or in-person
visits.

#### Researchers

A simple path to receive research participants’ basic clinical data, including
essential details like lab results, vital signs, problem lists, medications,
and immunizations, potentially increasing participation in studies. Data
delivered in a structured format with standard vocabularies may also need less
“cleanup” than typical EHR data.

#### Providers

A way to give patients access to the potential benefit from participating in
research studies and a reduction in staff time to support data requests, as
they flow automatically through our vendor-supplied patient portal.

#### EHR Vendors

A method to empower their health care provider customers, to facilitate
research, to participate in the development of stronger health care systems,
and to meet EHR Incentive Program requirements for API-based patient access.


### Technical Details

* [S4S FHIR API Calls](./api-calls)
* [Reference stack and demonstration](https://demo.syncfor.science/)

### In the News

 * [healthit.gov](https://www.healthit.gov/buzz-blog/health-innovation/nih-and-onc-launch-the-sync-for-science-pilot/)
 * [healthcareitnews.com](http://www.healthcareitnews.com/news/nih-and-onc-announce-sync-science-pilot-enable-patients-donate-data-precision-medicine)
 * [hitconsultant.net](http://hitconsultant.net/2016/03/25/nih-onc-launch-sync-science-5-things-know/)
 * [wadeschulz.com](http://www.wadeschulz.com/2016/02/sync-for-science-s4s/)

### Contact

<form class="form-horizontal" role="form" method="post" action="https://formspree.io/contact@mg.syncfor.science">
    <div class="form-group">
        <label for="name" class="col-sm-2 control-label">Name</label>
        <div class="col-sm-10">
            <input type="text" class="form-control" id="name" name="name" placeholder="First & Last Name" value="">
        </div>
    </div>
    <div class="form-group">
        <label for="_replyto" class="col-sm-2 control-label">Email</label>
        <div class="col-sm-10">
            <input type="email" class="form-control" id="email" name="_replyto" placeholder="example@domain.com" value="">
        </div>
    </div>
    <div class="form-group">
        <label for="body" class="col-sm-2 control-label">Message</label>
        <div class="col-sm-10">
            <textarea class="contact form-control" rows="4" name="body"></textarea>
        </div>
    </div>
    <div class="form-group">
        <div class="col-sm-10 col-sm-offset-2">
            <input id="submit" name="submit" type="submit" value="Send" class="btn btn-primary">
        </div>
    </div>
    <input type="hidden" name="_next" value="http://syncfor.science/thanks" />
</form>
