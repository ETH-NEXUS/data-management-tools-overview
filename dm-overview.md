

# Overview of Experimental- and Meta-Data Management Tools for Researchers

</div>

</div>

</div>

<div id="content" class="page view">

<div id="action-messages">

</div>

<div class="page-metadata">

- Created by <span class="author">
  <a href="/users/profile/editmyprofilepicture.action"
  class="userLogoLink" data-username="natalich"
  aria-label="Add your avatar" title="Add your avatar"><span
  class="aui-avatar aui-avatar-small"> <span class="aui-avatar-inner">
  <img
  src="/s/2d5u6g/9422/1fuz1d4/_/images/icons/profilepics/add_profile_pic.svg"
  class="userLogo logo defaultLogo" alt="Add your avatar" /> </span>
  </span></a> <a href="%20%20%20%20/display/~natalich%0A"
  class="url fn confluence-userlink"
  aria-label="created by Chicherova  Natalia"
  data-username="natalich">Chicherova Natalia</a></span>, last updated
  on <a
  href="/pages/diffpagesbyversion.action?pageId=372608099&amp;selectedPageVersions=51&amp;selectedPageVersions=52"
  class="last-modified"
  aria-label="modified on May 08, 2026, select to show changes"
  title="Show changes">May 08, 2026</a> <span class="read-time"> 8
  minute read </span>

</div>

<div id="main-content" class="wiki-content">

**Good data management practices**<span class="s2"> are built on several
key pillars:\
📋 </span><span class="s1">**structured metadata
collection**</span><span class="s2">,\
📁 </span><span class="s1">**standardized file
organization**</span><span class="s2">,\
🔄 </span><span class="s1">**version control**</span><span class="s2">,\
🧪 </span><span class="s1">**traceability of experiments and
samples**</span><span class="s2">,\
🔒 </span><span class="s1">**secure storage**</span><span class="s2">,\
and ♻️ </span><span class="s1">**reproducible
workflows**</span><span class="s2">.</span>

\

While spreadsheets such as <span class="s1">**Excel**</span> are widely
used in research, they are often prone to ⚠️ <span class="s1">**manual
errors**</span>, inconsistent metadata, duplicated entries, and limited
traceability, making long-term data management and collaboration
difficult. In addition, non-standardized file organization and the
transfer of experimental data via external hard drives can lead to 📂
data fragmentation, 🔀 version confusion, and increased risk of data
loss.

Dedicated <span class="s1">**data and metadata management
platforms**</span> help address these challenges by improving ✅
organization, ✅ standardization, ✅ reproducibility, ✅ collaboration,
and ✅ long-term accessibility of research data.

The table below provides a <span class="s1">**non-exhaustive
overview**</span> of selected tools for experimental data and metadata
management across different research domains.

\

<div class="confluence-information-macro confluence-information-macro-information conf-macro output-block"
role="region" aria-label="Info" data-hasbody="true"
data-macro-name="info"
data-host-id="e2c8872e-c43a-3440-9df9-7c210f566841"
data-macro-id="2e3565a8-b438-4750-a39f-23334f95d20b"
data-content-id="372608099" data-content-version="52">

Disclaimer

<span class="aui-icon aui-icon-small aui-iconfont-info-filled confluence-information-macro-icon"
role="presentation"></span>

<div class="confluence-information-macro-body">

The list below is not exhaustive and does not include all available
solutions on the market. It is intended as a comparative overview of
selected tools relevant to research metadata collection and
FAIR-compliant laboratory data management.

</div>

</div>

\

\

<div class="table-wrap">

<table class="relative-table wrapped confluenceTable"
style="width: 85.3403%;">
<colgroup>
<col style="width: 3%" />
<col style="width: 9%" />
<col style="width: 11%" />
<col style="width: 29%" />
<col style="width: 3%" />
<col style="width: 5%" />
<col style="width: 5%" />
<col style="width: 5%" />
<col style="width: 5%" />
<col style="width: 4%" />
<col style="width: 4%" />
<col style="width: 6%" />
<col style="width: 5%" />
</colgroup>
<tbody>
<tr>
<th class="confluenceTh">Tool</th>
<th class="confluenceTh">Description</th>
<th class="confluenceTh">Data Use Cases/Why to Use It</th>
<th class="confluenceTh">Homepage</th>
<th class="confluenceTh">License &amp; Cost</th>
<th class="confluenceTh">Deployment</th>
<th class="confluenceTh">Flexibility</th>
<th class="confluenceTh">Integration/API</th>
<th class="confluenceTh">Community &amp; Docs</th>
<th class="confluenceTh">Advice</th>
<th class="confluenceTh">Key words</th>
<th class="confluenceTh">    Supported Data</th>
<th class="confluenceTh">    Research Area</th>
</tr>
&#10;<tr>
<td class="confluenceTd">Agora (GyroTools)</td>
<td class="confluenceTd">Web-based research data management platform for
MRI and related imaging data; integrates, archives, and organizes
imaging + metadata for research workflows ETH/University of Zurich
spin-off</td>
<td class="confluenceTd"><p>MRI research data &amp; metadata management;
DICOM and raw MR data ingestion; experiment documentation; pipeline
automation; collaborative data access</p>
<p>✅ the main reasons to use it are:<br />
- strong support for Philipps' proprietary PAR/REC Imaging file
format<br />
-  excellent local support by Gyrotools</p></td>
<td class="confluenceTd"><a href="https://www.gyrotools.com/gt/"
class="external-link"
rel="nofollow">https://www.gyrotools.com/gt/</a><br />
&#10;<p><a href="https://www.gyrotools.com/gt/index.php/products/agora"
class="external-link"
rel="nofollow">https://www.gyrotools.com/gt/index.php/products/agora</a></p></td>
<td class="confluenceTd"><p>⚠️ Commercial / proprietary (contact vendor
for pricing)</p></td>
<td class="confluenceTd"><p>🐳 On-premises deployment; Docker images
&amp; connectors available; scalable server setup</p></td>
<td class="confluenceTd">⚠️ Limited flexibility. It is possible to
access docker containers; primarily imaging &amp; metadata workflows;
limited custom frontend modules</td>
<td class="confluenceTd"><p>✅ REST API + SDKs (Python/Matlab/C++) for
automation &amp; analysis</p></td>
<td class="confluenceTd"><p>⚠️ Vendor documentation + academic usage
examples; community is smaller than broad open-source tools</p>
<p>Link to <a href="https://docs.gyrotools.com/agora/latest/index.html"
class="external-link" rel="nofollow">documentation</a></p></td>
<td class="confluenceTd"><p>Best suited for research institutions
needing <span class="s1">MRI image database + FAIR metadata
workflows</span> with integration to analysis pipelines</p></td>
<td class="confluenceTd"><p>Metadata Management; FAIR Support; Imaging
Data Management;<br />
Imaging Data; MRI Data; Experimental Data;<br />
On-Premises; Commercial;<br />
REST API; Python API; Docker Support</p></td>
<td class="confluenceTd"><ul>
<li>PAR/REC</li>
</ul>
<p>* DICOM (.dcm)<br />
* NIfTI (.nii, .nii.gz)<br />
* JSON (.json)<br />
* CSV (.csv)<br />
* XML (.xml)<br />
* MATLAB files (.mat)</p>
<p>* ZIP archives (.zip)<br />
* Text metadata files (.txt)</p></td>
<td class="confluenceTd"><p>* MRI Research<br />
* Medical Imaging<br />
* Radiology<br />
* Neuroimaging<br />
* Biomedical Imaging Research</p></td>
</tr>
<tr>
<td class="confluenceTd"><p>RedCap</p></td>
<td class="confluenceTd"><p>REDCap is a secure web platform for building
and managing online databases and surveys, focused on clinical
research.<br />
 </p></td>
<td class="confluenceTd"><p>Clinical research data capture, electronic
case report forms (eCRFs), longitudinal studies, patient registries,
survey-based studies, regulatory-compliant data collection</p>
<p>✅ Strong for clinical &amp; regulated research data capture</p></td>
<td class="confluenceTd"><p><a href="https://project-redcap.org/"
class="external-link"
rel="nofollow">https://project-redcap.org/</a></p></td>
<td class="confluenceTd"><p>⚠️ Free for institutions but requires a
consortium membership or partnership</p></td>
<td class="confluenceTd"><p>⚠️ No official Docker support; typically
institutionally hosted; requires local IT setup</p></td>
<td class="confluenceTd"><p>⚠️ Limited frontend customization;
form/survey builder only (no custom modules)</p></td>
<td class="confluenceTd"><p>✅ REST API; data export in multiple formats
(CSV, SPSS, R, SAS); integration via external modules</p></td>
<td class="confluenceTd"><p>✅ Large academic user base; extensive
documentation</p></td>
<td class="confluenceTd"><p>REDCap is ideal if you need a secure and
compliant survey tool, especially for clinical studies. Less flexible
for custom workflows or non-clinical lab data management.</p></td>
<td class="confluenceTd"><p>Metadata Management; EDC (Electronic Data
Capture); FAIR Support;<br />
Clinical Data; Survey Data; Experimental Data;<br />
Institutional; REST API; On-Premises;</p></td>
<td class="confluenceTd"><ul>
<li>CSV (.csv)</li>
<li>JSON (.json)</li>
<li>XML (.xml)</li>
<li>SPSS (.sav)</li>
<li>SAS (.sas7bdat)</li>
<li>CDISC ODM (.xml)</li>
<li>PDF forms/reports (.pdf)</li>
<li>Text data (.txt)</li>
<li>DICOM metadata references</li>
<li>HL7/FHIR-compatible clinical metadata</li>
</ul></td>
<td class="confluenceTd"><ul>
<li>Clinical Research</li>
<li>Epidemiology</li>
<li>Public Health</li>
<li>Translational Medicine</li>
<li>Patient Registry Studies</li>
<li>Survey-Based Research</li>
<li>Biomedical Research</li>
<li>Clinical Trials</li>
</ul></td>
</tr>
<tr>
<td class="confluenceTd"><p>OpenBis</p></td>
<td class="confluenceTd"><p>OpenBis is a flexible ELN‑LIMS and FAIR data
management platform for scientific research, developed at ETH
Zürich. </p></td>
<td class="confluenceTd"><p>Laboratory data management, experiment
documentation (ELN), sample &amp; project tracking, omics data,
FAIR-compliant research data management</p>
<p>✅ Strong for academic labs, FAIR data compliance, structured
experiment tracking</p></td>
<td class="confluenceTd"><p><a href="https://openbis.ch/"
class="external-link" rel="nofollow">https://openbis.ch/</a></p>
<p><span class="nolink"><a href="https://de.wikipedia.org/wiki/OpenBIS"
class="external-link"
rel="nofollow">https://de.wikipedia.org/wiki/OpenBIS</a></span></p></td>
<td class="confluenceTd"><p>✅ Open‑source (Apache 2.0
license) </p></td>
<td class="confluenceTd"><p>🐳 Docker deployment supported; official
images &amp; documentation available; manual/orchestrated setup
possible</p>
<p><a
href="https://unlimited.ethz.ch/spaces/openbis/pages/53744366/openBIS%2BDownload%2BPage"
rel="nofollow">Confluence doc</a> </p></td>
<td class="confluenceTd"><p>✅ Limited frontend customization; survey
builder only</p></td>
<td class="confluenceTd"><p>✅ REST APIs available; integration via Java
&amp; Python clients</p></td>
<td class="confluenceTd"><p>⚠️ Moderate documentation;
academic/community support</p>
<p><span style="color:var(--ds-text,#172b4d);"><span> Link to
</span></span><a
href="https://community.openbis.ch/c/technical-support/14"
class="external-link" style="text-align: left;" rel="nofollow">community
doc </a></p></td>
<td class="confluenceTd"><p>Best suited for research institutions
needing FAIR-compliant ELN/LIMS with structured lab workflows rather
than highly customized web applications</p></td>
<td class="confluenceTd"><p>Metadata Management; LIMS; ELN; FAIR
Support;<br />
Sample Data; Experimental Data; Omics Data;<br />
On-Premises; Open Source;<br />
REST API; Docker Support</p></td>
<td class="confluenceTd"><p><br />
</p></td>
<td class="confluenceTd"><p><br />
</p></td>
</tr>
<tr>
<td class="confluenceTd"><p>LabKey</p></td>
<td class="confluenceTd"><p>LabKey is a web application for building and
managing online databases and surveys<br />
 </p></td>
<td class="confluenceTd"><p>clinical data, sample tracking (biobanking),
assay data, genomics &amp; proteomics data</p>
<p>✅ Great <span class="s1">for</span> lab data management, sample
tracking, analysis</p></td>
<td class="confluenceTd"> <a
href="https://www.labkey.com/download-community-edition/"
class="external-link"
rel="nofollow">https://www.labkey.com/download-community-edition/</a></td>
<td class="confluenceTd">✅ Free and open-source</td>
<td class="confluenceTd"><span style="color:var(--ds-text,#172b4d);">🐳
On-premises deployment; d</span>ocker image is easy to build;
docker-compose.yml examples available (to do - links)</td>
<td class="confluenceTd"><p>✅ Highly flexible — custom modules
(HTML/CSS/JS)</p>
<p>⚠️ 2FA available for premium version. The free version should wrapped
in another 2FA authentication app (e.g. SwitchEdu ID)</p></td>
<td class="confluenceTd">✅ Python, SQL, JavaScript APIs supported</td>
<td class="confluenceTd">⚠️ Moderate — some reliance on community
docs</td>
<td class="confluenceTd">LabKey is a strong option if you’re comfortable
with open-source deployments and need a flexible, integrative platform
for lab or biomedical data. Its module extensibility and API ecosystem
make it ideal for custom workflows.</td>
<td class="confluenceTd">Metadata Management; LIMS; FAIR Support;<br />
Clinical Data; Sample Data; Survey Data; Experimental Data;<br />
On-Premises; Open Source;<br />
REST API; Python API; Docker Support; Plugin Architecture</td>
<td class="confluenceTd"><br />
</td>
<td class="confluenceTd"><br />
</td>
</tr>
<tr>
<td class="confluenceTd">Lab Data Management NEXUS</td>
<td class="confluenceTd"><p>LDM is web-based lab data management
application focused on chemical assay experiments developed at ETH
Zürich.</p>
<p>Designed to support structured laboratory workflows, experiment
documentation, metadata capture, and FAIR-compliant research data
management. </p></td>
<td class="confluenceTd"><p>Laboratory experiment documentation;
structured metadata capture; sample and project tracking; biomedical
&amp; translational research workflows; FAIR data management;
reproducibility-focused research environments.</p></td>
<td class="confluenceTd"><p><a
href="https://www.sciencedirect.com/science/article/pii/S2472630325000160#:~:text=Abstract,with%20a%20more%20detailed%20analysis"
class="external-link"
rel="nofollow">https://www.sciencedirect.com/science/article/pii/S2472630325000160#:~:text=Abstract,with%20a%20more%20detailed%20analysis</a>.</p>
<p><a href="https://ldm.nexus.ethz.ch/" class="external-link"
rel="nofollow">https://ldm.nexus.ethz.ch/</a></p>
<p><a href="https://github.com/ETH-NEXUS/lab_data_management"
class="external-link"
rel="nofollow">https://github.com/ETH-NEXUS/lab_data_management</a></p>
<p><a
href="https://nexus-personalized-health-techno.gitbook.io/lab-data-management-app-user-guide"
class="external-link"
rel="nofollow">https://nexus-personalized-health-techno.gitbook.io/lab-data-management-app-user-guide</a></p>
<p><br />
</p></td>
<td class="confluenceTd"><p>✅ Free and open-source.</p>
<p>No licensing fees; institutional self-hosting required.</p></td>
<td class="confluenceTd"><p><span
style="color:var(--ds-text,#172b4d);">🐳 On-premises deployment; docker
image is easy to build; <a
href="https://github.com/ETH-NEXUS/lab_data_management"
class="external-link" rel="nofollow">docker-compose.yml</a> examples
available.</span></p>
<p>Scalable server-based architecture</p>
<p>Requires institutional IT infrastructure for production
setup</p></td>
<td class="confluenceTd">✅<br />
&#10;<p>LDM is built as a Django (backend) and Vue (frontend) application and
is fully open-source, allowing it to be forked and extended
programmatically. Institutions can modify backend logic and data models,
extend REST APIs, adapt or redesign frontend components, and integrate
additional workflows tailored to their specific laboratory needs. Deeper
customization requires software development expertise.</p></td>
<td class="confluenceTd"><p>✅ REST API. </p>
<p>Programmatic access for automation and integration</p>
<p>Designed for integration within institutional research
infrastructure</p>
<p>Supports structured data export and interoperability</p></td>
<td class="confluenceTd"><p>⚠️ Vendor/institutional documentation via
user guide; GitHub source; smaller user ecosystem than major open-source
tools</p></td>
<td class="confluenceTd"><p>LDM is best suited for chemical assay
experiments and biomedical research </p></td>
<td class="confluenceTd"><p>Metadata Management; FAIR Support; Data
Documentation;<br />
Experimental Data; Sample Data;<br />
On-Premises; Institutional;<br />
REST API</p></td>
<td class="confluenceTd"><p><br />
</p></td>
<td class="confluenceTd"><p><br />
</p></td>
</tr>
<tr>
<td class="confluenceTd">datasquid</td>
<td class="confluenceTd"><p>Web-based experiment metadata documentation
tool to auto-generate structured README and FAIR metadata for lab data
folders; developed at UNIL.</p></td>
<td class="confluenceTd"><p>Structured lab metadata and README
generation; experiment documentation; FAIR data capture; complements to
research data repositories</p></td>
<td class="confluenceTd"><p><a
href="https://wp.unil.ch/dsbu/tools_readme/" class="external-link"
rel="nofollow">https://wp.unil.ch/dsbu/tools_readme/</a></p>
<p><a href="https://dsbu.unil.ch/datasquid" class="external-link"
rel="nofollow">https://dsbu.unil.ch/datasquid</a> (NA)</p>
<p><em>Note: Distinct from commercial <a href="https://datasquid.io/"
class="external-link" rel="nofollow">datasquid.io</a> (data software
company)</em></p>
<br />
 </td>
<td class="confluenceTd">✅ Free and open-source</td>
<td class="confluenceTd"><p>Web-based institutional deployment;
integrates with file servers and research data stores; no official
Docker support</p></td>
<td class="confluenceTd"><p>⚠️ Moderate — auto-metadata generation;
configurable templates &amp; documentation workflows</p></td>
<td class="confluenceTd"><p>Integration depends on institutional setup
(filesystem, research repositories); no publicly documented REST
API</p></td>
<td class="confluenceTd"><p>⚠️ Institutional docs via UNIL/DSBU pages;
smaller community than major open-source projects</p></td>
<td class="confluenceTd">Best for labs needing automatic documentation
of research data with FAIR metadata outputs; complements other LIMS or
data management platforms</td>
<td class="confluenceTd">Data Documentation; FAIR Support; Metadata
Management;<br />
Experimental Data;<br />
Institutional; Academic Free</td>
<td class="confluenceTd"><br />
</td>
<td class="confluenceTd"><br />
</td>
</tr>
<tr>
<td class="confluenceTd">sciCat</td>
<td class="confluenceTd"><p>Open-source scientific metadata catalogue
and research data management platform designed to make scientific
datasets findable, accessible, and shareable according to FAIR
principles.</p></td>
<td class="confluenceTd"><p>Scientific dataset cataloguing; metadata
management &amp; lifecycle; linking datasets to samples/instruments;
publishing with DOIs; data discovery &amp; access.</p></td>
<td class="confluenceTd"><p><a href="https://www.scicatproject.org/"
class="external-link"
rel="nofollow">https://www.scicatproject.org/</a></p>
<p><a href="https://github.com/SciCatProject" class="external-link"
rel="nofollow">https://github.com/SciCatProject</a></p>
<p><a
href="https://www.researchgate.net/profile/Linus-Pithan-2/publication/369433495_SciCat_A_meta_data_catalog_and_research_data_management_system/links/641b06aa66f8522c38c749a5/SciCat-A-meta-data-catalog-and-research-data-management-system.pdf"
class="external-link"
rel="nofollow">https://www.researchgate.net/profile/Linus-Pithan-2/publication/369433495_SciCat_A_meta_data_catalog_and_research_data_management_system/links/641b06aa66f8522c38c749a5/SciCat-A-meta-data-catalog-and-research-data-management-system.pdf</a></p>
<p><br />
</p></td>
<td class="confluenceTd"><p>✅ Open-source (BSD-3-Clause on
GitHub) <br />
<br />
</p></td>
<td class="confluenceTd"><p><span
style="color:var(--ds-text,#172b4d);">🐳 </span>On-premises or
institutional deployment; supports Docker &amp; Kubernetes
setups </p></td>
<td class="confluenceTd"><p>✅ Flexible metadata model; supports
raw/derived datasets &amp; instrument/sample links</p></td>
<td class="confluenceTd"><p>✅ REST API backend (Swagger/OpenAPI);
Python clients &amp; additional tools available</p></td>
<td class="confluenceTd"><p>✅ Comprehensive vendor/community docs
(operator, user, developer guides); GitHub activity &amp; community
contributions</p></td>
<td class="confluenceTd">Best for research facilities or labs needing
centralized, FAIR metadata cataloguing and dataset discovery; scale from
facility to research group</td>
<td class="confluenceTd">Data Catalog; Metadata Management; FAIR
Support; DOI Support;<br />
Experimental Data; Imaging Data;<br />
On-Premises; Open Source;<br />
REST API; Kubernetes Support; Docker Support</td>
<td class="confluenceTd"><br />
</td>
<td class="confluenceTd"><br />
</td>
</tr>
<tr>
<td class="confluenceTd">Renku</td>
<td class="confluenceTd"><p>Open-source platform for reproducible data
science that integrates data, code, and metadata with versioning and
provenance developed at ETH Zurich.</p></td>
<td class="confluenceTd"><p>Project metadata &amp; versioning; dataset
tracking; reproducible workflows; FAIR outputs; provenance capture;
computational experiments</p></td>
<td class="confluenceTd"><a href="https://renkulab.io/"
class="external-link" rel="nofollow">https://renkulab.io/</a></td>
<td class="confluenceTd"><p>✅ Open-source (Apache 2.0)</p></td>
<td class="confluenceTd"><p>Cloud hosted (RenkuLab) &amp; self-hostable
(on-premises); no official Docker support</p></td>
<td class="confluenceTd">✅ Limited frontend customization; extensible
via backend services and APIs; flexible computational environments and
workflow pipelines</td>
<td class="confluenceTd"><p>✅ APIs + CLI + SDKs; integrates with Git,
storage backends, workflow engines</p></td>
<td class="confluenceTd"><p>✅ Strong documentation; active community;
open-source ecosystem</p></td>
<td class="confluenceTd"><p>Best for research groups wanting imited
frontend customization; extensibility via backend services &amp;
APIsFAIR reproducibility with integrated metadata + versioning across
data and code workflows</p></td>
<td class="confluenceTd">Reproducibility Platform; Workflow Management;
Provenance Tracking; Data Versioning; FAIR Support;<br />
Computational Data; Experimental Data;<br />
Cloud; On-Premises; Open Source;<br />
REST API; Python API; Git-Based; Docker Support</td>
<td class="confluenceTd"><br />
</td>
<td class="confluenceTd"><br />
</td>
</tr>
<tr>
<td class="confluenceTd">AiiDA</td>
<td class="confluenceTd"><p>Open-source workflow and data management
platform for computational science; captures, stores, and tracks
provenance of data and simulations</p></td>
<td class="confluenceTd"><p>Computational workflow management;
provenance capture; data tracking for simulations; reproducibility of
complex pipelines; FAIR-aligned metadata capture</p></td>
<td class="confluenceTd"><a href="https://www.aiida.net/"
class="external-link" rel="nofollow">https://www.aiida.net/</a></td>
<td class="confluenceTd"><p>✅ Open-source (MIT License)</p></td>
<td class="confluenceTd"><p><span
style="color:var(--ds-text,#172b4d);">🐳  </span>On-premises &amp; cloud
(Python environment; Docker images &amp; containers supported)</p></td>
<td class="confluenceTd"><p>⚠️ Limited frontend customization; backend
extensibility for workflows and plugins</p></td>
<td class="confluenceTd"><p>✅ Python APIs; command-line tools; plugin
ecosystem; database backend</p></td>
<td class="confluenceTd"><p>✅ Strong documentation; active scientific
community; workshops/tutorials</p></td>
<td class="confluenceTd">Best for computational research groups needing
workflow automation, provenance tracking, and reproducible data
pipelines with rich metadata</td>
<td class="confluenceTd">Workflow Management; Provenance Tracking; FAIR
Support; Computational Research Platform;<br />
Computational Data;<br />
On-Premises; Open Source;<br />
Python API; HPC Integration; Docker Support</td>
<td class="confluenceTd"><br />
</td>
<td class="confluenceTd"><br />
</td>
</tr>
<tr>
<td class="confluenceTd">DiData</td>
<td class="confluenceTd"><p>Swiss-based web platform for laboratory
informatics (LIMS), electronic data capture (EDC), and biobank/clinical
data management</p></td>
<td class="confluenceTd"><p>Laboratory data management, sample tracking,
clinical EDC, biobank inventory &amp; freezer management, workflows
&amp; protocol automation</p></td>
<td class="confluenceTd"><a href="https://swissdidata.com/"
class="external-link" rel="nofollow">https://swissdidata.com/</a></td>
<td class="confluenceTd"><p>⚠️ Commercial proprietary; pricing on
request</p></td>
<td class="confluenceTd"><p>On-premises or cloud deployment; scalable
enterprise setup; no official Docker support</p></td>
<td class="confluenceTd"><p>⚠️ Moderate — UI customizable via plugins
and configurable workflows</p></td>
<td class="confluenceTd"><p>✅ REST API &amp; plugin support;
instrument/storage integration</p></td>
<td class="confluenceTd"><p>⚠️ Vendor docs, feature pages, use cases;
smaller community vs open source</p></td>
<td class="confluenceTd"><p>Best for labs needing enterprise LIMS/EDC
with compliance, workflow automation &amp; integrated sample/inventory
systems</p></td>
<td class="confluenceTd">LIMS; EDC (Electronic Data Capture); Biobank
Management; Metadata Management;<br />
Clinical Data; Sample Data; Biobank Data;<br />
On-Premises; Commercial;<br />
REST API; Plugin Architecture</td>
<td class="confluenceTd"><br />
</td>
<td class="confluenceTd"><br />
</td>
</tr>
</tbody>
</table>

</div>

\

\

\

## Controlled Search Keywords Vocabulary

A. Functional Category\
    •    Metadata Management\
    •    Workflow Management\
    •    Data Catalog\
    •    LIMS\
    •    ELN\
    •    EDC (Electronic Data Capture)\
    •    Provenance Tracking\
    •    Data Versioning\
    •    Reproducibility Platform\
    •    FAIR Support\
    •    Data Documentation\
    •    Biobank Management\
    •    Imaging Data Management\
    •    Computational Research Platform

\

B. Data Type\
    •    Clinical Data\
    •    Sample Data\
    •    Imaging Data\
    •    MRI Data\
    •    Omics Data\
    •    Computational Data\
    •    Experimental Data\
    •    Biobank Data\
    •    Survey Data

\

C. Deployment Model\
    •    On-Premises\
    •    Cloud\
    •    Hybrid\
    •    Self-Hosted\
    •    SaaS

D. License Type\
    •    Open Source\
    •    Commercial\
    •    Institutional\
    •    Academic Free

\

E. Technical Scope\
    •    REST API\
    •    Python API\
    •    Plugin Architecture\
    •    Docker Support\
    •    Kubernetes Support\
    •    Git-Based\
    •    HPC Integration\
    •    DOI Support

\

F. Research Area

- MRI Research
- Medical Imaging
- Radiology
- Neuroimaging
- Biomedical Imaging Research
- Clinical Research
- Epidemiology
- Public Health
- Translational Medicine
- Patient Registry Studies
- Survey-Based Research
- Biomedical Research
- Clinical Trials

\

\

More overviews can found her

\

<a
href="https://unlimited.ethz.ch/spaces/DD/pages/216437022/Collection+of+ETH-external+Tools+and+Services+for+your+Research+Data+Management"
class="external-link"
rel="nofollow">https://unlimited.ethz.ch/spaces/DD/pages/216437022/Collection+of+ETH-external+Tools+and+Services+for+your+Research+Data+Management</a>

\

\

\

\

\

\

\

\

</div>

<div id="labels-section" class="pageSection group">

<div class="labels-section-content content-column"
data-entityid="372608099" data-entitytype="page">

<div class="labels-content">

- No labels
- <a href="#" class="show-labels-editor" title="Edit Labels"><span
  class="aui-icon aui-icon-small aui-iconfont-devtools-tag-small">Edit
  Labels</span></a>

</div>

</div>

</div>

<div id="comments-section" class="pageSection group">

<div class="bottom-comment-panels comment-panels">

<div class="quick-comment-container comment add">

<a href="/users/profile/editmyprofilepicture.action"
class="userLogoLink" data-username="natalich"
title="Add your avatar"><span class="aui-avatar aui-avatar-medium"><span
class="aui-avatar-inner"><img
src="/s/2d5u6g/9422/1fuz1d4/_/images/icons/profilepics/add_profile_pic.svg"
class="userLogo logo defaultLogo"
alt="Add your avatar" /></span></span></a>

<div class="quick-comment-body">

<div class="quick-comment-loading-container" style="display:none;">

</div>

<div id="editor-messages">

</div>

<div id="any-messages">

</div>

<div class="quick-comment-prompt" title="Write a Comment" role="button"
tabindex="0" aria-label="Write a Comment">

Write a comment...

</div>

</div>

</div>

</div>

<div id="comments-actions">

<a
href="/spaces/nexuswiki/pages/372608099/Overview+of+Experimental-+and+Meta-Data+Management+Tools+for+Researchers?showComments=true&amp;showCommentArea=true#addcomment"
id="add-comment-rte" class="aui-button" accesskey="m">Add Comment</a>

</div>

</div>

</div>

<div id="space-tools-web-items" class="hidden">

<div data-label="Overview"
data-href="/spaces/viewspacesummary.action?key=nexuswiki">

Overview

</div>

<div data-label="Content Tools"
data-href="/pages/reorderpages.action?key=nexuswiki">

Content Tools

</div>

</div>

<div id="sidebar-container">

</div>

</div>
