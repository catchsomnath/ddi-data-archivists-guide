===============
5.1. Good practices for completing the Document Description
===============

Documenting a study using the DDI and DCMI metadata standards consists of generating a metadata file which will be saved in XML format in what is called an XML Document. The Document Description described below is a description of that XML file. The IHSN Template selected 5 elements to describe the DDI document.


.. raw:: html
	

	<table border="1" cellpadding="0" cellspacing="0">
	    <tbody>
		<tr>
		    <td valign="top">
			<p>
			    Study Title
			</p>
		    </td>
		    <td valign="top">
			<p>
			    The title is the official name of the survey as it is stated on the questionnaire or as it appears in the design documents. The following
			    items should be noted:
			</p>
			<ul>
			<li>Include the reference year(s) of the survey in the title.</li>
			<li>Do not include the abbreviation of the survey name in the title.</li>
			<li>As the survey title is a proper noun, the first letter of each word should be capitalized (except for prepositions or other conjunctions).</li>
			<li>Including the country name in the title is optional.</li>
			</ul>
			<p>
			    Examples: <em> National Household Budget Survey 2002-2003</em>
			</p>
			<p>
			    <em> Popstan Multiple Indicator Cluster Survey 2002</em>
			</p>
		    </td>
		</tr>
		<tr>
		    <td valign="top">
			<p>
			    Metadata Producer
			</p>
		    </td>
		    <td valign="top">
			<p>
			    Name of the person(s) or organization(s) who documented the dataset. Use the "role" attribute to distinguish different stages of involvement in the production process.
			</p>
			<p>
			    Example:
			</p>


			
			<table border="1" cellpadding="0" cellspacing="0">
			    <tbody>
			        <tr>
			            <td valign="top">
			                <p>
			                    <em>Name</em>
			                </p>
			            </td>
			            <td valign="top">
			                <p>
			                    <em>Role</em>
			                </p>
			            </td>
			        </tr>
			        <tr>
			            <td valign="top">
			                <p>
			                    <em>National Statistics Office (NSO)</em>
			                </p>
			            </td>
			            <td valign="top">
			                <p>
			                    <em>Documentation of the study</em>
			                </p>
			            </td>
			        </tr>
			        <tr>
			            <td valign="top">
			                <p>
			                    <em>International Household Survey Network (IHSN) </em>
			                </p>
			            </td>
			            <td valign="top">
			                <p>
			                    <em>Review of the metadata</em>
			                </p>
			            </td>
			        </tr>
			    </tbody>
			</table>
		    </td>
		</tr>
		<tr>
		    <td valign="top">
			<p>
			    Date of Production
			</p>
		    </td>
		    <td valign="top">
			<p>
			    This is the date (in ISO format YYYY-MM-DD) the DDI document was produced (not distributed or archived). This date will be automatically imputed when you save the file.
			</p>
		    </td>
		</tr>
		<tr>
		    <td valign="top">
			<p>
			    DDI Document Version
			</p>
		    </td>
		    <td valign="top">
			<p>
			    Documenting a dataset is not a trivial exercise. Producing "perfect" metadata is probably impossible. It may therefore happen that, having
			    identified errors in a DDI document or having received suggestions for improvement, you decide to modify the Document even after a first
			    version has been disseminated. This element is used to identify and describe the current version of the document. It is good practice to
			    provide a version number (and date), and information on what distinguishes this version from the previous one(s) if relevant.
			</p>
			<p>
			    Example:
			</p>
			<p>
			    <em>Version 1.1 (July 2006). This version is identical to version 1.0, except for the section on Data Appraisal which was updated.</em>
			</p>
		    </td>
		</tr>
		<tr>
		    <td valign="top">
			<p>
			    DDI Document ID Number
			</p>
		    </td>
		    <td valign="top">
			<p>
			    The ID number of a DDI document is a unique number that is used to identify this DDI file. Define and use a consistent scheme to use. Such
			    an ID could be constructed as follows: DDI-country-producer-survey-year where
			</p>
			<ul>
			<li><em>country</em> is the 3-letter ISO country abbreviation</li>
			<li><em>producer</em> is the abbreviation of the producing agency</li>
			<li><em>survey</em> is the survey abbreviation</li>
			<li><em>year</em> is the reference year (or the year the survey started)</li>
			<li>DDI document version number</li>
			<ul>
			<p>
			    Example:
			</p>
			<p>
			    <em>
			        The DDI file related to the Demographic and Health Survey documented by staff from the Uganda Bureau of Statistics in 2005 would have the following ID:
			    </em>
			</p>
			<p>
			    <em>DDI-UGA-UBOS-DHS-2005-v01. </em>
			    <em>If the same survey is documented by a staff from the IHSN, this would be DDI-UGA-IHSN-DHS-205-v01.</em>
			</p>
		    </td>
		</tr>
	    </tbody>
	</table>	


