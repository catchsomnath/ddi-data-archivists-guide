================
Completing metadata
================

The IHSN Toolkit (version 1.n) makes use of the Data Documentation Initiative (DDI Version 2) and the Dublin Core (DCMI version X) metadata standards. 

A thorough completion of the DDI and DCMI elements will significantly raise the value of the archiving work by providing users with the necessary information to put the study into its proper context and to understand its purpose. 

The DDI requires completion of the following sections: Document Description, Study Description, Data Files Description, Variables Description, and External Resources Description. Recommendations for each field included in the IHSN template are provided below. 

.. image:: images/recommend.png

Overall recommendations:

*	As an archivist, you may need to seek assistance from key experts involved in some of the technical aspects of the survey. 
*	As a general rule, avoid using ALL CAPS when you fill DDI fields. Also, check the spelling of all entries. The Toolkit does not provide (yet) an automatic spell checker.
*	Some of the examples below present an optimal documentation of some fields. In many cases, for past surveys, you will not find such detailed information. Try to provide as much detail as possible. For future surveys, the information should be compiled and provided during the whole life cycle of the survey. This will ensure that the best possible documentation is available at completion of that survey.

**5.1.	Good practices for completing the Document Description**

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



**5.2.	Good practices for completing the Study Description**

In the DDI standard, the Study Description is the section that contains all elements needed to describe the study itself (investigators, dates and methods, scope and coverage, etc.) 

.. raw:: html

		<table border="1" cellpadding="0" cellspacing="0">
		<tbody>
        <tr>
            <td colspan="2" valign="top">
                <p>
                    <strong>Identification</strong>
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Title
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
                    The title will in most cases be identical to the Document Title (see above).
                </p>
                <p>
                    Examples: <em>National Household Budget Survey 2002-2003</em>
                </p>
                <p>
                    <em> Popstan Multiple Indicator Cluster Survey 2002</em>
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Subtitle
                </p>
            </td>
            <td valign="top">
                <p>
                    Subtitle is optional and rarely used. A subtitle can be used to add information usually associated with a sequential qualifier for a
                    survey.
                </p>
                <p>
                    <em>Example: Title: Welfare Monitoring Survey 2007</em>
                </p>
                <p>
                    <em> Subtitle: Fifth round</em>
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Abbreviation
                </p>
            </td>
            <td valign="top">
                <p>
                    The abbreviation of a survey is usually the first letter of each word of the titled survey. The survey reference year(s) may be included.
                </p>
                <p>
                    Examples:
                </p>
                <ul>
                    <li>
                        <em>DHS 2000 for "Demographic and Health Survey 2005"</em>
                    </li>
                    <li>
                        <em>HIES 2002-2003 for "Household Income and Expenditure Survey 2003"</em>
                    </li>
                </ul>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Study type
                </p>
            </td>
            <td valign="top">
                <p>
                    The study type or <em>survey type</em> is the broad category defining the survey. This item has a controlled vocabulary (you may customize
                    the IHSN template to adjust this controlled vocabulary if needed).
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Series information
                </p>
            </td>
            <td valign="top">
                <p>
                    A survey may be repeated at regular intervals (such as an annual labour force survey), or be part of an international survey program (such
                    as the MICS, CWIQ, DHS, LSMS and others). The Series information is a description of this "collection" of surveys. A brief description of
                    the characteristics of the survey, including when it started, how many rounds were already implemented, and who is in charge would be
                    provided here. If the survey does not belong to a series, leave this field empty.
                </p>
                <p>
                    <em> </em>
                </p>
                <p>
                    Example:
                </p>
                <p>
                    <em>
                        The Multiple Indicator Cluster Survey, Round 3 (MICS3) is the third round of MICS surveys, previously conducted around 1995 (MICS1) and
                        2000 (MICS2). MICS surveys are designed by UNICEF, and implemented by national agencies in participating countries. MICS was designed
                        to monitor various indicators identified at the World Summit for Children and the Millennium Development Goals.
                        <br/>
                        Many questions and indicators in MICS3 are consistent and compatible with the prior round of MICS (MICS2) but less so with MICS1,
                        although there have been a number of changes in definition of indicators between rounds.
                    </em>
                </p>
                <p>
                    <em>Round 1 covered X countries, round 2 covered Y countries, and Round Z covered N countries. </em>
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Translated title
                </p>
            </td>
            <td valign="top">
                <p>
                    In countries with more than one official language, a translation of the title may be provided. Likewise, the translated title may simply be
                    a translation into English from a country’s own language. Special characters should be properly displayed (such as accents and other stress
                    marks or different alphabets).
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    ID Number
                </p>
                <p>
                    <em> </em>
                </p>
            </td>
            <td valign="top">
                <p>
                    The ID number of a dataset is a unique number that is used to identify a particular survey. Define and use a consistent scheme to use. Such
                    an ID could be constructed as follows: country-producer-survey-year-version where
                </p>
                <ul>
                    <li><em>country</em> is the 3-letter ISO country abbreviation</li>
					<li><em>producer</em> is the abbreviation of the producing agency</li>
					<li><em>survey</em> is the survey abbreviation</li>
					<li><em>year</em> is the reference year (or the year the survey started)</li>
					<li><em>version</em> is the number dataset version number (see Version Description below)</li>
                </ul>
                <p>
                    Example:
                </p>
                <p>
                    <em>The Demographic and Health Survey implemented by the Uganda Bureau of Statistics in 2005 could have the following ID: </em>
                </p>
                <p>
                    <em>UGA-UBOS-DHS-2005-v01. </em>
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="2" valign="top">
                <p>
                    <strong>Version</strong>
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Description
                </p>
            </td>
            <td valign="top">
                <p>
                    The version description should contain a version number followed by a version label. The version number should follow a standard convention
                    to be adopted by the institute. We recommend that larger series be defined by a number to the left of a decimal and iterations of the same
                    series by a sequential number that identifies the release. Larger series will typically include (0) the raw, unedited dataset; (1) the
                    edited dataset, non anonymized, for internal use at the data producing agency; and (2) the edited dataset, prepared for dissemination to
                    secondary users (possibly anonymized).
                </p>
                <p>
                    Examples:
                </p>
                <ul>
                    <li>
                        <em>v0.1: Basic raw data, obtained from data entry (before editing).</em>
                    </li>
                    <li>
                        <em>v1.2: Edited data, second version, for internal use only.</em>
                    </li>
                    <li>
                        <em>v2.1: Edited, anonymous dataset for public distribution.</em>
                    </li>
                </ul>
                <p>
                    A brief description of the version should follow the numerical identification.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Production date
                </p>
            </td>
            <td valign="top">
                <p>
                    This is the date in ISO format (yyyy-mm-dd) of actual and final production of the data. Production dates of all versions should be
                    carefully tracked. Provide at least the month and year. Use the calendar icon in the Metadata editor to assure that the date selected is in
                    compliance with the ISO format.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Notes
                </p>
            </td>
            <td valign="top">
                <p>
                    Version notes should provide a brief report on the changes made through the versioning process. The note should indicate how this version
                    differs from other versions of the same dataset.
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="2" valign="top">
                <p>
                    <strong>Overview</strong>
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Abstract
                </p>
            </td>
            <td valign="top">
                <p>
                    The abstract should provide a clear summary of the purposes, objectives and content of the survey. It should be written by a researcher or
                    survey statistician aware of the survey.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Kind of data
                </p>
            </td>
            <td valign="top">
                <p>
                    This field is a broad classification of the data and it is associated with a drop down box providing controlled vocabulary. That controlled
                    vocabulary includes 9 items but is not limited to them.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Unit of analysis
                </p>
            </td>
            <td valign="top">
                <p>
                    A survey could have various units of analysis. These are fairly standard and are usually:
                </p>
                <ul>
                    <li>Household (household survey, census)</li>
					<li>Person (household survey, census)</li>
					<li>Enterprise (enterprise survey)</li>
					<li>Commodity (household survey, price survey)</li>
					<li>Plots of land (agricultural survey)</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td colspan="2" valign="top">
                <p>
                    <strong>Scope</strong>
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Description of scope
                </p>
            </td>
            <td valign="top">
                <p>
                    The scope is a description of the themes covered by the survey. It can be viewed as a summary of the modules that are included in the
                    questionnaire. The scope does not deal with geographic coverage.
                </p>
                <p>
                    Example:
                </p>
                <p>
                    <em>The scope of the Multiple Indicator Cluster Survey includes:</em>
                </p>
                <ul>
                    <li>
                        <em>
                            HOUSEHOLD: Household characteristics, household listing, orphaned and vulnerable children, education, child labour, water and
                            sanitation, household use of insecticide treated mosquito nets, and salt iodization, with optional modules for child discipline,
                            child disability, maternal mortality and security of tenure and durability of housing.
                        </em>
                    </li>
                    <li>
                        <em>
                            WOMEN: Women's characteristics, child mortality, tetanus toxoid, maternal and newborn health, marriage, polygyny, female genital
                            cutting, contraception, and HIV/AIDS knowledge, with optional modules for unmet need, domestic violence, and sexual behavior.
                        </em>
                    </li>
                    <li>
                        <em>
                            CHILDREN: Children's characteristics, birth registration and early learning, vitamin A, breastfeeding, care of illness, malaria,
                            immunization, and anthropometry, with an optional module for child development.
                        </em>
                    </li>
                </ul>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Topic classifications
                </p>
            </td>
            <td valign="top">
                <p>
                    A topic classification facilitates referencing and searches in electronic survey catalogs. Topics should be selected from a standard
                    thesaurus, preferably an international, multilingual thesaurus. The IHSN recommends the use of the thesaurus used by the Council of
                    European Social Science Data Archives (CESSDA). The CESSDA thesaurus has been introduced as a controlled vocabulary in the IHSN Study
                    Template version 1.3 (available at <a href="http://www.surveynetwork.org/toolkit">www.surveynetwork.org/toolkit</a>).
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Keywords
                </p>
                <p>
                    <em> </em>
                </p>
            </td>
            <td valign="top">
                <p>
                    Keywords summarize the content or subject matter of the survey. As topic classifications, these are used to facilitate referencing and
                    searches in electronic survey catalogs. Keywords should be selected from a standard thesaurus, preferably an international, multilingual
                    thesaurus. Entering a list of keywords is tedious. This option is provided for advanced users only.
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="2" valign="top">
                <p>
                    <strong>Coverage</strong>
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Country
                </p>
                <p>
                    <em> </em>
                </p>
            </td>
            <td valign="top">
                <p>
                    Enter the country name, even in cases where the survey did not cover the entire country. In the field "Abbreviation", we recommend that you
                    enter the 3-letter ISO code of the country. If the dataset you document covers more than one country, enter all in separate rows.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Geographic coverage
                </p>
            </td>
            <td valign="top">
                <p>
                    This filed aims at describing at what geographic level the data are representative. Typical entries will be "National coverage", "Urban (or rural) areas only", "state of...", "Capital city" etc.
                </p>
                <p>
                    Note that we do not describe here where the data was collected. For example, as sample survey could be declared as "national coverage" even
                    in cases where some districts where not included in the sample, as long as the sampling strategy was such that the representativity is
                    national.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Universe
                </p>
            </td>
            <td valign="top">
                <p>
                    We are interested here in the survey universe (not the universe of particular sections of the questionnaires or variables), i.e. in the
                    identification of the population of interest in the survey. The universe will rarely be the entire population of the country. Sample
                    household surveys, for example, usually do not cover homeless, nomads, diplomats, community households. Population censuses do not cover
                    diplomats. Try to provide the most detailed information possible on the population covered by the survey/census.
                </p>
                <p>
                    Example:
                </p>
                <p>
                    <em>
                        The survey covered all de jure household members (usual residents), all women aged 15-49 years resident in the household, and all
                        children aged 0-4 years (under age 5) resident in the household.
                    </em>
                </p>
            </td>
        </tr>
		</tbody>
		</table>


.. raw:: html
		
		<table border="1" cellpadding="0" cellspacing="0">
    	<tbody>
        <tr>
            <td colspan="2" valign="top">
                <p>
                    <strong>Producers and Sponsors</strong>
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Primary investigator
                </p>
            </td>
            <td valign="top">
                <p>
                    The primary investigator will in most cases be an institution, but could also be an individual in the case of small-scale academic surveys.
                    The two fields to be completed are the Name and the Affiliation fields. Generally, in a survey, the Primary Investigator will be the
                    institution implementing the survey. If various institutions have been equally involved as main investigators, then all should be
                    mentioned. This only includes the agencies responsible for the implementation of the survey, not its funding or technical assistance. The
                    order in which they are listed is discretionary. It can be alphabetic or by significance of contribution. Individual persons can also be
                    mentioned. If persons are mentioned use the appropriate format of Surname, First name.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Other producers
                </p>
            </td>
            <td valign="top">
                <p>
                    This field is provided to list other interested parties and persons that have played a significant but not the leading technical role in
                    implementing and producing the data. The specific fields to be competed are: Name of the organization, Abbreviation, Affiliation and Role.
                    If any of the fields are not applicable these can be left blank. The abbreviations should be the official abbreviation of the organization.
                    The role should be a short and succinct phrase or description on the specific assistance provided by the organization in order to produce
                    the data. The roles should be standard vocabulary such as:
                </p>
                <ul>
                    <li>[Technical assistance in] questionnaire design</li>
                <li>[Technical assistance in] sampling methodology / selection</li>
                <li>[Technical assistance in] data collection</li>
                <li>[Technical assistance in] data processing</li>
                <li>[Technical assistance in] data analysis</li>
                </ul>
                <p>
                    Do not include here the financial sponsors.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Funding
                </p>
            </td>
            <td valign="top">
                <p>
                    List the organizations (national or international) that have contributed, in cash or in kind, to the financing of the survey. The
                    government institution that has provided funding should not be forgotten.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Other acknowledgements
                </p>
            </td>
            <td valign="top">
                <p>
                    This optional field can be used to acknowledge any other people and institutions that have in some form contributed to the survey.
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="2" valign="top">
                <p>
                    <strong>Sampling</strong>
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Sampling procedure
                </p>
            </td>
            <td valign="top">
                <p>
                    This field only applies to sample surveys. Information on sampling procedure is crucial (although not applicable for censuses and administrative datasets). This section should include summary information that includes though is not limited to:
                </p>
                <ul>
                    <li>Sample size</li>
					<li>Selection process (e.g., probability proportional to size or over sampling)</li>
					<li>Stratification (implicit and explicit)</li>
					<li>Stages of sample selection</li>
					<li>Design omissions in the sample</li>
					<li>Level of representation</li>
					<li>Strategy for absent respondents/not found/refusals (replacement or not)</li>
					<li>Sample frame used, and listing exercise conducted to update it</li>
                </ul>
                <p>
                    It is useful also to indicate here what variables in the data files identify the various levels of stratification and the primary sample
                    unit. These are crucial to the data users who want to properly account for the sampling design in their analyses and calculations of
                    sampling errors.
                </p>
                <p>
                    This section accepts only text format; formulae cannot be entered. In most cases, technical documents will exist that describe the sampling
                    strategy in detail. In such cases, include here a reference (title/author/date) to this document, and make sure that the document is
                    provided in the External Resources.
                </p>
                <p>
                    Example:
                </p>
                <p>
                    <em>
                        5000 households were selected for the sample. Of these, 4996 were occupied households and 4811 were successfully interviewed for a
                        response rate of 96.3%. Within these households, 7815 eligible women aged 15-49 were identified for interview, of which 7505 were
                        successfully interviewed (response rate 96.0%), and 3242 children aged 0-4 were identified for whom the mother or caretaker was
                        successfully interviewed for 3167 children (response rate 97.7%). These give overall response rates (household response rate times
                        individual response rate) for the women's interview of 92.5% and for the children's interview of 94.1%.
                    </em>
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Deviation from sample design
                </p>
            </td>
            <td valign="top">
                <p>
                    This field only applies to sample surveys.
                </p>
                <p>
                    Sometimes the reality of the field requires a deviation from the sampling design (for example due to difficulty to access to zones due to
                    weather problems, political instability, etc). If for any reason, the sample design has deviated, this should be reported here.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Response rates
                </p>
            </td>
            <td valign="top">
                <p>
                    Response rate provides that percentage of households (or other sample unit) that participated in the survey based on the original sample
                    size. Omissions may occur due to refusal to participate, impossibility to locate the respondent, or other. Sometimes, a household may be
                    replaced by another by design. Check that the information provided here is consistent with the sample size indicated in the "Sampling
                    procedure field" and the number of records found in the dataset (for example, if the sample design mention a sample of 5,000 households and
                    the data on contain data on 4,500 households, the response rate should not be 100 percent).
                </p>
                <p>
                    Provide if possible the response rates by stratum. If information is available on the causes of non-response (refusal/not found/other),
                    provide this information as well.
                </p>
                <p>
                    This field can also in some cases be used to describe non-responses in population censuses.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Weighting
                </p>
            </td>
            <td valign="top">
                <p>
                    This field only applies to sample surveys.
                </p>
                <p>
                    Provide here the list of variables used as weighting coefficient. If more than one variable is a weighting variable, describe how these
                    variables differ from each other and what the purpose of each one of them is.
                </p>
                <p>
                    Example:
                </p>
                <p>
                    <em>Sample weights were calculated for each of the data files.</em>
                </p>
                <p>
                    <em>
                        Sample weights for the household data were computed as the inverse of the probability of selection of the household, computed at the
                        sampling domain level (urban/rural within each region). The household weights were adjusted for non-response at the domain level, and
                        were then normalized by a constant factor so that the total weighted number of households equals the total unweighted number of
                        households. The household weight variable is called HHWEIGHT and is used with the HH data and the HL data.
                    </em>
                </p>
                <p>
                    <em>
                        Sample weights for the women's data used the un-normalized household weights, adjusted for non-response for the women's questionnaire,
                        and were then normalized by a constant factor so that the total weighted number of women's cases equals the total unweighted number of
                        women's cases.
                    </em>
                </p>
                <p>
                    <em>
                        Sample weights for the children's data followed the same approach as the women's and used the un-normalized household weights, adjusted
                        for non-response for the children's questionnaire, and were then normalized by a constant factor so that the total weighted number of
                        children's cases equals the total unweighted number of children's cases.
                    </em>
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="2" valign="top">
                <p>
                    <strong>Data Collection</strong>
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Dates of data collection
                </p>
                <p>
                    <em> </em>
                </p>
            </td>
            <td valign="top">
                <p>
                    Enter the dates (at least month and year) of the start and end of the data collection. They should be in the standard ISO format of
                    YYYY-MM-DD.
                </p>
                <p>
                    In some cases, data collection for a same survey can be conducted in waves. In such case, you should enter the start and end date of each
                    wave separately, and identify each wave in the "cycle" field.
                </p>
            </td>
        </tr>
    	</tbody>
		</table>

.. raw:: html

		<table border="1" cellpadding="0" cellspacing="0">
		<tbody>
        <tr>
            <td valign="top">
                <p>
                    Time period
                </p>
            </td>
            <td valign="top">
                <p>
                    This field will usually be left empty. Time period differs from the dates of collection as they represent the period for which the data
                    collected are applicable or relevant.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Mode of data collection
                </p>
            </td>
            <td valign="top">
                <p>
                    The mode of data collection is the manner in which the interview was conducted or information was gathered. This field is a controlled
                    vocabulary field. Use the drop-down button in the Toolkit to select one option. In most cases, the response will be "face to face
                    interview". But for some specific kinds of datasets, such as for example data on rain falls, the response will be different.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Notes on data collection
                </p>
            </td>
            <td valign="top">
                <p>
                    This element is provided in order to document any specific observations, occurrences or events during data collection. Consider stating such items like:
                </p>
                <ul>
                    <li>Was a training of enumerators held? (elaborate)</li>
					<li>Any events that could have a bearing on the data quality?</li>
					<li>How long did an interview take on average?</li>
					<li>Was there a process of negotiation between households, the community and the implementing agency?</li>
					<li>Are anecdotal events recorded?</li>
					<li>Have the field teams contributed by supplying information on issues and occurrences during data collection?</li>
					<li>In what language was the interview conducted?</li>
					<li>Was a pilot survey conducted?</li>
					<li>Were there any corrective actions taken by management when problems occurred in the field?</li>
                </ul>
                <p>
                    Example:
                </p>
                <p>
                    <em>
                        The pre-test for the survey took place from August 15, 2006 - August 25, 2006 and included 14 interviewers who would later become
                        supervisors for the main survey.
                    </em>
                </p>
                <p>
                    <em>
                        Each interviewing team comprised of 3-4 female interviewers (no male interviewers were used due to the sensitivity of the subject
                        matter), together with a field editor and a supervisor and a driver. A total of 52 interviewers, 14 supervisors and 14 field editors
                        were used. Data collection took place over a period of about 6 weeks from September 2, 2006 until October 17, 2006. Interviewing took
                        place everyday throughout the fieldwork period, although interviewing teams were permitted to take one day off per week.
                    </em>
                </p>
                <p>
                    <em>
                        Interviews averaged 35 minutes for the household questionnaire (excluding salt testing), 23 minutes for the women's questionnaire, and
                        27 for the under five children's questionnaire (excluding the anthropometry). Interviews were conducted primarily in English and
                        Mumbo-jumbo, but occasionally used local translation in double-Dutch, when the respondent did not speak English or Mumbo-jumbo.
                    </em>
                </p>
                <p>
                    <em>
                        Six staff members of GenCenStat provided overall fieldwork coordination and supervision. The overall field coordinator was Mrs. Doe.
                    </em>
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="2" valign="top">
                <p>
                    <strong>Data Processing</strong>
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Questionnaires
                </p>
            </td>
            <td valign="top">
                <p>
                    This element is provided to describe the questionnaire(s) used for the data collection. The following should be mentioned:
                </p>
                <ul type="disc">
                    <li>
                        List of questionnaires and short description of each (all questionnaires must be provided as External Resources)
                    </li>
                    <li>
                        In what language were the questionnaires published?
                    </li>
                    <li>
                        Information on the questionnaire design process (based on a previous questionnaire, based on a standard model questionnaire, review by
                        stakeholders). If a document was compiled that contains the comments provided by the stakeholders on the draft questionnaire, or a
                        report prepared on the questionnaire testing, a reference to these documents should be provided here and the documents should be
                        provided as External Resources.
                    </li>
                </ul>
                <p>
                    Example
                </p>
                <p>
                    <em>
                        The questionnaires for the Generic MICS were structured questionnaires based on the MICS3 Model Questionnaire with some modifications
                        and additions. A household questionnaire was administered in each household, which collected various information on household members
                        including sex, age, relationship, and orphanhood status. The household questionnaire includes household characteristics, support to
                        orphaned and vulnerable children, education, child labour, water and sanitation, household use of insecticide treated mosquito nets,
                        and salt iodization, with optional modules for child discipline, child disability, maternal mortality and security of tenure and
                        durability of housing.
                    </em>
                </p>
                <p>
                    <em>
                        In addition to a household questionnaire, questionnaires were administered in each household for women age 15-49 and children under age
                        five. For children, the questionnaire was administered to the mother or caretaker of the child.
                    </em>
                </p>
                <p>
                    <em>
                        The women's questionnaire include women's characteristics, child mortality, tetanus toxoid, maternal and newborn health, marriage,
                        polygyny, female genital cutting, contraception, and HIV/AIDS knowledge, with optional modules for unmet need, domestic violence, and
                        sexual behavior.
                    </em>
                </p>
                <p>
                    <em>
                        The children's questionnaire includes children's characteristics, birth registration and early learning, vitamin A, breastfeeding, care
                        of illness, malaria, immunization, and anthropometry, with an optional module for child development.
                    </em>
                </p>
                <p>
                    <em>
                        The questionnaires were developed in English from the MICS3 Model Questionnaires, and were translated into Mumbo-jumbo. After an
                        initial review the questionnaires were translated back into English by an independent translator with no prior knowledge of the survey.
                        The back translation from the Mumbo-jumbo version was independently reviewed and compared to the English original. Differences in
                        translation were reviewed and resolved in collaboration with the original translators.
                    </em>
                </p>
                <p>
                    <em>The English and Mumbo-jumbo questionnaires were both piloted as part of the survey pretest.</em>
                </p>
                <p>
                    <em>All questionnaires and modules are provided as external resources.</em>
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Data collectors
                </p>
            </td>
            <td valign="top">
                <p>
                    This element is provided in order to record information regarding the persons and/or agencies that took charge of the data collection. This
                    element includes 3 fields: Name, Abbreviation and the Affiliation. In most cases, we will record here the name of the agency, not the name
                    of interviewers. Only in the case of very small-scale surveys, with a very limited number of interviewers, the name of person will be
                    included as well. The field Affiliation is optional and not relevant in all cases.
                </p>
                <p>
                    Example:
                </p>
                <p>
                    <em>Name: Central Statistics Office</em>
                </p>
                <p>
                    <em>Abbreviation: CSO</em>
                </p>
                <p>
                    <em> Affiliation: Ministry of Planning </em>
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Supervision
                </p>
            </td>
            <td valign="top">
                <p>
                    This element will provide information on the oversight of the data collection. The following should be considered:
                </p>
                <ul>
                    <li>Were the enumerators organized in teams that included a controller and a supervisor? With how many controllers/supervisors per interviewer?</li>
                <li>What were the main roles of the controllers/supervisors?</li>
                <li>Were there visits to the field by upper management? How often?</li>
                </ul>
                <p>
                    Example:
                </p>
                <p>
                    <em>
                        Interviewing was conducted by teams of interviewers. Each interviewing team comprised of 3-4 female interviewers, a field editor and a
                        supervisor, and a driver. Each team used a 4 wheel drive vehicle to travel from cluster to cluster (and where necessary within
                        cluster).
                    </em>
                </p>
                <p>
                    <em>
                        The role of the supervisor was to coordinator field data collection activities, including management of the field teams, supplies and
                        equipment, finances, maps and listings, coordinate with local authorities concerning the survey plan and make arrangements for
                        accommodation and travel. Additionally, the field supervisor assigned the work to the interviewers, spot checked work, maintained field
                        control documents, and sent completed questionnaires and progress reports to the central office.
                    </em>
                </p>
                <p>
                    <em>
                        The field editor was responsible for reviewing each questionnaire at the end of the day, checking for missed questions, skip errors,
                        fields incorrectly completed, and checking for inconsistencies in the data. The field editor also observed interviews and conducted
                        review sessions with interviewers.
                    </em>
                </p>
                <p>
                    <em>
                        Responsibilities of the supervisors and field editors are described in the Instructions for Supervisors and Field Editors, together
                        with the different field controls that were in place to control the quality of the fieldwork.
                    </em>
                </p>
                <p>
                    <em>
                        Field visits were also made by a team of central staff on a periodic basis during fieldwork. The senior staff of GenCenStat also made 3
                        visits to field teams to provide support and to review progress.
                    </em>
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="2" valign="top">
                <p>
                    <strong>Data Processing</strong>
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Data editing
                </p>
            </td>
            <td valign="top">
                <p>
                    The data editing should contain information on how the data was treated or controlled for in terms of consistency and coherence. This item
                    does not concern the data entry phase but only the editing of data whether manual or automatic.
                </p>
                <p>
                    · Was a hot deck or a cold deck technique used to edit the data?
                </p>
                <p>
                    · Were corrections made automatically (by program), or by visual control of the questionnaire?
                </p>
                <ul>
                    <li>
                        What software was used?
                    </li>
                </ul>
                <p>
                    If materials are available (specifications for data editing, report on data editing, programs used for data editing), they should be listed
                    here and provided as external resources.
                </p>
                <p>
                    Example:
                </p>
                <p>
                    <em>Data editing took place at a number of stages throughout the processing, including:</em>
                </p>
                <ul>
                    <li>Office editing and coding</li>
					<li>During data entry</li>
					<li>Structure checking and completeness</li>
					<li>Secondary editing</li>
					<li>Structural checking of SPSS data files</li>
                </ul>
                <p>
                    <em>
                        Detailed documentation of the editing of data can be found in the "Data processing guidelines" document provided as an external
                        resource.
                    </em>
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Other processing
                </p>
            </td>
            <td valign="top">
                <p>
                    Use this field to provide as much information as possible on the data entry design. This includes such details as:
                </p>
                <ul>
                    <li>Mode of data entry (manual or by scanning, in the field/in regions/at headquarters)
                <li>Computer architecture (laptop computers in the field, desktop computers, scanners, PDA, other; indicate the number of computers used)
                
               
                    <li>
                        Software used
                    </li>
                    <li>
                        Use (and rate) of double data entry
                    </li>
            
                <li>Average productivity of data entry operators; number of data entry operators involved and their work schedule
              <ul>
                <p>
                    Information on tabulation and analysis can also be provided here.
                </p>
                <p>
                    All available materials (data entry/tabulation/analysis programs; reports on data entry) should be listed here and provided as external
                    resources.
                </p>
                <p>
                    Example:
                </p>
                <p>
                    <em>
                        Data were processed in clusters, with each cluster being processed as a complete unit through each stage of data processing. Each
                        cluster goes through the following steps:
                    </em>
                </p>
                <ul>
                    <li>Questionnaire reception</li>
					<li>Office editing and coding</li>
					<li>Data entry</li>
					<li>Structure and completeness checking</li>
					<li>Verification entry<</li>
					<li>Comparison of verification data</li>
					<li>Back up of raw data</li>
					<li>Secondary editing</li>
					<li>Edited data back up</li>
					After all clusters are processed, all data is concatenated together and then the following steps are completed for all data files:
					<li>Export to SPSS in 4 files (hh - household, hl - household members, wm - women, ch - children under </li>
					<li>Recoding of variables needed for analysis</li>
					<li>Adding of sample weights</li>
					<li>Calculation of wealth quintiles and merging into data</li>
					<li>Structural checking of SPSS files</li>
					<li>Data quality tabulations</li>
					<li>Production of analysis tabulations</li>
                </ul>
                
				<p>
                    <em>
                        Details of each of these steps can be found in the data processing documentation, data editing guidelines, data processing programs in
                        CSPro and SPSS, and tabulation guidelines.
                    </em>
                </p>
                <p>
                    <em>
                        Data entry was conducted by 12 data entry operators in tow shifts, supervised by 2 data entry supervisors, using a total of 7 computers
                        (6 data entry computers plus one supervisors’ computer). All data entry was conducted at the GenCenStat head office using manual data
                        entry. For data entry, CSPro version 2.6.007 was used with a highly structured data entry program, using system controlled approach
                        that controlled entry of each variable. All range checks and skips were controlled by the program and operators could not override
                        these. A limited set of consistency checks were also included in the data entry program. In addition, the calculation of anthropometric
                        Z-scores was also included in the data entry programs for use during analysis. Open-ended responses ("Other" answers) were not entered
                        or coded, except in rare circumstances where the response matched an existing code in the questionnaire.
                    </em>
                </p>
                <p>
                    <em>
                        Structure and completeness checking ensured that all questionnaires for the cluster had been entered, were structurally sound, and that
                        women's and children's questionnaires existed for each eligible woman and child.
                    </em>
                </p>
                <p>
                    <em>
                        100% verification of all variables was performed using independent verification, i.e. double entry of data, with separate comparison of
                        data followed by modification of one or both datasets to correct keying errors by original operators who first keyed the files.
                    </em>
                </p>
                <p>
                    <em>
                        After completion of all processing in CSPro, all individual cluster files were backed up before concatenating data together using the
                        CSPro file concatenate utility.
                    </em>
                </p>
                <p>
                    <em>
                        For tabulation and analysis SPSS versions 10.0 and 14.0 were used. Version 10.0 was originally used for all tabulation programs, except
                        for child mortality. Later version 14.0 was used for child mortality, data quality tabulations and other analysis activities.
                    </em>
                </p>
                <p>
                    <em>
                        After transferring all files to SPSS, certain variables were recoded for use as background characteristics in the tabulation of the
                        data, including grouping age, education, geographic areas as needed for analysis. In the process of recoding ages and dates some random
                        imputation of dates (within calculated constraints) was performed to handle missing or "don't know" ages or dates. Additionally, a
                        wealth (asset) index of household members was calculated using principal components analysis, based on household assets, and both the
                        score and quintiles were included in the datasets for use in tabulations.
                    </em>
                </p>
            </td>
        </tr>
    	</tbody>
		</table>

		<table border="1" cellpadding="0" cellspacing="0">
    	<tbody>
        <tr>
            <td colspan="2" valign="top">
                <p>
                    <strong>Data Appraisal</strong>
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Estimate of sampling error
                </p>
            </td>
            <td valign="top">
                <p>
                    For sampling surveys, it is good practice to calculate and publish sampling error. This field is used to provide information on these
                    calculations. This includes:
                </p>
                <ul>
                    <li>A list of ratios/indicators for which sampling errors were computed.</li>
					<li>Details regarding the software used for computing the sampling error, and reference to the programs used (to be provided as external resources) as the program used to perform the calculations.</li>
					<li>Reference to the reports or other document where the results can be found (to be provided as external resources).</li>
                </p>
                <p>
                    Example:
                </p>
                <p>
                    <em>
                        Estimates from a sample survey are affected by two types of errors: 1) non-sampling errors and 2) sampling errors. Non-sampling errors
                        are the results of mistakes made in the implementation of data collection and data processing. Numerous efforts were made during
                        implementation of the 2005-2006 MICS to minimize this type of error, however, non-sampling errors are impossible to avoid and difficult
                        to evaluate statistically.
                    </em>
                </p>
                <p>
                    <em>
                        If the sample of respondents had been a simple random sample, it would have been possible to use straightforward formulae for
                        calculating sampling errors. However, the 2005-2006 MICS sample is the result of a multi-stage stratified design, and consequently
                        needs to use more complex formulae. The SPSS complex samples module has been used to calculate sampling errors for the 2005-2006 MICS.
                        This module uses the Taylor linearization method of variance estimation for survey estimates that are means or proportions. This method
                        is documented in the SPSS file CSDescriptives.pdf found under the Help, Algorithms options in SPSS.
                    </em>
                </p>
                <p>
                    <em>
                        Sampling errors have been calculated for a select set of statistics (all of which are proportions due to the limitations of the Taylor
                        linearization method) for the national sample, urban and rural areas, and for each of the five regions. For each statistic, the
                        estimate, its standard error, the coefficient of variation (or relative error -- the ratio between the standard error and the
                        estimate), the design effect, and the square root design effect (DEFT -- the ratio between the standard error using the given sample
                        design and the standard error that would result if a simple random sample had been used), as well as the 95 percent confidence
                        intervals (+/-2 standard errors).
                    </em>
                </p>
                <p>
                    <em>
                        Details of the sampling errors are presented in the sampling errors appendix to the report and in the sampling errors table presented
                        in the external resources.
                    </em>
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Other forms data appraisal
                </p>
            </td>
            <td valign="top">
                <p>
                    This section can be used to report any other action taken to assess the reliability of the data, or any observations regarding data
                    quality. This item can include:
                </p>
                <ul>
                    <li>For a population census, information on the post enumeration survey (a report should be provided in external resources and mentioned here).
                    <li> For any survey/census, a comparison with data from another source.Etc. </li>
                    
				</ul>
                <p>
                    Example:
                </p>
                <p>
                    <em>A series of data quality tables and graphs are available to review the quality of the data and include the following:</em>
                </p>
                <ul>
                    <li><em>Age distribution of the household population</em></li>
					<li><em>Age distribution of eligible women and interviewed women</em></li>
					<li><em>Age distribution of eligible children and children for whom the mother or caretaker was interviewed</em></li>
					<li><em>Age distribution of children under age 5 by 3 month groups</em></li>
					<li><em>Age and period ratios at boundaries of eligibility</em></li>
					<li><em>Percent of observations with missing information on selected variables</em></li>
					<li><em>Presence of mother in the household and person interviewed for the under 5 questionnaire</em></li>
					<li><em>School attendance by single year age</em></li>
					<li><em>Sex ratio at birth among children ever born, surviving and dead by age of respondent</em></li>
					<li><em>Distribution of women by time since last birth</em></li>
					<li><em>Scatter plot of weight by height, weight by age and height by age</em></li>
					<li><em>Graph of male and female population by single years of age</em></li>
					<li><em>Population pyramid</em></li>
                </ul>
                <p>
                    <em> </em>
                </p>
                <p>
                    <em>
                        The results of each of these data quality tables are shown in the appendix of the final report and are also given in the external
                        resources section.
                    </em>
                </p>
                <p>
                    <em> </em>
                </p>
                <p>
                    <em>
                        The general rule for presentation of missing data in the final report tabulations is that a column is presented for missing data if the
                        percentage of cases with missing data is 1% or more. Cases with missing data on the background characteristics (e.g. education) are
                        included in the tables, but the missing data rows are suppressed and noted at the bottom of the tables in the report (not in the SPSS
                        output, however).
                    </em>
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="2" valign="top">
                <p>
                    <strong>Data Access</strong>
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Access authority
                </p>
            </td>
            <td valign="top">
                <p>
                    This section is composed of various sections: Name-Affiliation-email-URI. This information provides the contact person or entity to gain authority to access the data. It is advisable to use a generic email contact such as <a href="mailto:data@popstatsoffice.org">data@popstatsoffice.org</a> whenever possible to avoid tying access to a particular individual whose functions may change over time.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Confidentiality
                </p>
            </td>
            <td valign="top">
                <p>
                    If the dataset is not anonymized, we may indicate here what Affidavit of Confidentiality must be signed before the data can be accessed.
                    Another option is to include this information in the next element (Access conditions). If there is no confidentiality issue, this field can
                    be left blank.
                </p>
                <p>
                    An example of statement could be the following:
                </p>
                <p>
                    <em>Confidentiality of respondents is guaranteed by Articles N to NN of the National Statistics Act of [date]. </em>
                </p>
                <p>
                    <em>Before being granted access to the dataset, all users have to formally agree: </em>
                </p>
                <p>
                    <em>1. </em>
                    <em>To make no copies of any files or portions of files to which s/he is granted access except those authorized by the </em>
                    <em>data depositor</em>
                    <em>. </em>
                </p>
                <p>
                    <em>2. </em>
                    <em>
                        Not to use any technique in an attempt to learn the identity of any person, establishment, or sampling unit not identified on public
                        use data files.
                    </em>
                </p>
                <p>
                    <em>3. </em>
                    <em>
                        To hold in strictest confidence the identification of any establishment or individual that may be inadvertently revealed in any
                        documents or discussion, or analysis. Such inadvertent identification revealed in her/his analysis will be immediately brought to the
                        attention of the data depositor.
                    </em>
                </p>
                <p>
                    This statement does not replace a more comprehensive data agreement (see Access condition).
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Access conditions
                </p>
            </td>
            <td valign="top">
                <p>
                    Each dataset should have an "Access policy" attached to it. The IHSN recommends three levels of accessibility:
                </p>
                <ul type="disc">
                    <li>
                        Public use files, accessible to all
                    </li>
                    <li>
                        Licensed datasets, accessible under conditions
                    </li>
                    <li>
                        Datasets only accessible in a data enclave, for the most sensitive and confidential data.
                    </li>
                </ul>
                <p>
                    The IHSN has formulated standard, generic policies and access forms for each one of these three levels (which each country can customize to
                    its specific needs). One of the three policies may be copy/pasted in this field once it has been edited as needed and approved by the
                    appropriate authority. Before you fill this field, a decision has to be made by the management of the data depositor agency. Avoid writing
                    a specific statement for each dataset.
                </p>
                <p>
                    If the access policy is subject to regular changes, you should enter here a URL where the user will find detailed information on access
                    policy which applies to this specific dataset. If the datasets are sold, pricing information should also be provided on a website instead
                    of being entered here.
                </p>
                <p>
                    If the access policy is not subject to regular changes, you may enter more detailed information here. For a public use file for example,
                    you could enter information like:
                </p>
                <p>
                    <em>
                        The dataset has been anonymized and is available as a Public Use Dataset. It is accessible to all for statistical and research purposes
                        only, under the following terms and conditions:
                    </em>
                </p>
                <ul>
                    <li>The data and other materials will not be redistributed or sold to other individuals, institutions, or organizations without the written agreement of the [National Data Archive].
                    <li>The data will be used for statistical and scientific research purposes only. They will be used solely for reporting of aggregated information, and not for investigation of specific individuals or organizations.
                    <li>No attempt will be made to re-identify respondents, and no use will be made of the identity of any person or establishment discovered inadvertently. Any such discovery would immediately be reported to the [National Data Archive].
                    <li>No attempt will be made to produce links among datasets provided by the [National Data Archive], or among data from the [National Data Archive] and other datasets that could identify individuals or organizations.
                    <li>Any books, articles, conference papers, theses, dissertations, reports, or other publications that employ data obtained from the [National Data Archive] will cite the source of data in accordance with the Citation Requirement provided with each dataset.
                    <li>An electronic copy of all reports and publications based on the requested data will be sent to the [National Data Archive]. </em>
					<li>The original collector of the data, the [National Data Archive], and the relevant funding agencies bear no responsibility for use of the data or for interpretations or inferences based upon such uses.
                    </em>
                    
                </li>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Citation requirements
                </p>
            </td>
            <td valign="top">
                <p>
                    Citation requirement is the way that the dataset should be referenced when cited in any publication. Every dataset should have a citation
                    requirement. This will guarantee that the data producer gets proper credit, and that analytical results can be linked to the proper version
                    of the dataset. The Access Policy should explicitly mention the obligation to comply with the citation requirement (in the example above,
                    see item 5). The citation should include at least the primary investigator, the name and abbreviation of the dataset, the reference year,
                    and the version number. Include also a website where the data or information on the data is made available by the official data depositor.
                </p>
                <p>
                    Example:
                </p>
                <p>
                    <em>
                        "National Statistics Office of Popstan, Multiple Indicators Cluster Survey 2000 (MICS 2000), Version 1.1 of the public use dataset
                        (April 2001), provided by the National Data Archive. www.nda_popstan.org"
                    </em>
                </p>
            </td>
        </tr>
        <tr>
            <td colspan="2" valign="top">
                <p>
                    <strong>Disclaimer and Copyright</strong>
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Disclaimer
                </p>
            </td>
            <td valign="top">
                <p>
                    A disclaimer limits the liability that the Statistics Office has regarding the use of the data. A standard legal statement should be used
                    for all datasets from a same agency. The IHSN recommends the following formulation:
                </p>
                <p>
                    <em>
                        The user of the data acknowledges that the original collector of the data, the authorized distributor of the data, and the relevant
                        funding agency bear no responsibility for use of the data or for interpretations or inferences based upon such uses.
                    </em>
                </p>
            </td>
        </tr>
    	</tbody>
		
.. raw:: html		
		
		</table>
		<table border="1" cellpadding="0" cellspacing="0">
    	<tbody>
        <tr>
            <td colspan="2" valign="top">
                <p>
                    <strong>Contacts</strong>
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Contact persons
                </p>
            </td>
            <td valign="top">
                <p>
                    Users of the data may need further clarification and information. This section may include the name-affiliation-email-URI of one or
                    multiple contact persons. Avoid putting the name of individuals. The information provided here should be valid for the long term. It is
                    therefore preferable to identify contact persons by a title. The same applies for the email field. Ideally, a "generic" email address
                    should be provided. It is easy to configure a mail server in such a way that all messages sent to the generic email address would be
                    automatically forwarded to some staff members.
                </p>
                <p>
                    Example:
                </p>
                <p>
                    <em>Name: Head, Data Processing Division</em>
                </p>
                <p>
                    <em>Affiliation: National Statistics Office</em>
                </p>
                <p>
                    <em>Email: dataproc@cso.org</em>
                </p>
                <p>
                    <em> </em>
                    <em>URI: </em>
                    <em><a href="http://www.cso.org/databank">www.cso.org/databank</a></em>
                    <em></em>
                </p>
            </td>
        </tr>
		</tbody>
		</table>



**5.3.	Good practices for completing the File Description**

The File Description is the DDI section that aims to provide a detailed description of each data file. The IHSN has selected six of the available DDI elements.

.. raw:: html

		<table align="left" border="1" cellpadding="0" cellspacing="0">
		<tbody>
        <tr>
            <td valign="top">
                <p>
                    Contents
                </p>
            </td>
            <td valign="top">
                <p>
                    A data filename usually provides little information on its content. Provide here a description of this content. This description should
                    clearly distinguish collected variables and derived variables. It is also useful to indicate the availability in the data file of some
                    particular variables such as the weighting coefficients. If the file contains derived variables, it is good practice to refer to the
                    computer program that generated it.
                </p>
                <p>
                    Examples:
                </p>
                <ul>
                    <li>
                        <em>
                            The file contains data related to section 3A of the household survey questionnaire (Education of household members aged 6 to 24
                            years). It also contains the weighting coefficient, and various recoded variables on levels of education.
                        </em>
                    </li>
                    <li>
                        <em>
                            The file contains derived data on household consumption, annualized and aggregated by category of products and services. The file
                            also contains a regional price deflator variable and the household weighting coefficient. The file was generated using a Stata
                            program named "cons_aggregate.do" available in the external resources.
                        </em>
                    </li>
                </ul>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Producer
                </p>
            </td>
            <td valign="top">
                <p>
                    Put the name of the agency that produced the data file. Most data files will have been produced by the survey primary investigator. In some
                    cases however, auxiliary or derived files from other producers may be released with a data set. This may for example include CPI data
                    generated by a different agency, or files containing derived variables generated by a researcher.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Version
                </p>
            </td>
            <td valign="top">
                <p>
                    A data file may undergo various changes and modifications. These file specific versions can be tracked in this element. This field will in
                    most cases be left empty. It is more important to fill the field identifying the version of the dataset (see above).
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Processing Checks
                </p>
            </td>
            <td valign="top">
                <p>
                    Use this element if needed to provide information about the types of checks and operations that have been performed on the data file to
                    make sure that the data are as correct as possible, e.g. consistency checking, wildcode checking, etc. Note that the information included
                    here should be specific to the data file. Information about data processing checks that have been carried out on the data collection
                    (study) as a whole should be provided in the "Data editing" element at the study level.
                </p>
                <p>
                    You may also provide here a reference to an external resource that contains the specifications for the data processing checks (that same
                    information may be provided also in the "Data Editing" filed in the Study Description section).
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Missing data
                </p>
            </td>
            <td valign="top">
                <p>
                    Missing data can be given certain coding. A common convention is to iterate the number "9" to fill a field. This value needs to be defined
                    as missing in the data set and can be explained in detail in this element.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Notes
                </p>
            </td>
            <td valign="top">
                <p>
                    This field, aiming to provide information to the user on items not covered elsewhere, will in most cases be left empty.
                </p>
            </td>
        </tr>
    	</tbody>
	</table>


**5.4.	Good practices for completing the Variables Description**

The Variable Description is the section of the DDI document that provides detailed information on each variable.

.. raw:: html

	<table border="1" cellpadding="0" cellspacing="0">
	    <tbody>
        <tr>
            <td valign="top">
                <p>
                    Variable Names
                </p>
            </td>
            <td valign="top">
                <p>
                    These are the names given to the variables. Ideally, the variable names should be a maximum of 8 characters, and use a logical naming
                    convention (e.g., section (S) and question (Q) numbers to name the question). If the variable names do not follow these principles, DO NOT
                    CHANGE THE VARIABLE NAMES IN THE TOOLKIT, but make recommendations to the data processor for consideration for future surveys.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Variable Labels
                </p>
            </td>
            <td valign="top">
                <p>
                    All variables should have a label that
                </p>
                <ul>
					<li>Provides the item or question number in the original data collection instrument (unless item number serves as the variable name)</li>
					<li>Provides a clear indication of what the variable contains</li>
					<li>Provides an indication of whether the variable is constructed from other items</li>
                
				<P>Recommendations: </p>
                <ul>
                    <li>Do not use ALL CAPS in labels.</li>
					<li>Make sure that different variables have different labels (avoid duplicate labels). The IHSN Toolkit provides a tool to check availability and unicity of variable labels (see Tools &gt; Validate Variable).
					<li>For expenditure or income: indicating the currency and period of reference is crucial (e.g. "Annual per capita real expenditure in local currency" </li>
                </ul>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Width, StartCol, Endcol
                </p>
            </td>
            <td valign="top">
                <p>
                    When you import your data files from Stata or SPSS, the information on StartCol and EndCol will be empty. It is crucial to add this
                    information, in order to allow users to export the data to ASCII fixed format. To do so, use the "Variables &gt; Resequence" command in the
                    Toolkit, for each data file.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Categories
                </p>
            </td>
            <td valign="top">
                <p>
                    Variable categories are the lists of codes (and their meaning) that apply to the variable. The Toolkit imports categories and their labels
                    from the source data files (SPSS, Stata).
                </p>
                <p>
                    If necessary, add/edit the codes. Use the Documentation &gt; Create categories from statistics if the source dataset did not include value
                    labels (e,g., when imported from ASCII). Make sure the categories are not hierarchical, and do not include codes for "Missing". The codes
                    for Missing must be specified in the "Missing data" field. If you fail to do that, the summary statistics (mean, standard deviation, etc)
                    will be calculated including the missing code, which will be considered as a valid value.
                </p>
                <p>
                    <img src="file:///C:\Users\hrudaya\AppData\Local\Temp\msohtmlclip1\01\clip_image002.jpg"height="128"/>
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Data type
                </p>
            </td>
            <td valign="top">
                <p>
                    Four types of variables are recognized by the Toolkit:
                </p>
                <ul>
                    <li>Numeric: <em>Numeric variables are used to store any number, integer or floating point (decimals).</em>
                <li>Fixed string:
                    <em>
                        A fixed string variable has a predefined length (default length is 8 but it can range from 1 to 255 characters in length) which enables the publisher to handle this data type more efficiently.
                    </em></li>
					<li>Dynamic string: <em>Dynamic string variables can be used to store open-ended questions.</em></li>
					<li>Date: <em>date variables stored in ISO format (YYYY-MM-DD?—should specify)</em></li>
                </ul>
                <p>
                    The data type is usually properly identified when the data is imported. It is important to avoid the use of string variables when this is not absolutely needed. Such issues must be taken care of before the data is imported in the Toolkit. See the section on "<a href="#_Gathering_and_preparing">Gathering and preparing the dataset</a>" above.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Measure
                </p>
            </td>
            <td valign="top">
                <p>
                    The Microdata Management Toolkit will allow you to define the measure of a variable as:
                </p>
                <ul>
                    <li>
                        <em>Nominal</em>
                        : variable with numeric assignations for responses; the number assigned to each response does not have a meaning by itself.
                    </li>
                </ul>
                <p>
                    <em>Example</em>
                    : Variable <em>sex</em>: 1 = Male, 2 = Female (the number does not have a meaning by itself; we could as well have assigned Male = 2 and
                    Female = 1). When variables are nominal, we can produce frequency tables by code, but calculating mean or standard deviation of the codes
                    would not make sense.
                </p>
                <ul>
                    <li>
                        <em>Ordinal</em>
                        : variable with numeric assignations and in a logical sequence. The absolute size of the number, or the difference between two numbers
                        has no meaning. But the sequence of the number matters.
                    </li>
                </ul>
                <p>
                    <em>Example</em>
                    : An example of an ordinal variable would be a variable indicating the level of satisfaction of the respondent, for example on a scale of 1
                    (very unsatisfied) to 5 (very satisfied).
                </p>
                <ul>
                    <li>
                        <em>Scale</em>
                        : continuous variables that have inherent and not categorical value. Examples of such variables include the age of the person, the
                        amount of income or expenditure, etc.
                    </li>
                </ul>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Time variable
                </p>
            </td>
            <td valign="top">
                <p>
                    This is a check-box used to tag and identify variables used to define time.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Weight variable
                </p>
            </td>
            <td valign="top">
                <p>
                    This is a check box that is used to tag the weight variable. It is a good practice to include the weight variable with each data file that
                    is being archived. If it is included, the check box should be ticked.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Min
                </p>
                <p>
                    Max
                </p>
            </td>
            <td valign="top">
                <p>
                    Allows modifying the minimum value of a variable. For each variable where it makes sense, you should check that the Min and Max values are
                    correct. Remember: if a specific value is used for "Missing", this should not be included in the Min-Max range. For example, if codes 1 and
                    2 are used for Male and Female, and 9 for unknown sex, then the Min will be 1 and the Max will be 2. The code 9 must be listed in the
                    "Missing" codes (see below).
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Decimals
                </p>
            </td>
            <td valign="top">
                <p>
                    Defines the number of decimal places of a numeric variable type.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Implicit decimals
                </p>
            </td>
            <td valign="top">
                <p>
                    This check box is selected only when a fixed ASCII-type file is imported and the data file includes a decimal character. As the decimal
                    character also requires a space in the variable length assignation, it is important to check this box in order to assure proper alignment
                    of the data.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Missing data
                </p>
            </td>
            <td valign="top">
                <p>
                    Missing values are those values that are blank in a data file but should have been responses and are within the path or universe of the
                    questionnaire. Missing values should always be coded. Missing values should be differentiated from "not applicable" and zero (0) values.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Statistics Options
                </p>
            </td>
            <td valign="top">
                <p>
                    Various options exist for displaying and presenting summary information of the variable to the user or the person browsing the output.
                    Summary statistics are saved in the DDI document and become part of the metadata. It is therefore important to select the appropriate ones.
                </p>
                <ul>
                    <li>For nominal variables you want to be sure that the categories are well defined and that some of the summary statistics are not displayed(such as means and standard deviations.
                <li>For ordinal values, you want to be sure that the categories are displayed if they are required. Not all ordinal values will require a category. In some cases you may want to include some summary statistics such as mean and standard deviation.
                <li>For scale values, you do not want to define categories and you may want to include some summary statistics such as mean and standard deviation.
                </p>
                <p>
                    Make sure you do not include "Frequencies" for variables such as the household identification number or enumeration area. This would
                    produce a useless frequency table, that would considerably increase the size of your DDI file (in general, a very large DDI file–8 to 10Mb
                    or more– indicates such a problem).
                </p>
                <p>
                    Make sure also that you do not include meaningless summary statistics, such as the mean or standard deviation calculated on the codes used
                    for variable SEX.
                </p>
                <p>
                    Notes:
                </p>
                <ul>
                    <li>Summary statistics such as the mean or standard deviation are calculated using all valid values. If special codes are used to indicate
                    missing values, make sure they are declared in the "Missing" section. If not, they will be included in the calculations. For example, if
                    you use code 99999 for indicating missing values in a variable on household expenditure, code 99999 must be listed in the missing section
                    as follows:
                </li>
                
                <li>
                    If you modify information such as the categories or missing values, you must use the "Documentation > Update Statistics" command in
                    the Toolkit to refresh the summary statistics.
                </li>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Weights
                </p>
            </td>
            <td valign="top">
                <p>
                    The appropriate weight should be attached to the file and selected in this element. The weight should be well labelled.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Definition
                </p>
            </td>
            <td valign="top">
                <p>
                    This element provides a space to describe the variable in detail. Not all variables require definition. The following variables should
                    always be defined when available in a questionnaire:
                </p>
				<ul>
                <li>Household (attach this definition to the "household ID" variable</li>
                <li>Head of household (attach this definition to the variable "relationship to the head"</li>
                </ul><li>
                        Urban/rural
                    </li>
                </ul>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Universe
                </p>
            </td>
            <td valign="top">
                <p>
                    The universe at the variable level reflects skip patterns within-records in a questionnaire. This information can typically be copy/pasted
                    from the survey questionnaire. Try to be as specific as possible. This information is very useful for the analyst.
                </p>
                <p>
                    In many cases, a block of variables will have the same universe (for example, a block of variables on education can all relate to the
                    "Population aged 6 to 24 year). The Toolkit allows you to select multiple variables and enter the universe information to all variables at
                    once.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Source of information
                </p>
            </td>
            <td valign="top">
                <p>
                    Enter information regarding who provided the information contained within the variable. In most cases, the source will be "Head of
                    household" or "Household member". But it may also be
                </p>
                <ul>
                    <li>GPS measure (for geographic position)</li>
					<li>Interviewer’s visual observation (for type of dwelling)</li>
					<li>Best informant in community</li>
					<li>Etc.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Concepts
                </p>
            </td>
            <td valign="top">
                <p>
                    Greater description on the nature of the variable can be placed in this element. For example this element can provide a clearer definition
                    for certain variables (i.e. a variable that provides information on whether a person is a household member). In the case of household
                    membership, a conceptual definition can be provided.
                </p>
                <p>
                    Example:
                </p>
                <p>
                    <em>
                        A household member is defined as any person who has been resident in the household for six months or more in a given year and takes
                        meals together OR by default the head of household, infants under 6 months, newly wedded couples etc.
                    </em>
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Pre-question text
                </p>
                <p>
                    Literal question
                </p>
                <p>
                    Post-question text
                </p>
            </td>
            <td valign="top">
                <p> The <em>pre-question texts </em>are the instructions provided to the interviewers and printed in the questionnaire before the literal question. This does not apply to all variables. Do not confuse this with instructions provided in the interviewer’s manual. With this and the next two fields, one should be able to understand how the question was asked during the interview. See example below.
                </p>
                <p>
                    The <em>literal question</em> is the full text of the questionnaire as the enumerator is expected to ask it when conducting the interview.
                    This does not apply to all variables (it does not apply to derived variables).
                </p>
                <p>
The <em>post-question texts</em> are instructions provided to the interviewers, printed in the questionnaire after the literal question</u>. Post-question can be used to enter information on skips provided in the
                    questionnaire. This does not apply to all variables. Do not confuse this with instructions provided in the interviewer’s manual. With this
                    and the next two fields, one should be able to understand how the question was asked during the interview. See example above.
                </p>
                <p>
                    Example: In the example below (extracted from a UNICEF-MICS standard questionnaire), we find a pre-question, a literal question and a
                    post-question.
                </p>
                
                <ul>
                    <li>
                        Pre-question: <em>Check age. If child is 3 years old or more, ask:</em>
                    </li>
                    <li>
                        Literal question:
                        <em>
                            Does (name) attend any organized learning or early childhood education programme, such as private or government facility, including
                            kindergarten or community child care?
                        </em>
                    </li>
                    <li>
                        Post-question: <em>If answer is 2 or 9 &gt; Goto next module</em>
                    </li>
                </ul>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Interviewer Instruction
                </p>
            </td>
            <td valign="top">
                <p>
                    Copy/paste the instructions provided to the interviewers <u>in the interviewer’s manual</u>. In cases where some instructions relate to
                    multiple variables, repeat the information in all variables. The Toolkit allows you to select multiple variables and enter the information
                    to all these variables at once.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Imputation
                </p>
            </td>
            <td valign="top">
                <p>
                    The field is provided to record any imputation or replacement technique used to correct inconsistent or unreasonable data. It is
                    recommended that this field provide a summary of what was done and include a reference to a file in the external resources section.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Recoding and derivation
                </p>
            </td>
            <td valign="top">
                <p>
                    This element applies to data that were obtained by recoding collected variables, or by calculating new variables that were not directly
                    obtained from data collection. It is very important to properly document such variables. Poorly documented variables cannot (or should not)
                    be used by researchers. In cases where the recoding or derivation method was very simple, a full description can be provided here. For
                    example, if variable AGE_GRP was obtained by recoding variable S1Q3, we could simply mention
                    <em>
                        “Variable obtained by recoding the age in years provided in variable S1Q3 into age groups for years 0-4, 5-9, …, 60-64, 65 and over.
                        Code 99 indicates unknown age.”
                    </em>
                </p>
                <p>
                    When the derivation method is more complex, provide here a reference to a document (and/or computer program) to be provided as an External
                    Resource. This will be the case for example for a variable “TOT_EXP” containing the household annual total expenditure, obtained from a
                    household budget survey. In such case, the information provided here could be:
                </p>
                <p>
                    <em>
                        “This variable provides the annual household expenditure. It was obtained by aggregating expenditure data on all goods and services,
                        available in sections 4 to 6 of the household questionnaire. It contains imputed rental values for owner-occupied dwellings. The values
                        have been deflated by a regional price deflator available in variable REG_DEF”. All values are in local currency. Outliers have been
                        fixed. Details on the calculations are available in Appendix 2 of the Report on Data Processing, and in the Stata program
                        “aggregates.do” available in external resources.”
                    </em>
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Security
                </p>
            </td>
            <td valign="top">
                <p>
                    This field will be left empty in most cases. It can be used to identify variables that are direct identifiers of the respondents (or highly
                    identifying indirect identifiers), and that should not be released.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Notes
                </p>
            </td>
            <td valign="top">
                <p>
                    This element is provided in order to record any additional or auxiliary information related to the specific variable.
                </p>
            </td>
        </tr>
   	 </tbody>
	</table>

**5.5.	Good practices for completing the External Resources description**

The External Resources are all materials related to the study others than the data files. They include documents (such as the questionnaires, interviewer’s manuals, reports, etc), programs (data entry, editing, tabulation, and analysis), maps, photos, and others. To document external resources, the IHSN Toolkit uses the Dublin Core metadata standard (which complements the DDI standard).

.. raw:: html

		<table border="1" cellpadding="0" cellspacing="0">
		<tbody>
        <tr>
            <td valign="top">
                <p>
                    Label
                </p>
            </td>
            <td valign="top">
                <p>
                    This is the label that will be used to display a hyper link to the attached document. It can be the title, name, or an abbreviated version
                    of the title.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Resource
                </p>
            </td>
            <td valign="top">
                <p>
                    The resource is used to point to the file that will be attached and distributed. The folder where the document is found is a relative path
                    and should be the folder that will be pasted into the **\document path. Once you have pointed to the specified resource make sure you check
                    file access by clicking the folder icon to the right of the entry field.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Type
                </p>
            </td>
            <td valign="top">
                <p>
                    This is crucial information. A controlled vocabulary is provided. The selection of the type is important as it determines the way it will
                    be presented or displayed to the user in the final output. The following are the choices:
                </p>
                <ul>
                    <li>Document Administrative: This includes materials such as the survey budget; grant agreement with sponsors; list of staff and interviewers, etc. </li>
					<li>Document Analytical: Documents that present analytical output (academic papers, etc. This does not include the descriptive survey report (see below). </li>
					<li>Document Questionnaire: the actual questionnaire(s) used in the field.</li>
					<li>Document Reference: Any reference documents that are not directly related to the specific dataset, but that provide background information regarding methodology, etc. For international standard surveys, this may for example include the generic guidelines provided by the survey sponsor.</li>
					<li>Document Report: Survey reports, studies and other reports that use the data as the basis for their findings.</li>
					<li>Document Technical: Methodological documents related to survey design, interviewer’s and supervisor’s manuals, editing specifications, data entry operator’s manual, tabulation and analysis plan, etc.</li>
					<li>Document Other: Miscellaneous items</li>
					<li>Audio: audio type files.</li>
					<li>Map: Any cartographic information.</li>
					<li>Photo: Photos can provide good documentary evidence of a survey.</li>
					<li>Program: programs generated during data entry and analysis (data entry, editing, tabulation and analysis). These can be zipped together (include a brief summary report to describe the contents)</li>
					<li>Table: Tabulations such as confidence intervals that may not be included in a general report.</li>
					<li>Video: video type files provided as additional visual information</li>
					<li>Website: Link to related website(s), such as a link to a Redatam server, or to the website of the survey sponsor in the case of	international survey programs like the DHS, LSMS, or MICS).</li>
					<li>Database: any databases related to the survey (e.g., a Devinfo database providing the aggregated results of the survey).</li>
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Title
                </p>
            </td>
            <td valign="top">
                <p>
                    Full title of the document as it is provided on the cover page.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Subtitle
                </p>
            </td>
            <td valign="top">
                <p>
                    Subtitle if relevant.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Author(s)
                </p>
            </td>
            <td valign="top">
                <p>
                    Include all authors that are listed on the report.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Date
                </p>
            </td>
            <td valign="top">
                <p>
                    Date of the publication of the report or resource (at least month and year). For reports, this is most likely stated on the cover page of
                    the document. For other types of resources, put here the date the resource was produced.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Country
                </p>
            </td>
            <td valign="top">
                <p>
                    The country (or countries) that are covered by the associated document.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Language
                </p>
            </td>
            <td valign="top">
                <p>
                    Use the Language element to list all languages which appear in a resource. The languages should be selected from the drop-down list, and
                    each language should appear on its own line. The proposed controlled vocabulary is based on ISO 639-3s.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Format
                </p>
            </td>
            <td valign="top">
                <p>
                    The file format provides information on the kind of electronic document being provided. This includes: PDF, Word, Excel etc. This is a
                    controlled vocabulary. If the controlled vocabulary does not provide the format you need, type it (or add it in the controlled vocabulary
                    using the Toolkit Template Editor). Providing information on the format will inform the user on the software needed to open the file.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    ID Number
                </p>
            </td>
            <td valign="top">
                <p>
                    If there is a unique ID number which references the document (such as a Library of Congress number or a World Bank Publication number)
                    include this as the ID Number.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Contributor(s)
                </p>
            </td>
            <td valign="top">
                <p>
                    Include the names of all organizations that have been involved or contributed to producing the publication. This included funding sources
                    as well as authoring entities.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Publisher(s)
                </p>
            </td>
            <td valign="top">
                <p>
                    Include the official organization(s) accredited with disseminating the report.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Rights
                </p>
            </td>
            <td valign="top">
                <p>
                    Some resources are protected by copyrights. Use the Rights element to provide a clear and complete description of the usage rights if
                    relevant.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Description
                </p>
            </td>
            <td valign="top">
                <p>
                    A brief description of the resource.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Abstract
                </p>
            </td>
            <td valign="top">
                <p>
                    An abstract of the content of the resource.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Table of Contents
                </p>
            </td>
            <td valign="top">
                <p>
                    Use the Table of Contents element to list all sections of a report, questionnaire, or other document. When copying a table of contents from
                    another file into a project, pay close attention to the formatting as tabs, indents, and fonts may not be preserved. Because the text
                    cannot be formatted, adopting strategies such as placing chapter titles in capital letters can help keep a table of contents organized.
                    Including page numbers is not crucial.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top">
                <p>
                    Subjects
                </p>
            </td>
            <td valign="top">
                <p>
                    The key topics discussed in the resource can be listed in the Subjects element. Although the IHSN Resource Template does not include a
                    controlled vocabulary for this element, organizations may opt to modify the template and establish a set list of subjects which all of
                    their projects should use when documenting studies.
                </p>
            </td>
			</tr>
		</tbody>
		</table>

