# BraggNet: Complex Photonic Integrated CircuitReconstruction Using Deep Learning

We  propose  the  use  of  a  deep  learning  model  toreconstruct the physical design of complex coupled-cavity systemsfrom  their  spectral  response.  The  model  is  demonstrated  usingsilicon photonic grating-assisted, contra-directional couplers con-sisting  of  thousands  of  Bragg  periods.  The  contra-directionalcouplers  are  modeled  as  coupled  optical  cavities,  for  which  atransfer  matrix  model  is  used  to  generate  a  synthetic  datasetcomprising   a   strategic   design   parameter   space.   A   modularapproach  is  adopted  to  build  a  deep  learning  model  made  of6  sub-models  trained  to  make  high-accuracy  prior  and  poste-rior  predictions  on  specific  physical  quantities.  The  free-form,architecture-independent  model  allows  the  user  to  include  anygeometries  to  the  design  parameter  space  simply  by  includingthem  in  the  training  dataset.  Upon  proper  training,  the  modelachieves 1.4% mean absolute error on device reconstruction andhence  proves  suitable  for  inverse  design  applications.  To  showthe  potential  of  the  approach,  a  second  dataset  is  generated  toemulate the fabrication conditions of a nominal design hinderedby  fabrication  imperfections.  The  model  is  then  trained  on  thisdataset  and  used  to  reconstruct  fabricated  devices  from  experi-mental  measurements,  showing  promise  for  on-chip  fabricationdiagnosis.


### Problem Definition

<div style="text-align: center; width: 80%;">
<img src="https://github.com/JonathanCauchon/BraggNet/figures/cdc_segment.pdf" />
</div>
