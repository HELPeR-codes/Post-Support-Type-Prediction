# PostRoleAnnotation
This trains a Distill BERT classifier for different roles of post like emotion, advice, opinion, personal background

The inference is used to obtain the class of new datafiles




The seven codes and no of incidents of each are tabulated below:


<table>
  <tr>
   <td> 
   </td>
   <td>Definition
   </td>
   <td>No. of incidents
   </td>
  </tr>
  <tr>
   <td>Advice
   </td>
   <td>offers ideas and suggestions actions for coping with challenges
   </td>
   <td>77
   </td>
  </tr>
  <tr>
   <td>Referral
   </td>
   <td>refers to information sources, e.g., books, websites, contacts
   </td>
   <td>44
   </td>
  </tr>
  <tr>
   <td>Facts or situation appraisal
   </td>
   <td>Offers facts or reassesses the situation
   </td>
   <td>181
   </td>
  </tr>
  <tr>
   <td>Personal Experience
   </td>
   <td>Shares personal stories or incidents
   </td>
   <td>220
   </td>
  </tr>
  <tr>
   <td>Opinions
   </td>
   <td>Offers view or judgment formed about something. It is not necessarily based on fact or knowledge
   </td>
   <td>60
   </td>
  </tr>
  <tr>
   <td>Emotional support
   </td>
   <td>Expressing feelings (e.g., fear, joy, despair), listening, and seeking or communicating concern, empathy, or reassurance
   </td>
   <td>196
   </td>
  </tr>
  <tr>
   <td>Others
   </td>
   <td>The comment doesn’t fit any of above
   </td>
   <td>38
   </td>
  </tr>
</table>

To obtain the API for calling our model - please contact k.thaker@pitt.edu

The table below shows the performance of each class:

<table>
  <tr>
   <td rowspan="2" > 
<p>
Support Type
   </td>
   <td colspan="3" >Support Type Prediction
   </td>
  </tr>
  <tr>
   <td>Precision
   </td>
   <td>Recall
   </td>
   <td>F-score
   </td>
  </tr>
  <tr>
   <td>Advice
   </td>
   <td>0.772
   </td>
   <td>0.850
   </td>
   <td>0.809
   </td>
  </tr>
  <tr>
   <td>Referral
   </td>
   <td>0.818
   </td>
   <td>1.000
   </td>
   <td>0.900
   </td>
  </tr>
  <tr>
   <td>Facts or situation appraisal
   </td>
   <td>0.816
   </td>
   <td>0.769
   </td>
   <td>0.792
   </td>
  </tr>
  <tr>
   <td>Personal Experience
   </td>
   <td>0.948
   </td>
   <td>0.873
   </td>
   <td>0.909
   </td>
  </tr>
  <tr>
   <td>Opinions
   </td>
   <td>0.807
   </td>
   <td>0.807
   </td>
   <td>0.807
   </td>
  </tr>
  <tr>
   <td>Emotional support
   </td>
   <td>0.910
   </td>
   <td>0.739
   </td>
   <td>0.816
   </td>
  </tr>
  <tr>
   <td>Others
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><strong>Average</strong>
   </td>
   <td><strong>0.85</strong>
   </td>
   <td><strong>0.84</strong>
   </td>
   <td><strong>0.84</strong>
   </td>
  </tr>
</table>


