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


<table border="1" cellpadding="0" cellspacing="0">
    <tbody>
        <tr>
            <td valign="top" width="129">
                <p>
                    Study Title
                </p>
            </td>
            <td valign="top" width="454">
                <p>
                    The title is the official name of the survey as it is stated on the questionnaire or as it appears in the design documents. The following
                    items should be noted:
                </p>
                <p>
                    o Include the reference year(s) of the survey in the title.
                </p>
                <p>
                    o Do not include the abbreviation of the survey name in the title.
                </p>
                <p>
                    o As the survey title is a proper noun, the first letter of each word should be capitalized (except for prepositions or other
                    conjunctions).
                </p>
                <p>
                    o Including the country name in the title is optional.
                </p>
                <p>
                    <em> </em>
                </p>
                <p>
                    Examples: <em> National Household Budget Survey 2002-2003</em>
                </p>
                <p>
                    <em> Popstan Multiple Indicator Cluster Survey 2002</em>
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top" width="129">
                <p>
                    Metadata Producer
                </p>
            </td>
            <td valign="top" width="454">
                <p>
                    Name of the person(s) or organization(s) who documented the dataset. Use the "role" attribute to distinguish different stages of
                    involvement in the production process.
                </p>
                <p>
                    Example:
                </p>
                <table border="1" cellpadding="0" cellspacing="0">
                    <tbody>
                        <tr>
                            <td valign="top" width="272">
                                <p>
                                    <em>Name</em>
                                </p>
                            </td>
                            <td valign="top" width="167">
                                <p>
                                    <em>Role</em>
                                </p>
                            </td>
                        </tr>
                        <tr>
                            <td valign="top" width="272">
                                <p>
                                    <em>National Statistics Office (NSO)</em>
                                </p>
                            </td>
                            <td valign="top" width="167">
                                <p>
                                    <em>Documentation of the study</em>
                                </p>
                            </td>
                        </tr>
                        <tr>
                            <td valign="top" width="272">
                                <p>
                                    <em>International Household Survey Network (IHSN) </em>
                                </p>
                            </td>
                            <td valign="top" width="167">
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
            <td valign="top" width="129">
                <p>
                    Date of Production
                </p>
            </td>
            <td valign="top" width="454">
                <p>
                    This is the date (in ISO format YYYY-MM-DD) the DDI document was produced (not distributed or archived). This date will be automatically
                    imputed when you save the file.
                </p>
            </td>
        </tr>
        <tr>
            <td valign="top" width="129">
                <p>
                    DDI Document Version
                </p>
            </td>
            <td valign="top" width="454">
                <p>
                    Documenting a dataset is not a trivial exercise. Producing “perfect” metadata is probably impossible. It may therefore happen that, having
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
            <td valign="top" width="129">
                <p>
                    DDI Document ID Number
                </p>
            </td>
            <td valign="top" width="454">
                <p>
                    The ID number of a DDI document is a unique number that is used to identify this DDI file. Define and use a consistent scheme to use. Such
                    an ID could be constructed as follows: DDI-country-producer-survey-year where
                </p>
                <p>
                    o <em>country</em> is the 3-letter ISO country abbreviation
                </p>
                <p>
                    o <em>producer</em> is the abbreviation of the producing agency
                </p>
                <p>
                    o <em>survey</em> is the survey abbreviation
                </p>
                <p>
                    o <em>year</em> is the reference year (or the year the survey started)
                </p>
                <p>
                    o DDI document version number
                </p>
                <p>
                    Example:
                </p>
                <p>
                    <em>
                        The DDI file related to the Demographic and Health Survey documented by staff from the Uganda Bureau of Statistics in 2005 would have
                        the following ID:
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



**5.3.	Good practices for completing the File Description**

The File Description is the DDI section that aims to provide a detailed description of each data file. The IHSN has selected six of the available DDI elements.

[Table]

**5.4.	Good practices for completing the Variables Description**

The Variable Description is the section of the DDI document that provides detailed information on each variable.

[Table]

**5.5.	Good practices for completing the External Resources description**

The External Resources are all materials related to the study others than the data files. They include documents (such as the questionnaires, interviewer’s manuals, reports, etc), programs (data entry, editing, tabulation, and analysis), maps, photos, and others. To document external resources, the IHSN Toolkit uses the Dublin Core metadata standard (which complements the DDI standard).

[Table]
