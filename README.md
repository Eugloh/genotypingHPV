HPV genotype

<h1 style="text-align: center;">HPV genotyping Human papillomavirus genotype distribution in cervical and vulval lesions from HIV-infected women from Harare, Zimbabwe</h1>
<h2 id="background">Background</h2>
<p><strong>145 women</strong> followed for <strong>20 years</strong> for an HIV infection are questioned about their habits and lifestyle. Cervical and vulval samples are collected for the detection of the most severe HPV, a diagnosis on this detection is then predicted. [<strong>CIN/VIN</strong>: Cervical and Vulvar squamous intraepithelial neoplasia.]</p>
<hr />
<p>The data is in the form of two excel tables. The first excel file is a questionnaire for 145 HIV+ women^[Table on demographic information] and the genotype to HPV (+ or -) for <strong>85</strong> of them^[Table on diagnosis, HIV: CIN and VIN]. The women have been reporting to <strong>the Newlands clinic</strong> and provided a sample at <strong>a 1-time point</strong> (cross-sectional analysis).</p>
<h2 id="table-on-demographic-information">The table on demographic information</h2>
<p>A demographics table contains several pieces of information on the patient's demographic information. ^[e.g: id, age, ethnic group, marital status, level of education, if smoking, if taking alcohol, if using herbs (Traditional Herbal Medicine and Healing in Zimbabwe), having wards (HPV related), their location, cd4 count, Viral Load test, time on medication, under treatment (tenofovir, efavirenz, raltegravir, lamivudine...), treatment the person may have taken before (same refs), TB, have they had other STIs before, number of partners, first intercourse, STIs of partners.] This table contains a lot of binary data and some empty cells for specific categories.</p>
<h2 id="table-on-diagnosis-cin-and-vin">The table on diagnosis: CIN and VIN</h2>
<table>
<thead>
<tr>
<th style="text-align: center;">Item</th>
<th style="text-align: center;">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: center;">pt_id</td>
<td style="text-align: center;">145 patients but a lot of lack of information</td>
</tr>
<tr>
<td style="text-align: center;">pt.ID</td>
<td style="text-align: center;">CIN or VIN followed by the ID</td>
</tr>
<tr>
<td style="text-align: center;">Age</td>
<td style="text-align: center;">Patient's age</td>
</tr>
<tr>
<td style="text-align: center;">Dx</td>
<td style="text-align: center;">Diagnosis</td>
</tr>
<tr>
<td style="text-align: center;">Lab</td>
<td style="text-align: center;">Name of the lab</td>
</tr>
<tr>
<td style="text-align: center;">Columns description</td>
<td style="text-align: center;">HPV 16 / 18 / 31 / 33 / 35 / 39 / 45 / 51 / 52 / 53 / 56 / 58 / 66 / 68 / 6 / 11, <br />
I have 1 or 0 considering HPV detection or not</td>
</tr>
</tbody>
</table>
<p><strong>Noteworthy</strong></p>
<ul>
	<li><strong>68</strong> results from CIN</li>
	<li><strong>13</strong> from VIN</li>
	<li>only <strong>3</strong> women have results for CIN and VIN</li>
	<li>HPV can accumulate in a patient.</li>
	<li><strong>BEWARE!</strong>: I modified the initial formatting of the HPVonly_CIN_VIN array. (The VIN lines are moved below).</li>
</ul>
<h2 id="questions">Questions</h2>
<p>The objectives are <strong>to describe the HPV type distribution in the samples</strong> and <strong>to find associations with demographic and clinical history</strong> captured in the questionnaire.</p>
<ul>
	<li>
<p>How many genotypes and what is their distribution (HPV genotypes in women with HIV)</p>
</li>
	<li>
<p>Are there patterns or associations between the variables?</p>
</li>
	<li>Can we explain each genotype individually ?^[HP the variable to explain?]</li>
	<li>
<p>Can we compute a linear regression between test responses and diagnosis? The dependent and independent variables must be quantitative. Categorical variables, such as religion, qualification, area of residence, should be recorded as binary ( mute ) variables or any other type of contrast variables.</p>
</li>
	<li>
<p>The T-test between HPV+ and - comparing VIN and CIN.</p>
</li>
</ul>
<p>I am ordering the factors that can be ordered and I combine CIN3 and ICC (<a href="#control-on-state-of-cancer-and-age">see below</a>) because they correspond to the late cancer stage and the ICC stage has few components.</p>


